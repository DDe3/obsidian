
# Descripcion

Esta lambda verifica que exista un archivo en un bucket S3 (ambos parámetros de entrada) y tambien verifica si el archivo es un archivo comprimido.


#### Ejemplo
~~~ json
Si el archivo a verificar es: "OID_REPORTE_DE_STOCK_ZMXMMMTR_238A_.txt"
La lambda verificará que exista en el bucket y carpeta el archivo:
"OID_REPORTE_DE_STOCK_ZMXMMMTR_238A_yyyyMMdd.txt" siendo yyyyMMdd el día en que se ejecuta la lambda.
~~~

# Input

~~~ json
{
  "bucket_name": "test-container-bucket",
  "file_folder": "02_Inventario",
  "file_name": "OID_REPORTE_DE_STOCK_ZMXMMMTR_238A" <- Sin extension
}
~~~

- **bucket_name**: Nombre del bucket en donde se verificará el archivo.
- **file_folder**: Directorio dentro del bucket donde está el archivo.
- **file_name**: Nombre del archivo a verificar (debe incluir la extensión y no debe incluir la fecha en el nombre).

# Output

~~~ json
{
	StatusCode = "200 o 404" Si encuentra o no el archivo,
	Body = body,
	Compressed = "true o false",
	compressedExtension =  "None" o ".zip, .tar, etc."
}
~~~

# Consideraciones

La lambda no verifica la extensión del archivo si no es comprimido (.csv, .txt) solo si está comprimido o no.
