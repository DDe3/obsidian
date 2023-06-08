
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


~~~ json

{
"bucket_name": "bucket",
"file_key" : "key",
}

~~~



| Tiempo normal (min) | Tiempo paralelo (min) | Particiones | DPU |
| ------------------- | --------------------- | ----------- | --- |
| 2.55                | 1.41                  | 2           | 2   |
|                     | 1.53                  | 4           | 2   |
|                     | 1.35                  | 4            |4     |

{
 "bucket_name" : "brightcell-nonprod-vmi-telcel",
 "file_folder" : "01_Ventas",
 "file_name" : "expor_gsm120230330.zip"
}

- [x] MaterialID
- [x] Material, 
- [x] Descripcion, 
- [x] Marca, 
- [x] Modelo, 
- [x] Categoria,
- [x] Color, 
- [x] Formfactor, 
- [x] Sector, 
- [x] SectorDescripcion, 
- [x] CreatedDate, 
- [x] UpdateDate, 
- [ ] StartDate, 
- [ ] EndDate, 
- [x] GamaR9, 
- [x] GamaDEUR, 
- [x] LanzamientoDEUR, 
- [x] CicloVidaR9, 
- [x] CicloVidaDEUR, 
- [x] GrupoArticulo, 
- [x] DescripcionGrupo, 
- [x] NoResurtible, 
- [x] NombreComercial, 
- [x] NombreComercialColor, 
- [x] NoComercializable, 
- [x] InsertDate



- [ ] Codigo de material | Material
- [x] Descripcion,
- [x] Nombre comercial,
- [x] Nombre comercial color,
- [x] Marca,
- [x] Modelo,
- [x] Color,
- [ ] Nueva Categoria, | Categoria
- [ ] No Comercializable, | NoComercializable
- [x] Form factor,
- [x] Sector,
- [x] Descripcion sector,
- [x] Tecnologia,
- [x] Sistema operativo,
- [x] Lanzamiento R9,
- [x] Precio R9,
- [x] Precio R9 IVA,
- [x] Obsoleto financiero,
- [x] Gama R9,
- [x] Lanzamiento DEUR
- [x] ,Precio DEUR,
- [x] Precio DEUR IVA,
- [x] Gama DEUR,
- [x] Ciclo de vida DEUR,
- [x] Ciclo de vida R9,
- [x] Grupo de articulo,
- [x] Descripcion de grupo,
- [x] Numero de nucleos,
- [x] Marca de chipset,
- [x] Velocidad del procesador,
- [x] Tipo pantalla,
- [ ] TamaÃ¯Ã±o pantalla (pulgadas), |Tamaño pantalla (pulgadas)
- [x] Camara frontal (MP),
- [x] Camara trasera (MP),
- [x] Flash camara frontal (Si/No),
- [x] Flash camara trasera (Si/No),
- [x] ROM (GB),
- [x] RAM (GB),
- [x] Capacidad bateria (mAh),
- [x] VoLTE (Si/No),
- [x] ViLTE (Si/No),
- [x] VoWiFi (Si/No),
- [x] Version de sistema operativo,
- [ ] [Capacidad memoria interna (GB), | Capacidad memoria interna (GB)
- [x] Ranura memoria externa (Si/No),
- [x] Capacidad memoria externa (max),
- [x] Weatherproof,
- [x] GigaRed,
- [x] Categoria LTE,
- [x] Frecuencias 2g,
- [x] Frecuencias 3g,
- [x] Frecuencias 4g,
- [x] Frecuencias 5g,
- [x] Equipo sustituto sugerido por marca
- [x] ,Seguridad de desbloqueo
- [x] No Resurtible

,Codigo de material,Descripcion,Nombre comercial,Nombre comercial color,Marca,Modelo,Color,Nueva Categoria,No Comercializable,Form factor,Sector,Descripcion sector,Tecnologia,Sistema operativo,Lanzamiento R9,Precio R9,Precio R9 IVA,Obsoleto financiero,Gama R9,Lanzamiento DEUR,Precio DEUR,Precio DEUR IVA,Gama DEUR,Ciclo de vida DEUR,Ciclo de vida R9,Grupo de articulo,Descripcion de grupo,Numero de nucleos,Marca de chipset,Velocidad del procesador,Tipo pantalla,TamaÃ¯Ã±o pantalla (pulgadas),Camara frontal (MP),Camara trasera (MP),Flash camara frontal (Si/No),Flash camara trasera (Si/No),ROM (GB),RAM (GB),Capacidad bateria (mAh),VoLTE (Si/No),ViLTE (Si/No),VoWiFi (Si/No),Version de sistema operativo,[Capacidad memoria interna (GB),Ranura memoria externa (Si/No),Capacidad memoria externa (max),Weatherproof,GigaRed,Categoria LTE,Frecuencias 2g,Frecuencias 3g,Frecuencias 4g,Frecuencias 5g,Equipo sustituto sugerido por marca,Seguridad de desbloqueo,No Resurtible