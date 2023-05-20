---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
brightcell-nonprod-vmi-telcel
 ^VcYypKGK

Se carga archivo .txt en
directorio 01_Ventas/unprocessed ^jCIJmBpq

Verificar archivos ^TJwsh39f

Notificación de proceso
fallido ^xfD1TC0c

Evento ^s0LTdJgH

AWS Step Functions: Ventas ^fo09fZfB

El archivo es correcto? ^yL8muwpx

Descomprimir
archivos ^U5r3kjCm

Brightcell-VMI-load-sales-files ^v2Ri6ovP

stating.dailySales ^XgssF7zW

Limpiar tabla ^l03jYce2

El proceso limpia
la tabla en caso
de que se tenga
que reprocesar ^r4X5xjGh

dw.FactSales ^XFKvq28Y

Brightcell-VMI-extract-daily-sales ^4N58shO9

No ^ekqXatZ1

Si ^cL3LeKGS

dw.dimMaterial ^orS3a38A

dw.dimStore ^8Pk80tl3

dw.dimCostumer ^IUgSvDof

dbo.R1_Uni ^54eyMLat

stating.EightWeekSales ^yD2iwP7o

Brightcell-VMI-extract-daily-sales-eight-weeks ^PKX2ZYgo

dbo.R2 ^CQr5Uqo8

dbo.R2_Cads ^xQbUJGCy

dbo.R3 ^2hv5dtY1

dbo.R3_Cads ^SA2vEfLc

dbo.R4 ^jtvjX5ZP

dbo.R4_Cads ^I6U0rOYB

dbo.R5 ^pnUK4gk3

dbo.R6 ^SNavG6gG

dbo.R7_Uni ^xhlcNUZj

dbo.R8 ^HKFiGkue

dbo.R8_Cads ^kic9FRKR

dbo.R9 ^sIc7Y0Ov

dbo.R9_Accesorios ^S87j9BLW

dw.FactSaleswoChannel ^Td0Dc4bn

dbo.FullDimDate ^W7p4JFRB

Consulta información de: ^22GgEefv

Carga información en: ^41lGpJ5G

Flujo principal ^tZlInIqI

Keys ^ATE10Hsb

Mover archivos a directorio processed ^tyoc6kMq

El tipo de dato de
columna FECHAFACTURA
puede ayudar con el rendimiento ^8aStKUGl

DELETE FROM [dw].[FactSales]
WHERE DATE IN 
(
SELECT 
CONCAT(SUBSTRING(SUB.FECHA1,5,2),'.',SUBSTRING(SUB.FECHA1,7,2),'.',SUBSTRING(SUB.FECHA1,1,4))
FROM ( 
        SELECT 
    MAX(CONCAT(SUBSTRING(FECHAFACTURA,7,4),SUBSTRING(FECHAFACTURA,1,2),SUBSTRING(FECHAFACTURA,4,2))) FECHA1
    FROM [stating].[DailySales] D  WITH(NOLOCK)
        ) SUB 
)
 
Puede Ser =>
Delete from dw.FactSales
Where Date = ( SELECT MAX(FECHAFACTURA) FROM stating.DailySales) ^69MBr8iS

Llamar SP
TruncateTable ^YQRBS0rf

Elimina ^Cb9pIQkS

