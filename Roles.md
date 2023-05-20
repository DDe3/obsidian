
## Glue


Para funcionar: 
- **AWSGlueServiceRole**
- **AmazonS3FullAccess** : A todos los buckets o al unico bucket que usamos



## Lambda

- AmazonS3FullAccess
- AmazonSQSFullAccess
- AccessSecretsValue
- AmazonSNSFullAccess


## Move files Lambda

~~~ json
{ "bucket_name" : "brightcell-nonprod-vmi-telcel", "file_folder": "02_Inventario", "destination" : "processed", "file_directory": "unprocessed" }
~~~

# Truncate table lambda

~~~ json
{ "table_name" : "preprocessing.statingDailyInventory", "sp_name" : "preprocessing.TruncateTable" }
~~~

EXEC preprocessing.TruncateTable 'preprocessing.statingDailyInventory'

[Brightcell-VMI-02Inventario-state-machine](https://us-east-1.console.aws.amazon.com/states/home?region=us-east-1#/statemachines/view/arn:aws:states:us-east-1:017283260485:stateMachine:Brightcell-VMI-02Inventario-state-machine)

~~~ yaml
  LoadInventoryFilesJob:
    Type: AWS::Glue::Job
    Properties:
      Command:
        Name: glueetl
        ScriptLocation: jobs/Brightcell-VMI-load-inventory-files.py
        PythonVersion: "3"
      GlueVersion: "3.0"
      DefaultArguments:
        "--job-language": "python"
        "--job-bookmark-option": "job-bookmark-disable"
      MaxCapacity: 4
      MaxRetries: 0
      Timeout: 2880
      Role: arn:aws:iam::017283260485:role/VMI_Telcel_GlueRole
      ExecutionProperty:
        MaxConcurrentRuns: 1
  FactInventoryJob:
    Type: AWS::Glue::Job
    Properties:
      Command:
        Name: glueetl
        ScriptLocation: jobs/Brightcell-VMI-factInventory.py
        PythonVersion: "3"
      GlueVersion: "3.0"
      DefaultArguments:
        "--job-language": "python"
        "--job-bookmark-option": "job-bookmark-disable"
      MaxCapacity: 4
      MaxRetries: 0
      Timeout: 2880
      Role: arn:aws:iam::017283260485:role/VMI_Telcel_GlueRole
      ExecutionProperty:
        MaxConcurrentRuns: 1
  # -------------------------------------------------------------------   Sales  ------------------------------------------------------------------------------------#
  LoadSalesFilesJob:
    Type: AWS::Glue::Job
    Properties:
      Command:
        Name: glueetl
        ScriptLocation: jobs/Brightcell-VMI-load-sales-files.py
        PythonVersion: "3"
      GlueVersion: "3.0"
      DefaultArguments:
        "--job-language": "python"
        "--job-bookmark-option": "job-bookmark-disable"
      MaxCapacity: 4
      MaxRetries: 0
      Timeout: 2880
      Role: arn:aws:iam::017283260485:role/VMI_Telcel_GlueRole
      ExecutionProperty:
        MaxConcurrentRuns: 1
~~~


~~~
~~~