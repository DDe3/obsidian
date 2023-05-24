
Para crear un nuevo proyecto lambda

~~~ cmd
dotnet new lambda.EmptyFunction --name {function_name}
~~~




Para testear lambdas en .NET

~~~ cmd
cd path/to/project
dotnet-lambda-test-tool-6.0
~~~

Antes se debe tener instalado **dotnet** y **dotnet-lambda-test-tool-6.0**

~~~ cmd
dotnet tool install -g Amazon.Lambda.TestTool-6.0
~~~