Consulta fecha ^4sVnV8Ua

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/1.8.26",
	"elements": [
		{
			"type": "rectangle",
			"version": 1507,
			"versionNonce": 1145384760,
			"isDeleted": false,
			"id": "xb4vbVEIcUkv8iliu2D12",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 16.8192361571123,
			"y": -124.03836952703386,
			"strokeColor": "#000000",
			"backgroundColor": "#40c05788",
			"width": 77.00500621045215,
			"height": 77.00500621045215,
			"seed": 754733865,
			"groupIds": [
				"MJ7MHvmzQktFqpOhREFiD",
				"_0GSA8FC_Hf97ha098XI6",
				"2vAgNv5uguQdiPvxjc_Mm",
				"0VPXabRyHvx5USpcisuQv"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "mho87IY1hf8lsf8eW6JQf",
					"type": "arrow"
				},
				{
					"id": "Spp70b7fyqAkvG9EPNEOP",
					"type": "arrow"
				},
				{
					"id": "mGQoYPOtcKTVwhAh0a10s",
					"type": "arrow"
				},
				{
					"id": "2Oo76BubcRAu_baXDKw9b",
					"type": "arrow"
				}
			],
			"updated": 1684527982456,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1276,
			"versionNonce": 1901232200,
			"isDeleted": false,
			"id": "LLAgfDHflZGa2fOf2QgZe",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 32.92624983967153,
			"y": -110.94355107912088,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 46.27059743037148,
			"height": 12.724351334011057,
			"seed": 1845792743,
			"groupIds": [
				"2vAgNv5uguQdiPvxjc_Mm",
				"0VPXabRyHvx5USpcisuQv"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"id": "Spp70b7fyqAkvG9EPNEOP",
					"type": "arrow"
				}
			],
			"updated": 1684527982456,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1893,
			"versionNonce": 1665828920,
			"isDeleted": false,
			"id": "ktt3mmQT4ODM5vpn5T22M",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 33.34974399565681,
			"y": -103.9880252867672,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 45.312356259233844,
			"height": 47.90461342961858,
			"seed": 1312425481,
			"groupIds": [
				"2vAgNv5uguQdiPvxjc_Mm",
				"0VPXabRyHvx5USpcisuQv"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982456,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					4.549812335030859,
					38.03683035714891
				],
				[
					8.008408556039365,
					44.94917585577548
				],
				[
					24.07697787613011,
					47.90461342961858
				],
				[
					38.49877304202918,
					45.43612987959536
				],
				[
					41.84681488220727,
					37.79701082001888
				],
				[
					45.312356259233844,
					0.11556742577621781
				]
			]
		},
		{
			"type": "ellipse",
			"version": 1285,
			"versionNonce": 850081608,
			"isDeleted": false,
			"id": "fux9AIELpWhGCQnrUPiK0",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 53.19269803692032,
			"y": -91.84522258108791,
			"strokeColor": "#000000",
			"backgroundColor": "#000",
			"width": 5.558985761351276,
			"height": 5.558985761351276,
			"seed": 1322777351,
			"groupIds": [
				"2vAgNv5uguQdiPvxjc_Mm",
				"0VPXabRyHvx5USpcisuQv"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982456,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1971,
			"versionNonce": 171753784,
			"isDeleted": false,
			"id": "K8FaSXLBnlrAoo4V8Cvfh",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 56.13905798482756,
			"y": -88.80080674630653,
			"strokeColor": "#000000",
			"backgroundColor": "#000",
			"width": 27.506237081118297,
			"height": 13.643881491353264,
			"seed": 654204137,
			"groupIds": [
				"2vAgNv5uguQdiPvxjc_Mm",
				"0VPXabRyHvx5USpcisuQv"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982456,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.309678076627355,
					8.797623061958465
				],
				[
					20.120596402543086,
					13.643881491353264
				],
				[
					27.123784638182695,
					12.00240453242703
				],
				[
					27.506237081118297,
					6.969895706429148
				],
				[
					21.25375565923947,
					2.0778835202418438
				]
			]
		},
		{
			"type": "text",
			"version": 1789,
			"versionNonce": 1440026184,
			"isDeleted": false,
			"id": "VcYypKGK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -75.88813012242736,
			"y": -26.840490493415246,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 262.41973876953125,
			"height": 48,
			"seed": 340853287,
			"groupIds": [
				"0VPXabRyHvx5USpcisuQv"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982456,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "brightcell-nonprod-vmi-telcel\n",
			"rawText": "brightcell-nonprod-vmi-telcel\n",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "brightcell-nonprod-vmi-telcel\n",
			"lineHeight": 1.2,
			"baseline": 41
		},
		{
			"type": "text",
			"version": 547,
			"versionNonce": 1753209400,
			"isDeleted": false,
			"id": "jCIJmBpq",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -476.9639721138635,
			"y": -126.94830770743283,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 328.85968017578125,
			"height": 50,
			"seed": 376765871,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "mho87IY1hf8lsf8eW6JQf",
					"type": "arrow"
				}
			],
			"updated": 1684527982456,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Se carga archivo .txt en\ndirectorio 01_Ventas/unprocessed",
			"rawText": "Se carga archivo .txt en\ndirectorio 01_Ventas/unprocessed",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Se carga archivo .txt en\ndirectorio 01_Ventas/unprocessed",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "arrow",
			"version": 781,
			"versionNonce": 1135347016,
			"isDeleted": false,
			"id": "mho87IY1hf8lsf8eW6JQf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -138.10332773144646,
			"y": -92.61441993184383,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 151.12470102590652,
			"height": 5.095126125185331,
			"seed": 230571777,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982456,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "jCIJmBpq",
				"focus": 0.11314870186121179,
				"gap": 10.000964206635786
			},
			"endBinding": {
				"elementId": "xb4vbVEIcUkv8iliu2D12",
				"focus": 0.014001863631910898,
				"gap": 3.7978628626522095
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					151.12470102590652,
					5.095126125185331
				]
			]
		},
		{
			"type": "rectangle",
			"version": 2558,
			"versionNonce": 553112376,
			"isDeleted": false,
			"id": "EFz2SaLgOvIYm3lu1ZtfS",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 998.0943312080931,
			"y": -293.004310692178,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e1488",
			"width": 66.53246337764709,
			"height": 66.4687522713753,
			"seed": 1087403015,
			"groupIds": [
				"WMk1kKjaLybQC3qpdGK6r",
				"i_HnorpLcY6TDQ7Y-3iob",
				"cZLsjZvEM74C7b3SZAU1T"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "XRbLZ1Q9JGQhfMeRDLxqN",
					"type": "arrow"
				},
				{
					"id": "wYmgQbfUIrNplTI6rA_oe",
					"type": "arrow"
				}
			],
			"updated": 1684527982456,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1718,
			"versionNonce": 1770789960,
			"isDeleted": false,
			"id": "krTCiK1REoPBDrsy6L9Uj",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1023.8885737884849,
			"y": -265.40769788130865,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.927534089288194,
			"height": 27.761273291189447,
			"seed": 1235612649,
			"groupIds": [
				"nNYFR2lx8lJhzPFgYwCyg",
				"i_HnorpLcY6TDQ7Y-3iob",
				"cZLsjZvEM74C7b3SZAU1T"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982456,
			"link": null,
			"locked": false,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-13.139406210549344,
					26.284291394335074
				],
				[
					-0.5344982801113882,
					27.761273291189447
				],
				[
					6.788127878738849,
					13.604541147755066
				],
				[
					0.9281768125046468,
					0.5821228440432334
				]
			]
		},
		{
			"type": "line",
			"version": 1718,
			"versionNonce": 1510517816,
			"isDeleted": false,
			"id": "eViARpRcuKgmBPfJDFE0M",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1049.1621184766318,
			"y": -248.99988431436714,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 35.98406748383116,
			"height": 45.41383889698984,
			"seed": 47340327,
			"groupIds": [
				"nNYFR2lx8lJhzPFgYwCyg",
				"i_HnorpLcY6TDQ7Y-3iob",
				"cZLsjZvEM74C7b3SZAU1T"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982456,
			"link": null,
			"locked": false,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-15.440832486938739,
					-33.46174220546388
				],
				[
					-30.111781812525994,
					-34.06037917274238
				],
				[
					-31.147886161368394,
					-23.74008428340144
				],
				[
					-23.63304613581318,
					-22.70691944849492
				],
				[
					-8.119234229046612,
					10.756887022373363
				],
				[
					3.8083000780720977,
					11.35345972424746
				],
				[
					4.836181322462766,
					1.0321327022043147
				],
				[
					3.808300078072098,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 2067,
			"versionNonce": 693195592,
			"isDeleted": false,
			"id": "TJwsh39f",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 944.1620831087955,
			"y": -221.41266596029845,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 174.3872528076172,
			"height": 24.77118485290355,
			"seed": 242323145,
			"groupIds": [
				"cZLsjZvEM74C7b3SZAU1T"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "mGQoYPOtcKTVwhAh0a10s",
					"type": "arrow"
				}
			],
			"updated": 1684527982456,
			"link": null,
			"locked": false,
			"fontSize": 20.642654044086292,
			"fontFamily": 1,
			"text": "Verificar archivos",
			"rawText": "Verificar archivos",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Verificar archivos",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 1423,
			"versionNonce": 1301701944,
			"isDeleted": false,
			"id": "rYc3LTkXTAb5zXjHc92KP",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1668.1486223137113,
			"y": -302.4434359502802,
			"strokeColor": "#000000",
			"backgroundColor": "#e6498088",
			"width": 65.08084106445301,
			"height": 65.08084106445301,
			"seed": 1898935145,
			"groupIds": [
				"j_NYUDhed2jVe8cPLwyyY",
				"ew0I8l5VY8CZ4Wa6ULzem",
				"qcu2_PJVcBYMiImF88Tmt",
				"ccX9SOBBX3p4xaPuFUqKA",
				"_QLm-Fg4O6FLmI0tqfJct",
				"7Pn933FhloCYNUXB1jkPH"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "kErjRV0CX7K9A-kmvhn05",
					"type": "arrow"
				}
			],
			"updated": 1684527982456,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1190,
			"versionNonce": 1230481992,
			"isDeleted": false,
			"id": "_WCGAgt5xkeBRhbEXkhY4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1677.8331174178716,
			"y": -272.4813262064572,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.935660646660656,
			"height": 5.935660646660656,
			"seed": 306353063,
			"groupIds": [
				"QEMRVQIaxYW_GBXJCoknz",
				"_QLm-Fg4O6FLmI0tqfJct",
				"7Pn933FhloCYNUXB1jkPH"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982456,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1283,
			"versionNonce": 1493499448,
			"isDeleted": false,
			"id": "_8IdsbaHKLuHGbZa0TDLe",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1717.8906553289235,
			"y": -272.5320381250631,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.935660646660656,
			"height": 5.935660646660656,
			"seed": 396303945,
			"groupIds": [
				"QEMRVQIaxYW_GBXJCoknz",
				"_QLm-Fg4O6FLmI0tqfJct",
				"7Pn933FhloCYNUXB1jkPH"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982456,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1328,
			"versionNonce": 1685791048,
			"isDeleted": false,
			"id": "Ok4gm8z91XOafaZRF_dEO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1714.721539319387,
			"y": -283.14914084342854,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.935660646660656,
			"height": 5.935660646660656,
			"seed": 203392711,
			"groupIds": [
				"QEMRVQIaxYW_GBXJCoknz",
				"_QLm-Fg4O6FLmI0tqfJct",
				"7Pn933FhloCYNUXB1jkPH"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982456,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1402,
			"versionNonce": 221804344,
			"isDeleted": false,
			"id": "wEmyc3AedRb30t3TmR1M4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1714.7529013447465,
			"y": -260.8457513057847,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.935660646660656,
			"height": 5.935660646660656,
			"seed": 1821797673,
			"groupIds": [
				"QEMRVQIaxYW_GBXJCoknz",
				"_QLm-Fg4O6FLmI0tqfJct",
				"7Pn933FhloCYNUXB1jkPH"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982456,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1308,
			"versionNonce": 1511503944,
			"isDeleted": false,
			"id": "Tna_UzBw0x08B1LEyPRzG",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1702.4627838161914,
			"y": -269.4776502559462,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.738770407595338,
			"height": 0,
			"seed": 540087783,
			"groupIds": [
				"QEMRVQIaxYW_GBXJCoknz",
				"_QLm-Fg4O6FLmI0tqfJct",
				"7Pn933FhloCYNUXB1jkPH"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982456,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.738770407595338,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1230,
			"versionNonce": 1049940024,
			"isDeleted": false,
			"id": "ZsqUWYRUncvgFmFXvb5iA",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1710.3591296534255,
			"y": -280.5992857102374,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 23.436189350564298,
			"seed": 125886473,
			"groupIds": [
				"QEMRVQIaxYW_GBXJCoknz",
				"_QLm-Fg4O6FLmI0tqfJct",
				"7Pn933FhloCYNUXB1jkPH"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982456,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					23.436189350564298
				]
			]
		},
		{
			"type": "line",
			"version": 1178,
			"versionNonce": 1040805704,
			"isDeleted": false,
			"id": "7FeZAguCbSJJwMM6vVUwK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1714.8978331940111,
			"y": -280.0836609607727,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.278540805703472,
			"height": 0,
			"seed": 1434697991,
			"groupIds": [
				"QEMRVQIaxYW_GBXJCoknz",
				"_QLm-Fg4O6FLmI0tqfJct",
				"7Pn933FhloCYNUXB1jkPH"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982456,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-4.278540805703472,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1190,
			"versionNonce": 352192824,
			"isDeleted": false,
			"id": "0vwoK0xaaHvVSwpEoixWu",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1714.8637898609372,
			"y": -257.64629351691565,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.278540805703472,
			"height": 0,
			"seed": 106559209,
			"groupIds": [
				"QEMRVQIaxYW_GBXJCoknz",
				"_QLm-Fg4O6FLmI0tqfJct",
				"7Pn933FhloCYNUXB1jkPH"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982456,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-4.278540805703472,
					0
				]
			]
		},
		{
			"type": "ellipse",
			"version": 1360,
			"versionNonce": 1219249736,
			"isDeleted": false,
			"id": "rPQgs3-dnKTrNllT433O-",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1689.4049037549375,
			"y": -277.579033614772,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13.538770570677526,
			"height": 4.283701206606613,
			"seed": 496240679,
			"groupIds": [
				"QEMRVQIaxYW_GBXJCoknz",
				"_QLm-Fg4O6FLmI0tqfJct",
				"7Pn933FhloCYNUXB1jkPH"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982456,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1495,
			"versionNonce": 467149368,
			"isDeleted": false,
			"id": "SlxLhQR6feaxYFZS-MRCw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1689.785821852798,
			"y": -274.7165328712231,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13.305408215826999,
			"height": 14.770218853011942,
			"seed": 1001206217,
			"groupIds": [
				"QEMRVQIaxYW_GBXJCoknz",
				"_QLm-Fg4O6FLmI0tqfJct",
				"7Pn933FhloCYNUXB1jkPH"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982456,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					4.688101705919888,
					7.0636621077687
				],
				[
					5.038452745833733,
					14.469005137499659
				],
				[
					7.963010128189474,
					13.59224095725204
				],
				[
					7.77908861177286,
					7.2105948482906355
				],
				[
					13.305408215826999,
					-0.3012137155122835
				]
			]
		},
		{
			"type": "line",
			"version": 1367,
			"versionNonce": 1188838728,
			"isDeleted": false,
			"id": "if-NDI21vuJi6z8VY_OB0",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1683.8626396443215,
			"y": -269.5780127421858,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.229181632062791,
			"height": 0,
			"seed": 105802567,
			"groupIds": [
				"QEMRVQIaxYW_GBXJCoknz",
				"_QLm-Fg4O6FLmI0tqfJct",
				"7Pn933FhloCYNUXB1jkPH"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982456,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.229181632062791,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1336,
			"versionNonce": 1376197432,
			"isDeleted": false,
			"id": "ZGpy5B7zcu-RmWS3zrida",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1681.021417846869,
			"y": -272.48397167908934,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 32.796640923919526,
			"height": 16.800743224146107,
			"seed": 479596713,
			"groupIds": [
				"QEMRVQIaxYW_GBXJCoknz",
				"_QLm-Fg4O6FLmI0tqfJct",
				"7Pn933FhloCYNUXB1jkPH"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982456,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.4117224647799933,
					-7.051918350830839
				],
				[
					7.475357337832827,
					-12.342294469851296
				],
				[
					13.06488265893112,
					-15.410926786229332
				],
				[
					20.229570868044398,
					-16.80074322414611
				],
				[
					28.177455992818626,
					-14.866518029758048
				],
				[
					32.796640923919526,
					-11.551977965492881
				]
			]
		},
		{
			"type": "line",
			"version": 1471,
			"versionNonce": 167072840,
			"isDeleted": false,
			"id": "4BE-zTq_9OA3CxrTHTGAJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1680.6081241713478,
			"y": -266.4110647554453,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.72406610309211,
			"height": 17.27583554628456,
			"seed": 739207783,
			"groupIds": [
				"QEMRVQIaxYW_GBXJCoknz",
				"_QLm-Fg4O6FLmI0tqfJct",
				"7Pn933FhloCYNUXB1jkPH"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982457,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.4799212825858095,
					7.251332877922252
				],
				[
					7.6867458954141155,
					12.691310537888764
				],
				[
					13.434332114713367,
					15.846717804251234
				],
				[
					20.801623763046752,
					17.27583554628456
				],
				[
					28.974259611621815,
					15.286914227630959
				],
				[
					33.72406610309211,
					11.878645420836776
				]
			]
		},
		{
			"type": "text",
			"version": 1640,
			"versionNonce": 971961400,
			"isDeleted": false,
			"id": "xfD1TC0c",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1581.6890428459378,
			"y": -232.98013362707115,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 226.73977661132812,
			"height": 48,
			"seed": 1858081673,
			"groupIds": [
				"7Pn933FhloCYNUXB1jkPH"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "kErjRV0CX7K9A-kmvhn05",
					"type": "arrow"
				}
			],
			"updated": 1684527982457,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Notificación de proceso\nfallido",
			"rawText": "Notificación de proceso\nfallido",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Notificación de proceso\nfallido",
			"lineHeight": 1.2,
			"baseline": 41
		},
		{
			"type": "rectangle",
			"version": 1168,
			"versionNonce": 1473481544,
			"isDeleted": false,
			"id": "9Mj3UxQ3ScH340WCWmMPT",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 339.79145962014286,
			"y": -292.9793540277908,
			"strokeColor": "#000000",
			"backgroundColor": "#e6498088",
			"width": 64.70089111328099,
			"height": 64.70089111328099,
			"seed": 1932782313,
			"groupIds": [
				"mNBoU50NhVZUSSannxXu6",
				"LdSnnFjBgW9wDp5eSRQEs"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "Spp70b7fyqAkvG9EPNEOP",
					"type": "arrow"
				},
				{
					"id": "XRbLZ1Q9JGQhfMeRDLxqN",
					"type": "arrow"
				}
			],
			"updated": 1684527982457,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1378,
			"versionNonce": 1769188664,
			"isDeleted": false,
			"id": "k70CqQ-syehzz0FsmKSK5",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 357.941579925817,
			"y": -260.3973198617084,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.0965264804551,
			"height": 25.394020168765657,
			"seed": 2055427111,
			"groupIds": [
				"m1PqCgsdHqTIXXjUaVumI",
				"mNBoU50NhVZUSSannxXu6",
				"LdSnnFjBgW9wDp5eSRQEs"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982457,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.263070773388013,
					-12.655407976268592
				],
				[
					21.749092160923496,
					-12.570519846452996
				],
				[
					29.0965264804551,
					0.07090797495479251
				],
				[
					21.970571387274813,
					12.415835859067506
				],
				[
					7.3574223926479565,
					12.738612192497058
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "ellipse",
			"version": 1162,
			"versionNonce": 1523769928,
			"isDeleted": false,
			"id": "ZG_G7oExu0HE5Dvzj1An2",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 357.6749497828098,
			"y": -283.58439816161376,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.527048406442323,
			"height": 6.527048406442323,
			"seed": 1630053833,
			"groupIds": [
				"m1PqCgsdHqTIXXjUaVumI",
				"mNBoU50NhVZUSSannxXu6",
				"LdSnnFjBgW9wDp5eSRQEs"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982457,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1223,
			"versionNonce": 435766840,
			"isDeleted": false,
			"id": "kcdiIB6yJmSfCCf_Li3dE",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 362.7601012789944,
			"y": -277.42558913254175,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.4300394358401154,
			"height": 4.165241568829386,
			"seed": 527710023,
			"groupIds": [
				"m1PqCgsdHqTIXXjUaVumI",
				"mNBoU50NhVZUSSannxXu6",
				"LdSnnFjBgW9wDp5eSRQEs"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982457,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.4300394358401154,
					4.165241568829386
				]
			]
		},
		{
			"type": "ellipse",
			"version": 1284,
			"versionNonce": 298801480,
			"isDeleted": false,
			"id": "IvnSqMFojgICBX4Y4oWYm",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.141592653589793,
			"x": 380.7527468121482,
			"y": -244.20046718712933,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.527048406442323,
			"height": 6.527048406442323,
			"seed": 1786971305,
			"groupIds": [
				"m1PqCgsdHqTIXXjUaVumI",
				"mNBoU50NhVZUSSannxXu6",
				"LdSnnFjBgW9wDp5eSRQEs"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982457,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1352,
			"versionNonce": 946061112,
			"isDeleted": false,
			"id": "8HWS-Pc9y4w4ALyvz30VL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.141592653589793,
			"x": 379.76460428656424,
			"y": -247.99746937858822,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.4300394358401154,
			"height": 4.165241568829386,
			"seed": 916174439,
			"groupIds": [
				"m1PqCgsdHqTIXXjUaVumI",
				"mNBoU50NhVZUSSannxXu6",
				"LdSnnFjBgW9wDp5eSRQEs"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982457,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.4300394358401154,
					4.165241568829386
				]
			]
		},
		{
			"type": "ellipse",
			"version": 1295,
			"versionNonce": 1076162632,
			"isDeleted": false,
			"id": "t5iH4pNNsNOzxAP7XXjJW",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 386.3807138859336,
			"y": -274.02210075977314,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.527048406442323,
			"height": 6.527048406442323,
			"seed": 1525581705,
			"groupIds": [
				"m1PqCgsdHqTIXXjUaVumI",
				"mNBoU50NhVZUSSannxXu6",
				"LdSnnFjBgW9wDp5eSRQEs"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982457,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1383,
			"versionNonce": 1964447800,
			"isDeleted": false,
			"id": "lHDcpJcH6KWu8N7ZVXc8H",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 351.6051127674393,
			"y": -253.61916898895265,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.527048406442323,
			"height": 6.527048406442323,
			"seed": 1992708487,
			"groupIds": [
				"m1PqCgsdHqTIXXjUaVumI",
				"mNBoU50NhVZUSSannxXu6",
				"LdSnnFjBgW9wDp5eSRQEs"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982457,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1189,
			"versionNonce": 1571792712,
			"isDeleted": false,
			"id": "EFP_JQ3wT_X-gZZUVXtTh",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 372.5621570252399,
			"y": -279.1875660161538,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14.881064367630502,
			"height": 5.819316836931806,
			"seed": 2091298409,
			"groupIds": [
				"m1PqCgsdHqTIXXjUaVumI",
				"mNBoU50NhVZUSSannxXu6",
				"LdSnnFjBgW9wDp5eSRQEs"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982457,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.971069476124091,
					-0.03892935430490446
				],
				[
					14.881064367630502,
					5.780387482626902
				]
			]
		},
		{
			"type": "line",
			"version": 1177,
			"versionNonce": 1408717112,
			"isDeleted": false,
			"id": "ciXFyRtQSmmTTiIfi1fEd",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 389.3581616294234,
			"y": -250.59334938506004,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.359881211089217,
			"height": 17.609098804231238,
			"seed": 154175655,
			"groupIds": [
				"m1PqCgsdHqTIXXjUaVumI",
				"mNBoU50NhVZUSSannxXu6",
				"LdSnnFjBgW9wDp5eSRQEs"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982457,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.359881211089217,
					-9.699887830271365
				],
				[
					1.5123117765600742,
					-17.609098804231238
				]
			]
		},
		{
			"type": "line",
			"version": 1362,
			"versionNonce": 113999432,
			"isDeleted": false,
			"id": "DbVEnG8t0usigKOlzbjkB",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.141592653589793,
			"x": 356.84058896069587,
			"y": -247.70371432535762,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14.881064367630502,
			"height": 5.819316836931806,
			"seed": 1182202185,
			"groupIds": [
				"m1PqCgsdHqTIXXjUaVumI",
				"mNBoU50NhVZUSSannxXu6",
				"LdSnnFjBgW9wDp5eSRQEs"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982457,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.971069476124091,
					-0.03892935430490446
				],
				[
					14.881064367630502,
					5.780387482626902
				]
			]
		},
		{
			"type": "line",
			"version": 1347,
			"versionNonce": 1013475896,
			"isDeleted": false,
			"id": "WviTbWrgSh249Kt50lTxu",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.141592653589793,
			"x": 349.56576751305397,
			"y": -252.94737402389796,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.359881211089217,
			"height": 17.609098804231238,
			"seed": 998693831,
			"groupIds": [
				"m1PqCgsdHqTIXXjUaVumI",
				"mNBoU50NhVZUSSannxXu6",
				"LdSnnFjBgW9wDp5eSRQEs"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982457,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					5.359881211089217,
					-9.699887830271365
				],
				[
					1.5123117765600742,
					-17.609098804231238
				]
			]
		},
		{
			"type": "text",
			"version": 2101,
			"versionNonce": 1817474376,
			"isDeleted": false,
			"id": "s0LTdJgH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 338.5863496212278,
			"y": -224.72992983527433,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.59994506835938,
			"height": 24,
			"seed": 1236985897,
			"groupIds": [
				"LdSnnFjBgW9wDp5eSRQEs"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982457,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Evento",
			"rawText": "Evento",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Evento",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "arrow",
			"version": 416,
			"versionNonce": 156132152,
			"isDeleted": false,
			"id": "Spp70b7fyqAkvG9EPNEOP",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 59.466591186136384,
			"y": -136.20653215459743,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 269.920864358214,
			"height": 122.12031145528226,
			"seed": 1347002703,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982457,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "xb4vbVEIcUkv8iliu2D12",
				"focus": -0.3386597489482006,
				"gap": 12.168162627563675
			},
			"endBinding": {
				"elementId": "9Mj3UxQ3ScH340WCWmMPT",
				"focus": -0.010561273127972315,
				"gap": 10.404004075792443
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					51.22245165980121,
					-112.17191930074523
				],
				[
					269.920864358214,
					-122.12031145528226
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1890,
			"versionNonce": 1134988360,
			"isDeleted": false,
			"id": "_poJPXOiUEUGhjRtUQIA9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 435.3843690458109,
			"y": -516.3820823978094,
			"strokeColor": "#e64980",
			"backgroundColor": "transparent",
			"width": 1530.1490301399365,
			"height": 2493.440136686889,
			"seed": 1073359495,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982457,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1621,
			"versionNonce": 420297784,
			"isDeleted": false,
			"id": "M4NbASTG2WEKvWO5e4yxT",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 713.6349967923982,
			"y": -493.45078245325647,
			"strokeColor": "#e64980",
			"backgroundColor": "#e6498088",
			"width": 113.8653583445497,
			"height": 113.8653583445497,
			"seed": 1259971911,
			"groupIds": [
				"w-BqDMdS69a7SySl-xgJT",
				"WcWmEuguE9l4VQ5NiALWH",
				"Iy9w9QS_9MxyBKCggztp2"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982457,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1121,
			"versionNonce": 916308808,
			"isDeleted": false,
			"id": "GsvUFkabBS0hnFkEVqzrr",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 764.5583149539655,
			"y": -479.58906389605033,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.131091700161791,
			"height": 10.131091700161791,
			"seed": 1219720873,
			"groupIds": [
				"mB5lj4M4Dqqmdg2isBeTw",
				"WcWmEuguE9l4VQ5NiALWH",
				"Iy9w9QS_9MxyBKCggztp2"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982457,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1228,
			"versionNonce": 1569256760,
			"isDeleted": false,
			"id": "M74EQYSHORTIAyX-StypU",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 764.6636641466137,
			"y": -403.5782343660752,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.131091700161791,
			"height": 10.131091700161791,
			"seed": 1734567015,
			"groupIds": [
				"mB5lj4M4Dqqmdg2isBeTw",
				"WcWmEuguE9l4VQ5NiALWH",
				"Iy9w9QS_9MxyBKCggztp2"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982457,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1087,
			"versionNonce": 1402346056,
			"isDeleted": false,
			"id": "g87sRy-His_CTBjWPCGP5",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 725.4947339288467,
			"y": -452.6096706639877,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.37948548155744,
			"height": 10.986936652204236,
			"seed": 1044429193,
			"groupIds": [
				"mB5lj4M4Dqqmdg2isBeTw",
				"WcWmEuguE9l4VQ5NiALWH",
				"Iy9w9QS_9MxyBKCggztp2"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982458,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1136,
			"versionNonce": 1814400568,
			"isDeleted": false,
			"id": "soB4Cj8WMndujj-S5rxr9",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 725.640439457967,
			"y": -431.1221935912339,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.37948548155744,
			"height": 10.986936652204236,
			"seed": 1315454855,
			"groupIds": [
				"mB5lj4M4Dqqmdg2isBeTw",
				"WcWmEuguE9l4VQ5NiALWH",
				"Iy9w9QS_9MxyBKCggztp2"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982458,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1204,
			"versionNonce": 2104201544,
			"isDeleted": false,
			"id": "Le0dzDs_mnxrEeHXfy9Bu",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 782.2611325189444,
			"y": -443.5903729167329,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.37948548155744,
			"height": 14.914612147334124,
			"seed": 1524801641,
			"groupIds": [
				"mB5lj4M4Dqqmdg2isBeTw",
				"WcWmEuguE9l4VQ5NiALWH",
				"Iy9w9QS_9MxyBKCggztp2"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982458,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1107,
			"versionNonce": 231147320,
			"isDeleted": false,
			"id": "-r4EwLh_j3EDAH5e8btv3",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 742.6572864881584,
			"y": -440.69626216839595,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.917422766232455,
			"seed": 845461159,
			"groupIds": [
				"mB5lj4M4Dqqmdg2isBeTw",
				"WcWmEuguE9l4VQ5NiALWH",
				"Iy9w9QS_9MxyBKCggztp2"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982458,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					8.917422766232455
				]
			]
		},
		{
			"type": "line",
			"version": 1154,
			"versionNonce": 1534732360,
			"isDeleted": false,
			"id": "IbOs-tqPNWm3IX8532RJZ",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 742.8893321205016,
			"y": -460.05962871402687,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 57.71378835781129,
			"height": 0,
			"seed": 476359497,
			"groupIds": [
				"mB5lj4M4Dqqmdg2isBeTw",
				"WcWmEuguE9l4VQ5NiALWH",
				"Iy9w9QS_9MxyBKCggztp2"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982458,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					57.71378835781129,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1169,
			"versionNonce": 1322344504,
			"isDeleted": false,
			"id": "__jcg4Ys7YXNWjivti6NQ",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 741.8646906814895,
			"y": -461.7568636520881,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.917422766232455,
			"seed": 1241860551,
			"groupIds": [
				"mB5lj4M4Dqqmdg2isBeTw",
				"WcWmEuguE9l4VQ5NiALWH",
				"Iy9w9QS_9MxyBKCggztp2"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982458,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					8.917422766232455
				]
			]
		},
		{
			"type": "line",
			"version": 1271,
			"versionNonce": 1235083080,
			"isDeleted": false,
			"id": "RC-F3wf5glHlYrSKz4wGh",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 799.0381717618723,
			"y": -460.41983378581597,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 10.488988336663578,
			"seed": 992107049,
			"groupIds": [
				"mB5lj4M4Dqqmdg2isBeTw",
				"WcWmEuguE9l4VQ5NiALWH",
				"Iy9w9QS_9MxyBKCggztp2"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982458,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					10.488988336663578
				]
			]
		},
		{
			"type": "line",
			"version": 1319,
			"versionNonce": 254318904,
			"isDeleted": false,
			"id": "K9-AlavwTC0ZSqxxOUBBE",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 769.6563228863008,
			"y": -468.57776813272255,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.010963966968777,
			"seed": 1114011879,
			"groupIds": [
				"mB5lj4M4Dqqmdg2isBeTw",
				"WcWmEuguE9l4VQ5NiALWH",
				"Iy9w9QS_9MxyBKCggztp2"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982458,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					8.010963966968777
				]
			]
		},
		{
			"type": "line",
			"version": 1189,
			"versionNonce": 1211283016,
			"isDeleted": false,
			"id": "UoYBLK1nawnKBrp-ph_tI",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 742.9253608838851,
			"y": -411.8587040246874,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 57.71378835781129,
			"height": 0,
			"seed": 1476865289,
			"groupIds": [
				"mB5lj4M4Dqqmdg2isBeTw",
				"WcWmEuguE9l4VQ5NiALWH",
				"Iy9w9QS_9MxyBKCggztp2"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982458,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					57.71378835781129,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1362,
			"versionNonce": 305181240,
			"isDeleted": false,
			"id": "xBpYzh-uuThmPyJHC9TY-",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 769.6923516496906,
			"y": -413.30052694554286,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.480946860464432,
			"seed": 1897186311,
			"groupIds": [
				"mB5lj4M4Dqqmdg2isBeTw",
				"WcWmEuguE9l4VQ5NiALWH",
				"Iy9w9QS_9MxyBKCggztp2"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982458,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					8.480946860464432
				]
			]
		},
		{
			"type": "line",
			"version": 1204,
			"versionNonce": 1813294408,
			"isDeleted": false,
			"id": "NbN4_A1v25ddQQ8eIsk9P",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 742.830098793878,
			"y": -419.19713063480947,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.917422766232455,
			"seed": 1787732969,
			"groupIds": [
				"mB5lj4M4Dqqmdg2isBeTw",
				"WcWmEuguE9l4VQ5NiALWH",
				"Iy9w9QS_9MxyBKCggztp2"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982458,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					8.917422766232455
				]
			]
		},
		{
			"type": "line",
			"version": 1362,
			"versionNonce": 248359736,
			"isDeleted": false,
			"id": "K3A8GYY_jtYuRBxyBUkW0",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 798.9641644494152,
			"y": -421.1868400304942,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 10.488988336663578,
			"seed": 1175235367,
			"groupIds": [
				"mB5lj4M4Dqqmdg2isBeTw",
				"WcWmEuguE9l4VQ5NiALWH",
				"Iy9w9QS_9MxyBKCggztp2"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982458,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					10.488988336663578
				]
			]
		},
		{
			"type": "text",
			"version": 1943,
			"versionNonce": 1319093320,
			"isDeleted": false,
			"id": "fo09fZfB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 852.5185317452813,
			"y": -469.55718940376244,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 494.27984619140625,
			"height": 43.199999999999996,
			"seed": 1017614857,
			"groupIds": [
				"dEjGJ3LtzjhynrUUTAvjo",
				"Iy9w9QS_9MxyBKCggztp2"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982458,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "AWS Step Functions: Ventas",
			"rawText": "AWS Step Functions: Ventas",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "AWS Step Functions: Ventas",
			"lineHeight": 1.2,
			"baseline": 31
		},
		{
			"type": "arrow",
			"version": 138,
			"versionNonce": 1063486520,
			"isDeleted": false,
			"id": "XRbLZ1Q9JGQhfMeRDLxqN",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 412.32694879963253,
			"y": -262.82177165020425,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 582.857142857143,
			"height": 1.6019977164648935,
			"seed": 1359218369,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982458,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "9Mj3UxQ3ScH340WCWmMPT",
				"focus": -0.07067718538808795,
				"gap": 7.8345980662086845
			},
			"endBinding": {
				"elementId": "EFz2SaLgOvIYm3lu1ZtfS",
				"focus": 0.040521369332291654,
				"gap": 2.910239551317545
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					582.857142857143,
					1.6019977164648935
				]
			]
		},
		{
			"type": "diamond",
			"version": 287,
			"versionNonce": 2108685128,
			"isDeleted": false,
			"id": "N_JClFVE8mGmoNHHXVStX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1239.1840916567758,
			"y": -345.4429366777231,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 180,
			"height": 164,
			"seed": 1679808769,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "yL8muwpx"
				},
				{
					"id": "wYmgQbfUIrNplTI6rA_oe",
					"type": "arrow"
				},
				{
					"id": "kErjRV0CX7K9A-kmvhn05",
					"type": "arrow"
				}
			],
			"updated": 1684527982458,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 259,
			"versionNonce": 1909865784,
			"isDeleted": false,
			"id": "yL8muwpx",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1290.576112835975,
			"y": -293.4429366777231,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 77.21595764160156,
			"height": 60,
			"seed": 1620544207,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982458,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "El archivo\nes \ncorrecto?",
			"rawText": "El archivo es correcto?",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "N_JClFVE8mGmoNHHXVStX",
			"originalText": "El archivo es correcto?",
			"lineHeight": 1.25,
			"baseline": 54
		},
		{
			"type": "arrow",
			"version": 191,
			"versionNonce": 1805734472,
			"isDeleted": false,
			"id": "wYmgQbfUIrNplTI6rA_oe",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1075.1840916567758,
			"y": -257.50748510872864,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 164.89158360037845,
			"height": 3.7702992881851856,
			"seed": 485934383,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982458,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "EFz2SaLgOvIYm3lu1ZtfS",
				"gap": 10.557297071035578,
				"focus": 0.09602843741616263
			},
			"endBinding": {
				"elementId": "N_JClFVE8mGmoNHHXVStX",
				"gap": 1,
				"focus": -0.0015568240788790867
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					164.89158360037845,
					-3.7702992881851856
				]
			]
		},
		{
			"type": "arrow",
			"version": 404,
			"versionNonce": 394909240,
			"isDeleted": false,
			"id": "kErjRV0CX7K9A-kmvhn05",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1423.112984130133,
			"y": -263.06260814673584,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 235.6211558299117,
			"height": 2.010868945114737,
			"seed": 45550529,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "ekqXatZ1"
				}
			],
			"updated": 1684527982458,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "N_JClFVE8mGmoNHHXVStX",
				"gap": 3.9472580177495473,
				"focus": 0.014414009683752425
			},
			"endBinding": {
				"elementId": "rYc3LTkXTAb5zXjHc92KP",
				"gap": 9.414482353666472,
				"focus": -0.13625033252131918
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					235.6211558299117,
					-2.010868945114737
				]
			]
		},
		{
			"type": "text",
			"version": 13,
			"versionNonce": 1599064392,
			"isDeleted": false,
			"id": "ekqXatZ1",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1528.9435739469445,
			"y": -276.56804261929324,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.959976196289062,
			"height": 25,
			"seed": 648642977,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982458,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "No",
			"rawText": "No",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "kErjRV0CX7K9A-kmvhn05",
			"originalText": "No",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 235,
			"versionNonce": 1432506168,
			"isDeleted": false,
			"id": "mGQoYPOtcKTVwhAh0a10s",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1033.1840916567755,
			"y": -183.4429366777233,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 928.0000000000005,
			"height": 72,
			"seed": 349728975,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982459,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "TJwsh39f",
				"focus": -0.4267135634643302,
				"gap": 13.198544429671585
			},
			"endBinding": {
				"elementId": "xb4vbVEIcUkv8iliu2D12",
				"focus": -0.6679961068961596,
				"gap": 11.35984928921063
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-122,
					70
				],
				[
					-928.0000000000005,
					72
				]
			]
		},
		{
			"type": "rectangle",
			"version": 2712,
			"versionNonce": 1679253576,
			"isDeleted": false,
			"id": "JjZQZYaiWv0MObZYneEBe",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1295.4939160123126,
			"y": -19.1701014383936,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e1488",
			"width": 78.38545166430555,
			"height": 78.3103902042661,
			"seed": 1087403015,
			"groupIds": [
				"b0iSUE-4tpRbvwnH1dvnk",
				"AUfnLjry7MTnnv-A7eADm",
				"2qqUCBQQd0wHiKId04jah"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "-hA7Plyvo9UyMsEDt-4He",
					"type": "arrow"
				},
				{
					"id": "2Oo76BubcRAu_baXDKw9b",
					"type": "arrow"
				},
				{
					"id": "KFJ_KhaJ820XNwywI0AOg",
					"type": "arrow"
				}
			],
			"updated": 1684527982459,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1865,
			"versionNonce": 331589688,
			"isDeleted": false,
			"id": "b9_gC12xIr0irRstwtDZb",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1325.8834920532017,
			"y": 13.342943318517023,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.47769315677398,
			"height": 32.70704007086569,
			"seed": 1235612649,
			"groupIds": [
				"sQoxWxRjd3DfG2Mw0hdCw",
				"AUfnLjry7MTnnv-A7eADm",
				"2qqUCBQQd0wHiKId04jah"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982459,
			"link": null,
			"locked": false,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-15.480236836694672,
					30.966928744643113
				],
				[
					-0.6297209959371768,
					32.70704007086569
				],
				[
					7.99745632007931,
					16.028237170468103
				],
				[
					1.0935347194277472,
					0.6858300405237853
				]
			]
		},
		{
			"type": "line",
			"version": 1866,
			"versionNonce": 970200904,
			"isDeleted": false,
			"id": "98q6sohh0xaTluysDmQsm",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1355.6596060728127,
			"y": 32.673865577748046,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 42.39475346687077,
			"height": 53.50447124653642,
			"seed": 47340327,
			"groupIds": [
				"sQoxWxRjd3DfG2Mw0hdCw",
				"AUfnLjry7MTnnv-A7eADm",
				"2qqUCBQQd0wHiKId04jah"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982459,
			"link": null,
			"locked": false,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-18.19167015794296,
					-39.423067223016155
				],
				[
					-35.47629980862651,
					-40.128353434902316
				],
				[
					-36.69698972798771,
					-27.969462344126914
				],
				[
					-27.843354980622397,
					-26.75223562326821
				],
				[
					-9.56570386699269,
					12.673263621168235
				],
				[
					4.486761898450669,
					13.376117811634105
				],
				[
					5.697763738883055,
					1.2160107101485553
				],
				[
					4.48676189845067,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 2238,
			"versionNonce": 244441400,
			"isDeleted": false,
			"id": "U5r3kjCm",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1261.9364017182381,
			"y": 65.1758422229117,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 145.50643920898438,
			"height": 58.36851408713064,
			"seed": 242323145,
			"groupIds": [
				"2qqUCBQQd0wHiKId04jah"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "5iBJS1QwKdhkk2GG8Bg7Q",
					"type": "arrow"
				}
			],
			"updated": 1684527982459,
			"link": null,
			"locked": false,
			"fontSize": 24.3202142029711,
			"fontFamily": 1,
			"text": "Descomprimir\narchivos",
			"rawText": "Descomprimir\narchivos",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Descomprimir\narchivos",
			"lineHeight": 1.2,
			"baseline": 50
		},
		{
			"type": "arrow",
			"version": 79,
			"versionNonce": 1155657288,
			"isDeleted": false,
			"id": "-hA7Plyvo9UyMsEDt-4He",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1327.6577294089577,
			"y": -187.2575001654758,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 4,
			"height": 166,
			"seed": 387920239,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "cL3LeKGS"
				}
			],
			"updated": 1684527982459,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "JjZQZYaiWv0MObZYneEBe",
				"focus": -0.05070519259646928,
				"gap": 2.0873987270821885
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					4,
					166
				]
			]
		},
		{
			"type": "text",
			"version": 14,
			"versionNonce": 1697708600,
			"isDeleted": false,
			"id": "cL3LeKGS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1321.3877403952858,
			"y": -116.75750016547579,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.53997802734375,
			"height": 25,
			"seed": 1402939681,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982459,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Si",
			"rawText": "Si",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "-hA7Plyvo9UyMsEDt-4He",
			"originalText": "Si",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 325,
			"versionNonce": 2115822920,
			"isDeleted": false,
			"id": "2Oo76BubcRAu_baXDKw9b",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1293.6577294089577,
			"y": 0.7424998345242102,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1182,
			"height": 82,
			"seed": 430586081,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982459,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "JjZQZYaiWv0MObZYneEBe",
				"focus": 0.1552432221464655,
				"gap": 1.8361866033549177
			},
			"endBinding": {
				"elementId": "xb4vbVEIcUkv8iliu2D12",
				"focus": 0.1008071858785256,
				"gap": 17.83348704139327
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-272,
					-76.00000000000011
				],
				[
					-1182,
					-82
				]
			]
		},
		{
			"type": "arrow",
			"version": 117,
			"versionNonce": 713356088,
			"isDeleted": false,
			"id": "KFJ_KhaJ820XNwywI0AOg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1293.6577294089577,
			"y": 26.742499834524097,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1180,
			"height": 84,
			"seed": 453207009,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982459,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "JjZQZYaiWv0MObZYneEBe",
				"focus": -0.230732281615823,
				"gap": 1.8361866033549177
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-1180,
					-84
				]
			]
		},
		{
			"type": "text",
			"version": 2317,
			"versionNonce": 1658911816,
			"isDeleted": false,
			"id": "v2Ri6ovP",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1172.918987004444,
			"y": 356.4932457820138,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 293.13970947265625,
			"height": 24,
			"seed": 1245685479,
			"groupIds": [
				"_UtR1IAAJCNM7WZjbt35x"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "wgLkYPMPQUsu7wE7qRt_l",
					"type": "arrow"
				}
			],
			"updated": 1684527982459,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Brightcell-VMI-load-sales-files",
			"rawText": "Brightcell-VMI-load-sales-files",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Brightcell-VMI-load-sales-files",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4288,
			"versionNonce": 1962003512,
			"isDeleted": false,
			"id": "BQy8GYGReVqgKKtwWqSjt",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1279.0474642311722,
			"y": 234.26420345918189,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 107.76604983800789,
			"height": 107.66285368525563,
			"seed": 941612809,
			"groupIds": [
				"rovomrS4tRjFuf3TRB9nn",
				"JJPlRiGuWaWt3AlX4b2SZ",
				"c38zSZqm7m6q2YEveOWu3",
				"FVclUHDu7Je4LwiYpMKCp",
				"_UtR1IAAJCNM7WZjbt35x"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "5iBJS1QwKdhkk2GG8Bg7Q",
					"type": "arrow"
				},
				{
					"id": "54nUHnhbokMduGOiani60",
					"type": "arrow"
				}
			],
			"updated": 1684527982459,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2145,
			"versionNonce": 1695167304,
			"isDeleted": false,
			"id": "-cODEIGETuKt96uMaoXOh",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1337.7262490492215,
			"y": 303.96287063674424,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 17.21171637693966,
			"height": 30.981089478491384,
			"seed": 1100493319,
			"groupIds": [
				"2SwZ4dmhq8NCnqanV1Ayc",
				"FVclUHDu7Je4LwiYpMKCp",
				"_UtR1IAAJCNM7WZjbt35x"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982459,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.4302929094234964,
					-5.5938078225054255
				],
				[
					16.781423467516163,
					-30.981089478491384
				]
			]
		},
		{
			"type": "line",
			"version": 2225,
			"versionNonce": 1851491640,
			"isDeleted": false,
			"id": "s9-JzN1C6hjrbd5rSAwiC",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1328.6470686603839,
			"y": 303.96287063674424,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 17.21171637693966,
			"height": 30.981089478491384,
			"seed": 1757484521,
			"groupIds": [
				"2SwZ4dmhq8NCnqanV1Ayc",
				"FVclUHDu7Je4LwiYpMKCp",
				"_UtR1IAAJCNM7WZjbt35x"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982459,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.4302929094234877,
					-5.5938078225054255
				],
				[
					-16.781423467516174,
					-30.981089478491384
				]
			]
		},
		{
			"type": "line",
			"version": 2025,
			"versionNonce": 1525975624,
			"isDeleted": false,
			"id": "LEdQbebRGsLNBSQmr3o0Z",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1329.1203908607513,
			"y": 304.3931635461603,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 7.745272369622733,
			"height": 0,
			"seed": 1341282599,
			"groupIds": [
				"2SwZ4dmhq8NCnqanV1Ayc",
				"FVclUHDu7Je4LwiYpMKCp",
				"_UtR1IAAJCNM7WZjbt35x"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982459,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.745272369622733,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 2139,
			"versionNonce": 1680219704,
			"isDeleted": false,
			"id": "EjQ7g2gom4QUy4F8ofPPr",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1312.7692603026585,
			"y": 272.4310062341842,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 42.168705123502164,
			"height": 7.314979460199344,
			"seed": 567832777,
			"groupIds": [
				"2SwZ4dmhq8NCnqanV1Ayc",
				"FVclUHDu7Je4LwiYpMKCp",
				"_UtR1IAAJCNM7WZjbt35x"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982459,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.175565279046335,
					3.8726361848114155
				],
				[
					19.793473833480647,
					4.302929094234915
				],
				[
					32.27196820676183,
					3.8726361848114155
				],
				[
					42.168705123502164,
					0
				],
				[
					33.132554025608826,
					-3.0120503659644293
				]
			]
		},
		{
			"type": "line",
			"version": 2029,
			"versionNonce": 1870397768,
			"isDeleted": false,
			"id": "IfGeBKe0hwznhJ36qNHlb",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1311.8226159019275,
			"y": 272.121195339408,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 16.35113055809267,
			"height": 2.581757456540929,
			"seed": 1522179143,
			"groupIds": [
				"2SwZ4dmhq8NCnqanV1Ayc",
				"FVclUHDu7Je4LwiYpMKCp",
				"_UtR1IAAJCNM7WZjbt35x"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982459,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.745272369622827,
					-1.7211716376939366
				],
				[
					16.35113055809267,
					-2.581757456540929
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1983,
			"versionNonce": 1463129912,
			"isDeleted": false,
			"id": "Qy1nqkNV0Uxjvp_TjmShC",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1333.46634924593,
			"y": 251.51016497801197,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 956395433,
			"groupIds": [
				"2SwZ4dmhq8NCnqanV1Ayc",
				"FVclUHDu7Je4LwiYpMKCp",
				"_UtR1IAAJCNM7WZjbt35x"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982459,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1983,
			"versionNonce": 301766728,
			"isDeleted": false,
			"id": "HlZ-9TbBpVCpJ_2n7N4xW",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1321.8484406914963,
			"y": 260.0299645845972,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 1707965287,
			"groupIds": [
				"2SwZ4dmhq8NCnqanV1Ayc",
				"FVclUHDu7Je4LwiYpMKCp",
				"_UtR1IAAJCNM7WZjbt35x"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982459,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1984,
			"versionNonce": 200142904,
			"isDeleted": false,
			"id": "Nmzn-Lq9cZKhBPFJvv89A",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1335.6178137930451,
			"y": 264.806215879201,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 1147638409,
			"groupIds": [
				"2SwZ4dmhq8NCnqanV1Ayc",
				"FVclUHDu7Je4LwiYpMKCp",
				"_UtR1IAAJCNM7WZjbt35x"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982459,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1481,
			"versionNonce": 1716670280,
			"isDeleted": false,
			"id": "BxKXtgOPkBe7HYsfOxnmJ",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1335.4569812723341,
			"y": 308.3002980541153,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 18.44546425611026,
			"height": 14.81684833687558,
			"seed": 1165457031,
			"groupIds": [
				"FVclUHDu7Je4LwiYpMKCp",
				"_UtR1IAAJCNM7WZjbt35x"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982459,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.3023846599362763,
					6.047693198724755
				],
				[
					6.652462518597133,
					6.350077858660963
				],
				[
					-2.7214619394261446,
					14.81684833687558
				],
				[
					-11.793001737513126,
					6.350077858660944
				],
				[
					-5.442923878852352,
					6.047693198724749
				],
				[
					-5.442923878852257,
					1.509903313490213e-14
				]
			]
		},
		{
			"type": "arrow",
			"version": 37,
			"versionNonce": 439560504,
			"isDeleted": false,
			"id": "5iBJS1QwKdhkk2GG8Bg7Q",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1340.7132849645134,
			"y": 136.26761350948675,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 88.88888888888891,
			"seed": 1349603631,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982459,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "U5r3kjCm",
				"focus": -0.08279583604037677,
				"gap": 12.723257199444411
			},
			"endBinding": {
				"elementId": "BQy8GYGReVqgKKtwWqSjt",
				"focus": 0.14443873234727025,
				"gap": 9.107701060806221
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					0,
					88.88888888888891
				]
			]
		},
		{
			"type": "text",
			"version": 2784,
			"versionNonce": 561935688,
			"isDeleted": false,
			"id": "XgssF7zW",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 581.5374922098708,
			"y": 677.7313410201092,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 172.31983947753906,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"fVHTQmfg47kGnjS3RBOdh"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "r9_Vb6r_fLYEQ0dMn720k",
					"type": "arrow"
				}
			],
			"updated": 1684528071783,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "stating.dailySales",
			"rawText": "stating.dailySales",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "stating.dailySales",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 3902,
			"versionNonce": 1690516536,
			"isDeleted": false,
			"id": "VwyZ1sLWEIxAVGlSqVHC9",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 623.4969566157715,
			"y": 608.2642034591819,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"3ilDoKlnm4Iu1BRM2TzXc",
				"xPZU1hr2sg0cVyVXSPySg",
				"Fv4EMI4ftfPGJVUYlNYuK",
				"dfk_8IVl13hpXZb00rfcE",
				"fVHTQmfg47kGnjS3RBOdh"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "54nUHnhbokMduGOiani60",
					"type": "arrow"
				},
				{
					"id": "bcrdcpeqILRoUtTJwWny4",
					"type": "arrow"
				},
				{
					"id": "0rlyiRkoaoB4xZLNW5_es",
					"type": "arrow"
				}
			],
			"updated": 1684528071783,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2331,
			"versionNonce": 375662664,
			"isDeleted": false,
			"id": "_SRmw-LcL-CHUHwHzUJKr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 644.537628718821,
			"y": 631.5484916815914,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"QumHZxcmZ48HV3hu0kMgy",
				"lFz0tmgiCSOTlvzgGvDK9",
				"dfk_8IVl13hpXZb00rfcE",
				"fVHTQmfg47kGnjS3RBOdh"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528071785,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2473,
			"versionNonce": 260530232,
			"isDeleted": false,
			"id": "_OQL3Ucay-IfTPDs9frqe",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 645.5229277229728,
			"y": 635.7331361376911,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"QumHZxcmZ48HV3hu0kMgy",
				"lFz0tmgiCSOTlvzgGvDK9",
				"dfk_8IVl13hpXZb00rfcE",
				"fVHTQmfg47kGnjS3RBOdh"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528071785,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3179,
			"versionNonce": 390586184,
			"isDeleted": false,
			"id": "fz3OM-mKxInI-AzmmBnzs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 676.1800423649975,
			"y": 625.420308448328,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"oQmFNNnEVU2rnz4yiAuk5",
				"lFz0tmgiCSOTlvzgGvDK9",
				"dfk_8IVl13hpXZb00rfcE",
				"fVHTQmfg47kGnjS3RBOdh"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528071785,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3270,
			"versionNonce": 1226742072,
			"isDeleted": false,
			"id": "WI_w6nGnLSBfqYsQaRmha",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 641.8603289513699,
			"y": 623.9260436311848,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"x6uhmEod5-XasDra-jPsZ",
				"lFz0tmgiCSOTlvzgGvDK9",
				"dfk_8IVl13hpXZb00rfcE",
				"fVHTQmfg47kGnjS3RBOdh"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528071785,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 3380,
			"versionNonce": 1352447560,
			"isDeleted": false,
			"id": "dAMZ_sUqwA82ze2kTlzcz",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 661.1907620138736,
			"y": 619.0518629244071,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"x6uhmEod5-XasDra-jPsZ",
				"lFz0tmgiCSOTlvzgGvDK9",
				"dfk_8IVl13hpXZb00rfcE",
				"fVHTQmfg47kGnjS3RBOdh"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528071785,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3293,
			"versionNonce": 493269560,
			"isDeleted": false,
			"id": "7TpGRrRUuZlXzG_0h8d2d",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 642.1562145961866,
			"y": 619.2780528617801,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"x6uhmEod5-XasDra-jPsZ",
				"lFz0tmgiCSOTlvzgGvDK9",
				"dfk_8IVl13hpXZb00rfcE",
				"fVHTQmfg47kGnjS3RBOdh"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528071785,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 3488,
			"versionNonce": 1463725384,
			"isDeleted": false,
			"id": "widMWMHbwiEzerpTIZ91j",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 660.2294005091699,
			"y": 662.7949906267869,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"lFz0tmgiCSOTlvzgGvDK9",
				"dfk_8IVl13hpXZb00rfcE",
				"fVHTQmfg47kGnjS3RBOdh"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528071785,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3446,
			"versionNonce": 1128508216,
			"isDeleted": false,
			"id": "7AbtmC1WSlILutvNpQPLv",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 641.1948530914829,
			"y": 663.0211805641599,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"lFz0tmgiCSOTlvzgGvDK9",
				"dfk_8IVl13hpXZb00rfcE",
				"fVHTQmfg47kGnjS3RBOdh"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528071785,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "arrow",
			"version": 329,
			"versionNonce": 1115616568,
			"isDeleted": false,
			"id": "54nUHnhbokMduGOiani60",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1258.4810266691723,
			"y": 311.6903179401546,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 565.834484132424,
			"height": 309.1937175501181,
			"seed": 1226965409,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528071783,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "BQy8GYGReVqgKKtwWqSjt",
				"focus": 0.20718298524063467,
				"gap": 20.56643756199992
			},
			"endBinding": {
				"elementId": "VwyZ1sLWEIxAVGlSqVHC9",
				"focus": 0.011926627743840441,
				"gap": 4.688433556019845
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-565.834484132424,
					309.1937175501181
				]
			]
		},
		{
			"type": "rectangle",
			"version": 2165,
			"versionNonce": 2104384312,
			"isDeleted": false,
			"id": "_pSlEUKQIj3Rt9gfx8yib",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1164.1789141515671,
			"y": 550.1417542726507,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e1488",
			"width": 85.17426249185807,
			"height": 85.09270010541165,
			"seed": 1087403015,
			"groupIds": [
				"1T9eVsry0Slmmduj4eVSB",
				"W5BeZV7pTFJcOKJ_aA5XW",
				"BsEKvATNxcAPnzvPRJu1c"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "wgLkYPMPQUsu7wE7qRt_l",
					"type": "arrow"
				},
				{
					"id": "0rlyiRkoaoB4xZLNW5_es",
					"type": "arrow"
				},
				{
					"id": "y8phaNPqgenOKdtaOKS_B",
					"type": "arrow"
				}
			],
			"updated": 1684528061243,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1320,
			"versionNonce": 489279560,
			"isDeleted": false,
			"id": "5dX16EJ4rNeLvP16N8f_F",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1197.2004720014618,
			"y": 585.4706903154557,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.51105029288197,
			"height": 35.539732911894475,
			"seed": 1235612649,
			"groupIds": [
				"_Q3PXcz9hB2aqlDf4gAU7",
				"W5BeZV7pTFJcOKJ_aA5XW",
				"BsEKvATNxcAPnzvPRJu1c"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982460,
			"link": null,
			"locked": false,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-16.820949905493464,
					33.64891394335074
				],
				[
					-0.6842599011139163,
					35.539732911894475
				],
				[
					8.690100387388505,
					17.416411477550696
				],
				[
					1.1882436250464703,
					0.745228440432334
				]
			]
		},
		{
			"type": "line",
			"version": 1320,
			"versionNonce": 2135963704,
			"isDeleted": false,
			"id": "Xc3Yfa45wCdgfbUTtoRS5",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1229.5554370829316,
			"y": 606.4758259848754,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 46.066480238311605,
			"height": 58.1383889698984,
			"seed": 47340327,
			"groupIds": [
				"_Q3PXcz9hB2aqlDf4gAU7",
				"W5BeZV7pTFJcOKJ_aA5XW",
				"BsEKvATNxcAPnzvPRJu1c"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982460,
			"link": null,
			"locked": false,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-19.767215169387292,
					-42.83742205463878
				],
				[
					-38.54883282525994,
					-43.6037917274238
				],
				[
					-39.875244313683915,
					-30.391842834014387
				],
				[
					-30.254813558131797,
					-29.0691944849492
				],
				[
					-10.394170790466104,
					13.770870223733658
				],
				[
					4.87535158072104,
					14.5345972424746
				],
				[
					6.1912359246276925,
					1.3213270220431457
				],
				[
					4.875351580721041,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 1667,
			"versionNonce": 119048008,
			"isDeleted": false,
			"id": "l03jYce2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1121.8047844142277,
			"y": 641.7927353283982,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 169.8804931640625,
			"height": 31.71184852903549,
			"seed": 242323145,
			"groupIds": [
				"BsEKvATNxcAPnzvPRJu1c"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982460,
			"link": null,
			"locked": false,
			"fontSize": 26.426540440862908,
			"fontFamily": 1,
			"text": "Limpiar tabla",
			"rawText": "Limpiar tabla",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Limpiar tabla",
			"lineHeight": 1.2,
			"baseline": 22
		},
		{
			"type": "arrow",
			"version": 255,
			"versionNonce": 2047635768,
			"isDeleted": false,
			"id": "wgLkYPMPQUsu7wE7qRt_l",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1324.6898990456593,
			"y": 387.3787246205979,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 2.404754754446003,
			"height": 108.57142857142861,
			"seed": 2042430991,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982460,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "v2Ri6ovP",
				"focus": -0.032572212353877514,
				"gap": 6.885478838584106
			},
			"endBinding": {
				"elementId": "Fy2xLDgYmIj5zSinAwZ8U",
				"focus": 0.06361878741690975,
				"gap": 10.83872561075151
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					2.404754754446003,
					108.57142857142861
				]
			]
		},
		{
			"type": "text",
			"version": 236,
			"versionNonce": 1343774280,
			"isDeleted": false,
			"id": "r4X5xjGh",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 70,
			"angle": 0,
			"x": 897.1653780586271,
			"y": 327.6961849380584,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 134.07994079589844,
			"height": 80,
			"seed": 399369505,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982460,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "El proceso limpia\nla tabla en caso\nde que se tenga\nque reprocesar",
			"rawText": "El proceso limpia\nla tabla en caso\nde que se tenga\nque reprocesar",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "El proceso limpia\nla tabla en caso\nde que se tenga\nque reprocesar",
			"lineHeight": 1.25,
			"baseline": 74
		},
		{
			"type": "text",
			"version": 2931,
			"versionNonce": 584682040,
			"isDeleted": false,
			"id": "XFKvq28Y",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 705.0873017414312,
			"y": 1010.1078314327757,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 127.75990295410156,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"os7RqyOA2vVeRGHBQOJrB"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982460,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dw.FactSales",
			"rawText": "dw.FactSales",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dw.FactSales",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4027,
			"versionNonce": 1986933816,
			"isDeleted": false,
			"id": "gH2ETLFwpiBGyhEZcI6pe",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 738.5085384146087,
			"y": 932.3956495544511,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"wSP4nPRz-ztJFh2y-eWMx",
				"bZ0IBb0zjbHkOncbXGTAD",
				"VRkmN6YqwvUmWCDxcH595",
				"yc58ZuKw69Z9WrQxHLODY",
				"os7RqyOA2vVeRGHBQOJrB"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "jYFLSkqSuFZRtiGPf0sQZ",
					"type": "arrow"
				},
				{
					"id": "y8phaNPqgenOKdtaOKS_B",
					"type": "arrow"
				}
			],
			"updated": 1684528061244,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2458,
			"versionNonce": 1151042360,
			"isDeleted": false,
			"id": "Ek7Z0XCI9QbVlqhiTHPbQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 759.5492105176581,
			"y": 955.6799377768606,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"14DqQsBqzMMzdaQycIzF_",
				"BVjcwQoUGs4My-KTF28Y7",
				"yc58ZuKw69Z9WrQxHLODY",
				"os7RqyOA2vVeRGHBQOJrB"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982460,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2600,
			"versionNonce": 121334856,
			"isDeleted": false,
			"id": "Ya4hOo9rXs-yhJJtvzuTY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 760.5345095218099,
			"y": 959.8645822329603,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"14DqQsBqzMMzdaQycIzF_",
				"BVjcwQoUGs4My-KTF28Y7",
				"yc58ZuKw69Z9WrQxHLODY",
				"os7RqyOA2vVeRGHBQOJrB"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982460,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3306,
			"versionNonce": 766925880,
			"isDeleted": false,
			"id": "oDy8U0muInP3OI3zg2JBc",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 791.1916241638346,
			"y": 949.5517545435972,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"3rY3pmcfsQFc-MjBqdhdP",
				"BVjcwQoUGs4My-KTF28Y7",
				"yc58ZuKw69Z9WrQxHLODY",
				"os7RqyOA2vVeRGHBQOJrB"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982460,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3397,
			"versionNonce": 1956029256,
			"isDeleted": false,
			"id": "igJE_6ORu5OKhyRf7Lx_W",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 756.871910750207,
			"y": 948.057489726454,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"-b_15VkLKQx4G1iBX97X-",
				"BVjcwQoUGs4My-KTF28Y7",
				"yc58ZuKw69Z9WrQxHLODY",
				"os7RqyOA2vVeRGHBQOJrB"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982460,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 3507,
			"versionNonce": 1074664760,
			"isDeleted": false,
			"id": "K_H8DJ-HX_toguxkKJ9XG",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 776.2023438127108,
			"y": 943.1833090196764,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"-b_15VkLKQx4G1iBX97X-",
				"BVjcwQoUGs4My-KTF28Y7",
				"yc58ZuKw69Z9WrQxHLODY",
				"os7RqyOA2vVeRGHBQOJrB"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982460,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3420,
			"versionNonce": 527628872,
			"isDeleted": false,
			"id": "LMNAclAv6iCn_Ni1m_7bY",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 757.1677963950235,
			"y": 943.4094989570493,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"-b_15VkLKQx4G1iBX97X-",
				"BVjcwQoUGs4My-KTF28Y7",
				"yc58ZuKw69Z9WrQxHLODY",
				"os7RqyOA2vVeRGHBQOJrB"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982460,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 3615,
			"versionNonce": 17215032,
			"isDeleted": false,
			"id": "D3_BtlBYHxY8JrwjDTwyo",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 775.240982308007,
			"y": 986.9264367220561,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"BVjcwQoUGs4My-KTF28Y7",
				"yc58ZuKw69Z9WrQxHLODY",
				"os7RqyOA2vVeRGHBQOJrB"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982460,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3573,
			"versionNonce": 2058121544,
			"isDeleted": false,
			"id": "D20SLHXqMx0FoQm1n8rFi",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 756.20643489032,
			"y": 987.1526266594291,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"BVjcwQoUGs4My-KTF28Y7",
				"yc58ZuKw69Z9WrQxHLODY",
				"os7RqyOA2vVeRGHBQOJrB"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982460,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "text",
			"version": 2534,
			"versionNonce": 1411825480,
			"isDeleted": false,
			"id": "4N58shO9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1159.540255625011,
			"y": 1146.651975940743,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 331.419677734375,
			"height": 24,
			"seed": 1245685479,
			"groupIds": [
				"9wMhHCZUAikmS3_MrSM7W"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "HccE0RsWXEk03jr80hdqp",
					"type": "arrow"
				}
			],
			"updated": 1684527982461,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Brightcell-VMI-extract-daily-sales",
			"rawText": "Brightcell-VMI-extract-daily-sales",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Brightcell-VMI-extract-daily-sales",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4490,
			"versionNonce": 202549064,
			"isDeleted": false,
			"id": "8N0ahz44JiMhPYFlzwxy6",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1265.6687328517392,
			"y": 1024.422933617911,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 107.76604983800789,
			"height": 107.66285368525563,
			"seed": 941612809,
			"groupIds": [
				"PDq75TK5d2QC6Nsd46BiI",
				"TME5hqt8VocsNKlBgZuG4",
				"HkNbpBrrpYdFQ0HCzg3AW",
				"lOzjDUKCt-ZbB1_6egATv",
				"9wMhHCZUAikmS3_MrSM7W"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "JbYl_Zl1c-4R0FPusHWSj",
					"type": "arrow"
				},
				{
					"id": "SiAtTixwycZbELQATqw_U",
					"type": "arrow"
				},
				{
					"id": "J_wlv4dPw_jlVhbDMXrKf",
					"type": "arrow"
				},
				{
					"id": "XhCturJKkpJ-yvQevj2f9",
					"type": "arrow"
				},
				{
					"id": "jYFLSkqSuFZRtiGPf0sQZ",
					"type": "arrow"
				},
				{
					"id": "r9_Vb6r_fLYEQ0dMn720k",
					"type": "arrow"
				},
				{
					"id": "Gshdfn2q3jOGBsyihM4Zp",
					"type": "arrow"
				}
			],
			"updated": 1684528031670,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2324,
			"versionNonce": 1319081544,
			"isDeleted": false,
			"id": "C_6Dwc5pYwoKQKUkTobex",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1324.3475176697884,
			"y": 1094.1216007954731,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 17.21171637693966,
			"height": 30.981089478491384,
			"seed": 1100493319,
			"groupIds": [
				"E2ufxCRNTzb9Rh1uKGY5M",
				"lOzjDUKCt-ZbB1_6egATv",
				"9wMhHCZUAikmS3_MrSM7W"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982461,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.4302929094234964,
					-5.5938078225054255
				],
				[
					16.781423467516163,
					-30.981089478491384
				]
			]
		},
		{
			"type": "line",
			"version": 2404,
			"versionNonce": 495047224,
			"isDeleted": false,
			"id": "e2mxp1sVt9ahtfiqdlCpB",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1315.2683372809506,
			"y": 1094.1216007954731,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 17.21171637693966,
			"height": 30.981089478491384,
			"seed": 1757484521,
			"groupIds": [
				"E2ufxCRNTzb9Rh1uKGY5M",
				"lOzjDUKCt-ZbB1_6egATv",
				"9wMhHCZUAikmS3_MrSM7W"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982461,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.4302929094234877,
					-5.5938078225054255
				],
				[
					-16.781423467516174,
					-30.981089478491384
				]
			]
		},
		{
			"type": "line",
			"version": 2204,
			"versionNonce": 1373998408,
			"isDeleted": false,
			"id": "ikpjCgLQ3TCghfGQKzkL9",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1315.7416594813185,
			"y": 1094.5518937048892,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 7.745272369622733,
			"height": 0,
			"seed": 1341282599,
			"groupIds": [
				"E2ufxCRNTzb9Rh1uKGY5M",
				"lOzjDUKCt-ZbB1_6egATv",
				"9wMhHCZUAikmS3_MrSM7W"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982461,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.745272369622733,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 2318,
			"versionNonce": 1392167736,
			"isDeleted": false,
			"id": "lSBcceSMXNKDk6zwqShgs",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1299.3905289232252,
			"y": 1062.5897363929134,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 42.168705123502164,
			"height": 7.314979460199344,
			"seed": 567832777,
			"groupIds": [
				"E2ufxCRNTzb9Rh1uKGY5M",
				"lOzjDUKCt-ZbB1_6egATv",
				"9wMhHCZUAikmS3_MrSM7W"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982461,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.175565279046335,
					3.8726361848114155
				],
				[
					19.793473833480647,
					4.302929094234915
				],
				[
					32.27196820676183,
					3.8726361848114155
				],
				[
					42.168705123502164,
					0
				],
				[
					33.132554025608826,
					-3.0120503659644293
				]
			]
		},
		{
			"type": "line",
			"version": 2208,
			"versionNonce": 122987592,
			"isDeleted": false,
			"id": "9shAy4scGkwFAd5eneOlf",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1298.4438845224945,
			"y": 1062.279925498137,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 16.35113055809267,
			"height": 2.581757456540929,
			"seed": 1522179143,
			"groupIds": [
				"E2ufxCRNTzb9Rh1uKGY5M",
				"lOzjDUKCt-ZbB1_6egATv",
				"9wMhHCZUAikmS3_MrSM7W"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982461,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.745272369622827,
					-1.7211716376939366
				],
				[
					16.35113055809267,
					-2.581757456540929
				]
			]
		},
		{
			"type": "rectangle",
			"version": 2162,
			"versionNonce": 1089250360,
			"isDeleted": false,
			"id": "hLIzVFPvI-gD0b3JNJm5c",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1320.0876178664967,
			"y": 1041.668895136741,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 956395433,
			"groupIds": [
				"E2ufxCRNTzb9Rh1uKGY5M",
				"lOzjDUKCt-ZbB1_6egATv",
				"9wMhHCZUAikmS3_MrSM7W"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982461,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 2162,
			"versionNonce": 214489928,
			"isDeleted": false,
			"id": "uDxPfxmh8gQtRlsNnkn7k",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1308.469709312063,
			"y": 1050.1886947433263,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 1707965287,
			"groupIds": [
				"E2ufxCRNTzb9Rh1uKGY5M",
				"lOzjDUKCt-ZbB1_6egATv",
				"9wMhHCZUAikmS3_MrSM7W"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982461,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 2163,
			"versionNonce": 624647480,
			"isDeleted": false,
			"id": "kZo4he_IkQ22s4BCulqRa",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1322.2390824136119,
			"y": 1054.96494603793,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 1147638409,
			"groupIds": [
				"E2ufxCRNTzb9Rh1uKGY5M",
				"lOzjDUKCt-ZbB1_6egATv",
				"9wMhHCZUAikmS3_MrSM7W"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982461,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1660,
			"versionNonce": 1688089160,
			"isDeleted": false,
			"id": "ht1IPWIInqno6DHyoY13F",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1322.078249892901,
			"y": 1098.4590282128443,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 18.44546425611026,
			"height": 14.81684833687558,
			"seed": 1165457031,
			"groupIds": [
				"lOzjDUKCt-ZbB1_6egATv",
				"9wMhHCZUAikmS3_MrSM7W"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982461,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.3023846599362763,
					6.047693198724755
				],
				[
					6.652462518597133,
					6.350077858660963
				],
				[
					-2.7214619394261446,
					14.81684833687558
				],
				[
					-11.793001737513126,
					6.350077858660944
				],
				[
					-5.442923878852352,
					6.047693198724749
				],
				[
					-5.442923878852257,
					1.509903313490213e-14
				]
			]
		},
		{
			"type": "text",
			"version": 2948,
			"versionNonce": 380933688,
			"isDeleted": false,
			"id": "orS3a38A",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1697.4100114456326,
			"y": 805.9808473057914,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 139.93988037109375,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"dT878NalbWRBeUHF-esSj"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dw.dimMaterial",
			"rawText": "dw.dimMaterial",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dw.dimMaterial",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4037,
			"versionNonce": 1295059272,
			"isDeleted": false,
			"id": "mXY_a4ARLs5HQu5LpIIOM",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1736.9212368273063,
			"y": 728.2686654274665,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"ND4xbCh-249DASTfy_gtY",
				"61D8fL7_8UNPpn5C7FiIP",
				"Gq4l2Zy3oJGtEA10Z8ljc",
				"fsq4DdP8CbBjMCWxQlFWa",
				"dT878NalbWRBeUHF-esSj"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "JbYl_Zl1c-4R0FPusHWSj",
					"type": "arrow"
				}
			],
			"updated": 1684528024340,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2470,
			"versionNonce": 1463707704,
			"isDeleted": false,
			"id": "GUfMJcrpliVyN7cZls95T",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1757.9619089303558,
			"y": 751.552953649876,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"oZnhWKHDi5NoFM1KtiBx5",
				"a9KvQBbzPeRiRWbzpQO_8",
				"fsq4DdP8CbBjMCWxQlFWa",
				"dT878NalbWRBeUHF-esSj"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2612,
			"versionNonce": 275076936,
			"isDeleted": false,
			"id": "uDjaqV3TS33IqygWy1zeK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1758.9472079345076,
			"y": 755.7375981059757,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"oZnhWKHDi5NoFM1KtiBx5",
				"a9KvQBbzPeRiRWbzpQO_8",
				"fsq4DdP8CbBjMCWxQlFWa",
				"dT878NalbWRBeUHF-esSj"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3318,
			"versionNonce": 347382072,
			"isDeleted": false,
			"id": "xgEaV2oAKGKq3khIOgZgN",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1789.6043225765322,
			"y": 745.4247704166127,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"NNdXfsippP1LVeHdFA-Rm",
				"a9KvQBbzPeRiRWbzpQO_8",
				"fsq4DdP8CbBjMCWxQlFWa",
				"dT878NalbWRBeUHF-esSj"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3409,
			"versionNonce": 927673928,
			"isDeleted": false,
			"id": "Bs149imh7-ti-ii6v9iVN",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1755.2846091629046,
			"y": 743.9305055994695,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"aoT2F_CZ11VcQzkzWsKdb",
				"a9KvQBbzPeRiRWbzpQO_8",
				"fsq4DdP8CbBjMCWxQlFWa",
				"dT878NalbWRBeUHF-esSj"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 3519,
			"versionNonce": 419150392,
			"isDeleted": false,
			"id": "G1QBTR7wZD0Ta8wexna3z",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1774.6150422254084,
			"y": 739.0563248926918,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"aoT2F_CZ11VcQzkzWsKdb",
				"a9KvQBbzPeRiRWbzpQO_8",
				"fsq4DdP8CbBjMCWxQlFWa",
				"dT878NalbWRBeUHF-esSj"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3432,
			"versionNonce": 1365124424,
			"isDeleted": false,
			"id": "H2hJRCI-YdpJs5P6FFRzl",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1755.5804948077214,
			"y": 739.2825148300648,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"aoT2F_CZ11VcQzkzWsKdb",
				"a9KvQBbzPeRiRWbzpQO_8",
				"fsq4DdP8CbBjMCWxQlFWa",
				"dT878NalbWRBeUHF-esSj"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 3627,
			"versionNonce": 385332024,
			"isDeleted": false,
			"id": "P4k_bF4htKOprMIEZH6JS",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1773.6536807207046,
			"y": 782.7994525950716,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"a9KvQBbzPeRiRWbzpQO_8",
				"fsq4DdP8CbBjMCWxQlFWa",
				"dT878NalbWRBeUHF-esSj"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3585,
			"versionNonce": 1006255176,
			"isDeleted": false,
			"id": "qU2rVCc2FtXnnhouOQxOe",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1754.6191333030176,
			"y": 783.0256425324445,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"a9KvQBbzPeRiRWbzpQO_8",
				"fsq4DdP8CbBjMCWxQlFWa",
				"dT878NalbWRBeUHF-esSj"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "text",
			"version": 2952,
			"versionNonce": 1158450232,
			"isDeleted": false,
			"id": "8Pk80tl3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1711.6100083938752,
			"y": 968.2030695280134,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 111.53988647460938,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"RiKPTcVafponZv5yDRLB0"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dw.dimStore",
			"rawText": "dw.dimStore",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dw.dimStore",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4028,
			"versionNonce": 1224438600,
			"isDeleted": false,
			"id": "H5SebkVTZXmXKCdoLkJNL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1736.9212368273068,
			"y": 890.4908876496886,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"tgCu_vR2_Hfc2pISoR24K",
				"KRVK4WZc1PSvxiDUH1aI5",
				"dUo78q5WgU9mjQ2TvYlob",
				"PbTBzzr-03F8Rda3C3R3B",
				"RiKPTcVafponZv5yDRLB0"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "SiAtTixwycZbELQATqw_U",
					"type": "arrow"
				}
			],
			"updated": 1684528024340,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2463,
			"versionNonce": 2089868856,
			"isDeleted": false,
			"id": "JSP7zIgOhb3vXzIWAI_VJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1757.9619089303562,
			"y": 913.7751758720981,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"p4C4pEERjF0IZLWFBahbc",
				"D7Q-1f2pv6CD5nWn2_PAf",
				"PbTBzzr-03F8Rda3C3R3B",
				"RiKPTcVafponZv5yDRLB0"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2605,
			"versionNonce": 2015183176,
			"isDeleted": false,
			"id": "EBxvd86eato7f6Wg_Jf_j",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1758.947207934508,
			"y": 917.9598203281978,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"p4C4pEERjF0IZLWFBahbc",
				"D7Q-1f2pv6CD5nWn2_PAf",
				"PbTBzzr-03F8Rda3C3R3B",
				"RiKPTcVafponZv5yDRLB0"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3311,
			"versionNonce": 340285240,
			"isDeleted": false,
			"id": "7fH8SHftsKlYoFCiWEyod",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1789.6043225765327,
			"y": 907.6469926388347,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"OyyJZDqtlMEfUiEcMf8tr",
				"D7Q-1f2pv6CD5nWn2_PAf",
				"PbTBzzr-03F8Rda3C3R3B",
				"RiKPTcVafponZv5yDRLB0"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3402,
			"versionNonce": 1953880136,
			"isDeleted": false,
			"id": "4KHJ5jyU2LDn7U4Oe4ffK",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1755.284609162905,
			"y": 906.1527278216915,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"U8GIOQleHxtXmjgh3cLnV",
				"D7Q-1f2pv6CD5nWn2_PAf",
				"PbTBzzr-03F8Rda3C3R3B",
				"RiKPTcVafponZv5yDRLB0"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 3512,
			"versionNonce": 413708344,
			"isDeleted": false,
			"id": "yWEy_C3ojD85s_yJK3bpL",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1774.6150422254088,
			"y": 901.2785471149139,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"U8GIOQleHxtXmjgh3cLnV",
				"D7Q-1f2pv6CD5nWn2_PAf",
				"PbTBzzr-03F8Rda3C3R3B",
				"RiKPTcVafponZv5yDRLB0"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3425,
			"versionNonce": 665030472,
			"isDeleted": false,
			"id": "OPZ7nfVwo_IfTHTklJ6oo",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1755.5804948077218,
			"y": 901.5047370522868,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"U8GIOQleHxtXmjgh3cLnV",
				"D7Q-1f2pv6CD5nWn2_PAf",
				"PbTBzzr-03F8Rda3C3R3B",
				"RiKPTcVafponZv5yDRLB0"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 3620,
			"versionNonce": 1100343608,
			"isDeleted": false,
			"id": "niy2kIlxBMMaWfoHnlQri",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1773.653680720705,
			"y": 945.0216748172936,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"D7Q-1f2pv6CD5nWn2_PAf",
				"PbTBzzr-03F8Rda3C3R3B",
				"RiKPTcVafponZv5yDRLB0"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3578,
			"versionNonce": 973235784,
			"isDeleted": false,
			"id": "OZ7BiIa1yfF9ylipfp51w",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1754.619133303018,
			"y": 945.2478647546666,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"D7Q-1f2pv6CD5nWn2_PAf",
				"PbTBzzr-03F8Rda3C3R3B",
				"RiKPTcVafponZv5yDRLB0"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "text",
			"version": 2945,
			"versionNonce": 712245816,
			"isDeleted": false,
			"id": "IUgSvDof",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1696.0322504525232,
			"y": 1119.3141806391243,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 147.1398468017578,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"bkcqPSEdva0GZaU5x21wC"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dw.dimCostumer",
			"rawText": "dw.dimCostumer",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dw.dimCostumer",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4034,
			"versionNonce": 1752063304,
			"isDeleted": false,
			"id": "TQXRRz5KwyhCvmHlw36kU",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1739.143459049529,
			"y": 1041.6019987608,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"9sMkRNLtUo3Y01qGHOurb",
				"js8XdQWhxJb8iJjDhE3yx",
				"v017cUcaaEyVRErkpE9Kw",
				"GJF8ToLkj_01JOKzaB3cv",
				"bkcqPSEdva0GZaU5x21wC"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "J_wlv4dPw_jlVhbDMXrKf",
					"type": "arrow"
				}
			],
			"updated": 1684528024340,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2469,
			"versionNonce": 2064831544,
			"isDeleted": false,
			"id": "SO331P_3d3nSPmjqJiXcW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1760.1841311525784,
			"y": 1064.8862869832094,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"ZO23hO8iH6MQzOVopSQnj",
				"H2tXC4S_xe3n2JGgJC-tm",
				"GJF8ToLkj_01JOKzaB3cv",
				"bkcqPSEdva0GZaU5x21wC"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2611,
			"versionNonce": 324905800,
			"isDeleted": false,
			"id": "Grz_vd7ygLxkbJ6sJD2J7",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1761.1694301567302,
			"y": 1069.070931439309,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"ZO23hO8iH6MQzOVopSQnj",
				"H2tXC4S_xe3n2JGgJC-tm",
				"GJF8ToLkj_01JOKzaB3cv",
				"bkcqPSEdva0GZaU5x21wC"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3317,
			"versionNonce": 454790456,
			"isDeleted": false,
			"id": "G2rVoS5xjxcG4E9UmCNat",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1791.8265447987549,
			"y": 1058.758103749946,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"g-ej9KI1jgEA9Co2R7MKE",
				"H2tXC4S_xe3n2JGgJC-tm",
				"GJF8ToLkj_01JOKzaB3cv",
				"bkcqPSEdva0GZaU5x21wC"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3408,
			"versionNonce": 1612251720,
			"isDeleted": false,
			"id": "q_17DcCNk4js5c3hRxJxz",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1757.5068313851273,
			"y": 1057.2638389328029,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"Hvogh68DyHKwBGX13FGQs",
				"H2tXC4S_xe3n2JGgJC-tm",
				"GJF8ToLkj_01JOKzaB3cv",
				"bkcqPSEdva0GZaU5x21wC"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 3518,
			"versionNonce": 195372600,
			"isDeleted": false,
			"id": "-6CdKOH8q0A6IPIrbEXmH",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1776.837264447631,
			"y": 1052.3896582260252,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"Hvogh68DyHKwBGX13FGQs",
				"H2tXC4S_xe3n2JGgJC-tm",
				"GJF8ToLkj_01JOKzaB3cv",
				"bkcqPSEdva0GZaU5x21wC"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3431,
			"versionNonce": 1230076232,
			"isDeleted": false,
			"id": "u5pzqgUhZO9wFPsYp9xJJ",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1757.802717029944,
			"y": 1052.6158481633981,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"Hvogh68DyHKwBGX13FGQs",
				"H2tXC4S_xe3n2JGgJC-tm",
				"GJF8ToLkj_01JOKzaB3cv",
				"bkcqPSEdva0GZaU5x21wC"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 3626,
			"versionNonce": 1234411320,
			"isDeleted": false,
			"id": "kVhbwzILpzC08Ue6vTmYu",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1775.8759029429273,
			"y": 1096.132785928405,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"H2tXC4S_xe3n2JGgJC-tm",
				"GJF8ToLkj_01JOKzaB3cv",
				"bkcqPSEdva0GZaU5x21wC"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3584,
			"versionNonce": 40046664,
			"isDeleted": false,
			"id": "3LTJ3m5Qc9qoBbeHlzEpT",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1756.8413555252403,
			"y": 1096.358975865778,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"H2tXC4S_xe3n2JGgJC-tm",
				"GJF8ToLkj_01JOKzaB3cv",
				"bkcqPSEdva0GZaU5x21wC"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "arrow",
			"version": 588,
			"versionNonce": 64004168,
			"isDeleted": false,
			"id": "JbYl_Zl1c-4R0FPusHWSj",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1383.8878881391167,
			"y": 1046.6376896270647,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 345.7142857142851,
			"height": 275.0556712743539,
			"seed": 1552009345,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "8N0ahz44JiMhPYFlzwxy6",
				"focus": 0.19899859397163425,
				"gap": 10.453105449369787
			},
			"endBinding": {
				"elementId": "mXY_a4ARLs5HQu5LpIIOM",
				"focus": 0.3518613733173426,
				"gap": 7.319062973904465
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					345.7142857142851,
					-275.0556712743539
				]
			]
		},
		{
			"type": "arrow",
			"version": 593,
			"versionNonce": 784190024,
			"isDeleted": false,
			"id": "SiAtTixwycZbELQATqw_U",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1383.8878881391172,
			"y": 1066.0257887176117,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 350.15873015872944,
			"height": 127.26948054588661,
			"seed": 1953507023,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "8N0ahz44JiMhPYFlzwxy6",
				"focus": 0.14988057545921005,
				"gap": 10.453105449370241
			},
			"endBinding": {
				"elementId": "H5SebkVTZXmXKCdoLkJNL",
				"focus": -0.07528969539264023,
				"gap": 2.874618529460122
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					350.15873015872944,
					-127.26948054588661
				]
			]
		},
		{
			"type": "arrow",
			"version": 595,
			"versionNonce": 1950577736,
			"isDeleted": false,
			"id": "J_wlv4dPw_jlVhbDMXrKf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1383.8878881391172,
			"y": 1079.4870120443882,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 345.71428571428464,
			"height": 5.895516250068567,
			"seed": 1263192399,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528024340,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "8N0ahz44JiMhPYFlzwxy6",
				"focus": 0.002628758121739649,
				"gap": 10.453105449370241
			},
			"endBinding": {
				"elementId": "TQXRRz5KwyhCvmHlw36kU",
				"focus": -0.3753711345796599,
				"gap": 9.541285196127092
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					345.71428571428464,
					5.895516250068567
				]
			]
		},
		{
			"type": "text",
			"version": 2998,
			"versionNonce": 1289462328,
			"isDeleted": false,
			"id": "54eyMLat",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 518.7228438692522,
			"y": 1524.2824346073792,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 101.59992980957031,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"R1wDttrNkkBiv_pKkVAwj"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528121101,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dbo.R1_Uni",
			"rawText": "dbo.R1_Uni",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dbo.R1_Uni",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4073,
			"versionNonce": 969981256,
			"isDeleted": false,
			"id": "gW9G7u2K-qbwDn2L_icbu",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 539.0640939701638,
			"y": 1446.5702527290543,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"T1kOCnao4y4-l4DR8VOPZ",
				"is_fHoQlWcxnbfCMurT4r",
				"_AG4RNHRNqSLRP0kBWeCv",
				"dhoX6JSxbGAL-pLSKJssO",
				"R1wDttrNkkBiv_pKkVAwj"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528121101,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2508,
			"versionNonce": 379231032,
			"isDeleted": false,
			"id": "usuuFV9pA-fWkg4j9O76I",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 560.1047660732132,
			"y": 1469.8545409514638,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"gRKtWtp7JfZnwQJs6VUPq",
				"CBzPoW0v5syWCqsRK7oR3",
				"dhoX6JSxbGAL-pLSKJssO",
				"R1wDttrNkkBiv_pKkVAwj"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528121101,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2650,
			"versionNonce": 710530120,
			"isDeleted": false,
			"id": "Zej8wZq--lFVQkUXIGuqm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 561.090065077365,
			"y": 1474.0391854075635,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"gRKtWtp7JfZnwQJs6VUPq",
				"CBzPoW0v5syWCqsRK7oR3",
				"dhoX6JSxbGAL-pLSKJssO",
				"R1wDttrNkkBiv_pKkVAwj"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528121101,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3356,
			"versionNonce": 538080312,
			"isDeleted": false,
			"id": "iS35T8bsG8b2Pvt1zjozD",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 591.7471797193897,
			"y": 1463.7263577182005,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"bjBrJbCxcjlVr89T5h2bh",
				"CBzPoW0v5syWCqsRK7oR3",
				"dhoX6JSxbGAL-pLSKJssO",
				"R1wDttrNkkBiv_pKkVAwj"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528121101,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3447,
			"versionNonce": 2007501640,
			"isDeleted": false,
			"id": "WmeyQiRYcqJp8siFWCHAh",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 557.4274663057626,
			"y": 1462.2320929010573,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"zStHbFVJJUuTLFuUC0G7A",
				"CBzPoW0v5syWCqsRK7oR3",
				"dhoX6JSxbGAL-pLSKJssO",
				"R1wDttrNkkBiv_pKkVAwj"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528121101,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 3557,
			"versionNonce": 1059532088,
			"isDeleted": false,
			"id": "u6g5kFvnVBmgtQ7b54LG-",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 576.7578993682658,
			"y": 1457.3579121942796,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"zStHbFVJJUuTLFuUC0G7A",
				"CBzPoW0v5syWCqsRK7oR3",
				"dhoX6JSxbGAL-pLSKJssO",
				"R1wDttrNkkBiv_pKkVAwj"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528121101,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3470,
			"versionNonce": 202859080,
			"isDeleted": false,
			"id": "1GY4srlEMn6dtQWGyGhtT",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 557.7233519505793,
			"y": 1457.5841021316526,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"zStHbFVJJUuTLFuUC0G7A",
				"CBzPoW0v5syWCqsRK7oR3",
				"dhoX6JSxbGAL-pLSKJssO",
				"R1wDttrNkkBiv_pKkVAwj"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528121101,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 3665,
			"versionNonce": 1832699448,
			"isDeleted": false,
			"id": "i2DEgxlVt10M50xZw2Rg7",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 575.7965378635621,
			"y": 1501.1010398966594,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"CBzPoW0v5syWCqsRK7oR3",
				"dhoX6JSxbGAL-pLSKJssO",
				"R1wDttrNkkBiv_pKkVAwj"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528121101,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3623,
			"versionNonce": 646175048,
			"isDeleted": false,
			"id": "5XlEo7UTUZI_83VUJg1ls",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 556.7619904458755,
			"y": 1501.3272298340323,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"CBzPoW0v5syWCqsRK7oR3",
				"dhoX6JSxbGAL-pLSKJssO",
				"R1wDttrNkkBiv_pKkVAwj"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528121101,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "text",
			"version": 2999,
			"versionNonce": 903838776,
			"isDeleted": false,
			"id": "yD2iwP7o",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1613.7027528881165,
			"y": 1463.7586250835695,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 224.17979431152344,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"5-MskSu7TNMWySnnmUG91"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982463,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "stating.EightWeekSales",
			"rawText": "stating.EightWeekSales",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "stating.EightWeekSales",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4064,
			"versionNonce": 166455352,
			"isDeleted": false,
			"id": "vH07WZdf3zOQsWlnXyRd7",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1695.3339352400055,
			"y": 1386.0464432052452,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"Qg2lJMvCPfMqCBUQccSCq",
				"XFPOeDoy2NEMiqML_Jnyr",
				"PXdMt7WYntW7UZN657egq",
				"HcDq394rexHYvOL_s4WKQ",
				"5-MskSu7TNMWySnnmUG91"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "J25aM7QW2YunLiYCAtZ2E",
					"type": "arrow"
				},
				{
					"id": "i-vwSw6s7D0BEuQro-e8F",
					"type": "arrow"
				}
			],
			"updated": 1684528095030,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2495,
			"versionNonce": 638793016,
			"isDeleted": false,
			"id": "sZVl9rDJF1aiCewtqe_AG",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1716.374607343055,
			"y": 1409.3307314276547,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"Oakdm72HrMx8RRe0y6sN2",
				"jYAuVu3lWscosAe3usZ6o",
				"HcDq394rexHYvOL_s4WKQ",
				"5-MskSu7TNMWySnnmUG91"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982463,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2637,
			"versionNonce": 1607457352,
			"isDeleted": false,
			"id": "hqs0xcfx5_HH2A0zejhKr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1717.3599063472068,
			"y": 1413.5153758837544,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"Oakdm72HrMx8RRe0y6sN2",
				"jYAuVu3lWscosAe3usZ6o",
				"HcDq394rexHYvOL_s4WKQ",
				"5-MskSu7TNMWySnnmUG91"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982463,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3343,
			"versionNonce": 694668856,
			"isDeleted": false,
			"id": "CStA_4Eu7FR_yHi2E3krB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1748.0170209892315,
			"y": 1403.2025481943913,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"88etT4HLlUYgrwetRojma",
				"jYAuVu3lWscosAe3usZ6o",
				"HcDq394rexHYvOL_s4WKQ",
				"5-MskSu7TNMWySnnmUG91"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982463,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3434,
			"versionNonce": 1550668104,
			"isDeleted": false,
			"id": "9DuMJjlOJNUyPjkO9MXJF",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1713.6973075756034,
			"y": 1401.708283377248,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"VdHCORgmfmORrEts8b6zN",
				"jYAuVu3lWscosAe3usZ6o",
				"HcDq394rexHYvOL_s4WKQ",
				"5-MskSu7TNMWySnnmUG91"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982463,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 3544,
			"versionNonce": 1757497144,
			"isDeleted": false,
			"id": "I9-zEREk-9aqL9j6Dj9sl",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1733.0277406381076,
			"y": 1396.8341026704704,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"VdHCORgmfmORrEts8b6zN",
				"jYAuVu3lWscosAe3usZ6o",
				"HcDq394rexHYvOL_s4WKQ",
				"5-MskSu7TNMWySnnmUG91"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982463,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3457,
			"versionNonce": 1950607432,
			"isDeleted": false,
			"id": "wMIOV98OBc6iRJyTsdvAT",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1713.9931932204202,
			"y": 1397.0602926078434,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"VdHCORgmfmORrEts8b6zN",
				"jYAuVu3lWscosAe3usZ6o",
				"HcDq394rexHYvOL_s4WKQ",
				"5-MskSu7TNMWySnnmUG91"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982463,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 3652,
			"versionNonce": 1350803512,
			"isDeleted": false,
			"id": "2JEXzFGUJtEwNEa4nUIli",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1732.0663791334039,
			"y": 1440.5772303728502,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"jYAuVu3lWscosAe3usZ6o",
				"HcDq394rexHYvOL_s4WKQ",
				"5-MskSu7TNMWySnnmUG91"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982463,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3610,
			"versionNonce": 590323528,
			"isDeleted": false,
			"id": "c55fSLB_-bMlDvqfDkOsk",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1713.0318317157164,
			"y": 1440.8034203102231,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"jYAuVu3lWscosAe3usZ6o",
				"HcDq394rexHYvOL_s4WKQ",
				"5-MskSu7TNMWySnnmUG91"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982463,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "text",
			"version": 2552,
			"versionNonce": 546494776,
			"isDeleted": false,
			"id": "PKX2ZYgo",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1095.003446097325,
			"y": 1474.271023559791,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 449.03955078125,
			"height": 24,
			"seed": 1245685479,
			"groupIds": [
				"Q2SEhXFj8LPBJANXETEmO"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "8zAO-KuP6Htmma9tBBn-h",
					"type": "arrow"
				},
				{
					"id": "MU2OcMhYdESJXWu1jyQVn",
					"type": "arrow"
				},
				{
					"id": "CLRRPNHhLeU09EXr57_Zf",
					"type": "arrow"
				}
			],
			"updated": 1684527982463,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Brightcell-VMI-extract-daily-sales-eight-weeks",
			"rawText": "Brightcell-VMI-extract-daily-sales-eight-weeks",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Brightcell-VMI-extract-daily-sales-eight-weeks",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4516,
			"versionNonce": 160200264,
			"isDeleted": false,
			"id": "QjuIQCHJPfYAyks8P6A-H",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1267.7985899907196,
			"y": 1352.0419812369591,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 107.76604983800789,
			"height": 107.66285368525563,
			"seed": 941612809,
			"groupIds": [
				"SeNRx6F9LKGhNUoXQmoCT",
				"W7SPUuxJG8QTWzKwjeCT0",
				"ImGK5oaAwUg82Jh1_Fdvy",
				"7NBDxQ9AhXRU-gdbKmqIg",
				"Q2SEhXFj8LPBJANXETEmO"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "J25aM7QW2YunLiYCAtZ2E",
					"type": "arrow"
				},
				{
					"id": "FQzdXOQpXouZhMIOBUQyS",
					"type": "arrow"
				},
				{
					"id": "MU2OcMhYdESJXWu1jyQVn",
					"type": "arrow"
				},
				{
					"id": "HccE0RsWXEk03jr80hdqp",
					"type": "arrow"
				}
			],
			"updated": 1684527982463,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2359,
			"versionNonce": 2085810744,
			"isDeleted": false,
			"id": "es2kc23CQNS7jOeXCAAEh",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1326.477374808769,
			"y": 1421.7406484145217,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 17.21171637693966,
			"height": 30.981089478491384,
			"seed": 1100493319,
			"groupIds": [
				"tLCr4Jy-7LLyWOfjbLtGO",
				"7NBDxQ9AhXRU-gdbKmqIg",
				"Q2SEhXFj8LPBJANXETEmO"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982463,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.4302929094234964,
					-5.5938078225054255
				],
				[
					16.781423467516163,
					-30.981089478491384
				]
			]
		},
		{
			"type": "line",
			"version": 2439,
			"versionNonce": 1547070792,
			"isDeleted": false,
			"id": "8aWPKHyWp0SeIebNTKhQY",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1317.398194419931,
			"y": 1421.7406484145217,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 17.21171637693966,
			"height": 30.981089478491384,
			"seed": 1757484521,
			"groupIds": [
				"tLCr4Jy-7LLyWOfjbLtGO",
				"7NBDxQ9AhXRU-gdbKmqIg",
				"Q2SEhXFj8LPBJANXETEmO"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982463,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.4302929094234877,
					-5.5938078225054255
				],
				[
					-16.781423467516174,
					-30.981089478491384
				]
			]
		},
		{
			"type": "line",
			"version": 2239,
			"versionNonce": 2057825080,
			"isDeleted": false,
			"id": "H7FRUrC_oTkeGreHBMSGH",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1317.871516620299,
			"y": 1422.1709413239378,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 7.745272369622733,
			"height": 0,
			"seed": 1341282599,
			"groupIds": [
				"tLCr4Jy-7LLyWOfjbLtGO",
				"7NBDxQ9AhXRU-gdbKmqIg",
				"Q2SEhXFj8LPBJANXETEmO"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982463,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.745272369622733,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 2353,
			"versionNonce": 1418298440,
			"isDeleted": false,
			"id": "jSNW6QWXPxE9dGQf8aLw2",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1301.5203860622057,
			"y": 1390.2087840119616,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 42.168705123502164,
			"height": 7.314979460199344,
			"seed": 567832777,
			"groupIds": [
				"tLCr4Jy-7LLyWOfjbLtGO",
				"7NBDxQ9AhXRU-gdbKmqIg",
				"Q2SEhXFj8LPBJANXETEmO"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982463,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.175565279046335,
					3.8726361848114155
				],
				[
					19.793473833480647,
					4.302929094234915
				],
				[
					32.27196820676183,
					3.8726361848114155
				],
				[
					42.168705123502164,
					0
				],
				[
					33.132554025608826,
					-3.0120503659644293
				]
			]
		},
		{
			"type": "line",
			"version": 2243,
			"versionNonce": 905299000,
			"isDeleted": false,
			"id": "wx67SfNiWoU5IzI2xyMyz",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1300.5737416614754,
			"y": 1389.8989731171855,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 16.35113055809267,
			"height": 2.581757456540929,
			"seed": 1522179143,
			"groupIds": [
				"tLCr4Jy-7LLyWOfjbLtGO",
				"7NBDxQ9AhXRU-gdbKmqIg",
				"Q2SEhXFj8LPBJANXETEmO"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982463,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.745272369622827,
					-1.7211716376939366
				],
				[
					16.35113055809267,
					-2.581757456540929
				]
			]
		},
		{
			"type": "rectangle",
			"version": 2197,
			"versionNonce": 543275848,
			"isDeleted": false,
			"id": "khHfTfV_S5ADgPofd79a6",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1322.2174750054771,
			"y": 1369.2879427557896,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 956395433,
			"groupIds": [
				"tLCr4Jy-7LLyWOfjbLtGO",
				"7NBDxQ9AhXRU-gdbKmqIg",
				"Q2SEhXFj8LPBJANXETEmO"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982463,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 2197,
			"versionNonce": 1545633080,
			"isDeleted": false,
			"id": "chugBBd_ihda2zSRG7rJe",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1310.5995664510435,
			"y": 1377.8077423623745,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 1707965287,
			"groupIds": [
				"tLCr4Jy-7LLyWOfjbLtGO",
				"7NBDxQ9AhXRU-gdbKmqIg",
				"Q2SEhXFj8LPBJANXETEmO"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982463,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 2198,
			"versionNonce": 1377505864,
			"isDeleted": false,
			"id": "O93WwtKC57q4FvFamc78J",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1324.3689395525923,
			"y": 1382.5839936569782,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 1147638409,
			"groupIds": [
				"tLCr4Jy-7LLyWOfjbLtGO",
				"7NBDxQ9AhXRU-gdbKmqIg",
				"Q2SEhXFj8LPBJANXETEmO"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982463,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1695,
			"versionNonce": 1049368120,
			"isDeleted": false,
			"id": "s6663YR4ZyiISzkZk2e4q",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1324.2081070318816,
			"y": 1426.0780758318924,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 18.44546425611026,
			"height": 14.81684833687558,
			"seed": 1165457031,
			"groupIds": [
				"7NBDxQ9AhXRU-gdbKmqIg",
				"Q2SEhXFj8LPBJANXETEmO"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982463,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.3023846599362763,
					6.047693198724755
				],
				[
					6.652462518597133,
					6.350077858660963
				],
				[
					-2.7214619394261446,
					14.81684833687558
				],
				[
					-11.793001737513126,
					6.350077858660944
				],
				[
					-5.442923878852352,
					6.047693198724749
				],
				[
					-5.442923878852257,
					1.509903313490213e-14
				]
			]
		},
		{
			"type": "arrow",
			"version": 338,
			"versionNonce": 1351715144,
			"isDeleted": false,
			"id": "J25aM7QW2YunLiYCAtZ2E",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1391.023377989659,
			"y": 1406.0816606400522,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 291.7460317460318,
			"height": 3.8076313462065627,
			"seed": 1226965409,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982463,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "QjuIQCHJPfYAyks8P6A-H",
				"focus": -0.023146890474145265,
				"gap": 15.458738160931489
			},
			"endBinding": {
				"elementId": "vH07WZdf3zOQsWlnXyRd7",
				"focus": 0.23826329760795914,
				"gap": 12.564525504314815
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					291.7460317460318,
					3.8076313462065627
				]
			]
		},
		{
			"type": "text",
			"version": 3026,
			"versionNonce": 1319443784,
			"isDeleted": false,
			"id": "CQr5Uqo8",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 538.0014061425499,
			"y": 1645.7593691311884,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 65.89994812011719,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"YQyChQdJnxc2bsAkuMX9I"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528122963,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dbo.R2",
			"rawText": "dbo.R2",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dbo.R2",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4100,
			"versionNonce": 800865080,
			"isDeleted": false,
			"id": "f0iIZl-IHuEw2gsD3R_RV",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 540.4926653987349,
			"y": 1568.0471872528635,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"j_3LUJIyTL_TtOfTVRrEq",
				"T80X2GW0Yzcg2_Zpy-RpR",
				"-kBTAweVEja7BnRBurA5F",
				"nCrXGhvJT3W9Z6DoyJEO9",
				"YQyChQdJnxc2bsAkuMX9I"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528122963,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2535,
			"versionNonce": 1705129032,
			"isDeleted": false,
			"id": "zhDGMOhWzFYPOr88AThfU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 561.5333375017843,
			"y": 1591.331475475273,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"Vl8Oatng-TX4TQkadQasp",
				"7Bkj-ooveAFsmFAaB2TVR",
				"nCrXGhvJT3W9Z6DoyJEO9",
				"YQyChQdJnxc2bsAkuMX9I"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528122964,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2677,
			"versionNonce": 1677726776,
			"isDeleted": false,
			"id": "nYIbdhsg1PCqK1PRzBpBw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 562.5186365059361,
			"y": 1595.5161199313727,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"Vl8Oatng-TX4TQkadQasp",
				"7Bkj-ooveAFsmFAaB2TVR",
				"nCrXGhvJT3W9Z6DoyJEO9",
				"YQyChQdJnxc2bsAkuMX9I"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528122964,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3383,
			"versionNonce": 1793354568,
			"isDeleted": false,
			"id": "e-EBavSLA1gRmFZbIxJsr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 593.1757511479608,
			"y": 1585.2032922420096,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"wZKBRnycA3J6sHv9YpaCB",
				"7Bkj-ooveAFsmFAaB2TVR",
				"nCrXGhvJT3W9Z6DoyJEO9",
				"YQyChQdJnxc2bsAkuMX9I"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528122964,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3474,
			"versionNonce": 1952501048,
			"isDeleted": false,
			"id": "3acjTiVy8Up1kJQPHaesk",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 558.8560377343337,
			"y": 1583.7090274248665,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"Oq7alW9m4jUDkbtomnOpK",
				"7Bkj-ooveAFsmFAaB2TVR",
				"nCrXGhvJT3W9Z6DoyJEO9",
				"YQyChQdJnxc2bsAkuMX9I"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528122964,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 3584,
			"versionNonce": 415744584,
			"isDeleted": false,
			"id": "X_1Bnx2wSPaUGtYItmEN1",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 578.1864707968369,
			"y": 1578.8348467180888,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"Oq7alW9m4jUDkbtomnOpK",
				"7Bkj-ooveAFsmFAaB2TVR",
				"nCrXGhvJT3W9Z6DoyJEO9",
				"YQyChQdJnxc2bsAkuMX9I"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528122964,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3497,
			"versionNonce": 172123704,
			"isDeleted": false,
			"id": "HIA7IyrJbRh1Rv274VKh2",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 559.1519233791504,
			"y": 1579.0610366554617,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"Oq7alW9m4jUDkbtomnOpK",
				"7Bkj-ooveAFsmFAaB2TVR",
				"nCrXGhvJT3W9Z6DoyJEO9",
				"YQyChQdJnxc2bsAkuMX9I"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528122964,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 3692,
			"versionNonce": 2116565320,
			"isDeleted": false,
			"id": "B50ktIQBDA9oDByq23EME",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 577.2251092921332,
			"y": 1622.5779744204685,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"7Bkj-ooveAFsmFAaB2TVR",
				"nCrXGhvJT3W9Z6DoyJEO9",
				"YQyChQdJnxc2bsAkuMX9I"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528122964,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3650,
			"versionNonce": 42524472,
			"isDeleted": false,
			"id": "u8UXblNyNgF_u10YwJsAh",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 558.1905618744466,
			"y": 1622.8041643578415,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"7Bkj-ooveAFsmFAaB2TVR",
				"nCrXGhvJT3W9Z6DoyJEO9",
				"YQyChQdJnxc2bsAkuMX9I"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528122964,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "text",
			"version": 3040,
			"versionNonce": 2050001976,
			"isDeleted": false,
			"id": "xQbUJGCy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 509.79714545267836,
			"y": 1771.473654845474,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 130.87989807128906,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"A25gm-vUdz771GpRa2hgx"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528126030,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dbo.R2_Cads",
			"rawText": "dbo.R2_Cads",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dbo.R2_Cads",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4114,
			"versionNonce": 1746367304,
			"isDeleted": false,
			"id": "PYlTxgRT0HHcUaHFcEKTh",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 544.7783796844492,
			"y": 1693.761472967149,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"Z6YXSy_ibP_R9ZFDgZO3k",
				"pcBHT3DhbfgwjWgE2pAfa",
				"zJdSk7QKH9j86RynbW_T_",
				"wTilkQhxe4y67a44qq5PD",
				"A25gm-vUdz771GpRa2hgx"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528126030,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2549,
			"versionNonce": 1573012792,
			"isDeleted": false,
			"id": "nPkA_os224tlzqg84PAT5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 565.8190517874989,
			"y": 1717.0457611895586,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"qIsxrfg14caPbYpaRgzNi",
				"EklELfgmabRok_fEXAH4a",
				"wTilkQhxe4y67a44qq5PD",
				"A25gm-vUdz771GpRa2hgx"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528126030,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2691,
			"versionNonce": 173656648,
			"isDeleted": false,
			"id": "OMM7XcesDsi3yQKCEYrBz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 566.8043507916507,
			"y": 1721.2304056456583,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"qIsxrfg14caPbYpaRgzNi",
				"EklELfgmabRok_fEXAH4a",
				"wTilkQhxe4y67a44qq5PD",
				"A25gm-vUdz771GpRa2hgx"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528126030,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3397,
			"versionNonce": 951377464,
			"isDeleted": false,
			"id": "3bidoNdI6PCbI_8pWFpFS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 597.4614654336751,
			"y": 1710.9175779562952,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"B2DsjtSXzBM_Uw3OKBmLV",
				"EklELfgmabRok_fEXAH4a",
				"wTilkQhxe4y67a44qq5PD",
				"A25gm-vUdz771GpRa2hgx"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528126030,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3488,
			"versionNonce": 3752264,
			"isDeleted": false,
			"id": "UCTZvMLfTfOHvvh3hGv2q",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 563.141752020048,
			"y": 1709.423313139152,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"-TA2hceDVstzcc9ZF4n8f",
				"EklELfgmabRok_fEXAH4a",
				"wTilkQhxe4y67a44qq5PD",
				"A25gm-vUdz771GpRa2hgx"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528126030,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 3598,
			"versionNonce": 736909112,
			"isDeleted": false,
			"id": "2kz5vNkKfvlqHnJ2RQa9S",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 582.4721850825513,
			"y": 1704.5491324323743,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"-TA2hceDVstzcc9ZF4n8f",
				"EklELfgmabRok_fEXAH4a",
				"wTilkQhxe4y67a44qq5PD",
				"A25gm-vUdz771GpRa2hgx"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528126030,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3511,
			"versionNonce": 420599880,
			"isDeleted": false,
			"id": "p_oedSG7kvU37q4tIMTED",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 563.4376376648647,
			"y": 1704.7753223697473,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"-TA2hceDVstzcc9ZF4n8f",
				"EklELfgmabRok_fEXAH4a",
				"wTilkQhxe4y67a44qq5PD",
				"A25gm-vUdz771GpRa2hgx"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528126030,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 3706,
			"versionNonce": 466399288,
			"isDeleted": false,
			"id": "AlAmqO00YPS5FVugMEGRM",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 581.5108235778475,
			"y": 1748.292260134754,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"EklELfgmabRok_fEXAH4a",
				"wTilkQhxe4y67a44qq5PD",
				"A25gm-vUdz771GpRa2hgx"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528126030,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3664,
			"versionNonce": 1488949064,
			"isDeleted": false,
			"id": "b8D97pnIjuzEcSJiNHn3E",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 562.476276160161,
			"y": 1748.518450072127,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"EklELfgmabRok_fEXAH4a",
				"wTilkQhxe4y67a44qq5PD",
				"A25gm-vUdz771GpRa2hgx"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528126030,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "text",
			"version": 3010,
			"versionNonce": 1864198456,
			"isDeleted": false,
			"id": "2hv5dtY1",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 661.4066417963819,
			"y": 1516.2113780597604,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 65.27995300292969,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"SR3q-tbSqkCvYGbl0kTqY"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982464,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dbo.R3",
			"rawText": "dbo.R3",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dbo.R3",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4084,
			"versionNonce": 716367432,
			"isDeleted": false,
			"id": "jkZgjQIrzxrvz9h7HHe4P",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 663.5879034939732,
			"y": 1438.4991961814355,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"jfW9Nne_E1wyus_3oKwLQ",
				"siozZXW9Scsx2Lomyez9P",
				"T6IhCeXSZubDSAiLbmKpV",
				"fPWGOieJ-QM4mgIohluV8",
				"SR3q-tbSqkCvYGbl0kTqY"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982464,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2519,
			"versionNonce": 990609976,
			"isDeleted": false,
			"id": "pKwWxWtTWkheT2CKNUGi-",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 684.6285755970226,
			"y": 1461.783484403845,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"AUy65H1iSIB42KflOE5wq",
				"wWfpxM0qG-7s2vTQ5Dtwo",
				"fPWGOieJ-QM4mgIohluV8",
				"SR3q-tbSqkCvYGbl0kTqY"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982464,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2661,
			"versionNonce": 1863245128,
			"isDeleted": false,
			"id": "HjxxSsiqEL963D1LVxVEy",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 685.6138746011744,
			"y": 1465.9681288599447,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"AUy65H1iSIB42KflOE5wq",
				"wWfpxM0qG-7s2vTQ5Dtwo",
				"fPWGOieJ-QM4mgIohluV8",
				"SR3q-tbSqkCvYGbl0kTqY"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982464,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3367,
			"versionNonce": 1942911800,
			"isDeleted": false,
			"id": "uKtk6FgbtaYzAzDKMrJt8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 716.2709892431991,
			"y": 1455.6553011705817,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"IOBSs5K_FY_PtfKJ4I1rZ",
				"wWfpxM0qG-7s2vTQ5Dtwo",
				"fPWGOieJ-QM4mgIohluV8",
				"SR3q-tbSqkCvYGbl0kTqY"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982464,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3458,
			"versionNonce": 1389622344,
			"isDeleted": false,
			"id": "9nXNiaqdqApV95xggMuKM",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 681.951275829572,
			"y": 1454.1610363534385,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"N_mWcO_xcm_1JXglRjSAh",
				"wWfpxM0qG-7s2vTQ5Dtwo",
				"fPWGOieJ-QM4mgIohluV8",
				"SR3q-tbSqkCvYGbl0kTqY"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982464,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 3568,
			"versionNonce": 1808421944,
			"isDeleted": false,
			"id": "Pc5cCbzGbHqYoWniJX-DJ",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 701.2817088920752,
			"y": 1449.2868556466608,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"N_mWcO_xcm_1JXglRjSAh",
				"wWfpxM0qG-7s2vTQ5Dtwo",
				"fPWGOieJ-QM4mgIohluV8",
				"SR3q-tbSqkCvYGbl0kTqY"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982464,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3481,
			"versionNonce": 1272851272,
			"isDeleted": false,
			"id": "uvgtCKt5vrRXwL5nxlmq4",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 682.2471614743887,
			"y": 1449.5130455840338,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"N_mWcO_xcm_1JXglRjSAh",
				"wWfpxM0qG-7s2vTQ5Dtwo",
				"fPWGOieJ-QM4mgIohluV8",
				"SR3q-tbSqkCvYGbl0kTqY"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982464,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 3676,
			"versionNonce": 149097784,
			"isDeleted": false,
			"id": "uuLNvpsz2KcgLpiJeOkPo",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 700.3203473873715,
			"y": 1493.0299833490405,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"wWfpxM0qG-7s2vTQ5Dtwo",
				"fPWGOieJ-QM4mgIohluV8",
				"SR3q-tbSqkCvYGbl0kTqY"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982464,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3634,
			"versionNonce": 881427016,
			"isDeleted": false,
			"id": "Ntgq7dNif63DFS0N9QY2w",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 681.285799969685,
			"y": 1493.2561732864135,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"wWfpxM0qG-7s2vTQ5Dtwo",
				"fPWGOieJ-QM4mgIohluV8",
				"SR3q-tbSqkCvYGbl0kTqY"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982464,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "text",
			"version": 3040,
			"versionNonce": 1417455160,
			"isDeleted": false,
			"id": "SA2vEfLc",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 758.916666820796,
			"y": 1514.8311697264269,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 130.25990295410156,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"Z-04kHabduUYQ-KOnLcbm"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982464,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dbo.R3_Cads",
			"rawText": "dbo.R3_Cads",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dbo.R3_Cads",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4114,
			"versionNonce": 1001519432,
			"isDeleted": false,
			"id": "1HlUQLp0S9Cv-ctN7HaUB",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 793.5879034939732,
			"y": 1437.1189878481016,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"etY-Ut7X9uxIdm0lsX_eJ",
				"U6UXW3dFL5vkIMsaX6l_N",
				"3aQ_HUWCIxNn7rJpCxGBc",
				"9idblLo0nrlC-Ir6vpT3F",
				"Z-04kHabduUYQ-KOnLcbm"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2550,
			"versionNonce": 192618296,
			"isDeleted": false,
			"id": "oH1lYWw3PdTcoCFGWjS_0",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 814.6285755970226,
			"y": 1460.403276070511,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"0KKcgheRVP0cCHlfuATok",
				"Mrpd1upYi0Ah9vvABumdM",
				"9idblLo0nrlC-Ir6vpT3F",
				"Z-04kHabduUYQ-KOnLcbm"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"id": "FQzdXOQpXouZhMIOBUQyS",
					"type": "arrow"
				}
			],
			"updated": 1684527982465,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2691,
			"versionNonce": 1421054024,
			"isDeleted": false,
			"id": "lNWgfNNEsxsmarBaHdi5a",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 815.6138746011744,
			"y": 1464.5879205266108,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"0KKcgheRVP0cCHlfuATok",
				"Mrpd1upYi0Ah9vvABumdM",
				"9idblLo0nrlC-Ir6vpT3F",
				"Z-04kHabduUYQ-KOnLcbm"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3397,
			"versionNonce": 776108088,
			"isDeleted": false,
			"id": "nGjaz5CQkaDH4sZz5LldH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 846.2709892431991,
			"y": 1454.2750928372477,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"27BQwJ16ViwNcQEs9OtI1",
				"Mrpd1upYi0Ah9vvABumdM",
				"9idblLo0nrlC-Ir6vpT3F",
				"Z-04kHabduUYQ-KOnLcbm"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3488,
			"versionNonce": 661276488,
			"isDeleted": false,
			"id": "6exwyiOzDLGxeigWEsUdS",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 811.951275829572,
			"y": 1452.780828020105,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"TSqRn_AhKDStOHXP4vvDt",
				"Mrpd1upYi0Ah9vvABumdM",
				"9idblLo0nrlC-Ir6vpT3F",
				"Z-04kHabduUYQ-KOnLcbm"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 3598,
			"versionNonce": 280408376,
			"isDeleted": false,
			"id": "WhAjXyWLxcoNWCnjhgPND",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 831.2817088920752,
			"y": 1447.9066473133269,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"TSqRn_AhKDStOHXP4vvDt",
				"Mrpd1upYi0Ah9vvABumdM",
				"9idblLo0nrlC-Ir6vpT3F",
				"Z-04kHabduUYQ-KOnLcbm"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3511,
			"versionNonce": 3284552,
			"isDeleted": false,
			"id": "4WB9lY4YSEcYYczq1a4On",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 812.2471614743887,
			"y": 1448.1328372507003,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"TSqRn_AhKDStOHXP4vvDt",
				"Mrpd1upYi0Ah9vvABumdM",
				"9idblLo0nrlC-Ir6vpT3F",
				"Z-04kHabduUYQ-KOnLcbm"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 3706,
			"versionNonce": 1782303288,
			"isDeleted": false,
			"id": "7WiXkvgJ_4rkuoi2NoidY",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 830.3203473873715,
			"y": 1491.6497750157066,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"Mrpd1upYi0Ah9vvABumdM",
				"9idblLo0nrlC-Ir6vpT3F",
				"Z-04kHabduUYQ-KOnLcbm"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3664,
			"versionNonce": 1072108872,
			"isDeleted": false,
			"id": "1uF-mB2OagSxfl3sSBGUo",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 811.285799969685,
			"y": 1491.87596495308,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"Mrpd1upYi0Ah9vvABumdM",
				"9idblLo0nrlC-Ir6vpT3F",
				"Z-04kHabduUYQ-KOnLcbm"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "text",
			"version": 3049,
			"versionNonce": 1706410808,
			"isDeleted": false,
			"id": "jtvjX5ZP",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 921.8166454584912,
			"y": 1514.8311697264264,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 64.45994567871094,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"uO52Dd8VecRNE3nphIbpZ"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dbo.R4",
			"rawText": "dbo.R4",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dbo.R4",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4123,
			"versionNonce": 1273310280,
			"isDeleted": false,
			"id": "OPKIPVZvQBR2ijUv7y7s9",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 923.587903493973,
			"y": 1437.1189878481016,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"PIKYiFU0OKmhX9bh2dh2Y",
				"__OyooGokl0hUy8d3s2Jt",
				"pKk5cj9tWoDiJ2DCWucvi",
				"f_JGv7VbM4-OKZGnS8MAJ",
				"uO52Dd8VecRNE3nphIbpZ"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2558,
			"versionNonce": 831036472,
			"isDeleted": false,
			"id": "thVelzPYTOYfwrsY9cX26",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 944.6285755970225,
			"y": 1460.403276070511,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"LwTVwk60oaD5zb4Ia_0OL",
				"V8WD2xqloqnNfGdYfGZS1",
				"f_JGv7VbM4-OKZGnS8MAJ",
				"uO52Dd8VecRNE3nphIbpZ"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2700,
			"versionNonce": 2114478920,
			"isDeleted": false,
			"id": "K0sA9SpFzFztHNrhLht5S",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 945.6138746011743,
			"y": 1464.5879205266108,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"LwTVwk60oaD5zb4Ia_0OL",
				"V8WD2xqloqnNfGdYfGZS1",
				"f_JGv7VbM4-OKZGnS8MAJ",
				"uO52Dd8VecRNE3nphIbpZ"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3406,
			"versionNonce": 261641528,
			"isDeleted": false,
			"id": "usXkRbr_LYpW4_kOkqwoI",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 976.270989243199,
			"y": 1454.2750928372477,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"f9jw8lfTRNBVS2coZ4NXb",
				"V8WD2xqloqnNfGdYfGZS1",
				"f_JGv7VbM4-OKZGnS8MAJ",
				"uO52Dd8VecRNE3nphIbpZ"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3497,
			"versionNonce": 346864200,
			"isDeleted": false,
			"id": "F7pym1w8VXPOGQpvpNZAe",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 941.9512758295718,
			"y": 1452.7808280201045,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"c_jN5OOlIoJp33htfmyBW",
				"V8WD2xqloqnNfGdYfGZS1",
				"f_JGv7VbM4-OKZGnS8MAJ",
				"uO52Dd8VecRNE3nphIbpZ"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 3607,
			"versionNonce": 1699278392,
			"isDeleted": false,
			"id": "-G9qYQYWJxMfQPSgrxAbw",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 961.2817088920751,
			"y": 1447.9066473133269,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"c_jN5OOlIoJp33htfmyBW",
				"V8WD2xqloqnNfGdYfGZS1",
				"f_JGv7VbM4-OKZGnS8MAJ",
				"uO52Dd8VecRNE3nphIbpZ"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3520,
			"versionNonce": 581841224,
			"isDeleted": false,
			"id": "csPmxa9Vpg-u4U6qrkMsZ",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 942.2471614743886,
			"y": 1448.1328372506998,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"c_jN5OOlIoJp33htfmyBW",
				"V8WD2xqloqnNfGdYfGZS1",
				"f_JGv7VbM4-OKZGnS8MAJ",
				"uO52Dd8VecRNE3nphIbpZ"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 3715,
			"versionNonce": 1266575160,
			"isDeleted": false,
			"id": "EexlrWLzPtjVGGd1SnMyg",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 960.3203473873714,
			"y": 1491.6497750157066,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"V8WD2xqloqnNfGdYfGZS1",
				"f_JGv7VbM4-OKZGnS8MAJ",
				"uO52Dd8VecRNE3nphIbpZ"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3673,
			"versionNonce": 2137573448,
			"isDeleted": false,
			"id": "Q-w0lJXpKbYDoKEvGPrvk",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 941.2857999696848,
			"y": 1491.8759649530796,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"V8WD2xqloqnNfGdYfGZS1",
				"f_JGv7VbM4-OKZGnS8MAJ",
				"uO52Dd8VecRNE3nphIbpZ"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "text",
			"version": 2995,
			"versionNonce": 513589304,
			"isDeleted": false,
			"id": "I6U0rOYB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 625.1600038162387,
			"y": 1639.0564301430936,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 129.4398956298828,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"L8sX90A1I9Hayi9uUCl0h"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dbo.R4_Cads",
			"rawText": "dbo.R4_Cads",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dbo.R4_Cads",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4069,
			"versionNonce": 918060872,
			"isDeleted": false,
			"id": "yj6yK6v89iyUhG9OEovX7",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 659.4212368273065,
			"y": 1561.3442482647683,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"CYh9YqO4BweBlxsUUjisj",
				"Bk2urxU_MY9Hpb1v0rU25",
				"H1dRMzYE8keWT7s9Lz6Lq",
				"7rxkB-OooNny_CNe6anjy",
				"L8sX90A1I9Hayi9uUCl0h"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2504,
			"versionNonce": 243792184,
			"isDeleted": false,
			"id": "YLTl1rQq15207VdHmdr3h",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 680.461908930356,
			"y": 1584.6285364871778,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"JbXuccVk2vT4Q7ozZHdYN",
				"1Yl_kgF4Na1YK5ymWZPxd",
				"7rxkB-OooNny_CNe6anjy",
				"L8sX90A1I9Hayi9uUCl0h"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2646,
			"versionNonce": 2029606472,
			"isDeleted": false,
			"id": "_zZICajY5v_nUeAuXnLv_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 681.4472079345078,
			"y": 1588.8131809432775,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"JbXuccVk2vT4Q7ozZHdYN",
				"1Yl_kgF4Na1YK5ymWZPxd",
				"7rxkB-OooNny_CNe6anjy",
				"L8sX90A1I9Hayi9uUCl0h"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3352,
			"versionNonce": 782504504,
			"isDeleted": false,
			"id": "2BxyhrK7asefMpN9wp4-Z",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 712.1043225765325,
			"y": 1578.5003532539145,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"Njv-fSh846n-YQdFmyxy_",
				"1Yl_kgF4Na1YK5ymWZPxd",
				"7rxkB-OooNny_CNe6anjy",
				"L8sX90A1I9Hayi9uUCl0h"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3443,
			"versionNonce": 185027912,
			"isDeleted": false,
			"id": "NjWm7UG_UN3EfH2JzX9Pv",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 677.7846091629053,
			"y": 1577.0060884367717,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"rCESanNIhJfQGTlgSea2D",
				"1Yl_kgF4Na1YK5ymWZPxd",
				"7rxkB-OooNny_CNe6anjy",
				"L8sX90A1I9Hayi9uUCl0h"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 3553,
			"versionNonce": 97848120,
			"isDeleted": false,
			"id": "6_-MRUymgO8GaxjUHglgF",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 697.1150422254086,
			"y": 1572.1319077299936,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"rCESanNIhJfQGTlgSea2D",
				"1Yl_kgF4Na1YK5ymWZPxd",
				"7rxkB-OooNny_CNe6anjy",
				"L8sX90A1I9Hayi9uUCl0h"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3466,
			"versionNonce": 910058568,
			"isDeleted": false,
			"id": "JFn098WPFtu6HiViOcDa8",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 678.0804948077221,
			"y": 1572.358097667367,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"rCESanNIhJfQGTlgSea2D",
				"1Yl_kgF4Na1YK5ymWZPxd",
				"7rxkB-OooNny_CNe6anjy",
				"L8sX90A1I9Hayi9uUCl0h"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 3661,
			"versionNonce": 511632440,
			"isDeleted": false,
			"id": "OD3zghM28SyZ0_RmTwfrQ",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 696.1536807207049,
			"y": 1615.8750354323734,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"1Yl_kgF4Na1YK5ymWZPxd",
				"7rxkB-OooNny_CNe6anjy",
				"L8sX90A1I9Hayi9uUCl0h"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982465,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3619,
			"versionNonce": 947559240,
			"isDeleted": false,
			"id": "dSH35KPcI4vXnJcUo7D6a",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 677.1191333030183,
			"y": 1616.1012253697468,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"1Yl_kgF4Na1YK5ymWZPxd",
				"7rxkB-OooNny_CNe6anjy",
				"L8sX90A1I9Hayi9uUCl0h"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "text",
			"version": 3025,
			"versionNonce": 377855288,
			"isDeleted": false,
			"id": "pnUK4gk3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 787.8699800125278,
			"y": 1637.6762218097597,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 64.01994323730469,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"_99ObhYh3mZfMMliLSuWy"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dbo.R5",
			"rawText": "dbo.R5",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dbo.R5",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4099,
			"versionNonce": 873984584,
			"isDeleted": false,
			"id": "J9nwvOrQ5_QsMtiJpZ8Um",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 789.4212368273065,
			"y": 1559.9640399314349,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"iRg9JNPsTC_p6xty1KANI",
				"2hKz04aAFRcCfe7OrjGjr",
				"hzpiP8mZ6W6VctV-auDq0",
				"OdGDx2J1WTUBRtAYZUX0k",
				"_99ObhYh3mZfMMliLSuWy"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2534,
			"versionNonce": 793589304,
			"isDeleted": false,
			"id": "1Omc05Athg1qNxuW2DX-C",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 810.461908930356,
			"y": 1583.2483281538443,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"vvwyxl-L9rNGOhAfAxVXF",
				"yWG0fd3-f9YFw5oEsf0rc",
				"OdGDx2J1WTUBRtAYZUX0k",
				"_99ObhYh3mZfMMliLSuWy"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2676,
			"versionNonce": 535980360,
			"isDeleted": false,
			"id": "eaRipbhIYyasrNZoQqrqT",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 811.4472079345078,
			"y": 1587.432972609944,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"vvwyxl-L9rNGOhAfAxVXF",
				"yWG0fd3-f9YFw5oEsf0rc",
				"OdGDx2J1WTUBRtAYZUX0k",
				"_99ObhYh3mZfMMliLSuWy"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3382,
			"versionNonce": 1572450104,
			"isDeleted": false,
			"id": "xe1KjEUgOD37KbW0WsoeD",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 842.1043225765325,
			"y": 1577.120144920581,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"BNyWdgWpYOO0OabS5WH7q",
				"yWG0fd3-f9YFw5oEsf0rc",
				"OdGDx2J1WTUBRtAYZUX0k",
				"_99ObhYh3mZfMMliLSuWy"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3473,
			"versionNonce": 929431624,
			"isDeleted": false,
			"id": "lT0dq0s5c_jHH3bFPiHlB",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 807.7846091629053,
			"y": 1575.6258801034378,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"Kl-4HBaW7TIN9mwOx00S7",
				"yWG0fd3-f9YFw5oEsf0rc",
				"OdGDx2J1WTUBRtAYZUX0k",
				"_99ObhYh3mZfMMliLSuWy"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 3583,
			"versionNonce": 1513031736,
			"isDeleted": false,
			"id": "8wlraZ3Am5bCVZAyYfyvE",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 827.1150422254086,
			"y": 1570.7516993966601,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"Kl-4HBaW7TIN9mwOx00S7",
				"yWG0fd3-f9YFw5oEsf0rc",
				"OdGDx2J1WTUBRtAYZUX0k",
				"_99ObhYh3mZfMMliLSuWy"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3496,
			"versionNonce": 1783543624,
			"isDeleted": false,
			"id": "NnhKQV3Nh-px-GfAq8lJa",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 808.0804948077221,
			"y": 1570.977889334033,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"Kl-4HBaW7TIN9mwOx00S7",
				"yWG0fd3-f9YFw5oEsf0rc",
				"OdGDx2J1WTUBRtAYZUX0k",
				"_99ObhYh3mZfMMliLSuWy"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 3691,
			"versionNonce": 814825784,
			"isDeleted": false,
			"id": "5awXtpmbpZE7UBQKZQLO7",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 826.1536807207049,
			"y": 1614.4948270990399,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"yWG0fd3-f9YFw5oEsf0rc",
				"OdGDx2J1WTUBRtAYZUX0k",
				"_99ObhYh3mZfMMliLSuWy"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3649,
			"versionNonce": 1292406344,
			"isDeleted": false,
			"id": "KrU-EhftMvtj2R5vyaIcc",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 807.1191333030183,
			"y": 1614.7210170364128,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"yWG0fd3-f9YFw5oEsf0rc",
				"OdGDx2J1WTUBRtAYZUX0k",
				"_99ObhYh3mZfMMliLSuWy"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "text",
			"version": 3034,
			"versionNonce": 1346656824,
			"isDeleted": false,
			"id": "SNavG6gG",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 917.6499787918244,
			"y": 1637.6762218097597,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 64.45994567871094,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"KUlz2NmNAIseJkH4fvF5c"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dbo.R6",
			"rawText": "dbo.R6",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dbo.R6",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4108,
			"versionNonce": 141526344,
			"isDeleted": false,
			"id": "IYXiZL8jTd7QQcEaZob70",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 919.4212368273063,
			"y": 1559.9640399314344,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"iwKJT8-_7VbT0_2y_xLGC",
				"jA6puUUzAF5UuGCxAWPSD",
				"C0GtJ9Vy3qL_VJEOrlxOS",
				"rRU8eZVx7pGh6I1PNo4iD",
				"KUlz2NmNAIseJkH4fvF5c"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2543,
			"versionNonce": 472666936,
			"isDeleted": false,
			"id": "TMzJyR8caxF-t0_PnJWR8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 940.4619089303558,
			"y": 1583.2483281538439,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"olzWRFPOchebqfrIHteqw",
				"TEARWgEcX5wPq2B0K0Ud6",
				"rRU8eZVx7pGh6I1PNo4iD",
				"KUlz2NmNAIseJkH4fvF5c"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2685,
			"versionNonce": 1239391304,
			"isDeleted": false,
			"id": "OuzIEzRH6koFZvUeTKMtb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 941.4472079345076,
			"y": 1587.4329726099436,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"olzWRFPOchebqfrIHteqw",
				"TEARWgEcX5wPq2B0K0Ud6",
				"rRU8eZVx7pGh6I1PNo4iD",
				"KUlz2NmNAIseJkH4fvF5c"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3391,
			"versionNonce": 2058169400,
			"isDeleted": false,
			"id": "5Cs6hEG6eQp_n9SxTpB1M",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 972.1043225765322,
			"y": 1577.1201449205805,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"AT_dMRoM7kRRYXO9GJLyF",
				"TEARWgEcX5wPq2B0K0Ud6",
				"rRU8eZVx7pGh6I1PNo4iD",
				"KUlz2NmNAIseJkH4fvF5c"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3482,
			"versionNonce": 859099976,
			"isDeleted": false,
			"id": "P2OYRfEhDnVDWpjDiEdj9",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 937.7846091629051,
			"y": 1575.6258801034378,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"xduAOIVVbEo_Z4jKCzD8w",
				"TEARWgEcX5wPq2B0K0Ud6",
				"rRU8eZVx7pGh6I1PNo4iD",
				"KUlz2NmNAIseJkH4fvF5c"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 3592,
			"versionNonce": 1705698616,
			"isDeleted": false,
			"id": "zYuqeV_9Jkr3AaVUAP65k",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 957.1150422254084,
			"y": 1570.7516993966597,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"xduAOIVVbEo_Z4jKCzD8w",
				"TEARWgEcX5wPq2B0K0Ud6",
				"rRU8eZVx7pGh6I1PNo4iD",
				"KUlz2NmNAIseJkH4fvF5c"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3505,
			"versionNonce": 1254828616,
			"isDeleted": false,
			"id": "AVoTCn8Fv21Nv4OcLwO2P",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 938.0804948077218,
			"y": 1570.977889334033,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"xduAOIVVbEo_Z4jKCzD8w",
				"TEARWgEcX5wPq2B0K0Ud6",
				"rRU8eZVx7pGh6I1PNo4iD",
				"KUlz2NmNAIseJkH4fvF5c"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 3700,
			"versionNonce": 2055831096,
			"isDeleted": false,
			"id": "mrd-LUloiXKCSeGYkcU4V",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 956.1536807207046,
			"y": 1614.4948270990394,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"TEARWgEcX5wPq2B0K0Ud6",
				"rRU8eZVx7pGh6I1PNo4iD",
				"KUlz2NmNAIseJkH4fvF5c"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3658,
			"versionNonce": 1803460936,
			"isDeleted": false,
			"id": "8DFN4Ztc68kDbR8Go1pct",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 937.1191333030181,
			"y": 1614.7210170364128,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"TEARWgEcX5wPq2B0K0Ud6",
				"rRU8eZVx7pGh6I1PNo4iD",
				"KUlz2NmNAIseJkH4fvF5c"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "text",
			"version": 3041,
			"versionNonce": 170719032,
			"isDeleted": false,
			"id": "xhlcNUZj",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 638.0766552241164,
			"y": 1756.6996593097601,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 106.93992614746094,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"hmF5DxJ7v2m9QcUo2iTfd"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dbo.R7_Uni",
			"rawText": "dbo.R7_Uni",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dbo.R7_Uni",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4115,
			"versionNonce": 883636296,
			"isDeleted": false,
			"id": "gffADWa_-iwNRtXlpWN0t",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 661.0879034939733,
			"y": 1678.9874774314353,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"umF5xXWAa5LX1QGZMY5qN",
				"35zymEeQKxCh7CFgeaser",
				"XPkWpN-Pk3boOIz5wCtu0",
				"bunINs8A41TCc4-DIx9dP",
				"hmF5DxJ7v2m9QcUo2iTfd"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2550,
			"versionNonce": 687427640,
			"isDeleted": false,
			"id": "tJcM0d_2WjsFl_smanrnh",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 682.1285755970227,
			"y": 1702.2717656538448,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"DVwsConCt8_LQcaPH60Lu",
				"rw1k4G_Xbm619CXWLhG2E",
				"bunINs8A41TCc4-DIx9dP",
				"hmF5DxJ7v2m9QcUo2iTfd"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2692,
			"versionNonce": 2049765192,
			"isDeleted": false,
			"id": "f1MxVzguxEJv_eCGuJOyh",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 683.1138746011745,
			"y": 1706.4564101099445,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"DVwsConCt8_LQcaPH60Lu",
				"rw1k4G_Xbm619CXWLhG2E",
				"bunINs8A41TCc4-DIx9dP",
				"hmF5DxJ7v2m9QcUo2iTfd"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3398,
			"versionNonce": 1053985080,
			"isDeleted": false,
			"id": "Hdhf5H5_xvXnhu_7dv94G",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 713.7709892431992,
			"y": 1696.1435824205814,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"ufNQc18Y_YI6ELhdt8QAT",
				"rw1k4G_Xbm619CXWLhG2E",
				"bunINs8A41TCc4-DIx9dP",
				"hmF5DxJ7v2m9QcUo2iTfd"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3489,
			"versionNonce": 878691912,
			"isDeleted": false,
			"id": "VBR-L3k4h8h_Z9cTu8QKf",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 679.4512758295721,
			"y": 1694.6493176034382,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"ddwr0wd_NyxoMHV8KdngO",
				"rw1k4G_Xbm619CXWLhG2E",
				"bunINs8A41TCc4-DIx9dP",
				"hmF5DxJ7v2m9QcUo2iTfd"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 3599,
			"versionNonce": 387752504,
			"isDeleted": false,
			"id": "IU4-dh5U2miiDg5bxtSHy",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 698.7817088920754,
			"y": 1689.7751368966606,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"ddwr0wd_NyxoMHV8KdngO",
				"rw1k4G_Xbm619CXWLhG2E",
				"bunINs8A41TCc4-DIx9dP",
				"hmF5DxJ7v2m9QcUo2iTfd"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982466,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3512,
			"versionNonce": 1881128264,
			"isDeleted": false,
			"id": "uC1Zvh2zzmOPUG5f9XKJn",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 679.7471614743888,
			"y": 1690.0013268340335,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"ddwr0wd_NyxoMHV8KdngO",
				"rw1k4G_Xbm619CXWLhG2E",
				"bunINs8A41TCc4-DIx9dP",
				"hmF5DxJ7v2m9QcUo2iTfd"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 3707,
			"versionNonce": 1891343160,
			"isDeleted": false,
			"id": "ZluJBc7aun5h1z83M1TvD",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 697.8203473873716,
			"y": 1733.5182645990403,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"rw1k4G_Xbm619CXWLhG2E",
				"bunINs8A41TCc4-DIx9dP",
				"hmF5DxJ7v2m9QcUo2iTfd"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3665,
			"versionNonce": 1053348936,
			"isDeleted": false,
			"id": "UqmsSuBHU6-dK0-PGn5CN",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 678.7857999696851,
			"y": 1733.7444545364133,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"rw1k4G_Xbm619CXWLhG2E",
				"bunINs8A41TCc4-DIx9dP",
				"hmF5DxJ7v2m9QcUo2iTfd"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "text",
			"version": 3071,
			"versionNonce": 236155960,
			"isDeleted": false,
			"id": "HKFiGkue",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 788.0666454584914,
			"y": 1755.3194509764267,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.95994567871094,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"gxy3k1gyeWs4KxWsrkX-u"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dbo.R8",
			"rawText": "dbo.R8",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dbo.R8",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4145,
			"versionNonce": 641141576,
			"isDeleted": false,
			"id": "_fqZEBxYSZ_8oxZoASHWy",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 791.0879034939733,
			"y": 1677.6072690981014,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"ajkv7yRDw0QO3ERf8adFM",
				"fUkFMMHq_Eid4ok2cFxWP",
				"_nP4PCCloFJdioWDg2pkp",
				"GZGthrYte2uvq1lmARsJH",
				"gxy3k1gyeWs4KxWsrkX-u"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2580,
			"versionNonce": 1158163768,
			"isDeleted": false,
			"id": "n2GkZXLzOufaaM1EsgHrC",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 812.1285755970227,
			"y": 1700.8915573205109,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"8A9WfBOCzeN1B1PrlSdBA",
				"2F0zVBjU0Bi_DJlZZUGPp",
				"GZGthrYte2uvq1lmARsJH",
				"gxy3k1gyeWs4KxWsrkX-u"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2722,
			"versionNonce": 281436744,
			"isDeleted": false,
			"id": "0aOrQ-Bp2Hc_b19TvyfWs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 813.1138746011745,
			"y": 1705.0762017766106,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"8A9WfBOCzeN1B1PrlSdBA",
				"2F0zVBjU0Bi_DJlZZUGPp",
				"GZGthrYte2uvq1lmARsJH",
				"gxy3k1gyeWs4KxWsrkX-u"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3428,
			"versionNonce": 251512376,
			"isDeleted": false,
			"id": "Q1sgsTrrdj79AbV_o8JXp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 843.7709892431992,
			"y": 1694.7633740872475,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"k65NGNqJ-I-5Fu8Em3Vn5",
				"2F0zVBjU0Bi_DJlZZUGPp",
				"GZGthrYte2uvq1lmARsJH",
				"gxy3k1gyeWs4KxWsrkX-u"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3519,
			"versionNonce": 1028839752,
			"isDeleted": false,
			"id": "HeBz-pS5IsjAXkCYIyLUA",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 809.4512758295721,
			"y": 1693.2691092701048,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"HpOjAhcEQVgnghw-mTJ2o",
				"2F0zVBjU0Bi_DJlZZUGPp",
				"GZGthrYte2uvq1lmARsJH",
				"gxy3k1gyeWs4KxWsrkX-u"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 3629,
			"versionNonce": 416825144,
			"isDeleted": false,
			"id": "ZZr63AK-CRDLH5enxRU8D",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 828.7817088920754,
			"y": 1688.3949285633266,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"HpOjAhcEQVgnghw-mTJ2o",
				"2F0zVBjU0Bi_DJlZZUGPp",
				"GZGthrYte2uvq1lmARsJH",
				"gxy3k1gyeWs4KxWsrkX-u"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3542,
			"versionNonce": 792227912,
			"isDeleted": false,
			"id": "ultJs-TpHeqfdlmNGq0HC",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 809.7471614743888,
			"y": 1688.6211185007,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"HpOjAhcEQVgnghw-mTJ2o",
				"2F0zVBjU0Bi_DJlZZUGPp",
				"GZGthrYte2uvq1lmARsJH",
				"gxy3k1gyeWs4KxWsrkX-u"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 3737,
			"versionNonce": 1392220216,
			"isDeleted": false,
			"id": "H4Q1hbQds6bqHr4oufWb-",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 827.8203473873716,
			"y": 1732.1380562657064,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"2F0zVBjU0Bi_DJlZZUGPp",
				"GZGthrYte2uvq1lmARsJH",
				"gxy3k1gyeWs4KxWsrkX-u"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3695,
			"versionNonce": 508766024,
			"isDeleted": false,
			"id": "-o0UZGttMqc1z887KsIs2",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 808.7857999696851,
			"y": 1732.3642462030798,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"2F0zVBjU0Bi_DJlZZUGPp",
				"GZGthrYte2uvq1lmARsJH",
				"gxy3k1gyeWs4KxWsrkX-u"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "text",
			"version": 3080,
			"versionNonce": 21745976,
			"isDeleted": false,
			"id": "kic9FRKR",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 885.5766704829052,
			"y": 1755.3194509764262,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 131.9398956298828,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"R4Wt27IpI3SParqnWsQL4"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dbo.R8_Cads",
			"rawText": "dbo.R8_Cads",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dbo.R8_Cads",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4154,
			"versionNonce": 1727987272,
			"isDeleted": false,
			"id": "lfD_tPYd6cWg2MaSyTo1t",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 921.087903493973,
			"y": 1677.6072690981014,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"PT-raaHYxRGelBPmVQlW6",
				"GXpmRcsOCZ3Pf_snZIC-3",
				"1Y5wsz0IqpWLVbByLxnzt",
				"L5P8oUyUefU8AEg2VAol9",
				"R4Wt27IpI3SParqnWsQL4"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2589,
			"versionNonce": 1261234744,
			"isDeleted": false,
			"id": "97NTNbveHd-m4Nz-hmKqM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 942.1285755970225,
			"y": 1700.8915573205109,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"yGQg9iclai4IlTZEFzU0F",
				"ZiZYXb1Ovd8LQgKl9CZRM",
				"L5P8oUyUefU8AEg2VAol9",
				"R4Wt27IpI3SParqnWsQL4"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2731,
			"versionNonce": 2048390472,
			"isDeleted": false,
			"id": "FdkyGBsTowKwYuJyLMOoM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 943.1138746011743,
			"y": 1705.0762017766106,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"yGQg9iclai4IlTZEFzU0F",
				"ZiZYXb1Ovd8LQgKl9CZRM",
				"L5P8oUyUefU8AEg2VAol9",
				"R4Wt27IpI3SParqnWsQL4"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3437,
			"versionNonce": 1266869048,
			"isDeleted": false,
			"id": "pXlsA2vp0Vd-0W96u78cI",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 973.770989243199,
			"y": 1694.7633740872475,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"oesfKSizZqP17sISMOUmS",
				"ZiZYXb1Ovd8LQgKl9CZRM",
				"L5P8oUyUefU8AEg2VAol9",
				"R4Wt27IpI3SParqnWsQL4"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3528,
			"versionNonce": 1291455560,
			"isDeleted": false,
			"id": "qZ9CzhdrLFP3ipGvsgN0R",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 939.4512758295718,
			"y": 1693.2691092701043,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"WvM_3Mo6zq_0sjh-NN_Tz",
				"ZiZYXb1Ovd8LQgKl9CZRM",
				"L5P8oUyUefU8AEg2VAol9",
				"R4Wt27IpI3SParqnWsQL4"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 3638,
			"versionNonce": 548518968,
			"isDeleted": false,
			"id": "eGNwC3omyrJ5klC3imyaz",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 958.7817088920751,
			"y": 1688.3949285633266,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"WvM_3Mo6zq_0sjh-NN_Tz",
				"ZiZYXb1Ovd8LQgKl9CZRM",
				"L5P8oUyUefU8AEg2VAol9",
				"R4Wt27IpI3SParqnWsQL4"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3551,
			"versionNonce": 1233208136,
			"isDeleted": false,
			"id": "KPuSqBEms3cY-I3gBuVZ1",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 939.7471614743886,
			"y": 1688.6211185006996,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"WvM_3Mo6zq_0sjh-NN_Tz",
				"ZiZYXb1Ovd8LQgKl9CZRM",
				"L5P8oUyUefU8AEg2VAol9",
				"R4Wt27IpI3SParqnWsQL4"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 3746,
			"versionNonce": 2090693944,
			"isDeleted": false,
			"id": "cVmAvxG05WNBZA0q60s0E",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 957.8203473873714,
			"y": 1732.1380562657064,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"ZiZYXb1Ovd8LQgKl9CZRM",
				"L5P8oUyUefU8AEg2VAol9",
				"R4Wt27IpI3SParqnWsQL4"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3704,
			"versionNonce": 1040816712,
			"isDeleted": false,
			"id": "ZdB3KbvfqkXsXEhfxj_P9",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 938.7857999696848,
			"y": 1732.3642462030793,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"ZiZYXb1Ovd8LQgKl9CZRM",
				"L5P8oUyUefU8AEg2VAol9",
				"R4Wt27IpI3SParqnWsQL4"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982467,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "text",
			"version": 3068,
			"versionNonce": 770826824,
			"isDeleted": false,
			"id": "sIc7Y0Ov",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 678.5270724400752,
			"y": 1889.0685209169026,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 63.83995056152344,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"X84EIMAhGOlZkyQUc-Cft"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528128137,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dbo.R9",
			"rawText": "dbo.R9",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dbo.R9",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4141,
			"versionNonce": 1279936056,
			"isDeleted": false,
			"id": "G_OfiIuPqmSvh-l4ddWey",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 679.9883329169634,
			"y": 1811.3563390385777,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"w2Ky3PUUMjD00UyCdYlY-",
				"PqJM6ms4v54K6FBnCrh2-",
				"41-yAlKQAfb3SZZ91LB07",
				"DRwgozgD6p-eXuv8UmmQu",
				"X84EIMAhGOlZkyQUc-Cft"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528128137,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2576,
			"versionNonce": 688806216,
			"isDeleted": false,
			"id": "bofk5-CM3UN56G441St-c",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 701.0290050200128,
			"y": 1834.6406272609872,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"wn_T0AlWun5HDobDM6C6P",
				"tiGcg4sAG_VtGH3xKkjkS",
				"DRwgozgD6p-eXuv8UmmQu",
				"X84EIMAhGOlZkyQUc-Cft"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528128137,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2718,
			"versionNonce": 2023014200,
			"isDeleted": false,
			"id": "UhfhFuR5Q1OMewO2kAPyJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 702.0143040241646,
			"y": 1838.825271717087,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"wn_T0AlWun5HDobDM6C6P",
				"tiGcg4sAG_VtGH3xKkjkS",
				"DRwgozgD6p-eXuv8UmmQu",
				"X84EIMAhGOlZkyQUc-Cft"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528128137,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3424,
			"versionNonce": 394522696,
			"isDeleted": false,
			"id": "65cs2zn4K6PQnUxQt01-j",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 732.6714186661893,
			"y": 1828.5124440277239,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"YLQxyelpIl0G-4QaI1Whb",
				"tiGcg4sAG_VtGH3xKkjkS",
				"DRwgozgD6p-eXuv8UmmQu",
				"X84EIMAhGOlZkyQUc-Cft"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528128137,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3515,
			"versionNonce": 120068152,
			"isDeleted": false,
			"id": "5_w-jji4nEKhNGNiqWhuQ",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 698.3517052525622,
			"y": 1827.0181792105807,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"nJHGPaAvCzg-lexnqv1Ay",
				"tiGcg4sAG_VtGH3xKkjkS",
				"DRwgozgD6p-eXuv8UmmQu",
				"X84EIMAhGOlZkyQUc-Cft"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528128137,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 3625,
			"versionNonce": 1898882888,
			"isDeleted": false,
			"id": "KxFjVmp-UQXrgsa0YU0kI",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 717.6821383150655,
			"y": 1822.143998503803,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"nJHGPaAvCzg-lexnqv1Ay",
				"tiGcg4sAG_VtGH3xKkjkS",
				"DRwgozgD6p-eXuv8UmmQu",
				"X84EIMAhGOlZkyQUc-Cft"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528128137,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3538,
			"versionNonce": 2078822712,
			"isDeleted": false,
			"id": "LFIPGdLBjbTfHnGtIOrVX",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 698.6475908973789,
			"y": 1822.370188441176,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"nJHGPaAvCzg-lexnqv1Ay",
				"tiGcg4sAG_VtGH3xKkjkS",
				"DRwgozgD6p-eXuv8UmmQu",
				"X84EIMAhGOlZkyQUc-Cft"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528128137,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 3733,
			"versionNonce": 1382710856,
			"isDeleted": false,
			"id": "fcd6V1RKu22mVLvmlqzT5",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 716.7207768103617,
			"y": 1865.8871262061828,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"tiGcg4sAG_VtGH3xKkjkS",
				"DRwgozgD6p-eXuv8UmmQu",
				"X84EIMAhGOlZkyQUc-Cft"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528128137,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3691,
			"versionNonce": 1043950136,
			"isDeleted": false,
			"id": "30d7YuYVAd74Iot-K6f2A",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 697.6862293926752,
			"y": 1866.1133161435557,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"tiGcg4sAG_VtGH3xKkjkS",
				"DRwgozgD6p-eXuv8UmmQu",
				"X84EIMAhGOlZkyQUc-Cft"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528128137,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "text",
			"version": 3092,
			"versionNonce": 1954687800,
			"isDeleted": false,
			"id": "S87j9BLW",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 806.4337980056677,
			"y": 1884.8311697264264,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 181.35983276367188,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"K89XGDrHxoxnguMEb-H48"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982468,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dbo.R9_Accesorios",
			"rawText": "dbo.R9_Accesorios",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dbo.R9_Accesorios",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4165,
			"versionNonce": 745751624,
			"isDeleted": false,
			"id": "ZCZ6R_JWa3MFT7B97onsH",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 866.65499958363,
			"y": 1807.1189878481011,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"Ha4afnichyf-iMOhuJfSJ",
				"heeW5813im86RWDOiZyG2",
				"bl0exoIBmv5l7BHHhuutU",
				"EWuB91fcVcUJUYahPjnQc",
				"K89XGDrHxoxnguMEb-H48"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982468,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2600,
			"versionNonce": 2055734328,
			"isDeleted": false,
			"id": "it5m9EEIwEwUYAnsTLQcp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 887.6956716866795,
			"y": 1830.4032760705106,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"z-OdjmHmp3pwDNn-CuN6p",
				"ILV9xvcx6HhzIRvpp-Noe",
				"EWuB91fcVcUJUYahPjnQc",
				"K89XGDrHxoxnguMEb-H48"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982468,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2742,
			"versionNonce": 1427340104,
			"isDeleted": false,
			"id": "r9XDBd4YzTAvZvPErMx83",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 888.6809706908313,
			"y": 1834.5879205266103,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"z-OdjmHmp3pwDNn-CuN6p",
				"ILV9xvcx6HhzIRvpp-Noe",
				"EWuB91fcVcUJUYahPjnQc",
				"K89XGDrHxoxnguMEb-H48"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982468,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3448,
			"versionNonce": 1416281400,
			"isDeleted": false,
			"id": "txLbQdXP-jfgzxXYowzw4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 919.3380853328558,
			"y": 1824.2750928372473,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"Z6SedwXIHsWuU_11i3pZn",
				"ILV9xvcx6HhzIRvpp-Noe",
				"EWuB91fcVcUJUYahPjnQc",
				"K89XGDrHxoxnguMEb-H48"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982468,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3539,
			"versionNonce": 177525320,
			"isDeleted": false,
			"id": "jtNL57D6PsO0BkoB2OsbJ",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 885.0183719192288,
			"y": 1822.7808280201045,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"SNI7_dicM4wi_sNPsgl_w",
				"ILV9xvcx6HhzIRvpp-Noe",
				"EWuB91fcVcUJUYahPjnQc",
				"K89XGDrHxoxnguMEb-H48"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982468,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 3649,
			"versionNonce": 864966200,
			"isDeleted": false,
			"id": "9jyfM06zmfTlTgqMAsSvg",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 904.3488049817321,
			"y": 1817.9066473133264,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"SNI7_dicM4wi_sNPsgl_w",
				"ILV9xvcx6HhzIRvpp-Noe",
				"EWuB91fcVcUJUYahPjnQc",
				"K89XGDrHxoxnguMEb-H48"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982468,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3562,
			"versionNonce": 1406355784,
			"isDeleted": false,
			"id": "pstfivRkGu_l524JQaO-0",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 885.3142575640455,
			"y": 1818.1328372506998,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"SNI7_dicM4wi_sNPsgl_w",
				"ILV9xvcx6HhzIRvpp-Noe",
				"EWuB91fcVcUJUYahPjnQc",
				"K89XGDrHxoxnguMEb-H48"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982468,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 3757,
			"versionNonce": 2094452536,
			"isDeleted": false,
			"id": "00sw1-lgpdBnWhXWmrIyN",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 903.3874434770283,
			"y": 1861.6497750157062,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"ILV9xvcx6HhzIRvpp-Noe",
				"EWuB91fcVcUJUYahPjnQc",
				"K89XGDrHxoxnguMEb-H48"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982468,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3715,
			"versionNonce": 2083184712,
			"isDeleted": false,
			"id": "dIr_W_m5lYtQSfGXJAdgY",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 884.3528960593418,
			"y": 1861.8759649530796,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"ILV9xvcx6HhzIRvpp-Noe",
				"EWuB91fcVcUJUYahPjnQc",
				"K89XGDrHxoxnguMEb-H48"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982468,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "rectangle",
			"version": 202,
			"versionNonce": 1594298168,
			"isDeleted": false,
			"id": "pcNpjPzeHTWDE6X_bHNh7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 498.33233258356086,
			"y": 1426.9985162872642,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 552.3809523809524,
			"height": 518.3333333333333,
			"seed": 1220187873,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "FQzdXOQpXouZhMIOBUQyS",
					"type": "arrow"
				}
			],
			"updated": 1684528118814,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 589,
			"versionNonce": 1870578760,
			"isDeleted": false,
			"id": "FQzdXOQpXouZhMIOBUQyS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1249.849357096851,
			"y": 1441.6992633602952,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 172.45273858817882,
			"height": 1.688131918334875,
			"seed": 1369015183,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528135395,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "QjuIQCHJPfYAyks8P6A-H",
				"focus": -0.6461260643397446,
				"gap": 17.94923289386861
			},
			"endBinding": {
				"elementId": "pcNpjPzeHTWDE6X_bHNh7",
				"focus": -0.9157700812257996,
				"gap": 26.68333354415904
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-172.45273858817882,
					1.688131918334875
				]
			]
		},
		{
			"type": "text",
			"version": 3445,
			"versionNonce": 1122394424,
			"isDeleted": false,
			"id": "Td0Dc4bn",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 673.189559364044,
			"y": 1148.5212738930927,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 221.9998321533203,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"OmJIQNiMRfJosVaI4LnYG"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "MU2OcMhYdESJXWu1jyQVn",
					"type": "arrow"
				}
			],
			"updated": 1684527982468,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dw.FactSaleswoChannel",
			"rawText": "dw.FactSaleswoChannel",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dw.FactSaleswoChannel",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4521,
			"versionNonce": 236285512,
			"isDeleted": false,
			"id": "SAuxfWZ4_qIN7R_M6wpxE",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 753.7307606368302,
			"y": 1070.8090920147683,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"NPgjsN_fHvY75_QghCM9f",
				"MwOGzQG64-gYLZhk80xyr",
				"JrBkwhDHX5Zt-nPGh6ik1",
				"rQuMIFotm8_EYh7TjxtVC",
				"OmJIQNiMRfJosVaI4LnYG"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "MU2OcMhYdESJXWu1jyQVn",
					"type": "arrow"
				},
				{
					"id": "XhCturJKkpJ-yvQevj2f9",
					"type": "arrow"
				}
			],
			"updated": 1684527982468,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2952,
			"versionNonce": 452295224,
			"isDeleted": false,
			"id": "XXh_I3W1RtSBEkh83-khm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 774.7714327398801,
			"y": 1094.0933802371778,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"H1SLJSlxKk5cEejbO4pyL",
				"ror-BqBjxed5LxzznW1mx",
				"rQuMIFotm8_EYh7TjxtVC",
				"OmJIQNiMRfJosVaI4LnYG"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982468,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 3094,
			"versionNonce": 1423992136,
			"isDeleted": false,
			"id": "hfuQ-QoKlOzpgyDTzJr29",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 775.7567317440319,
			"y": 1098.2780246932775,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"H1SLJSlxKk5cEejbO4pyL",
				"ror-BqBjxed5LxzznW1mx",
				"rQuMIFotm8_EYh7TjxtVC",
				"OmJIQNiMRfJosVaI4LnYG"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982468,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3800,
			"versionNonce": 867791672,
			"isDeleted": false,
			"id": "XSu6cCiiqwJ3Z7BH2G8fb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 806.4138463860561,
			"y": 1087.9651970039145,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"7jV95ht9Ggp3f5sN5aRrZ",
				"ror-BqBjxed5LxzznW1mx",
				"rQuMIFotm8_EYh7TjxtVC",
				"OmJIQNiMRfJosVaI4LnYG"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982468,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3891,
			"versionNonce": 355761224,
			"isDeleted": false,
			"id": "GDqlR3CKfzqVK7F_XhbPo",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 772.094132972429,
			"y": 1086.4709321867708,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"kr2hUqcZCHrZAZkJLCUF0",
				"ror-BqBjxed5LxzznW1mx",
				"rQuMIFotm8_EYh7TjxtVC",
				"OmJIQNiMRfJosVaI4LnYG"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982468,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 4001,
			"versionNonce": 1670794296,
			"isDeleted": false,
			"id": "-4LnGwOGiOs8HQfKmusqr",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 791.4245660349322,
			"y": 1081.5967514799936,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"kr2hUqcZCHrZAZkJLCUF0",
				"ror-BqBjxed5LxzznW1mx",
				"rQuMIFotm8_EYh7TjxtVC",
				"OmJIQNiMRfJosVaI4LnYG"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982468,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3914,
			"versionNonce": 15577928,
			"isDeleted": false,
			"id": "pnA_zXL_dxqusT-xy6qIG",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 772.3900186172457,
			"y": 1081.822941417366,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"kr2hUqcZCHrZAZkJLCUF0",
				"ror-BqBjxed5LxzznW1mx",
				"rQuMIFotm8_EYh7TjxtVC",
				"OmJIQNiMRfJosVaI4LnYG"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982468,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 4109,
			"versionNonce": 342885688,
			"isDeleted": false,
			"id": "Owei7W3rOX1dtBfAwPzFB",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 790.4632045302285,
			"y": 1125.3398791823734,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"ror-BqBjxed5LxzznW1mx",
				"rQuMIFotm8_EYh7TjxtVC",
				"OmJIQNiMRfJosVaI4LnYG"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982468,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 4067,
			"versionNonce": 778570312,
			"isDeleted": false,
			"id": "LQ7Q_AvoVnruujnZJ8u3f",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 771.4286571125419,
			"y": 1125.5660691197459,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"ror-BqBjxed5LxzznW1mx",
				"rQuMIFotm8_EYh7TjxtVC",
				"OmJIQNiMRfJosVaI4LnYG"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982468,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "text",
			"version": 3164,
			"versionNonce": 1403690552,
			"isDeleted": false,
			"id": "W7p4JFRB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1692.168592334654,
			"y": 1735.2355596073785,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 155.2798614501953,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"yZawximiFWpDHaigmjEbN"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982468,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dbo.FullDimDate",
			"rawText": "dbo.FullDimDate",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dbo.FullDimDate",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4238,
			"versionNonce": 142573896,
			"isDeleted": false,
			"id": "c0okYJiDNFSqzMBu4NMjp",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1739.349808255878,
			"y": 1657.5233777290541,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"TVJreWfY7L3tyhsiTYRp-",
				"0xdrUmK0BoVlTiUbn-ykO",
				"NJ4VNdm-JIHwo3Ub4pIqB",
				"uC88nmpeLXRGyrtitJeyo",
				"yZawximiFWpDHaigmjEbN"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "8zAO-KuP6Htmma9tBBn-h",
					"type": "arrow"
				}
			],
			"updated": 1684527982469,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2672,
			"versionNonce": 1646925624,
			"isDeleted": false,
			"id": "rf4y_WuB6_fgb5ukFyFOA",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1760.3904803589276,
			"y": 1680.8076659514636,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"qqK-0P-AXps5SolnYVzZ1",
				"O35YwRNUNaQq4jFkd7VTB",
				"uC88nmpeLXRGyrtitJeyo",
				"yZawximiFWpDHaigmjEbN"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2814,
			"versionNonce": 1049630792,
			"isDeleted": false,
			"id": "8RudJr9TtytoQHlpFa_Vb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1761.3757793630793,
			"y": 1684.9923104075633,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"qqK-0P-AXps5SolnYVzZ1",
				"O35YwRNUNaQq4jFkd7VTB",
				"uC88nmpeLXRGyrtitJeyo",
				"yZawximiFWpDHaigmjEbN"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.895953960699555,
					10.390279849859406
				],
				[
					7.4113021320667185,
					21.283154578180127
				],
				[
					11.713174047234979,
					19.99348003597825
				],
				[
					11.442635055303672,
					10.606410274819945
				],
				[
					19.57156398053291,
					-0.4430697209237241
				]
			]
		},
		{
			"type": "line",
			"version": 3520,
			"versionNonce": 1146253368,
			"isDeleted": false,
			"id": "fD3XAbXEZQt4_nBnlFQxz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1792.032894005104,
			"y": 1674.6794827182002,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"lSwuK8Iaoqg8UluaDL6cZ",
				"O35YwRNUNaQq4jFkd7VTB",
				"uC88nmpeLXRGyrtitJeyo",
				"yZawximiFWpDHaigmjEbN"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.03742304744946434,
					-10.280296978811299
				],
				[
					-41.69086341129026,
					-10.610470106732999
				],
				[
					-41.94767995449673,
					41.58596015961359
				],
				[
					0.20056107620854924,
					41.8310160463804
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3611,
			"versionNonce": 880136008,
			"isDeleted": false,
			"id": "aTCbaKxjQWZyW7wyrvbhv",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1757.7131805914769,
			"y": 1673.1852179010566,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"vDwinTZJ-xLIxUAPebWKc",
				"O35YwRNUNaQq4jFkd7VTB",
				"uC88nmpeLXRGyrtitJeyo",
				"yZawximiFWpDHaigmjEbN"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.931807646605147,
					0.034763199846892336
				]
			]
		},
		{
			"type": "line",
			"version": 3721,
			"versionNonce": 1376233784,
			"isDeleted": false,
			"id": "94JEjG-RDyZWeQuTj4hDc",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1777.0436136539802,
			"y": 1668.3110371942794,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"vDwinTZJ-xLIxUAPebWKc",
				"O35YwRNUNaQq4jFkd7VTB",
				"uC88nmpeLXRGyrtitJeyo",
				"yZawximiFWpDHaigmjEbN"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3634,
			"versionNonce": 1921820232,
			"isDeleted": false,
			"id": "nd4APExlixiADSnjx6RUM",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1758.0090662362936,
			"y": 1668.537227131652,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"vDwinTZJ-xLIxUAPebWKc",
				"O35YwRNUNaQq4jFkd7VTB",
				"uC88nmpeLXRGyrtitJeyo",
				"yZawximiFWpDHaigmjEbN"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "line",
			"version": 3829,
			"versionNonce": 1185792568,
			"isDeleted": false,
			"id": "F4kfPK36gMw7kSFFKT4q4",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1776.0822521492764,
			"y": 1712.0541648966591,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"O35YwRNUNaQq4jFkd7VTB",
				"uC88nmpeLXRGyrtitJeyo",
				"yZawximiFWpDHaigmjEbN"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.124279794031136,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 3787,
			"versionNonce": 363896136,
			"isDeleted": false,
			"id": "z_5CvPQKK-0ApeBw4b8G1",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1757.0477047315899,
			"y": 1712.2803548340316,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"O35YwRNUNaQq4jFkd7VTB",
				"uC88nmpeLXRGyrtitJeyo",
				"yZawximiFWpDHaigmjEbN"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.487284381001047,
					0.03476319984691851
				]
			]
		},
		{
			"type": "arrow",
			"version": 1293,
			"versionNonce": 1361623864,
			"isDeleted": false,
			"id": "MU2OcMhYdESJXWu1jyQVn",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1252.4769569521338,
			"y": 1395.0406603669796,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 433.98632662159775,
			"height": 210.360538427419,
			"seed": 1369015183,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "QjuIQCHJPfYAyks8P6A-H",
				"focus": -0.28604898637910064,
				"gap": 15.321633038585787
			},
			"endBinding": {
				"elementId": "Td0Dc4bn",
				"focus": 0.11446946033763146,
				"gap": 12.158848046467938
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-433.98632662159775,
					-210.360538427419
				]
			]
		},
		{
			"type": "arrow",
			"version": 687,
			"versionNonce": 1061008456,
			"isDeleted": false,
			"id": "8zAO-KuP6Htmma9tBBn-h",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1353.6945540253196,
			"y": 1505.7507189706212,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 379.093956348559,
			"height": 187.08912603304725,
			"seed": 1369015183,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "PKX2ZYgo",
				"focus": -0.0699326804655159,
				"gap": 7.479695410830118
			},
			"endBinding": {
				"elementId": "c0okYJiDNFSqzMBu4NMjp",
				"focus": -0.3499511732636092,
				"gap": 6.561297881999508
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					93.01873093919357,
					102.3297621767274
				],
				[
					379.093956348559,
					187.08912603304725
				]
			]
		},
		{
			"type": "arrow",
			"version": 665,
			"versionNonce": 601658424,
			"isDeleted": false,
			"id": "G726pOmcvlcBkYhJHc2jH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 80,
			"angle": 0,
			"x": -536.3858881673692,
			"y": 589.7320952586517,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 363.60588277371824,
			"height": 5.960752176618509,
			"seed": 574520847,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					363.60588277371824,
					-5.960752176618509
				]
			]
		},
		{
			"type": "text",
			"version": 688,
			"versionNonce": 84929352,
			"isDeleted": false,
			"id": "22GgEefv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 80,
			"angle": 0,
			"x": -121.25162725191524,
			"y": 488.39930825614033,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 341.9183349609375,
			"height": 36.14748415627665,
			"seed": 1664452687,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false,
			"fontSize": 28.91798732502132,
			"fontFamily": 1,
			"text": "Consulta información de:",
			"rawText": "Consulta información de:",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Consulta información de:",
			"lineHeight": 1.25,
			"baseline": 25
		},
		{
			"type": "text",
			"version": 738,
			"versionNonce": 78466360,
			"isDeleted": false,
			"id": "41lGpJ5G",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 80,
			"angle": 0,
			"x": -94.12294232989791,
			"y": 563.7106836116889,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 299.5941467285156,
			"height": 36.14748415627665,
			"seed": 1664452687,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false,
			"fontSize": 28.91798732502132,
			"fontFamily": 1,
			"text": "Carga información en:",
			"rawText": "Carga información en:",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Carga información en:",
			"lineHeight": 1.25,
			"baseline": 25
		},
		{
			"type": "arrow",
			"version": 376,
			"versionNonce": 1635992136,
			"isDeleted": false,
			"id": "vVYeJo1WCYL3zpSlOnb9f",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -532.2714129004231,
			"y": 433.4936959302793,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 352.7994453652601,
			"height": 2.891798732502132,
			"seed": 1834760815,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					352.7994453652601,
					-2.891798732502132
				]
			]
		},
		{
			"type": "text",
			"version": 771,
			"versionNonce": 1560208952,
			"isDeleted": false,
			"id": "tZlInIqI",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 80,
			"angle": 0,
			"x": -92.08172908956396,
			"y": 405.2986582883834,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 264.7391357421875,
			"height": 50.60647781878732,
			"seed": 1664452687,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false,
			"fontSize": 40.485182255029855,
			"fontFamily": 1,
			"text": "Flujo principal",
			"rawText": "Flujo principal",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Flujo principal",
			"lineHeight": 1.25,
			"baseline": 35
		},
		{
			"type": "arrow",
			"version": 377,
			"versionNonce": 594786632,
			"isDeleted": false,
			"id": "TMIQnHpCmOgF-f1AC8XPi",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -529.5550935301422,
			"y": 511.48991674197237,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 355.69124409776225,
			"height": 0,
			"seed": 1720843407,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					355.69124409776225,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 880,
			"versionNonce": 1236623160,
			"isDeleted": false,
			"id": "D42w7S2KZ7Ybm0j3ROjEj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -704.2580555022802,
			"y": 184.46897943418867,
			"strokeColor": "#0091e2",
			"backgroundColor": "transparent",
			"width": 965.5141095050149,
			"height": 589.4717721188509,
			"seed": 302519605,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 2752,
			"versionNonce": 1581076552,
			"isDeleted": false,
			"id": "ATE10Hsb",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -683.2282183956037,
			"y": 206.62932530013495,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 158.51254272460938,
			"height": 91.22729405629221,
			"seed": 35046555,
			"groupIds": [
				"bxf6ScLMkzwiMLpyHgKRE"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false,
			"fontSize": 72.98183524503376,
			"fontFamily": 1,
			"text": "Keys",
			"rawText": "Keys",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Keys",
			"lineHeight": 1.25,
			"baseline": 64
		},
		{
			"type": "rectangle",
			"version": 2117,
			"versionNonce": 724875320,
			"isDeleted": false,
			"id": "ttha8pfpdcDv_nAwmzyxC",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1282.1471681198216,
			"y": 1672.399066354957,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e1488",
			"width": 85.17426249185807,
			"height": 85.09270010541165,
			"seed": 1087403015,
			"groupIds": [
				"S2zAz-DY1b5BBm3HyNjlA",
				"IJNOzg7FUqceq_7t2z4-X",
				"pMnty1TZjTSswDhzADw4x"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "CLRRPNHhLeU09EXr57_Zf",
					"type": "arrow"
				}
			],
			"updated": 1684527982469,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1273,
			"versionNonce": 1505494856,
			"isDeleted": false,
			"id": "5m0msMW58rOKmi1uADe78",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1315.1687259697162,
			"y": 1707.7280023977619,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.51105029288197,
			"height": 35.539732911894475,
			"seed": 1235612649,
			"groupIds": [
				"6DUGneghXdyC_WKC6jlaN",
				"IJNOzg7FUqceq_7t2z4-X",
				"pMnty1TZjTSswDhzADw4x"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-16.820949905493464,
					33.64891394335074
				],
				[
					-0.6842599011139163,
					35.539732911894475
				],
				[
					8.690100387388505,
					17.416411477550696
				],
				[
					1.1882436250464703,
					0.745228440432334
				]
			]
		},
		{
			"type": "line",
			"version": 1273,
			"versionNonce": 895545656,
			"isDeleted": false,
			"id": "kaG09SE9cvIZJsKi0K-9k",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1347.5236910511856,
			"y": 1728.7331380671817,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 46.066480238311605,
			"height": 58.1383889698984,
			"seed": 47340327,
			"groupIds": [
				"6DUGneghXdyC_WKC6jlaN",
				"IJNOzg7FUqceq_7t2z4-X",
				"pMnty1TZjTSswDhzADw4x"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-19.767215169387292,
					-42.83742205463878
				],
				[
					-38.54883282525994,
					-43.6037917274238
				],
				[
					-39.875244313683915,
					-30.391842834014387
				],
				[
					-30.254813558131797,
					-29.0691944849492
				],
				[
					-10.394170790466104,
					13.770870223733658
				],
				[
					4.87535158072104,
					14.5345972424746
				],
				[
					6.1912359246276925,
					1.3213270220431457
				],
				[
					4.875351580721041,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 1619,
			"versionNonce": 38526536,
			"isDeleted": false,
			"id": "tyoc6kMq",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1077.210843558263,
			"y": 1764.0500474107043,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 495.0048828125,
			"height": 31.71184852903549,
			"seed": 242323145,
			"groupIds": [
				"pMnty1TZjTSswDhzADw4x"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false,
			"fontSize": 26.426540440862908,
			"fontFamily": 1,
			"text": "Mover archivos a directorio processed",
			"rawText": "Mover archivos a directorio processed",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Mover archivos a directorio processed",
			"lineHeight": 1.2,
			"baseline": 22
		},
		{
			"type": "arrow",
			"version": 377,
			"versionNonce": 2141063736,
			"isDeleted": false,
			"id": "CLRRPNHhLeU09EXr57_Zf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1328.8351330377513,
			"y": 1506.9866317761239,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 2.1219478608991267,
			"height": 150.99999999999977,
			"seed": 348269103,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982469,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "PKX2ZYgo",
				"focus": -0.04013325315322282,
				"gap": 8.71560821633284
			},
			"endBinding": {
				"elementId": "ttha8pfpdcDv_nAwmzyxC",
				"focus": 0.16263052800939648,
				"gap": 14.412434578833313
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					2.1219478608991267,
					150.99999999999977
				]
			]
		},
		{
			"type": "line",
			"version": 526,
			"versionNonce": 1379341624,
			"isDeleted": false,
			"id": "g1Lp0HpKhP8Mxlk0evK9y",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 5.870211371438813,
			"y": 970.4392778828646,
			"strokeColor": "#000000",
			"backgroundColor": "#fa5252",
			"width": 56.06060606060636,
			"height": 112.1212121212127,
			"seed": 947402726,
			"groupIds": [
				"E-hRvO02-1AxIlf__2eMU"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527986773,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					56.06060606060636,
					3.552713678800501e-14
				],
				[
					28.030303030303124,
					112.12121212121271
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "ellipse",
			"version": 501,
			"versionNonce": 1616509512,
			"isDeleted": false,
			"id": "HbJiN46mvqnF_1k9IpgZU",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 19.88536288658986,
			"y": 1096.575641519229,
			"strokeColor": "#000000",
			"backgroundColor": "#fa5252",
			"width": 28.030303030303173,
			"height": 28.030303030303173,
			"seed": 1412702586,
			"groupIds": [
				"E-hRvO02-1AxIlf__2eMU"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527986773,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 271,
			"versionNonce": 1712303672,
			"isDeleted": false,
			"id": "8aStKUGl",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -117.67144215021028,
			"y": 1160.3603073742065,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 312.8797302246094,
			"height": 75,
			"seed": 1326396232,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527986773,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "El tipo de dato de\ncolumna FECHAFACTURA\npuede ayudar con el rendimiento",
			"rawText": "El tipo de dato de\ncolumna FECHAFACTURA\npuede ayudar con el rendimiento",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "El tipo de dato de\ncolumna FECHAFACTURA\npuede ayudar con el rendimiento",
			"lineHeight": 1.25,
			"baseline": 68
		},
		{
			"type": "rectangle",
			"version": 154,
			"versionNonce": 1884280136,
			"isDeleted": false,
			"id": "fDTjA4yGaKbcNFwaCPMQ-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -133.33433408310623,
			"y": 911.702298716198,
			"strokeColor": "#000000",
			"backgroundColor": "#e64980",
			"width": 353.33333333333303,
			"height": 373.33333333333326,
			"seed": 12986440,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "bcrdcpeqILRoUtTJwWny4",
					"type": "arrow"
				}
			],
			"updated": 1684528001166,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 270,
			"versionNonce": 1075463240,
			"isDeleted": false,
			"id": "69MBr8iS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1470.5508181199023,
			"y": 1365.087580101479,
			"strokeColor": "#000000",
			"backgroundColor": "#fa5252",
			"width": 1768.70361328125,
			"height": 525,
			"seed": 15497032,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "bcrdcpeqILRoUtTJwWny4",
					"type": "arrow"
				}
			],
			"updated": 1684527991941,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "DELETE FROM [dw].[FactSales]\nWHERE DATE IN \n(\nSELECT \nCONCAT(SUBSTRING(SUB.FECHA1,5,2),'.',SUBSTRING(SUB.FECHA1,7,2),'.',SUBSTRING(SUB.FECHA1,1,4))\nFROM ( \n        SELECT \n    MAX(CONCAT(SUBSTRING(FECHAFACTURA,7,4),SUBSTRING(FECHAFACTURA,1,2),SUBSTRING(FECHAFACTURA,4,2))) FECHA1\n    FROM [stating].[DailySales] D  WITH(NOLOCK)\n        ) SUB \n)\n \nPuede Ser =>\nDelete from dw.FactSales\nWhere Date = ( SELECT MAX(FECHAFACTURA) FROM stating.DailySales)",
			"rawText": "DELETE FROM [dw].[FactSales]\nWHERE DATE IN \n(\nSELECT \nCONCAT(SUBSTRING(SUB.FECHA1,5,2),'.',SUBSTRING(SUB.FECHA1,7,2),'.',SUBSTRING(SUB.FECHA1,1,4))\nFROM ( \n        SELECT \n    MAX(CONCAT(SUBSTRING(FECHAFACTURA,7,4),SUBSTRING(FECHAFACTURA,1,2),SUBSTRING(FECHAFACTURA,4,2))) FECHA1\n    FROM [stating].[DailySales] D  WITH(NOLOCK)\n        ) SUB \n)\n \nPuede Ser =>\nDelete from dw.FactSales\nWhere Date = ( SELECT MAX(FECHAFACTURA) FROM stating.DailySales)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "DELETE FROM [dw].[FactSales]\nWHERE DATE IN \n(\nSELECT \nCONCAT(SUBSTRING(SUB.FECHA1,5,2),'.',SUBSTRING(SUB.FECHA1,7,2),'.',SUBSTRING(SUB.FECHA1,1,4))\nFROM ( \n        SELECT \n    MAX(CONCAT(SUBSTRING(FECHAFACTURA,7,4),SUBSTRING(FECHAFACTURA,1,2),SUBSTRING(FECHAFACTURA,4,2))) FECHA1\n    FROM [stating].[DailySales] D  WITH(NOLOCK)\n        ) SUB \n)\n \nPuede Ser =>\nDelete from dw.FactSales\nWhere Date = ( SELECT MAX(FECHAFACTURA) FROM stating.DailySales)",
			"lineHeight": 1.25,
			"baseline": 515
		},
		{
			"id": "XhCturJKkpJ-yvQevj2f9",
			"type": "arrow",
			"x": 1257.022982952313,
			"y": 1106.5959687641048,
			"width": 428.57142857142844,
			"height": 2.4191721062818488,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "#fa5252",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"seed": 245933112,
			"version": 741,
			"versionNonce": 1541831240,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1684527982470,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-428.57142857142844,
					-2.4191721062818488
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "8N0ahz44JiMhPYFlzwxy6",
				"focus": -0.5300717446271163,
				"gap": 8.645749899426164
			},
			"endBinding": {
				"elementId": "SAuxfWZ4_qIN7R_M6wpxE",
				"focus": 0.02866272695898613,
				"gap": 10.259641379097445
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"type": "arrow",
			"version": 388,
			"versionNonce": 1555034440,
			"isDeleted": false,
			"id": "HccE0RsWXEk03jr80hdqp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1324.277535665955,
			"y": 1176.2426484791724,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 0.4354240894829218,
			"height": 156.190476190475,
			"seed": 348269103,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684527982470,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "4N58shO9",
				"focus": 0.005571990010269892,
				"gap": 5.590672538429544
			},
			"endBinding": {
				"elementId": "QjuIQCHJPfYAyks8P6A-H",
				"focus": 0.0361956241418527,
				"gap": 19.60885656731182
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-0.4354240894829218,
					156.190476190475
				]
			]
		},
		{
			"id": "Fy2xLDgYmIj5zSinAwZ8U",
			"type": "rectangle",
			"x": 1071.308697238028,
			"y": 506.7888788027781,
			"width": 485.71428571428555,
			"height": 220.0000000000001,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"seed": 1384263496,
			"version": 94,
			"versionNonce": 2145036872,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "wgLkYPMPQUsu7wE7qRt_l",
					"type": "arrow"
				},
				{
					"id": "Gshdfn2q3jOGBsyihM4Zp",
					"type": "arrow"
				}
			],
			"updated": 1684528030070,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 2200,
			"versionNonce": 2073202488,
			"isDeleted": false,
			"id": "JQs8MNCnaqSdNyq_izyP9",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1385.8854375361927,
			"y": 550.8217497246723,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e1488",
			"width": 85.17426249185807,
			"height": 85.09270010541165,
			"seed": 1087403015,
			"groupIds": [
				"usYu13yRmxxJP3PiLpHC3",
				"oZKGchiCCFElATuXEjQfC",
				"cZkdeHyf77d5Uzi8KBHUx"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "i-vwSw6s7D0BEuQro-e8F",
					"type": "arrow"
				}
			],
			"updated": 1684528095029,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1355,
			"versionNonce": 1431240760,
			"isDeleted": false,
			"id": "AtyCEA79Y7s4h99la6xbL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1418.9069953860871,
			"y": 586.1506857674773,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.51105029288197,
			"height": 35.539732911894475,
			"seed": 1235612649,
			"groupIds": [
				"6Mdte74StfS5q7odM-K5A",
				"oZKGchiCCFElATuXEjQfC",
				"cZkdeHyf77d5Uzi8KBHUx"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982470,
			"link": null,
			"locked": false,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-16.820949905493464,
					33.64891394335074
				],
				[
					-0.6842599011139163,
					35.539732911894475
				],
				[
					8.690100387388505,
					17.416411477550696
				],
				[
					1.1882436250464703,
					0.745228440432334
				]
			]
		},
		{
			"type": "line",
			"version": 1355,
			"versionNonce": 726286152,
			"isDeleted": false,
			"id": "MdCd921sdAEiRd9s8S1ts",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1451.2619604675565,
			"y": 607.1558214368969,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 46.066480238311605,
			"height": 58.1383889698984,
			"seed": 47340327,
			"groupIds": [
				"6Mdte74StfS5q7odM-K5A",
				"oZKGchiCCFElATuXEjQfC",
				"cZkdeHyf77d5Uzi8KBHUx"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684527982470,
			"link": null,
			"locked": false,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-19.767215169387292,
					-42.83742205463878
				],
				[
					-38.54883282525994,
					-43.6037917274238
				],
				[
					-39.875244313683915,
					-30.391842834014387
				],
				[
					-30.254813558131797,
					-29.0691944849492
				],
				[
					-10.394170790466104,
					13.770870223733658
				],
				[
					4.87535158072104,
					14.5345972424746
				],
				[
					6.1912359246276925,
					1.3213270220431457
				],
				[
					4.875351580721041,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 1724,
			"versionNonce": 673786168,
			"isDeleted": false,
			"id": "YQRBS0rf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1331.503411375513,
			"y": 642.4727307804197,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 193.8962860107422,
			"height": 63.42369705807098,
			"seed": 242323145,
			"groupIds": [
				"cZkdeHyf77d5Uzi8KBHUx"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684528081720,
			"link": null,
			"locked": false,
			"fontSize": 26.426540440862908,
			"fontFamily": 1,
			"text": "Llamar SP\nTruncateTable",
			"rawText": "Llamar SP\nTruncateTable",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Llamar SP\nTruncateTable",
			"lineHeight": 1.2,
			"baseline": 54
		},
		{
			"id": "bcrdcpeqILRoUtTJwWny4",
			"type": "arrow",
			"x": 608.916931946356,
			"y": 631.8138442308052,
			"width": 428.0940820168737,
			"height": 277.9903940857464,
			"angle": 0,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"seed": 14539320,
			"version": 434,
			"versionNonce": 1113296440,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1684528071783,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-428.0940820168737,
					277.9903940857464
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "VwyZ1sLWEIxAVGlSqVHC9",
				"focus": 0.735522121316589,
				"gap": 14.580024669415423
			},
			"endBinding": {
				"elementId": "fDTjA4yGaKbcNFwaCPMQ-",
				"focus": -0.3294184365138444,
				"gap": 1.89806039964634
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "jYFLSkqSuFZRtiGPf0sQZ",
			"type": "arrow",
			"x": 1262.7372686665985,
			"y": 1072.5031645170639,
			"width": 454.2857142857142,
			"height": 85.7142857142859,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"seed": 315154248,
			"version": 118,
			"versionNonce": 1982618440,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1684527982470,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-454.2857142857142,
					-85.7142857142859
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "8N0ahz44JiMhPYFlzwxy6",
				"focus": -0.07763549235775782,
				"gap": 2.9314641851406122
			},
			"endBinding": {
				"elementId": "gH2ETLFwpiBGyhEZcI6pe",
				"focus": 0.3938763526460501,
				"gap": 5.481863601318707
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "r9_Vb6r_fLYEQ0dMn720k",
			"type": "arrow",
			"x": 1264.6687328517392,
			"y": 1053.8524636447946,
			"width": 574.5758128254051,
			"height": 344.20644198487366,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"seed": 822651720,
			"version": 78,
			"versionNonce": 1133546568,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1684528071783,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-574.5758128254051,
					-344.20644198487366
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "8N0ahz44JiMhPYFlzwxy6",
				"focus": -0.10007481352030767,
				"gap": 1
			},
			"endBinding": {
				"elementId": "XgssF7zW",
				"focus": 0.10215160245064184,
				"gap": 7.914680639811763
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"type": "arrow",
			"version": 315,
			"versionNonce": 672492088,
			"isDeleted": false,
			"id": "Gshdfn2q3jOGBsyihM4Zp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1325.0479195974322,
			"y": 738.0185856217878,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 2.404754754446003,
			"height": 268.57142857142856,
			"seed": 2042430991,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684528032091,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "Fy2xLDgYmIj5zSinAwZ8U",
				"focus": -0.040176020536036035,
				"gap": 11.229706819009664
			},
			"endBinding": {
				"elementId": "8N0ahz44JiMhPYFlzwxy6",
				"focus": 0.15713393225522412,
				"gap": 17.83291942469475
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					2.404754754446003,
					268.57142857142856
				]
			]
		},
		{
			"id": "0rlyiRkoaoB4xZLNW5_es",
			"type": "arrow",
			"x": 1157.0229829523123,
			"y": 599.9314320048445,
			"width": 465.7142857142858,
			"height": 50.24837028465504,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"seed": 1223265352,
			"version": 100,
			"versionNonce": 758974264,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "4sVnV8Ua"
				}
			],
			"updated": 1684528071783,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-465.7142857142858,
					50.24837028465504
				]
			],
			"lastCommittedPoint": [
				-371.42857142857156,
				48.571428571428555
			],
			"startBinding": {
				"elementId": "_pSlEUKQIj3Rt9gfx8yib",
				"focus": -0.03910650905493222,
				"gap": 7.155931199254951
			},
			"endBinding": {
				"elementId": "VwyZ1sLWEIxAVGlSqVHC9",
				"focus": 0.37993203058245256,
				"gap": 3.3505882572980568
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "4sVnV8Ua",
			"type": "text",
			"x": 866.7707410002336,
			"y": 607.8603073742067,
			"width": 209.07591247558594,
			"height": 35,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 1289762104,
			"version": 17,
			"versionNonce": 396235336,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1684528070344,
			"link": null,
			"locked": false,
			"text": "Consulta fecha",
			"rawText": "Consulta fecha",
			"fontSize": 28,
			"fontFamily": 1,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 25,
			"containerId": "0rlyiRkoaoB4xZLNW5_es",
			"originalText": "Consulta fecha",
			"lineHeight": 1.25
		},
		{
			"id": "y8phaNPqgenOKdtaOKS_B",
			"type": "arrow",
			"x": 1162.7372686665976,
			"y": 603.9317359456353,
			"width": 345.7142857142853,
			"height": 331.42857142857133,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"seed": 1847287368,
			"version": 54,
			"versionNonce": 1445658424,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "Cb9pIQkS"
				}
			],
			"updated": 1684528063331,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-345.7142857142853,
					331.42857142857133
				]
			],
			"lastCommittedPoint": [
				-345.7142857142853,
				331.42857142857133
			],
			"startBinding": {
				"elementId": "_pSlEUKQIj3Rt9gfx8yib",
				"focus": 0.3714094573695,
				"gap": 1.4416454849696265
			},
			"endBinding": {
				"elementId": "gH2ETLFwpiBGyhEZcI6pe",
				"focus": 0.23988319982156675,
				"gap": 14.053292172746694
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "Cb9pIQkS",
			"type": "text",
			"x": 945.8921497352362,
			"y": 752.146021659921,
			"width": 87.9759521484375,
			"height": 35,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 1639192904,
			"version": 10,
			"versionNonce": 1284721736,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1684528066666,
			"link": null,
			"locked": false,
			"text": "Elimina",
			"rawText": "Elimina",
			"fontSize": 28,
			"fontFamily": 1,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 25,
			"containerId": "y8phaNPqgenOKdtaOKS_B",
			"originalText": "Elimina",
			"lineHeight": 1.25
		},
		{
			"id": "i-vwSw6s7D0BEuQro-e8F",
			"type": "arrow",
			"x": 1482.7372686665976,
			"y": 601.0745930884924,
			"width": 225.71428571428578,
			"height": 782.857142857143,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"seed": 753548088,
			"version": 175,
			"versionNonce": 1036622920,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1684528099886,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					142.85714285714312,
					114.28571428571433
				],
				[
					225.71428571428578,
					782.857142857143
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "JQs8MNCnaqSdNyq_izyP9",
				"focus": -0.4660285180882984,
				"gap": 11.677568638546632
			},
			"endBinding": {
				"elementId": "vH07WZdf3zOQsWlnXyRd7",
				"focus": -0.4102663741265527,
				"gap": 2.1147072596098724
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#000000",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "hachure",
		"currentItemStrokeWidth": 1,
		"currentItemStrokeStyle": "dashed",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 28,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 1827.262731333402,
		"scrollY": 463.2557640543646,
		"zoom": {
			"value": 0.35000000000000003
		},
		"currentItemRoundness": "round",
		"gridSize": null,
		"colorPalette": {},
		"currentStrokeOptions": null,
		"previousGridSize": null
	},
	"files": {}
}
```
%%