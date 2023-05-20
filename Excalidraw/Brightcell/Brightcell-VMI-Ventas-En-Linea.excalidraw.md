---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
brightcell-nonprod-vmi-telcel
 ^OKLTHH3z

Se carga archivo .txt en
directorio 02_VentasEnLinea/unprocessed ^YYbTPeAQ

Evento ^dBQAn9x9

AWS Step Functions: Venta en Línea ^JXsZt1pG

Verificar archivos ^SeiwIshO

Notificación de proceso
fallido ^lemzTglr

El archivo es correcto? ^DNdEAFgS

No ^WELdYmAb

Si ^4Iqv3OGJ

Brightcell-VMI-load-online-sales-files ^A8sen9Ro

Limpiar tabla ^NV1uv1oL

stating.VentaEnLinea_temp ^HnFDMl2w

Limpiar tabla ^zurYGVXL

stating.VentaEnLinea ^rKYozOTs

Brightcell-VMI-load-dwventaEnLinea ^15KgnQ6C

dw.VentaEnLinea ^BuXH8iYs

Limpiar tabla ^TA2YfGWb

Brightcell-VMI-stating-VentaEnLinea ^09vATIjO

dw.dmMaterial ^A9ogQAbV

Consulta información de: ^cz6FsgQ5

Carga información en: ^OtH3CpSA

Flujo principal ^J95mfbNH

Keys ^P6JaUnjG

Mover archivos a directorio processed ^7iO4Y7VI

delete from @table  
where CAST([Fecha] AS DATE) 
in (select distinct CAST([Fecha] AS DATE) 
FROM [stating].[VentaEnLinea_temp] ) ^5TKy7Zny

Consulta fecha ^PoYkZS4O

Misma lambda
Invocan a un mismo SP parametrizable
"preprocessing.DeleteFromTableWithDate" ^dW4KIFTt

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
			"version": 1533,
			"versionNonce": 863945544,
			"isDeleted": false,
			"id": "om-kUoZ6ra8JZf79rNkp-",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -126.37549533861761,
			"y": -155.94206333785928,
			"strokeColor": "#000000",
			"backgroundColor": "#40c05788",
			"width": 77.00500621045215,
			"height": 77.00500621045215,
			"seed": 754733865,
			"groupIds": [
				"vPIQtreIy4hR9BWgE-1Vm",
				"OEB5oKlKTRLqt1NjcmvUM",
				"juwWI8jPx0WpoKnWGsHZq",
				"g5mb3Un9CeDxSS2UCir5O"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "k2L0JVPhOaXP_-swNFLk-",
					"type": "arrow"
				},
				{
					"id": "9JUw77nmHj0_VnnnIANnW",
					"type": "arrow"
				}
			],
			"updated": 1684536985221,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1307,
			"versionNonce": 1530393912,
			"isDeleted": false,
			"id": "DQY8dmO7QY07W-WK6OtQT",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -110.26848165605838,
			"y": -142.8472448899463,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 46.27059743037148,
			"height": 12.724351334011057,
			"seed": 1845792743,
			"groupIds": [
				"juwWI8jPx0WpoKnWGsHZq",
				"g5mb3Un9CeDxSS2UCir5O"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"id": "9JUw77nmHj0_VnnnIANnW",
					"type": "arrow"
				}
			],
			"updated": 1684536985221,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1924,
			"versionNonce": 207034952,
			"isDeleted": false,
			"id": "muG0PETTs44OOPia9VuWr",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -109.8449875000731,
			"y": -135.8917190975926,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 45.312356259233844,
			"height": 47.90461342961858,
			"seed": 1312425481,
			"groupIds": [
				"juwWI8jPx0WpoKnWGsHZq",
				"g5mb3Un9CeDxSS2UCir5O"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985221,
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
			"version": 1316,
			"versionNonce": 1542753848,
			"isDeleted": false,
			"id": "oh7rVKSC_7z0cf1-wVLFV",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -90.00203345880959,
			"y": -123.74891639191355,
			"strokeColor": "#000000",
			"backgroundColor": "#000",
			"width": 5.558985761351276,
			"height": 5.558985761351276,
			"seed": 1322777351,
			"groupIds": [
				"juwWI8jPx0WpoKnWGsHZq",
				"g5mb3Un9CeDxSS2UCir5O"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985221,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2002,
			"versionNonce": 1980535112,
			"isDeleted": false,
			"id": "k-cbrvsxvXp4hfbHP6OPq",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -87.05567351090235,
			"y": -120.70450055713195,
			"strokeColor": "#000000",
			"backgroundColor": "#000",
			"width": 27.506237081118297,
			"height": 13.643881491353264,
			"seed": 654204137,
			"groupIds": [
				"juwWI8jPx0WpoKnWGsHZq",
				"g5mb3Un9CeDxSS2UCir5O"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985221,
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
			"version": 1819,
			"versionNonce": 733349688,
			"isDeleted": false,
			"id": "OKLTHH3z",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -219.08286161815727,
			"y": -58.74418430424066,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 262.41973876953125,
			"height": 48,
			"seed": 340853287,
			"groupIds": [
				"g5mb3Un9CeDxSS2UCir5O"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985222,
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
			"version": 589,
			"versionNonce": 402335816,
			"isDeleted": false,
			"id": "YYbTPeAQ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -660.9687011681874,
			"y": -158.85200151825848,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 410.47967529296875,
			"height": 50,
			"seed": 376765871,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "k2L0JVPhOaXP_-swNFLk-",
					"type": "arrow"
				}
			],
			"updated": 1684536985222,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Se carga archivo .txt en\ndirectorio 02_VentasEnLinea/unprocessed",
			"rawText": "Se carga archivo .txt en\ndirectorio 02_VentasEnLinea/unprocessed",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Se carga archivo .txt en\ndirectorio 02_VentasEnLinea/unprocessed",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "arrow",
			"version": 900,
			"versionNonce": 1457545272,
			"isDeleted": false,
			"id": "k2L0JVPhOaXP_-swNFLk-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -240.48806166858253,
			"y": -122.0550350322621,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 110.31470346731248,
			"height": 2.93614799404763,
			"seed": 230571777,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985222,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "YYbTPeAQ",
				"focus": 0.19942484631081572,
				"gap": 10.000964206636127
			},
			"endBinding": {
				"elementId": "om-kUoZ6ra8JZf79rNkp-",
				"focus": 0.01400186363191401,
				"gap": 3.797862862652444
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
					110.31470346731248,
					2.93614799404763
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1171,
			"versionNonce": 1308548936,
			"isDeleted": false,
			"id": "PYoO0tqa0OYuWZ-hZZIV7",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 319.4538709815556,
			"y": -327.74019069575934,
			"strokeColor": "#000000",
			"backgroundColor": "#e6498088",
			"width": 64.70089111328099,
			"height": 64.70089111328099,
			"seed": 1932782313,
			"groupIds": [
				"8OBmizm3za3WDiWWhNHKa",
				"CwP_FMCbhNQwJo_aNlBPL"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "9JUw77nmHj0_VnnnIANnW",
					"type": "arrow"
				},
				{
					"id": "8_xrcuKsNJK7vpgug2dUF",
					"type": "arrow"
				}
			],
			"updated": 1684536985222,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1380,
			"versionNonce": 1029151032,
			"isDeleted": false,
			"id": "oH4W6hSXxe1RnK2BhgFR2",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 337.60399128722975,
			"y": -295.15815652967694,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.0965264804551,
			"height": 25.394020168765657,
			"seed": 2055427111,
			"groupIds": [
				"zXV0jA71G1NKOhPHzQYIF",
				"8OBmizm3za3WDiWWhNHKa",
				"CwP_FMCbhNQwJo_aNlBPL"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985222,
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
			"version": 1164,
			"versionNonce": 410236488,
			"isDeleted": false,
			"id": "sXoRhx0pUunbFQNx41IV1",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 337.33736114422254,
			"y": -318.3452348295823,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.527048406442323,
			"height": 6.527048406442323,
			"seed": 1630053833,
			"groupIds": [
				"zXV0jA71G1NKOhPHzQYIF",
				"8OBmizm3za3WDiWWhNHKa",
				"CwP_FMCbhNQwJo_aNlBPL"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985222,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1225,
			"versionNonce": 578794040,
			"isDeleted": false,
			"id": "jEiA_8kLDU9RMSkh2NWJL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 342.42251264040715,
			"y": -312.1864258005103,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.4300394358401154,
			"height": 4.165241568829386,
			"seed": 527710023,
			"groupIds": [
				"zXV0jA71G1NKOhPHzQYIF",
				"8OBmizm3za3WDiWWhNHKa",
				"CwP_FMCbhNQwJo_aNlBPL"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985222,
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
			"version": 1286,
			"versionNonce": 204844360,
			"isDeleted": false,
			"id": "Fc6OBs1vmBpR5NYefDFZ3",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.141592653589793,
			"x": 360.41515817356094,
			"y": -278.96130385509787,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.527048406442323,
			"height": 6.527048406442323,
			"seed": 1786971305,
			"groupIds": [
				"zXV0jA71G1NKOhPHzQYIF",
				"8OBmizm3za3WDiWWhNHKa",
				"CwP_FMCbhNQwJo_aNlBPL"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985222,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1354,
			"versionNonce": 1027386168,
			"isDeleted": false,
			"id": "uJLr1EO6-MXvUGaTgG05_",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.141592653589793,
			"x": 359.427015647977,
			"y": -282.75830604655675,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.4300394358401154,
			"height": 4.165241568829386,
			"seed": 916174439,
			"groupIds": [
				"zXV0jA71G1NKOhPHzQYIF",
				"8OBmizm3za3WDiWWhNHKa",
				"CwP_FMCbhNQwJo_aNlBPL"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985222,
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
			"version": 1297,
			"versionNonce": 1117832264,
			"isDeleted": false,
			"id": "Ahn9PxcqCoVssDdZ9lZwb",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 366.0431252473463,
			"y": -308.7829374277417,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.527048406442323,
			"height": 6.527048406442323,
			"seed": 1525581705,
			"groupIds": [
				"zXV0jA71G1NKOhPHzQYIF",
				"8OBmizm3za3WDiWWhNHKa",
				"CwP_FMCbhNQwJo_aNlBPL"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985222,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1385,
			"versionNonce": 1207075896,
			"isDeleted": false,
			"id": "9oQtmp_gwdfCOCbKJ2Vp_",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 331.2675241288521,
			"y": -288.3800056569212,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.527048406442323,
			"height": 6.527048406442323,
			"seed": 1992708487,
			"groupIds": [
				"zXV0jA71G1NKOhPHzQYIF",
				"8OBmizm3za3WDiWWhNHKa",
				"CwP_FMCbhNQwJo_aNlBPL"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985222,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1191,
			"versionNonce": 1234238280,
			"isDeleted": false,
			"id": "exVxiMaZ_q3705Ez_4l4O",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 352.22456838665266,
			"y": -313.94840268412236,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14.881064367630502,
			"height": 5.819316836931806,
			"seed": 2091298409,
			"groupIds": [
				"zXV0jA71G1NKOhPHzQYIF",
				"8OBmizm3za3WDiWWhNHKa",
				"CwP_FMCbhNQwJo_aNlBPL"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985222,
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
			"version": 1179,
			"versionNonce": 277167416,
			"isDeleted": false,
			"id": "9R8W4zosyCN_122ergADw",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 369.0205729908362,
			"y": -285.35418605302857,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.359881211089217,
			"height": 17.609098804231238,
			"seed": 154175655,
			"groupIds": [
				"zXV0jA71G1NKOhPHzQYIF",
				"8OBmizm3za3WDiWWhNHKa",
				"CwP_FMCbhNQwJo_aNlBPL"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985222,
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
			"version": 1364,
			"versionNonce": 325210696,
			"isDeleted": false,
			"id": "qm60QvgZs90EWkkBimCaX",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.141592653589793,
			"x": 336.5030003221086,
			"y": -282.46455099332616,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14.881064367630502,
			"height": 5.819316836931806,
			"seed": 1182202185,
			"groupIds": [
				"zXV0jA71G1NKOhPHzQYIF",
				"8OBmizm3za3WDiWWhNHKa",
				"CwP_FMCbhNQwJo_aNlBPL"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985222,
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
			"version": 1349,
			"versionNonce": 140039736,
			"isDeleted": false,
			"id": "wRK8NDk6THQVZreNTY29O",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.141592653589793,
			"x": 329.2281788744667,
			"y": -287.7082106918665,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.359881211089217,
			"height": 17.609098804231238,
			"seed": 998693831,
			"groupIds": [
				"zXV0jA71G1NKOhPHzQYIF",
				"8OBmizm3za3WDiWWhNHKa",
				"CwP_FMCbhNQwJo_aNlBPL"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985222,
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
			"version": 2103,
			"versionNonce": 1727056200,
			"isDeleted": false,
			"id": "dBQAn9x9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 318.24876098264053,
			"y": -259.49076650324287,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.59994506835938,
			"height": 24,
			"seed": 1236985897,
			"groupIds": [
				"CwP_FMCbhNQwJo_aNlBPL"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985222,
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
			"version": 484,
			"versionNonce": 1414614840,
			"isDeleted": false,
			"id": "9JUw77nmHj0_VnnnIANnW",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -83.72814030959375,
			"y": -168.11022596542307,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 392.77800721535675,
			"height": 125.28349161994038,
			"seed": 1347002703,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985222,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "om-kUoZ6ra8JZf79rNkp-",
				"focus": -0.3386597489482078,
				"gap": 12.168162627563795
			},
			"endBinding": {
				"elementId": "PYoO0tqa0OYuWZ-hZZIV7",
				"focus": -0.010561273127968797,
				"gap": 10.404004075792585
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
					392.77800721535675,
					-125.28349161994038
				]
			]
		},
		{
			"type": "rectangle",
			"version": 2008,
			"versionNonce": 1335386184,
			"isDeleted": false,
			"id": "fDZVgemjVNxVlBRct6J2_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 178.27360698641337,
			"y": -490.4884119381694,
			"strokeColor": "#e64980",
			"backgroundColor": "transparent",
			"width": 1425.6252206161264,
			"height": 2053.960661007741,
			"seed": 1073359495,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985222,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1635,
			"versionNonce": 1557309496,
			"isDeleted": false,
			"id": "V4oUPheixPphJ542EWZgG",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 216.3477179412555,
			"y": -495.8444064399072,
			"strokeColor": "#e64980",
			"backgroundColor": "#e6498088",
			"width": 113.8653583445497,
			"height": 113.8653583445497,
			"seed": 1259971911,
			"groupIds": [
				"sDQKksqEU0pW1B80jcbr3",
				"RKCbz4poOjgZrui_WuUZh",
				"BD7I1ER6CK-sYrUahBVez"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985222,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1135,
			"versionNonce": 221583176,
			"isDeleted": false,
			"id": "8kv1wflaE2Xk2e_O05rRm",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 267.2710361028228,
			"y": -481.98268788270104,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.131091700161791,
			"height": 10.131091700161791,
			"seed": 1219720873,
			"groupIds": [
				"vdYx-0lDLTvQjpOQjv1bV",
				"RKCbz4poOjgZrui_WuUZh",
				"BD7I1ER6CK-sYrUahBVez"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985222,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1242,
			"versionNonce": 1572921656,
			"isDeleted": false,
			"id": "2GyVi6e_zQpjsABh1_NpS",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 267.376385295471,
			"y": -405.9718583527259,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.131091700161791,
			"height": 10.131091700161791,
			"seed": 1734567015,
			"groupIds": [
				"vdYx-0lDLTvQjpOQjv1bV",
				"RKCbz4poOjgZrui_WuUZh",
				"BD7I1ER6CK-sYrUahBVez"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985222,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1101,
			"versionNonce": 69398088,
			"isDeleted": false,
			"id": "wSz58O5mXf1ML78cgGFeL",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 228.20745507770403,
			"y": -455.0032946506384,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.37948548155744,
			"height": 10.986936652204236,
			"seed": 1044429193,
			"groupIds": [
				"vdYx-0lDLTvQjpOQjv1bV",
				"RKCbz4poOjgZrui_WuUZh",
				"BD7I1ER6CK-sYrUahBVez"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985223,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1150,
			"versionNonce": 1988098616,
			"isDeleted": false,
			"id": "HgnG5YGMwMo_s-hdddGxL",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 228.3531606068243,
			"y": -433.5158175778846,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.37948548155744,
			"height": 10.986936652204236,
			"seed": 1315454855,
			"groupIds": [
				"vdYx-0lDLTvQjpOQjv1bV",
				"RKCbz4poOjgZrui_WuUZh",
				"BD7I1ER6CK-sYrUahBVez"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985223,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1218,
			"versionNonce": 759031112,
			"isDeleted": false,
			"id": "SchLbJGv-fJarYCIxBxXB",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 284.9738536678017,
			"y": -445.9839969033836,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.37948548155744,
			"height": 14.914612147334124,
			"seed": 1524801641,
			"groupIds": [
				"vdYx-0lDLTvQjpOQjv1bV",
				"RKCbz4poOjgZrui_WuUZh",
				"BD7I1ER6CK-sYrUahBVez"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985223,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1121,
			"versionNonce": 972288824,
			"isDeleted": false,
			"id": "Y1yTEY4GpQCBL97I81IEq",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 245.37000763701576,
			"y": -443.08988615504666,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.917422766232455,
			"seed": 845461159,
			"groupIds": [
				"vdYx-0lDLTvQjpOQjv1bV",
				"RKCbz4poOjgZrui_WuUZh",
				"BD7I1ER6CK-sYrUahBVez"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985223,
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
			"version": 1168,
			"versionNonce": 98696264,
			"isDeleted": false,
			"id": "FLPETqiINwkcvfgdLCovu",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 245.60205326935898,
			"y": -462.4532527006776,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 57.71378835781129,
			"height": 0,
			"seed": 476359497,
			"groupIds": [
				"vdYx-0lDLTvQjpOQjv1bV",
				"RKCbz4poOjgZrui_WuUZh",
				"BD7I1ER6CK-sYrUahBVez"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985223,
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
			"version": 1183,
			"versionNonce": 1048628280,
			"isDeleted": false,
			"id": "OJeYPWAsawBr60UZXcZg3",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 244.57741183034682,
			"y": -464.1504876387388,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.917422766232455,
			"seed": 1241860551,
			"groupIds": [
				"vdYx-0lDLTvQjpOQjv1bV",
				"RKCbz4poOjgZrui_WuUZh",
				"BD7I1ER6CK-sYrUahBVez"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985223,
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
			"version": 1285,
			"versionNonce": 2146120520,
			"isDeleted": false,
			"id": "e_uZBP_6vS9HmvSJw2Jly",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 301.7508929107296,
			"y": -462.8134577724667,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 10.488988336663578,
			"seed": 992107049,
			"groupIds": [
				"vdYx-0lDLTvQjpOQjv1bV",
				"RKCbz4poOjgZrui_WuUZh",
				"BD7I1ER6CK-sYrUahBVez"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985223,
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
			"version": 1333,
			"versionNonce": 772441400,
			"isDeleted": false,
			"id": "AVbDYtoZL-BpFyEUI5nBE",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 272.36904403515814,
			"y": -470.97139211937326,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.010963966968777,
			"seed": 1114011879,
			"groupIds": [
				"vdYx-0lDLTvQjpOQjv1bV",
				"RKCbz4poOjgZrui_WuUZh",
				"BD7I1ER6CK-sYrUahBVez"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985223,
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
			"version": 1203,
			"versionNonce": 1907722824,
			"isDeleted": false,
			"id": "C_7AAf-6BrhUKhdGnZq8s",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 245.63808203274243,
			"y": -414.25232801133814,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 57.71378835781129,
			"height": 0,
			"seed": 1476865289,
			"groupIds": [
				"vdYx-0lDLTvQjpOQjv1bV",
				"RKCbz4poOjgZrui_WuUZh",
				"BD7I1ER6CK-sYrUahBVez"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985223,
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
			"version": 1376,
			"versionNonce": 1442127416,
			"isDeleted": false,
			"id": "pU4mUREgymg5dgSGp_h_6",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 272.40507279854796,
			"y": -415.69415093219357,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.480946860464432,
			"seed": 1897186311,
			"groupIds": [
				"vdYx-0lDLTvQjpOQjv1bV",
				"RKCbz4poOjgZrui_WuUZh",
				"BD7I1ER6CK-sYrUahBVez"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985223,
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
			"version": 1218,
			"versionNonce": 102564168,
			"isDeleted": false,
			"id": "arowR7eFv3uE_v9ksXy2I",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 245.54281994273538,
			"y": -421.5907546214602,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.917422766232455,
			"seed": 1787732969,
			"groupIds": [
				"vdYx-0lDLTvQjpOQjv1bV",
				"RKCbz4poOjgZrui_WuUZh",
				"BD7I1ER6CK-sYrUahBVez"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985223,
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
			"version": 1376,
			"versionNonce": 925144888,
			"isDeleted": false,
			"id": "9BIfk1V-CO1-sumCKa8_V",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 301.6768855982725,
			"y": -423.5804640171451,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 10.488988336663578,
			"seed": 1175235367,
			"groupIds": [
				"vdYx-0lDLTvQjpOQjv1bV",
				"RKCbz4poOjgZrui_WuUZh",
				"BD7I1ER6CK-sYrUahBVez"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985223,
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
			"version": 1969,
			"versionNonce": 746428488,
			"isDeleted": false,
			"id": "JXsZt1pG",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 355.2312528941386,
			"y": -471.95081339041315,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 640.6198120117188,
			"height": 43.199999999999996,
			"seed": 1017614857,
			"groupIds": [
				"AVfAM70Iw39SvuE1DApWt",
				"BD7I1ER6CK-sYrUahBVez"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985223,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "AWS Step Functions: Venta en Línea",
			"rawText": "AWS Step Functions: Venta en Línea",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "AWS Step Functions: Venta en Línea",
			"lineHeight": 1.2,
			"baseline": 31
		},
		{
			"type": "rectangle",
			"version": 2678,
			"versionNonce": 368898104,
			"isDeleted": false,
			"id": "QQiZtsaPwDN5iScUdtLbs",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 606.5989345973167,
			"y": -331.6637771697594,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e1488",
			"width": 66.53246337764709,
			"height": 66.4687522713753,
			"seed": 1087403015,
			"groupIds": [
				"bXeY61d0MyHXnYTvZTuUI",
				"2IV5nuPvu0zL4g9mcyAcW",
				"2o6B83-0HMCRwrwL-CvhE"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "ppE8jLscllFnN2Sizr3aw",
					"type": "arrow"
				},
				{
					"id": "8_xrcuKsNJK7vpgug2dUF",
					"type": "arrow"
				}
			],
			"updated": 1684536985223,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1837,
			"versionNonce": 145968968,
			"isDeleted": false,
			"id": "IyzsymcDb_7kgXOP_Afbj",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 632.3931771777086,
			"y": -304.06716435889,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.927534089288194,
			"height": 27.761273291189447,
			"seed": 1235612649,
			"groupIds": [
				"2E517PIaNtHU84nhAeays",
				"2IV5nuPvu0zL4g9mcyAcW",
				"2o6B83-0HMCRwrwL-CvhE"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985223,
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
			"version": 1837,
			"versionNonce": 174205240,
			"isDeleted": false,
			"id": "EctCzj87ni_jNZSmR5_wN",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 657.6667218658556,
			"y": -287.65935079194827,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 35.98406748383116,
			"height": 45.41383889698984,
			"seed": 47340327,
			"groupIds": [
				"2E517PIaNtHU84nhAeays",
				"2IV5nuPvu0zL4g9mcyAcW",
				"2o6B83-0HMCRwrwL-CvhE"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985223,
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
			"version": 2187,
			"versionNonce": 1662658120,
			"isDeleted": false,
			"id": "SeiwIshO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 552.6666864980191,
			"y": -260.0721324378798,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 174.3872528076172,
			"height": 24.77118485290355,
			"seed": 242323145,
			"groupIds": [
				"2o6B83-0HMCRwrwL-CvhE"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "8_xrcuKsNJK7vpgug2dUF",
					"type": "arrow"
				}
			],
			"updated": 1684536985223,
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
			"version": 1542,
			"versionNonce": 263733816,
			"isDeleted": false,
			"id": "tgeTpH5KYuMMNBSmF03iM",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1276.653225702935,
			"y": -341.10290242786135,
			"strokeColor": "#000000",
			"backgroundColor": "#e6498088",
			"width": 65.08084106445301,
			"height": 65.08084106445301,
			"seed": 1898935145,
			"groupIds": [
				"zdP6Wu9T--6NsYCjlcEti",
				"-1BVo7p395Z36SmW2bwx6",
				"6HlbstQhj75o2Arwl9gjT",
				"4BKOzRd7DwcSUk_FEAsXq",
				"6MQ06cZYFb7Vw4mK-ipsR",
				"8K9clHbN-i-alZmev9xbo"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "T7Z8UOmtbK6VOH_N6JCiI",
					"type": "arrow"
				}
			],
			"updated": 1684536985223,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1309,
			"versionNonce": 411966792,
			"isDeleted": false,
			"id": "fhh5hB4rLlQpEksIk3Nuj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1286.3377208070954,
			"y": -311.14079268403833,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.935660646660656,
			"height": 5.935660646660656,
			"seed": 306353063,
			"groupIds": [
				"gsVQUEDpHha-u1WMlq5oH",
				"6MQ06cZYFb7Vw4mK-ipsR",
				"8K9clHbN-i-alZmev9xbo"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985223,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1402,
			"versionNonce": 350436152,
			"isDeleted": false,
			"id": "pcaNBDtR_kDJ64uDKM-5c",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1326.3952587181473,
			"y": -311.1915046026442,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.935660646660656,
			"height": 5.935660646660656,
			"seed": 396303945,
			"groupIds": [
				"gsVQUEDpHha-u1WMlq5oH",
				"6MQ06cZYFb7Vw4mK-ipsR",
				"8K9clHbN-i-alZmev9xbo"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985223,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1447,
			"versionNonce": 174797896,
			"isDeleted": false,
			"id": "DFhpLPZRLrARifMxR93Aa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1323.2261427086107,
			"y": -321.8086073210097,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.935660646660656,
			"height": 5.935660646660656,
			"seed": 203392711,
			"groupIds": [
				"gsVQUEDpHha-u1WMlq5oH",
				"6MQ06cZYFb7Vw4mK-ipsR",
				"8K9clHbN-i-alZmev9xbo"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985223,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1521,
			"versionNonce": 205984824,
			"isDeleted": false,
			"id": "wk_hPtCzt4RTS78Gstnci",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1323.2575047339703,
			"y": -299.5052177833658,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.935660646660656,
			"height": 5.935660646660656,
			"seed": 1821797673,
			"groupIds": [
				"gsVQUEDpHha-u1WMlq5oH",
				"6MQ06cZYFb7Vw4mK-ipsR",
				"8K9clHbN-i-alZmev9xbo"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985223,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1427,
			"versionNonce": 244149064,
			"isDeleted": false,
			"id": "1z5CA6gMj1OhDxVjLkfHH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1310.9673872054152,
			"y": -308.1371167335273,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.738770407595338,
			"height": 0,
			"seed": 540087783,
			"groupIds": [
				"gsVQUEDpHha-u1WMlq5oH",
				"6MQ06cZYFb7Vw4mK-ipsR",
				"8K9clHbN-i-alZmev9xbo"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985223,
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
			"version": 1349,
			"versionNonce": 2076691768,
			"isDeleted": false,
			"id": "d3zX7sLnhr2wc-Akw8X0g",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1318.8637330426493,
			"y": -319.2587521878185,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 23.436189350564298,
			"seed": 125886473,
			"groupIds": [
				"gsVQUEDpHha-u1WMlq5oH",
				"6MQ06cZYFb7Vw4mK-ipsR",
				"8K9clHbN-i-alZmev9xbo"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985223,
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
			"version": 1297,
			"versionNonce": 1599128136,
			"isDeleted": false,
			"id": "qF7uPpPE-sxVj99fpOmmT",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1323.402436583235,
			"y": -318.74312743835384,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.278540805703472,
			"height": 0,
			"seed": 1434697991,
			"groupIds": [
				"gsVQUEDpHha-u1WMlq5oH",
				"6MQ06cZYFb7Vw4mK-ipsR",
				"8K9clHbN-i-alZmev9xbo"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985223,
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
			"version": 1309,
			"versionNonce": 214525496,
			"isDeleted": false,
			"id": "eZIGmcZTgl7DR-h8VYCDK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1323.368393250161,
			"y": -296.3057599944968,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.278540805703472,
			"height": 0,
			"seed": 106559209,
			"groupIds": [
				"gsVQUEDpHha-u1WMlq5oH",
				"6MQ06cZYFb7Vw4mK-ipsR",
				"8K9clHbN-i-alZmev9xbo"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985223,
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
			"version": 1479,
			"versionNonce": 194066760,
			"isDeleted": false,
			"id": "i5n5KZVctnqK1sc3_wAw3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1297.9095071441614,
			"y": -316.23850009235315,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13.538770570677526,
			"height": 4.283701206606613,
			"seed": 496240679,
			"groupIds": [
				"gsVQUEDpHha-u1WMlq5oH",
				"6MQ06cZYFb7Vw4mK-ipsR",
				"8K9clHbN-i-alZmev9xbo"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985223,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1614,
			"versionNonce": 472899384,
			"isDeleted": false,
			"id": "NXSy_Rb2QhTf9CxieUaLd",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1298.290425242022,
			"y": -313.3759993488042,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13.305408215826999,
			"height": 14.770218853011942,
			"seed": 1001206217,
			"groupIds": [
				"gsVQUEDpHha-u1WMlq5oH",
				"6MQ06cZYFb7Vw4mK-ipsR",
				"8K9clHbN-i-alZmev9xbo"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985223,
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
			"version": 1486,
			"versionNonce": 1722470472,
			"isDeleted": false,
			"id": "hMJxHUjs5Ug-mG-ZoNmdC",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1292.3672430335453,
			"y": -308.23747921976695,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.229181632062791,
			"height": 0,
			"seed": 105802567,
			"groupIds": [
				"gsVQUEDpHha-u1WMlq5oH",
				"6MQ06cZYFb7Vw4mK-ipsR",
				"8K9clHbN-i-alZmev9xbo"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985224,
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
			"version": 1455,
			"versionNonce": 1247754296,
			"isDeleted": false,
			"id": "XHuNFxpqYY7CIiFZYspET",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1289.526021236093,
			"y": -311.14343815667047,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 32.796640923919526,
			"height": 16.800743224146107,
			"seed": 479596713,
			"groupIds": [
				"gsVQUEDpHha-u1WMlq5oH",
				"6MQ06cZYFb7Vw4mK-ipsR",
				"8K9clHbN-i-alZmev9xbo"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985224,
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
			"version": 1590,
			"versionNonce": 2021230408,
			"isDeleted": false,
			"id": "9gXyqRzV4nCVd0Wj8v5jb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1289.1127275605716,
			"y": -305.07053123302643,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.72406610309211,
			"height": 17.27583554628456,
			"seed": 739207783,
			"groupIds": [
				"gsVQUEDpHha-u1WMlq5oH",
				"6MQ06cZYFb7Vw4mK-ipsR",
				"8K9clHbN-i-alZmev9xbo"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985224,
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
			"version": 1759,
			"versionNonce": 188444984,
			"isDeleted": false,
			"id": "lemzTglr",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1190.1936462351616,
			"y": -271.6396001046523,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 226.73977661132812,
			"height": 48,
			"seed": 1858081673,
			"groupIds": [
				"8K9clHbN-i-alZmev9xbo"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "T7Z8UOmtbK6VOH_N6JCiI",
					"type": "arrow"
				}
			],
			"updated": 1684536985224,
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
			"type": "diamond",
			"version": 390,
			"versionNonce": 1834573384,
			"isDeleted": false,
			"id": "vRLWJtUi9erXuRcLc6mTT",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 841.0220283793326,
			"y": -392.4357364886378,
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
					"id": "DNdEAFgS"
				},
				{
					"id": "ppE8jLscllFnN2Sizr3aw",
					"type": "arrow"
				},
				{
					"id": "T7Z8UOmtbK6VOH_N6JCiI",
					"type": "arrow"
				},
				{
					"id": "jrP2bVVpNxEDw4VptQAvO",
					"type": "arrow"
				}
			],
			"updated": 1684536985224,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 363,
			"versionNonce": 908626488,
			"isDeleted": false,
			"id": "DNdEAFgS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 892.4140495585318,
			"y": -340.4357364886378,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 77.21595764160156,
			"height": 60,
			"seed": 1620544207,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985224,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "El archivo\nes \ncorrecto?",
			"rawText": "El archivo es correcto?",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "vRLWJtUi9erXuRcLc6mTT",
			"originalText": "El archivo es correcto?",
			"lineHeight": 1.25,
			"baseline": 54
		},
		{
			"type": "arrow",
			"version": 511,
			"versionNonce": 103175496,
			"isDeleted": false,
			"id": "ppE8jLscllFnN2Sizr3aw",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 683.6886950459993,
			"y": -296.16695158631,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 164.89158360037845,
			"height": 3.7702992881852424,
			"seed": 485934383,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985224,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "QQiZtsaPwDN5iScUdtLbs",
				"gap": 10.55729707103552,
				"focus": 0.09602843741616211
			},
			"endBinding": {
				"elementId": "vRLWJtUi9erXuRcLc6mTT",
				"gap": 2.6700361693985855,
				"focus": -0.10504180967344016
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
					-3.7702992881852424
				]
			]
		},
		{
			"type": "arrow",
			"version": 724,
			"versionNonce": 369787704,
			"isDeleted": false,
			"id": "T7Z8UOmtbK6VOH_N6JCiI",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1031.432720746318,
			"y": -301.7204969100768,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 235.80602260295063,
			"height": 2.012446659354964,
			"seed": 45550529,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "WELdYmAb"
				}
			],
			"updated": 1684536985224,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "vRLWJtUi9erXuRcLc6mTT",
				"gap": 13.577110019136043,
				"focus": 0.11673387399637328
			},
			"endBinding": {
				"elementId": "tgeTpH5KYuMMNBSmF03iM",
				"gap": 9.414482353666358,
				"focus": -0.13625033252131744
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
					235.80602260295063,
					-2.012446659354964
				]
			]
		},
		{
			"type": "text",
			"version": 146,
			"versionNonce": 138177608,
			"isDeleted": false,
			"id": "WELdYmAb",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1137.3557439496487,
			"y": -315.22672023975434,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.959976196289062,
			"height": 25,
			"seed": 1226593793,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985224,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "No",
			"rawText": "No",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "T7Z8UOmtbK6VOH_N6JCiI",
			"originalText": "No",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 558,
			"versionNonce": 2034588728,
			"isDeleted": false,
			"id": "jrP2bVVpNxEDw4VptQAvO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 936.8347769429895,
			"y": -216.21826961418256,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 1.985905705523237,
			"height": 219.11586645887812,
			"seed": 1002414529,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "4Iqv3OGJ"
				}
			],
			"updated": 1684536985224,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "vRLWJtUi9erXuRcLc6mTT",
				"gap": 13.529765064209613,
				"focus": -0.0740740740740749
			},
			"endBinding": {
				"elementId": "DF5u1EtvOGep8OCESrBPx",
				"gap": 11.675927761947271,
				"focus": 0.28709153911495616
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
					-1.985905705523237,
					219.11586645887812
				]
			]
		},
		{
			"type": "text",
			"version": 144,
			"versionNonce": 762815304,
			"isDeleted": false,
			"id": "4Iqv3OGJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 927.571835076556,
			"y": -119.16033638474346,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.53997802734375,
			"height": 25,
			"seed": 324324737,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985224,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Si",
			"rawText": "Si",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "jrP2bVVpNxEDw4VptQAvO",
			"originalText": "Si",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 546,
			"versionNonce": 1102910776,
			"isDeleted": false,
			"id": "8_xrcuKsNJK7vpgug2dUF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 397.8266763807707,
			"y": -293.6013056677067,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 203.224916933712,
			"height": 0.07869992314095953,
			"seed": 485934383,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985224,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "PYoO0tqa0OYuWZ-hZZIV7",
				"focus": 0.04411898342242138,
				"gap": 13.67191428593415
			},
			"endBinding": {
				"elementId": "QQiZtsaPwDN5iScUdtLbs",
				"focus": -0.14803704874273552,
				"gap": 5.547341282833997
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
					203.224916933712,
					0.07869992314095953
				]
			]
		},
		{
			"type": "text",
			"version": 2430,
			"versionNonce": 338950728,
			"isDeleted": false,
			"id": "A8sen9Ro",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 744.7835344899629,
			"y": 356.8694605604502,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 351.69964599609375,
			"height": 24,
			"seed": 1245685479,
			"groupIds": [
				"8jFCvI-CVkSKeKw9FLdsv"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "vdDHXanixBvTKmxTX5DU9",
					"type": "arrow"
				}
			],
			"updated": 1684536985224,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Brightcell-VMI-load-online-sales-files",
			"rawText": "Brightcell-VMI-load-online-sales-files",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Brightcell-VMI-load-online-sales-files",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4455,
			"versionNonce": 1960160824,
			"isDeleted": false,
			"id": "05iHuFGide19YsTmcubrD",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 872.5786783833578,
			"y": 236.30708490428503,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 107.76604983800789,
			"height": 107.66285368525563,
			"seed": 941612809,
			"groupIds": [
				"VLWk8QdDn0thNvjBgAW_4",
				"AVe2MESkpKlHwCO6omCNW",
				"ckYhs7zfFh4i6YsYVOmrn",
				"ok7dETMO3MmF2fShylaYi",
				"8jFCvI-CVkSKeKw9FLdsv"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "FiUZOyF4gdlXgFNi-4RkA",
					"type": "arrow"
				},
				{
					"id": "A1UpYsdZB-AJhfrGcybEm",
					"type": "arrow"
				}
			],
			"updated": 1684536985224,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2312,
			"versionNonce": 793604424,
			"isDeleted": false,
			"id": "jK7EZT-mxZRhRky-lvFcI",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 931.2574632014071,
			"y": 306.0057520818474,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 17.21171637693966,
			"height": 30.981089478491384,
			"seed": 1100493319,
			"groupIds": [
				"PMu33Ut0tNXzBIgG9A3GM",
				"ok7dETMO3MmF2fShylaYi",
				"8jFCvI-CVkSKeKw9FLdsv"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985224,
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
			"version": 2392,
			"versionNonce": 1265837880,
			"isDeleted": false,
			"id": "Viu16NfTXXFKYlLMONL8z",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 922.1782828125695,
			"y": 306.0057520818474,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 17.21171637693966,
			"height": 30.981089478491384,
			"seed": 1757484521,
			"groupIds": [
				"PMu33Ut0tNXzBIgG9A3GM",
				"ok7dETMO3MmF2fShylaYi",
				"8jFCvI-CVkSKeKw9FLdsv"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985224,
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
			"version": 2192,
			"versionNonce": 908068936,
			"isDeleted": false,
			"id": "TDFQte_oqhKkx6cBt_uzq",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 922.6516050129369,
			"y": 306.43604499126343,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 7.745272369622733,
			"height": 0,
			"seed": 1341282599,
			"groupIds": [
				"PMu33Ut0tNXzBIgG9A3GM",
				"ok7dETMO3MmF2fShylaYi",
				"8jFCvI-CVkSKeKw9FLdsv"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985224,
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
			"version": 2306,
			"versionNonce": 1106870328,
			"isDeleted": false,
			"id": "UPavejfMYgmqWQnc7dVf7",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 906.3004744548441,
			"y": 274.4738876792875,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 42.168705123502164,
			"height": 7.314979460199344,
			"seed": 567832777,
			"groupIds": [
				"PMu33Ut0tNXzBIgG9A3GM",
				"ok7dETMO3MmF2fShylaYi",
				"8jFCvI-CVkSKeKw9FLdsv"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985224,
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
			"version": 2196,
			"versionNonce": 344440648,
			"isDeleted": false,
			"id": "aRZ84k1CnSBfrE-8SQXCi",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 905.3538300541131,
			"y": 274.16407678451117,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 16.35113055809267,
			"height": 2.581757456540929,
			"seed": 1522179143,
			"groupIds": [
				"PMu33Ut0tNXzBIgG9A3GM",
				"ok7dETMO3MmF2fShylaYi",
				"8jFCvI-CVkSKeKw9FLdsv"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985224,
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
			"version": 2150,
			"versionNonce": 676116792,
			"isDeleted": false,
			"id": "Ac_ZJFPHITFKoy_i-CV6l",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 926.9975633981155,
			"y": 253.55304642311523,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 956395433,
			"groupIds": [
				"PMu33Ut0tNXzBIgG9A3GM",
				"ok7dETMO3MmF2fShylaYi",
				"8jFCvI-CVkSKeKw9FLdsv"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985224,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 2150,
			"versionNonce": 1524667976,
			"isDeleted": false,
			"id": "RU0AwuIQFgVzGEaWvS9CA",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 915.3796548436819,
			"y": 262.0728460297004,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 1707965287,
			"groupIds": [
				"PMu33Ut0tNXzBIgG9A3GM",
				"ok7dETMO3MmF2fShylaYi",
				"8jFCvI-CVkSKeKw9FLdsv"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985224,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 2151,
			"versionNonce": 835768888,
			"isDeleted": false,
			"id": "GYrBo-JsoPu4D87-7KP2R",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 929.1490279452307,
			"y": 266.8490973243041,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 1147638409,
			"groupIds": [
				"PMu33Ut0tNXzBIgG9A3GM",
				"ok7dETMO3MmF2fShylaYi",
				"8jFCvI-CVkSKeKw9FLdsv"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985224,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1648,
			"versionNonce": 772181320,
			"isDeleted": false,
			"id": "aVP6Kv73aIJQo8nWMZyRK",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 928.9881954245197,
			"y": 310.34317949921854,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 18.44546425611026,
			"height": 14.81684833687558,
			"seed": 1165457031,
			"groupIds": [
				"ok7dETMO3MmF2fShylaYi",
				"8jFCvI-CVkSKeKw9FLdsv"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985224,
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
			"type": "rectangle",
			"version": 2716,
			"versionNonce": 90819384,
			"isDeleted": false,
			"id": "DF5u1EtvOGep8OCESrBPx",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 891.5386763677434,
			"y": 14.57352460664282,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e1488",
			"width": 66.53246337764709,
			"height": 66.4687522713753,
			"seed": 1087403015,
			"groupIds": [
				"omTJGIDzaQBJv_Q0-PAdL",
				"6yOBOOg7Dpn4vxoL5s0tX",
				"YvZz3wwtjuML3cO1-BV1m"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "jrP2bVVpNxEDw4VptQAvO",
					"type": "arrow"
				},
				{
					"id": "keMwFdrdFGfY8SdqYbhIU",
					"type": "arrow"
				}
			],
			"updated": 1684536985224,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1873,
			"versionNonce": 928359496,
			"isDeleted": false,
			"id": "okW4qPdA8bnM7_iiopo_i",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 917.3329189481353,
			"y": 42.170137417512194,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.927534089288194,
			"height": 27.761273291189447,
			"seed": 1235612649,
			"groupIds": [
				"_Mi_vdlSSYpZlYaU2Pk2M",
				"6yOBOOg7Dpn4vxoL5s0tX",
				"YvZz3wwtjuML3cO1-BV1m"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985224,
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
			"version": 1873,
			"versionNonce": 1299948600,
			"isDeleted": false,
			"id": "O2m3qx7cbhFKdKBQ8Ltwa",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 942.6064636362823,
			"y": 58.577950984453935,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 35.98406748383116,
			"height": 45.41383889698984,
			"seed": 47340327,
			"groupIds": [
				"_Mi_vdlSSYpZlYaU2Pk2M",
				"6yOBOOg7Dpn4vxoL5s0tX",
				"YvZz3wwtjuML3cO1-BV1m"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985224,
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
			"version": 2237,
			"versionNonce": 346676040,
			"isDeleted": false,
			"id": "NV1uv1oL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 858.4424954681529,
			"y": 86.16516933852239,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 132.71511840820312,
			"height": 24.77118485290355,
			"seed": 242323145,
			"groupIds": [
				"YvZz3wwtjuML3cO1-BV1m"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "FiUZOyF4gdlXgFNi-4RkA",
					"type": "arrow"
				}
			],
			"updated": 1684536985224,
			"link": null,
			"locked": false,
			"fontSize": 20.642654044086292,
			"fontFamily": 1,
			"text": "Limpiar tabla",
			"rawText": "Limpiar tabla",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Limpiar tabla",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 2796,
			"versionNonce": 1775941192,
			"isDeleted": false,
			"id": "HnFDMl2w",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 374.58620668101685,
			"y": 322.15517484616447,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 265.35980224609375,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"QfnIiyDusM4zo-Nx-lkhd"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "BshKi0GB811_uE14pAJ8D",
					"type": "arrow"
				}
			],
			"updated": 1684537036064,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "stating.VentaEnLinea_temp",
			"rawText": "stating.VentaEnLinea_temp",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "stating.VentaEnLinea_temp",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 3904,
			"versionNonce": 1214198344,
			"isDeleted": false,
			"id": "UpHK4gABCAwgOIIc99wx9",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 463.0656524711949,
			"y": 252.68803728523727,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"sxK08yZ2s2qFGgxt8ZYE2",
				"pxhDla2uwNfdQDm2C3MaE",
				"jZIY4bqdR8-BZ63T_Wed8",
				"iJf-L_UnhrdA3F8jdE_FG",
				"QfnIiyDusM4zo-Nx-lkhd"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "keMwFdrdFGfY8SdqYbhIU",
					"type": "arrow"
				},
				{
					"id": "A1UpYsdZB-AJhfrGcybEm",
					"type": "arrow"
				}
			],
			"updated": 1684536985225,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2339,
			"versionNonce": 1444542008,
			"isDeleted": false,
			"id": "2CnP1Gk41xq1WaGGnUCsC",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 484.10632457424435,
			"y": 275.97232550764676,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"gZld3ON9U_MVK2yaDyb03",
				"_qtyrOUhFyGHfjtA9mWNS",
				"iJf-L_UnhrdA3F8jdE_FG",
				"QfnIiyDusM4zo-Nx-lkhd"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985225,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2481,
			"versionNonce": 693217608,
			"isDeleted": false,
			"id": "J3dKXKAkjRuNU8J_C2lnm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 485.09162357839614,
			"y": 280.15696996374646,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"gZld3ON9U_MVK2yaDyb03",
				"_qtyrOUhFyGHfjtA9mWNS",
				"iJf-L_UnhrdA3F8jdE_FG",
				"QfnIiyDusM4zo-Nx-lkhd"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985225,
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
			"version": 3187,
			"versionNonce": 216952632,
			"isDeleted": false,
			"id": "x8tgWrDdkXr0ZWVR78CAR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 515.7487382204208,
			"y": 269.8441422743834,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"ruOzcP7K9lfDjib-w3noT",
				"_qtyrOUhFyGHfjtA9mWNS",
				"iJf-L_UnhrdA3F8jdE_FG",
				"QfnIiyDusM4zo-Nx-lkhd"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985225,
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
			"version": 3278,
			"versionNonce": 1390231624,
			"isDeleted": false,
			"id": "hzvKE118XEVXjrWWYGoyW",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 481.4290248067932,
			"y": 268.3498774572402,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"av7wpJ-VT38n4rxKMH3Ge",
				"_qtyrOUhFyGHfjtA9mWNS",
				"iJf-L_UnhrdA3F8jdE_FG",
				"QfnIiyDusM4zo-Nx-lkhd"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985225,
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
			"version": 3388,
			"versionNonce": 1154205752,
			"isDeleted": false,
			"id": "m4_oJN3NJivvonV0s9BKN",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 500.75945786929697,
			"y": 263.47569675046253,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"av7wpJ-VT38n4rxKMH3Ge",
				"_qtyrOUhFyGHfjtA9mWNS",
				"iJf-L_UnhrdA3F8jdE_FG",
				"QfnIiyDusM4zo-Nx-lkhd"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985225,
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
			"version": 3301,
			"versionNonce": 350091080,
			"isDeleted": false,
			"id": "1Fo_BCkj-XP1q8-9Xa-SR",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 481.72491045160996,
			"y": 263.7018866878355,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"av7wpJ-VT38n4rxKMH3Ge",
				"_qtyrOUhFyGHfjtA9mWNS",
				"iJf-L_UnhrdA3F8jdE_FG",
				"QfnIiyDusM4zo-Nx-lkhd"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985225,
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
			"version": 3496,
			"versionNonce": 697696568,
			"isDeleted": false,
			"id": "o1lEc58nCaibfw0N6gzAR",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 499.7980963645932,
			"y": 307.2188244528423,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"_qtyrOUhFyGHfjtA9mWNS",
				"iJf-L_UnhrdA3F8jdE_FG",
				"QfnIiyDusM4zo-Nx-lkhd"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985225,
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
			"version": 3454,
			"versionNonce": 1672465992,
			"isDeleted": false,
			"id": "DTSEClsqjcPV6zZTioNtF",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 480.7635489469062,
			"y": 307.44501439021525,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"_qtyrOUhFyGHfjtA9mWNS",
				"iJf-L_UnhrdA3F8jdE_FG",
				"QfnIiyDusM4zo-Nx-lkhd"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985225,
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
			"version": 333,
			"versionNonce": 1253120568,
			"isDeleted": false,
			"id": "keMwFdrdFGfY8SdqYbhIU",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 885.0493844754416,
			"y": 61.20075029191112,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 398.67068737895113,
			"height": 179.5843167106368,
			"seed": 1651137455,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985225,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "DF5u1EtvOGep8OCESrBPx",
				"focus": -0.3770091383641173,
				"gap": 6.489291892301878
			},
			"endBinding": {
				"elementId": "UpHK4gABCAwgOIIc99wx9",
				"focus": -0.6807250608343925,
				"gap": 11.902970282689353
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
					-296.116610004711,
					4.887522440456493
				],
				[
					-398.67068737895113,
					179.5843167106368
				]
			]
		},
		{
			"type": "arrow",
			"version": 566,
			"versionNonce": 1211024712,
			"isDeleted": false,
			"id": "FiUZOyF4gdlXgFNi-4RkA",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 925.2927295125808,
			"y": 116.47065270073358,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 0.10841639962188765,
			"height": 106.22970071181476,
			"seed": 485934383,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985225,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "NV1uv1oL",
				"focus": -0.0076986901875691766,
				"gap": 5.534298509307639
			},
			"endBinding": {
				"elementId": "05iHuFGide19YsTmcubrD",
				"focus": -0.024958608486561392,
				"gap": 13.606731491736696
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
					-0.10841639962188765,
					106.22970071181476
				]
			]
		},
		{
			"type": "arrow",
			"version": 203,
			"versionNonce": 721490744,
			"isDeleted": false,
			"id": "A1UpYsdZB-AJhfrGcybEm",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 864.2428674958768,
			"y": 280.4934814837633,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 326.6666666666665,
			"height": 2.2222222222221717,
			"seed": 1226965409,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985225,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "05iHuFGide19YsTmcubrD",
				"focus": 0.17014975856058742,
				"gap": 8.335810887480932
			},
			"endBinding": {
				"elementId": "UpHK4gABCAwgOIIc99wx9",
				"focus": -0.2129651151092326,
				"gap": 10.049395993058397
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
					-326.6666666666665,
					-2.2222222222221717
				]
			]
		},
		{
			"type": "rectangle",
			"version": 2818,
			"versionNonce": 1337384008,
			"isDeleted": false,
			"id": "iaRsIub9ipFKj11SMWFDh",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1016.5047294995527,
			"y": 507.90685793997613,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e1488",
			"width": 66.53246337764709,
			"height": 66.4687522713753,
			"seed": 1087403015,
			"groupIds": [
				"dMvgJ2g0QcDV9EglYAlo4",
				"wJFp6t2ZdYvCE-MPg9oJ0",
				"Pin2IEgDGnpt0y0jkQzXe"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "yAEMJgVKTrF5WpnF6FoWq",
					"type": "arrow"
				}
			],
			"updated": 1684536985225,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1958,
			"versionNonce": 1357507640,
			"isDeleted": false,
			"id": "-wDg7Iix-AUzoLa76UF99",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1042.2989720799449,
			"y": 535.5034707508455,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.927534089288194,
			"height": 27.761273291189447,
			"seed": 1235612649,
			"groupIds": [
				"F4wVeokJEBSaU7lpOCRes",
				"wJFp6t2ZdYvCE-MPg9oJ0",
				"Pin2IEgDGnpt0y0jkQzXe"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985225,
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
			"version": 1958,
			"versionNonce": 2082739016,
			"isDeleted": false,
			"id": "J73CcvLRcUzDh586J7fPt",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1067.5725167680919,
			"y": 551.9112843177872,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 35.98406748383116,
			"height": 45.41383889698984,
			"seed": 47340327,
			"groupIds": [
				"F4wVeokJEBSaU7lpOCRes",
				"wJFp6t2ZdYvCE-MPg9oJ0",
				"Pin2IEgDGnpt0y0jkQzXe"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985225,
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
			"version": 2324,
			"versionNonce": 1448060216,
			"isDeleted": false,
			"id": "zurYGVXL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 983.4085485999624,
			"y": 579.4985026718557,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 132.71511840820312,
			"height": 24.77118485290355,
			"seed": 242323145,
			"groupIds": [
				"Pin2IEgDGnpt0y0jkQzXe"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985225,
			"link": null,
			"locked": false,
			"fontSize": 20.642654044086292,
			"fontFamily": 1,
			"text": "Limpiar tabla",
			"rawText": "Limpiar tabla",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Limpiar tabla",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 3126,
			"versionNonce": 869427784,
			"isDeleted": false,
			"id": "rKYozOTs",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 250.22618318248192,
			"y": 1062.7504129414024,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 204.07984924316406,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"AHA8T_QgUipg9xX26IQdZ"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985225,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "stating.VentaEnLinea",
			"rawText": "stating.VentaEnLinea",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "stating.VentaEnLinea",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4241,
			"versionNonce": 1462314056,
			"isDeleted": false,
			"id": "_oK5wAGDh-vsn7X2GniSV",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 308.0656524711951,
			"y": 993.2832753804753,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"l3YTZEUgdgD80h3t5aqZ5",
				"xilxxkcJeelYel3plXATG",
				"M2TgkUlPUIUz1nvIlhsM3",
				"eLhujw3Gj98Nw6Ac5HPAF",
				"AHA8T_QgUipg9xX26IQdZ"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "ZDp_XNbdarN5UH28XX6h9",
					"type": "arrow"
				},
				{
					"id": "Lpu7e0U4B65kG_zEZqetU",
					"type": "arrow"
				}
			],
			"updated": 1684537004888,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2668,
			"versionNonce": 832430408,
			"isDeleted": false,
			"id": "7-zHuzpCXGs4rb0dw55Md",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 329.1063245742446,
			"y": 1016.5675636028848,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"1s906WiUpmWsjg0fvwNS7",
				"9MZID3zLmTZC3Tb1KOJ6-",
				"eLhujw3Gj98Nw6Ac5HPAF",
				"AHA8T_QgUipg9xX26IQdZ"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985225,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2810,
			"versionNonce": 681686840,
			"isDeleted": false,
			"id": "-HZHiCzkhjL87bxWvtNXB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 330.09162357839637,
			"y": 1020.7522080589845,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"1s906WiUpmWsjg0fvwNS7",
				"9MZID3zLmTZC3Tb1KOJ6-",
				"eLhujw3Gj98Nw6Ac5HPAF",
				"AHA8T_QgUipg9xX26IQdZ"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985225,
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
			"version": 3516,
			"versionNonce": 1960998984,
			"isDeleted": false,
			"id": "LNHsNcXUmrWWwQu0vpW1n",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 360.74873822042105,
			"y": 1010.4393803696214,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"8VaxPMY_siNAmNO6Ft06i",
				"9MZID3zLmTZC3Tb1KOJ6-",
				"eLhujw3Gj98Nw6Ac5HPAF",
				"AHA8T_QgUipg9xX26IQdZ"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985225,
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
			"version": 3607,
			"versionNonce": 450236472,
			"isDeleted": false,
			"id": "q_Z2ZVr6ZiLPQBPEqBVau",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 326.42902480679345,
			"y": 1008.9451155524782,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"oOr7doL1WZTWvzwl_uosi",
				"9MZID3zLmTZC3Tb1KOJ6-",
				"eLhujw3Gj98Nw6Ac5HPAF",
				"AHA8T_QgUipg9xX26IQdZ"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985225,
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
			"version": 3717,
			"versionNonce": 830222152,
			"isDeleted": false,
			"id": "VDSM6xuQ6k65ItbkBLwU_",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 345.7594578692972,
			"y": 1004.0709348457005,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"oOr7doL1WZTWvzwl_uosi",
				"9MZID3zLmTZC3Tb1KOJ6-",
				"eLhujw3Gj98Nw6Ac5HPAF",
				"AHA8T_QgUipg9xX26IQdZ"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985225,
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
			"version": 3630,
			"versionNonce": 1461143864,
			"isDeleted": false,
			"id": "rhioRbYpHbyiHX3aTTlQo",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 326.7249104516102,
			"y": 1004.2971247830735,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"oOr7doL1WZTWvzwl_uosi",
				"9MZID3zLmTZC3Tb1KOJ6-",
				"eLhujw3Gj98Nw6Ac5HPAF",
				"AHA8T_QgUipg9xX26IQdZ"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985225,
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
			"version": 3825,
			"versionNonce": 1070007880,
			"isDeleted": false,
			"id": "yUJwCDcHSXyctTjJlSlX7",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 344.79809636459345,
			"y": 1047.8140625480803,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"9MZID3zLmTZC3Tb1KOJ6-",
				"eLhujw3Gj98Nw6Ac5HPAF",
				"AHA8T_QgUipg9xX26IQdZ"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985225,
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
			"version": 3783,
			"versionNonce": 1221157432,
			"isDeleted": false,
			"id": "jsI8V52cwoMxUiM5FhU8b",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 325.76354894690644,
			"y": 1048.0402524854533,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"9MZID3zLmTZC3Tb1KOJ6-",
				"eLhujw3Gj98Nw6Ac5HPAF",
				"AHA8T_QgUipg9xX26IQdZ"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985225,
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
			"version": 2497,
			"versionNonce": 211746120,
			"isDeleted": false,
			"id": "15KgnQ6C",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 739.7496181393503,
			"y": 881.036127227117,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 344.2397155761719,
			"height": 24,
			"seed": 1245685479,
			"groupIds": [
				"UpcL6m-3sADrdXMu9X5VJ"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985225,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Brightcell-VMI-load-dwventaEnLinea",
			"rawText": "Brightcell-VMI-load-dwventaEnLinea",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Brightcell-VMI-load-dwventaEnLinea",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4526,
			"versionNonce": 1322277688,
			"isDeleted": false,
			"id": "8CVdBDTUOk_Vvtb8ZHDIV",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 867.544762032745,
			"y": 760.4737515709519,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 107.76604983800789,
			"height": 107.66285368525563,
			"seed": 941612809,
			"groupIds": [
				"Qifiiw00kx44_vW6yHUVx",
				"AxA6afElwUkmjjJxF44AR",
				"dotnLTyAJ2kDDNh3bJSos",
				"G6axnEZ5ULYsblOtKXH5u",
				"UpcL6m-3sADrdXMu9X5VJ"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "kEtI3fLcVj4AtYotPhbIJ",
					"type": "arrow"
				}
			],
			"updated": 1684536985225,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2378,
			"versionNonce": 157291592,
			"isDeleted": false,
			"id": "QHgvViJkSZ4yG86s_jRoE",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 926.2235468507943,
			"y": 830.1724187485142,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 17.21171637693966,
			"height": 30.981089478491384,
			"seed": 1100493319,
			"groupIds": [
				"gcBg2fyJuAsQ-0SSTt2fJ",
				"G6axnEZ5ULYsblOtKXH5u",
				"UpcL6m-3sADrdXMu9X5VJ"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985226,
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
			"version": 2458,
			"versionNonce": 1267741752,
			"isDeleted": false,
			"id": "zsoNJyebx3Jko9gRgjOJQ",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 917.1443664619569,
			"y": 830.1724187485142,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 17.21171637693966,
			"height": 30.981089478491384,
			"seed": 1757484521,
			"groupIds": [
				"gcBg2fyJuAsQ-0SSTt2fJ",
				"G6axnEZ5ULYsblOtKXH5u",
				"UpcL6m-3sADrdXMu9X5VJ"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985226,
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
			"version": 2258,
			"versionNonce": 468077384,
			"isDeleted": false,
			"id": "FpGgg--ZkW136MPnxvImU",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 917.6176886623243,
			"y": 830.6027116579303,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 7.745272369622733,
			"height": 0,
			"seed": 1341282599,
			"groupIds": [
				"gcBg2fyJuAsQ-0SSTt2fJ",
				"G6axnEZ5ULYsblOtKXH5u",
				"UpcL6m-3sADrdXMu9X5VJ"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985226,
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
			"version": 2372,
			"versionNonce": 887942456,
			"isDeleted": false,
			"id": "uOu28AcUfzbae3ob-njGc",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 901.2665581042315,
			"y": 798.6405543459543,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 42.168705123502164,
			"height": 7.314979460199344,
			"seed": 567832777,
			"groupIds": [
				"gcBg2fyJuAsQ-0SSTt2fJ",
				"G6axnEZ5ULYsblOtKXH5u",
				"UpcL6m-3sADrdXMu9X5VJ"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985226,
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
			"version": 2262,
			"versionNonce": 244163144,
			"isDeleted": false,
			"id": "7DhnT2zY-XBnly-7F7ozv",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 900.3199137035003,
			"y": 798.330743451178,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 16.35113055809267,
			"height": 2.581757456540929,
			"seed": 1522179143,
			"groupIds": [
				"gcBg2fyJuAsQ-0SSTt2fJ",
				"G6axnEZ5ULYsblOtKXH5u",
				"UpcL6m-3sADrdXMu9X5VJ"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985226,
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
			"version": 2216,
			"versionNonce": 608863800,
			"isDeleted": false,
			"id": "xRcIQyhz7GIoVHo00sxHY",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 921.963647047503,
			"y": 777.7197130897821,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 956395433,
			"groupIds": [
				"gcBg2fyJuAsQ-0SSTt2fJ",
				"G6axnEZ5ULYsblOtKXH5u",
				"UpcL6m-3sADrdXMu9X5VJ"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985226,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 2216,
			"versionNonce": 3283272,
			"isDeleted": false,
			"id": "A-QObPNK_mNVwcxjjKxPX",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 910.3457384930693,
			"y": 786.2395126963672,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 1707965287,
			"groupIds": [
				"gcBg2fyJuAsQ-0SSTt2fJ",
				"G6axnEZ5ULYsblOtKXH5u",
				"UpcL6m-3sADrdXMu9X5VJ"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985226,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 2217,
			"versionNonce": 1720516408,
			"isDeleted": false,
			"id": "xUexPizDM7VxIiCgdd9Tg",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 924.1151115946182,
			"y": 791.015763990971,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 1147638409,
			"groupIds": [
				"gcBg2fyJuAsQ-0SSTt2fJ",
				"G6axnEZ5ULYsblOtKXH5u",
				"UpcL6m-3sADrdXMu9X5VJ"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985226,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1714,
			"versionNonce": 1412411464,
			"isDeleted": false,
			"id": "Z6pKzhISrIBOK21P-cbiG",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 923.954279073907,
			"y": 834.5098461658854,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 18.44546425611026,
			"height": 14.81684833687558,
			"seed": 1165457031,
			"groupIds": [
				"G6axnEZ5ULYsblOtKXH5u",
				"UpcL6m-3sADrdXMu9X5VJ"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985226,
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
			"version": 396,
			"versionNonce": 202922040,
			"isDeleted": false,
			"id": "kEtI3fLcVj4AtYotPhbIJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 992.1344444010278,
			"y": 819.0015750740092,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 374.65690183862534,
			"height": 0.893059367507476,
			"seed": 1226965409,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985226,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "8CVdBDTUOk_Vvtb8ZHDIV",
				"focus": 0.09015845495698988,
				"gap": 16.823632530275006
			},
			"endBinding": {
				"elementId": "hNCGRFym5fZ586xFix9fz",
				"focus": -0.045552031114349405,
				"gap": 2.9409728982088836
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
					374.65690183862534,
					-0.893059367507476
				]
			]
		},
		{
			"type": "text",
			"version": 2979,
			"versionNonce": 576874312,
			"isDeleted": false,
			"id": "BuXH8iYs",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1335.3828248247348,
			"y": 853.8218415128309,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 157.0998992919922,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"3WyqKpNQ6Uhbh8HEj8iJP"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "wB93Srys8q-W7ig5zK7dp",
					"type": "arrow"
				}
			],
			"updated": 1684536985226,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dw.VentaEnLinea",
			"rawText": "dw.VentaEnLinea",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dw.VentaEnLinea",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4093,
			"versionNonce": 2026934584,
			"isDeleted": false,
			"id": "hNCGRFym5fZ586xFix9fz",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1369.732319137862,
			"y": 784.3547039519037,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"_trLpVXyvibkeIlb9rj7e",
				"rd1jhIVzCdA065e69pIFK",
				"f8rKKaZDz0bmBfBmayKMf",
				"pfNxC1g6THFPOIK7yQ_7R",
				"3WyqKpNQ6Uhbh8HEj8iJP"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "kEtI3fLcVj4AtYotPhbIJ",
					"type": "arrow"
				},
				{
					"id": "yAEMJgVKTrF5WpnF6FoWq",
					"type": "arrow"
				}
			],
			"updated": 1684536985226,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2519,
			"versionNonce": 656817736,
			"isDeleted": false,
			"id": "SDc0GBbx8BNZryuvhGyOn",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1390.7729912409116,
			"y": 807.6389921743132,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"jECCxAFMToTY6GXZ4RCVV",
				"ehf5L4nueHYWQ1tDECkpm",
				"pfNxC1g6THFPOIK7yQ_7R",
				"3WyqKpNQ6Uhbh8HEj8iJP"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985226,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2661,
			"versionNonce": 1947839032,
			"isDeleted": false,
			"id": "wddMmM3Kv7ZuXGO5R3X9M",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1391.7582902450633,
			"y": 811.8236366304129,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"jECCxAFMToTY6GXZ4RCVV",
				"ehf5L4nueHYWQ1tDECkpm",
				"pfNxC1g6THFPOIK7yQ_7R",
				"3WyqKpNQ6Uhbh8HEj8iJP"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985226,
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
			"versionNonce": 861353288,
			"isDeleted": false,
			"id": "UjPr-lUz2kdHawmAYXvng",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1422.415404887088,
			"y": 801.5108089410498,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"q7epC15SlopjF14DJLpb0",
				"ehf5L4nueHYWQ1tDECkpm",
				"pfNxC1g6THFPOIK7yQ_7R",
				"3WyqKpNQ6Uhbh8HEj8iJP"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985226,
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
			"versionNonce": 953656120,
			"isDeleted": false,
			"id": "iufaf5Buyh2cx8aOhaM7B",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1388.0956914734604,
			"y": 800.0165441239067,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"QP1lE2jh_LIX_h2_8-QKQ",
				"ehf5L4nueHYWQ1tDECkpm",
				"pfNxC1g6THFPOIK7yQ_7R",
				"3WyqKpNQ6Uhbh8HEj8iJP"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985226,
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
			"versionNonce": 475089992,
			"isDeleted": false,
			"id": "q7Xe0Mt-0SyqBirMUXGxC",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1407.4261245359642,
			"y": 795.142363417129,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"QP1lE2jh_LIX_h2_8-QKQ",
				"ehf5L4nueHYWQ1tDECkpm",
				"pfNxC1g6THFPOIK7yQ_7R",
				"3WyqKpNQ6Uhbh8HEj8iJP"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985226,
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
			"versionNonce": 91126840,
			"isDeleted": false,
			"id": "s6nUyB5Ag52YVdFrLltjp",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1388.3915771182772,
			"y": 795.368553354502,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"QP1lE2jh_LIX_h2_8-QKQ",
				"ehf5L4nueHYWQ1tDECkpm",
				"pfNxC1g6THFPOIK7yQ_7R",
				"3WyqKpNQ6Uhbh8HEj8iJP"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985226,
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
			"versionNonce": 737182536,
			"isDeleted": false,
			"id": "YiY59okOpDp0vPPgEl_GF",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1406.4647630312604,
			"y": 838.8854911195084,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"ehf5L4nueHYWQ1tDECkpm",
				"pfNxC1g6THFPOIK7yQ_7R",
				"3WyqKpNQ6Uhbh8HEj8iJP"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985226,
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
			"versionNonce": 734147896,
			"isDeleted": false,
			"id": "wKxGDsmuUUdEhBi_b_i8p",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1387.4302156135734,
			"y": 839.1116810568814,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"ehf5L4nueHYWQ1tDECkpm",
				"pfNxC1g6THFPOIK7yQ_7R",
				"3WyqKpNQ6Uhbh8HEj8iJP"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985226,
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
			"version": 2889,
			"versionNonce": 277928520,
			"isDeleted": false,
			"id": "EpanAGhNG3kgeD8Vkp0Gy",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 774.838062832886,
			"y": 502.906857939976,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e1488",
			"width": 66.53246337764709,
			"height": 66.4687522713753,
			"seed": 1087403015,
			"groupIds": [
				"CVhtOQX6N7Dj-NyiNlz0L",
				"BD1-da6jGoow8YCC3USQO",
				"pP9bTf9HMVeYz10Hq6F5f"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985226,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2039,
			"versionNonce": 557239864,
			"isDeleted": false,
			"id": "10By53ivANwOdJeB5_1EM",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 800.6323054132781,
			"y": 530.5034707508455,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.927534089288194,
			"height": 27.761273291189447,
			"seed": 1235612649,
			"groupIds": [
				"xY6KFG2TlDlfY1cIIOxS5",
				"BD1-da6jGoow8YCC3USQO",
				"pP9bTf9HMVeYz10Hq6F5f"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985226,
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
			"version": 2039,
			"versionNonce": 1292783944,
			"isDeleted": false,
			"id": "IlXvO6ILmF7f9g30-SZxB",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 825.9058501014251,
			"y": 546.9112843177875,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 35.98406748383116,
			"height": 45.41383889698984,
			"seed": 47340327,
			"groupIds": [
				"xY6KFG2TlDlfY1cIIOxS5",
				"BD1-da6jGoow8YCC3USQO",
				"pP9bTf9HMVeYz10Hq6F5f"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985226,
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
			"version": 2406,
			"versionNonce": 246433592,
			"isDeleted": false,
			"id": "TA2YfGWb",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 741.7418819332956,
			"y": 574.4985026718557,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 132.71511840820312,
			"height": 24.77118485290355,
			"seed": 242323145,
			"groupIds": [
				"pP9bTf9HMVeYz10Hq6F5f"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985226,
			"link": null,
			"locked": false,
			"fontSize": 20.642654044086292,
			"fontFamily": 1,
			"text": "Limpiar tabla",
			"rawText": "Limpiar tabla",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Limpiar tabla",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "text",
			"version": 2581,
			"versionNonce": 1372419656,
			"isDeleted": false,
			"id": "09vATIjO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 731.1623397413111,
			"y": 1133.9896403929147,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 350.0397033691406,
			"height": 24,
			"seed": 1245685479,
			"groupIds": [
				"tD8xJ4625d_2Z84cFWgW3"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "yG8ymLj9cmzAQ4Uy1P8yH",
					"type": "arrow"
				},
				{
					"id": "Muj_YI5yyGkvPeF-MukIs",
					"type": "arrow"
				}
			],
			"updated": 1684536985227,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Brightcell-VMI-stating-VentaEnLinea",
			"rawText": "Brightcell-VMI-stating-VentaEnLinea",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Brightcell-VMI-stating-VentaEnLinea",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4611,
			"versionNonce": 346157624,
			"isDeleted": false,
			"id": "WSWlzcXvJ_P47ohwMAfLe",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 858.9574836347058,
			"y": 1013.4272647367495,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 107.76604983800789,
			"height": 107.66285368525563,
			"seed": 941612809,
			"groupIds": [
				"7V2htvd_YYNYrB5V6cm7e",
				"4GmzvoFUKxcn7RtvD54E4",
				"F-oZKevBXfPhlETXvTxbk",
				"T-d4eYImLwIvE7W9iBY78",
				"tD8xJ4625d_2Z84cFWgW3"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "ZDp_XNbdarN5UH28XX6h9",
					"type": "arrow"
				},
				{
					"id": "y2TQ0_kuaXdIx4Fn_CTIq",
					"type": "arrow"
				},
				{
					"id": "yG8ymLj9cmzAQ4Uy1P8yH",
					"type": "arrow"
				},
				{
					"id": "wB93Srys8q-W7ig5zK7dp",
					"type": "arrow"
				}
			],
			"updated": 1684536985227,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2460,
			"versionNonce": 1951886664,
			"isDeleted": false,
			"id": "kaJDKeKa_Hi-FQL2DRjlB",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 917.6362684527551,
			"y": 1083.1259319143119,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 17.21171637693966,
			"height": 30.981089478491384,
			"seed": 1100493319,
			"groupIds": [
				"_TIRzBAv21rYqMF3XPR78",
				"T-d4eYImLwIvE7W9iBY78",
				"tD8xJ4625d_2Z84cFWgW3"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985227,
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
			"version": 2540,
			"versionNonce": 823585592,
			"isDeleted": false,
			"id": "_BkUEEjeoFVfQFZQdOi6F",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 908.5570880639177,
			"y": 1083.1259319143119,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 17.21171637693966,
			"height": 30.981089478491384,
			"seed": 1757484521,
			"groupIds": [
				"_TIRzBAv21rYqMF3XPR78",
				"T-d4eYImLwIvE7W9iBY78",
				"tD8xJ4625d_2Z84cFWgW3"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985227,
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
			"version": 2340,
			"versionNonce": 1082819656,
			"isDeleted": false,
			"id": "gCaDYhaE2TdIn3Q_01EzE",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 909.0304102642851,
			"y": 1083.556224823728,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 7.745272369622733,
			"height": 0,
			"seed": 1341282599,
			"groupIds": [
				"_TIRzBAv21rYqMF3XPR78",
				"T-d4eYImLwIvE7W9iBY78",
				"tD8xJ4625d_2Z84cFWgW3"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985227,
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
			"version": 2454,
			"versionNonce": 1183106104,
			"isDeleted": false,
			"id": "KQnfosC1T5iseypvWMpqt",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 892.6792797061923,
			"y": 1051.594067511752,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 42.168705123502164,
			"height": 7.314979460199344,
			"seed": 567832777,
			"groupIds": [
				"_TIRzBAv21rYqMF3XPR78",
				"T-d4eYImLwIvE7W9iBY78",
				"tD8xJ4625d_2Z84cFWgW3"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985227,
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
			"version": 2344,
			"versionNonce": 1682094920,
			"isDeleted": false,
			"id": "knudYgm_0dWSxNJGLaM-N",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 891.7326353054611,
			"y": 1051.2842566169757,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 16.35113055809267,
			"height": 2.581757456540929,
			"seed": 1522179143,
			"groupIds": [
				"_TIRzBAv21rYqMF3XPR78",
				"T-d4eYImLwIvE7W9iBY78",
				"tD8xJ4625d_2Z84cFWgW3"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985227,
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
			"version": 2298,
			"versionNonce": 47152440,
			"isDeleted": false,
			"id": "oDDWKGIPr4gaRGOc1Z-Aj",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 913.3763686494638,
			"y": 1030.6732262555797,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 956395433,
			"groupIds": [
				"_TIRzBAv21rYqMF3XPR78",
				"T-d4eYImLwIvE7W9iBY78",
				"tD8xJ4625d_2Z84cFWgW3"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985227,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 2298,
			"versionNonce": 1910248008,
			"isDeleted": false,
			"id": "5qgrJrgmR2fr1MevURbXS",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 901.7584600950302,
			"y": 1039.1930258621649,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 1707965287,
			"groupIds": [
				"_TIRzBAv21rYqMF3XPR78",
				"T-d4eYImLwIvE7W9iBY78",
				"tD8xJ4625d_2Z84cFWgW3"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985227,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 2299,
			"versionNonce": 928716344,
			"isDeleted": false,
			"id": "COOB-tpEJ1qqNihKb4hRp",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 915.527833196579,
			"y": 1043.9692771567686,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 1147638409,
			"groupIds": [
				"_TIRzBAv21rYqMF3XPR78",
				"T-d4eYImLwIvE7W9iBY78",
				"tD8xJ4625d_2Z84cFWgW3"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985227,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1796,
			"versionNonce": 1345489224,
			"isDeleted": false,
			"id": "CIjwt4hY42zZufMnzmDW1",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 915.3670006758678,
			"y": 1087.463359331683,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 18.44546425611026,
			"height": 14.81684833687558,
			"seed": 1165457031,
			"groupIds": [
				"T-d4eYImLwIvE7W9iBY78",
				"tD8xJ4625d_2Z84cFWgW3"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985227,
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
			"version": 762,
			"versionNonce": 1762365240,
			"isDeleted": false,
			"id": "ZDp_XNbdarN5UH28XX6h9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 847.692411063802,
			"y": 1063.2317000824478,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 461.77166958994565,
			"height": 28.228582368657953,
			"seed": 1226965409,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985227,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "WSWlzcXvJ_P47ohwMAfLe",
				"focus": 0.0013324773940907753,
				"gap": 11.265072570903783
			},
			"endBinding": {
				"elementId": "_oK5wAGDh-vsn7X2GniSV",
				"focus": 0.19698729450635474,
				"gap": 13.3939366377042
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
					-461.77166958994565,
					-28.228582368657953
				]
			]
		},
		{
			"type": "text",
			"version": 3153,
			"versionNonce": 715268168,
			"isDeleted": false,
			"id": "A9ogQAbV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 409.43082358443326,
			"y": 1339.5134499167245,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 135.5598907470703,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"mLbqXiPU3LXrjKxLLXPyC"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985227,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dw.dmMaterial",
			"rawText": "dw.dmMaterial",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dw.dmMaterial",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4253,
			"versionNonce": 1615128632,
			"isDeleted": false,
			"id": "xvqfOD9m9Lh8UInngIP7P",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 433.01031362509957,
			"y": 1270.0463123557972,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"GdAdarKy2ZtMfx9j0Je9Q",
				"GOjhBV7u2-YYZGV5GCJ9F",
				"DXuTWF9fGB_g_MvD1PdWt",
				"HrX6EJIhx32y6ZEklzk3m",
				"mLbqXiPU3LXrjKxLLXPyC"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "yG8ymLj9cmzAQ4Uy1P8yH",
					"type": "arrow"
				}
			],
			"updated": 1684536985227,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2684,
			"versionNonce": 1627838280,
			"isDeleted": false,
			"id": "vQK3q_Z2kWO8VmHne9dMK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 454.05098572814904,
			"y": 1293.3306005782067,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"e14Df-z4JVJ0qV92tqHnN",
				"dnqLET3xweGTnVxnkQ-If",
				"HrX6EJIhx32y6ZEklzk3m",
				"mLbqXiPU3LXrjKxLLXPyC"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985227,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2826,
			"versionNonce": 954933560,
			"isDeleted": false,
			"id": "qPh9zOibuZl0oaAqdUm5a",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 455.0362847323008,
			"y": 1297.5152450343064,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"e14Df-z4JVJ0qV92tqHnN",
				"dnqLET3xweGTnVxnkQ-If",
				"HrX6EJIhx32y6ZEklzk3m",
				"mLbqXiPU3LXrjKxLLXPyC"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985227,
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
			"version": 3532,
			"versionNonce": 2008854088,
			"isDeleted": false,
			"id": "5Y4iete1a1ET_M2DZhAn7",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 485.6933993743255,
			"y": 1287.2024173449433,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"gEhvwtace4Mdd1SwB2qid",
				"dnqLET3xweGTnVxnkQ-If",
				"HrX6EJIhx32y6ZEklzk3m",
				"mLbqXiPU3LXrjKxLLXPyC"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985227,
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
			"version": 3623,
			"versionNonce": 1919040056,
			"isDeleted": false,
			"id": "fpM-X5_-kn5LQEYEjlt4-",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 451.3736859606979,
			"y": 1285.7081525278002,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"_0WWbnCAEaY8Le5__rBpS",
				"dnqLET3xweGTnVxnkQ-If",
				"HrX6EJIhx32y6ZEklzk3m",
				"mLbqXiPU3LXrjKxLLXPyC"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985227,
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
			"version": 3733,
			"versionNonce": 127903048,
			"isDeleted": false,
			"id": "KtU-CqoVJdJaFFJiYcRyT",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 470.70411902320166,
			"y": 1280.8339718210225,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"_0WWbnCAEaY8Le5__rBpS",
				"dnqLET3xweGTnVxnkQ-If",
				"HrX6EJIhx32y6ZEklzk3m",
				"mLbqXiPU3LXrjKxLLXPyC"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985227,
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
			"version": 3646,
			"versionNonce": 2140025656,
			"isDeleted": false,
			"id": "idiQDIYMQ9GSOYnobp8ab",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 451.66957160551465,
			"y": 1281.0601617583955,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"_0WWbnCAEaY8Le5__rBpS",
				"dnqLET3xweGTnVxnkQ-If",
				"HrX6EJIhx32y6ZEklzk3m",
				"mLbqXiPU3LXrjKxLLXPyC"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985227,
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
			"version": 3841,
			"versionNonce": 772521032,
			"isDeleted": false,
			"id": "vZ2MLK1v1QN_h4hu7aBNQ",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 469.7427575184979,
			"y": 1324.5770995234018,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"dnqLET3xweGTnVxnkQ-If",
				"HrX6EJIhx32y6ZEklzk3m",
				"mLbqXiPU3LXrjKxLLXPyC"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985227,
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
			"version": 3799,
			"versionNonce": 1456671800,
			"isDeleted": false,
			"id": "2Vv_7kh-3zBcGWnxEqmLP",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 450.7082101008109,
			"y": 1324.8032894607747,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"dnqLET3xweGTnVxnkQ-If",
				"HrX6EJIhx32y6ZEklzk3m",
				"mLbqXiPU3LXrjKxLLXPyC"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985227,
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
			"version": 209,
			"versionNonce": 1154665272,
			"isDeleted": false,
			"id": "y2TQ0_kuaXdIx4Fn_CTIq",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 851.2386714627883,
			"y": 1043.0350403557943,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 371.5279025048195,
			"height": 680.5408735052478,
			"seed": 1522967344,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684537053145,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "WSWlzcXvJ_P47ohwMAfLe",
				"focus": -0.005351722850135337,
				"gap": 7.718812171917477
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
					-315.81361679053384,
					-126.25515921953365
				],
				[
					-371.5279025048195,
					-680.5408735052478
				]
			]
		},
		{
			"type": "arrow",
			"version": 427,
			"versionNonce": 34915640,
			"isDeleted": false,
			"id": "yG8ymLj9cmzAQ4Uy1P8yH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 833.634008232888,
			"y": 1172.6487824786884,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 331.79156900427193,
			"height": 118.54428988667541,
			"seed": 709581776,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985227,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "09vATIjO",
				"focus": -0.007441877817983731,
				"gap": 14.659142085773738
			},
			"endBinding": {
				"elementId": "xvqfOD9m9Lh8UInngIP7P",
				"focus": 0.04630531975700639,
				"gap": 4.370973238559486
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
					-331.79156900427193,
					118.54428988667541
				]
			]
		},
		{
			"type": "arrow",
			"version": 187,
			"versionNonce": 1785678408,
			"isDeleted": false,
			"id": "wB93Srys8q-W7ig5zK7dp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 977.5679118151115,
			"y": 1083.4041834426469,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 423.57142857142844,
			"height": 200.91001659210042,
			"seed": 1785295664,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985227,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "WSWlzcXvJ_P47ohwMAfLe",
				"focus": 0.3453430395624281,
				"gap": 10.844378342397874
			},
			"endBinding": {
				"elementId": "BuXH8iYs",
				"focus": 0.09288713374809446,
				"gap": 4.672325337715506
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
					367.4999999999998,
					-19.481445163529088
				],
				[
					423.57142857142844,
					-200.91001659210042
				]
			]
		},
		{
			"type": "arrow",
			"version": 526,
			"versionNonce": 783769144,
			"isDeleted": false,
			"id": "ppFyfMj0ELQ56v9p1t8e8",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 80,
			"angle": 0,
			"x": -495.318851723251,
			"y": 382.5972147184814,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 275.1065210237075,
			"height": 4.509942967601897,
			"seed": 574520847,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985227,
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
					275.1065210237075,
					-4.509942967601897
				]
			]
		},
		{
			"type": "text",
			"version": 549,
			"versionNonce": 1100923208,
			"isDeleted": false,
			"id": "cz6FsgQ5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 80,
			"angle": 0,
			"x": -181.22563241944732,
			"y": 305.9281842692516,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 258.65631103515625,
			"height": 27.34941617042409,
			"seed": 1664452687,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985227,
			"link": null,
			"locked": false,
			"fontSize": 21.87953293633927,
			"fontFamily": 1,
			"text": "Consulta información de:",
			"rawText": "Consulta información de:",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Consulta información de:",
			"lineHeight": 1.25,
			"baseline": 19
		},
		{
			"type": "text",
			"version": 599,
			"versionNonce": 1033819960,
			"isDeleted": false,
			"id": "OtH3CpSA",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 80,
			"angle": 0,
			"x": -160.69989704929355,
			"y": 362.9092493431335,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 226.638671875,
			"height": 27.34941617042409,
			"seed": 1664452687,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985227,
			"link": null,
			"locked": false,
			"fontSize": 21.87953293633927,
			"fontFamily": 1,
			"text": "Carga información en:",
			"rawText": "Carga información en:",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Carga información en:",
			"lineHeight": 1.25,
			"baseline": 19
		},
		{
			"type": "arrow",
			"version": 237,
			"versionNonce": 298276936,
			"isDeleted": false,
			"id": "xNsdI6RpGoXZDCqUY9j_4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -492.2058135955592,
			"y": 264.38624914867967,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 266.9303018233391,
			"height": 2.187953293633927,
			"seed": 1834760815,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985228,
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
					266.9303018233391,
					-2.187953293633927
				]
			]
		},
		{
			"type": "text",
			"version": 632,
			"versionNonce": 1395601464,
			"isDeleted": false,
			"id": "J95mfbNH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 80,
			"angle": 0,
			"x": -159.15550214310537,
			"y": 243.05370453574892,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 200.32008361816406,
			"height": 38.28918263859373,
			"seed": 1664452687,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985228,
			"link": null,
			"locked": false,
			"fontSize": 30.631346110874986,
			"fontFamily": 1,
			"text": "Flujo principal",
			"rawText": "Flujo principal",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Flujo principal",
			"lineHeight": 1.25,
			"baseline": 27
		},
		{
			"type": "arrow",
			"version": 238,
			"versionNonce": 516230984,
			"isDeleted": false,
			"id": "bbqi12iMkwyrprhcG4-Cj",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -490.1506291022645,
			"y": 323.3986853524559,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 269.11825511697305,
			"height": 0,
			"seed": 1720843407,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985228,
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
					269.11825511697305,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 726,
			"versionNonce": 1733060920,
			"isDeleted": false,
			"id": "NklZnkGjJZ0MMZ9FRmc8e",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -622.3320000802532,
			"y": 75.97256650540652,
			"strokeColor": "#0091e2",
			"backgroundColor": "transparent",
			"width": 730.5141095050149,
			"height": 445.99808790832464,
			"seed": 302519605,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985228,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 2613,
			"versionNonce": 1358161480,
			"isDeleted": false,
			"id": "P6JaUnjG",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -606.4206917153292,
			"y": 92.73922498011706,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 119.91607666015625,
			"height": 69.02315028234011,
			"seed": 35046555,
			"groupIds": [
				"DzPwiYJnDkgwtg9pgexxx"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985228,
			"link": null,
			"locked": false,
			"fontSize": 55.21852022587209,
			"fontFamily": 1,
			"text": "Keys",
			"rawText": "Keys",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Keys",
			"lineHeight": 1.25,
			"baseline": 48
		},
		{
			"type": "rectangle",
			"version": 41,
			"versionNonce": 1471494968,
			"isDeleted": false,
			"id": "_HfUq2tnCcBTcHQCdl85O",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 690.8400632171761,
			"y": 450.708452564832,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 487.5,
			"height": 217.5,
			"seed": 424119624,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "vdDHXanixBvTKmxTX5DU9",
					"type": "arrow"
				},
				{
					"id": "Lpu7e0U4B65kG_zEZqetU",
					"type": "arrow"
				},
				{
					"id": "BshKi0GB811_uE14pAJ8D",
					"type": "arrow"
				},
				{
					"id": "doMoHWU1NRuQiaiQinhia",
					"type": "arrow"
				}
			],
			"updated": 1684537118728,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 653,
			"versionNonce": 623893832,
			"isDeleted": false,
			"id": "vdDHXanixBvTKmxTX5DU9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 921.2581403195982,
			"y": 385.097634467167,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 2.3915836003779987,
			"height": 56.22970071181476,
			"seed": 485934383,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684536985228,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "A8sen9Ro",
				"focus": 0.00037105989470560683,
				"gap": 4.2281739067167905
			},
			"endBinding": {
				"elementId": "_HfUq2tnCcBTcHQCdl85O",
				"focus": -0.023818544497180762,
				"gap": 9.381117385850246
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
					2.3915836003779987,
					56.22970071181476
				]
			]
		},
		{
			"type": "rectangle",
			"version": 2137,
			"versionNonce": 1815968568,
			"isDeleted": false,
			"id": "EPDetCwII8tQ_4XEr7VbZ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 869.6854289998853,
			"y": 1336.5270377724405,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e1488",
			"width": 85.17426249185807,
			"height": 85.09270010541165,
			"seed": 1087403015,
			"groupIds": [
				"A9WkFO9V-TnnDr6ALoY2W",
				"Lan8MuOSKWZmLQQyraaxu",
				"zBgLgjfWMGE_VotNswRkU"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "Muj_YI5yyGkvPeF-MukIs",
					"type": "arrow"
				}
			],
			"updated": 1684536985228,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1294,
			"versionNonce": 483718216,
			"isDeleted": false,
			"id": "2RcSrRGa_zi_Ns3edoqJF",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 902.7069868497798,
			"y": 1371.8559738152455,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.51105029288197,
			"height": 35.539732911894475,
			"seed": 1235612649,
			"groupIds": [
				"6TG8HBEH0QPM1uNml0DPG",
				"Lan8MuOSKWZmLQQyraaxu",
				"zBgLgjfWMGE_VotNswRkU"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985228,
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
			"version": 1294,
			"versionNonce": 2119783480,
			"isDeleted": false,
			"id": "tV-v7ncHODBVNxHe7ZwmR",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 935.0619519312496,
			"y": 1392.8611094846653,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 46.066480238311605,
			"height": 58.1383889698984,
			"seed": 47340327,
			"groupIds": [
				"6TG8HBEH0QPM1uNml0DPG",
				"Lan8MuOSKWZmLQQyraaxu",
				"zBgLgjfWMGE_VotNswRkU"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985228,
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
			"version": 1696,
			"versionNonce": 767503176,
			"isDeleted": false,
			"id": "7iO4Y7VI",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 664.7491044383273,
			"y": 1428.178018828188,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 495.0048828125,
			"height": 31.71184852903549,
			"seed": 242323145,
			"groupIds": [
				"zBgLgjfWMGE_VotNswRkU"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684536985228,
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
			"version": 53,
			"versionNonce": 1905397048,
			"isDeleted": false,
			"id": "Muj_YI5yyGkvPeF-MukIs",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 912.7644709085071,
			"y": 1170.708452564832,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 2.7870799096942847,
			"height": 157.5,
			"seed": 674654792,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": null,
			"updated": 1684536985228,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "09vATIjO",
				"focus": -0.03687976956056531,
				"gap": 12.718812171917307
			},
			"endBinding": {
				"elementId": "EPDetCwII8tQ_4XEr7VbZ",
				"focus": 0.09642550831969661,
				"gap": 8.318585207608407
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
					2.7870799096942847,
					157.5
				]
			]
		},
		{
			"type": "text",
			"version": 212,
			"versionNonce": 1472461624,
			"isDeleted": false,
			"id": "5TKy7Zny",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1892.2515458445773,
			"y": 331.508452564832,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 689.0625,
			"height": 134.4,
			"seed": 71747,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684537237407,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 3,
			"text": "delete from @table  \nwhere CAST([Fecha] AS DATE) \nin (select distinct CAST([Fecha] AS DATE) \nFROM [stating].[VentaEnLinea_temp] )",
			"rawText": "delete from @table  \nwhere CAST([Fecha] AS DATE) \nin (select distinct CAST([Fecha] AS DATE) \nFROM [stating].[VentaEnLinea_temp] )",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "delete from @table  \nwhere CAST([Fecha] AS DATE) \nin (select distinct CAST([Fecha] AS DATE) \nFROM [stating].[VentaEnLinea_temp] )",
			"lineHeight": 1.2,
			"baseline": 127
		},
		{
			"id": "yAEMJgVKTrF5WpnF6FoWq",
			"type": "arrow",
			"x": 1094.7515458445773,
			"y": 550.708452564832,
			"width": 300,
			"height": 227.5,
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
			"seed": 1935248456,
			"version": 95,
			"versionNonce": 1330357816,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1684536985228,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					260,
					25
				],
				[
					300,
					227.5
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "iaRsIub9ipFKj11SMWFDh",
				"focus": 0.143884795456374,
				"gap": 11.71435296737775
			},
			"endBinding": {
				"elementId": "hNCGRFym5fZ586xFix9fz",
				"focus": 0.009410529888726222,
				"gap": 6.1462513870718
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "Lpu7e0U4B65kG_zEZqetU",
			"type": "arrow",
			"x": 687.2515458445773,
			"y": 550.708452564832,
			"width": 340,
			"height": 440,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"seed": 1470881864,
			"version": 100,
			"versionNonce": 1427813704,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1684537008960,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-297.5,
					52.5
				],
				[
					-340,
					440
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "_HfUq2tnCcBTcHQCdl85O",
				"focus": 0.34525796593713026,
				"gap": 3.5885173725987443
			},
			"endBinding": {
				"elementId": "_oK5wAGDh-vsn7X2GniSV",
				"focus": 0.08783966429817475,
				"gap": 2.574822815643415
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "BshKi0GB811_uE14pAJ8D",
			"type": "arrow",
			"x": 684.7515458445773,
			"y": 543.208452564832,
			"width": 162.5,
			"height": 185,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"seed": 954248248,
			"version": 61,
			"versionNonce": 1084000840,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "PoYkZS4O"
				}
			],
			"updated": 1684537042986,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-107.5,
					-35
				],
				[
					-162.5,
					-185
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "_HfUq2tnCcBTcHQCdl85O",
				"focus": -0.34603483149020337,
				"gap": 6.088517372598744
			},
			"endBinding": {
				"elementId": "HnFDMl2w",
				"focus": -0.04498035690489361,
				"gap": 12.053277718667516
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "PoYkZS4O",
			"type": "text",
			"x": 495.2202958445773,
			"y": 496.208452564832,
			"width": 164.0625,
			"height": 24,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 1379108152,
			"version": 17,
			"versionNonce": 389530184,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1684537047396,
			"link": null,
			"locked": false,
			"text": "Consulta fecha",
			"rawText": "Consulta fecha",
			"fontSize": 20,
			"fontFamily": 3,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 19,
			"containerId": "BshKi0GB811_uE14pAJ8D",
			"originalText": "Consulta fecha",
			"lineHeight": 1.2
		},
		{
			"type": "line",
			"version": 475,
			"versionNonce": 1254361416,
			"isDeleted": false,
			"id": "vH1VSG1tRNUwXEO3llJPx",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1707.7060912991228,
			"y": 178.208452564832,
			"strokeColor": "#000000",
			"backgroundColor": "#fa5252",
			"width": 93.409090909091,
			"height": 186.81818181818198,
			"seed": 947402726,
			"groupIds": [
				"4mxNVPSc_jJns9XrQTsTK"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684537235674,
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
					93.409090909091,
					4.263256414560601e-14
				],
				[
					46.70454545454545,
					186.818181818182
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "ellipse",
			"version": 448,
			"versionNonce": 978456376,
			"isDeleted": false,
			"id": "7khnK33SAfbQWyqPht7TP",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1731.058364026395,
			"y": 388.37890711028683,
			"strokeColor": "#000000",
			"backgroundColor": "#fa5252",
			"width": 46.704545454545496,
			"height": 46.704545454545496,
			"seed": 1412702586,
			"groupIds": [
				"4mxNVPSc_jJns9XrQTsTK"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684537235674,
			"link": null,
			"locked": false
		},
		{
			"id": "dW4KIFTt",
			"type": "text",
			"x": 1836.3016251902804,
			"y": 143.208452564832,
			"width": 720.3956298828125,
			"height": 135,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 1996166728,
			"version": 147,
			"versionNonce": 298495304,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1684537262300,
			"link": null,
			"locked": false,
			"text": "Misma lambda\nInvocan a un mismo SP parametrizable\n\"preprocessing.DeleteFromTableWithDate\"",
			"rawText": "Misma lambda\nInvocan a un mismo SP parametrizable\n\"preprocessing.DeleteFromTableWithDate\"",
			"fontSize": 36,
			"fontFamily": 1,
			"textAlign": "center",
			"verticalAlign": "top",
			"baseline": 122,
			"containerId": null,
			"originalText": "Misma lambda\nInvocan a un mismo SP parametrizable\n\"preprocessing.DeleteFromTableWithDate\"",
			"lineHeight": 1.25
		},
		{
			"id": "doMoHWU1NRuQiaiQinhia",
			"type": "arrow",
			"x": 1165.5614904292381,
			"y": 447.8379290237553,
			"width": 496.3473134798553,
			"height": 155.41435791796488,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"seed": 1818354248,
			"version": 127,
			"versionNonce": 913783864,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1684537240795,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					496.3473134798553,
					-155.41435791796488
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "_HfUq2tnCcBTcHQCdl85O",
				"gap": 2.8705235410767274,
				"focus": -0.2139909918338822
			},
			"endBinding": {
				"elementId": "azOAAV0LByfxSAUZ5-y9R",
				"gap": 12.842741935483874,
				"focus": 0.40955081331144616
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "azOAAV0LByfxSAUZ5-y9R",
			"type": "rectangle",
			"x": 1674.7515458445773,
			"y": 63.20845256483199,
			"width": 975,
			"height": 455,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"seed": 389525816,
			"version": 87,
			"versionNonce": 2094252872,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "doMoHWU1NRuQiaiQinhia",
					"type": "arrow"
				}
			],
			"updated": 1684537240795,
			"link": null,
			"locked": false
		},
		{
			"id": "W4rKN0l0oAcNSZNnZgrr8",
			"type": "arrow",
			"x": 1374.7515458445773,
			"y": 593.208452564832,
			"width": 335,
			"height": 22.5,
			"angle": 0,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"seed": 1774372152,
			"version": 73,
			"versionNonce": 1334542392,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1684537172856,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					335,
					-22.5
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": {
				"elementId": "5TKy7Zny",
				"focus": 0.3050118456447813,
				"gap": 7.5
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "Y3sC4D7h",
			"type": "text",
			"x": -720.2484541554227,
			"y": 680.708452564832,
			"width": 855.46875,
			"height": 72,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 1059373880,
			"version": 85,
			"versionNonce": 1681640248,
			"isDeleted": true,
			"boundElements": [],
			"updated": 1684537183152,
			"link": null,
			"locked": false,
			"text": "delete from [stating].[VentaEnLinea]   \nwhere [Fecha] in (select distinct CAST(replace([Fecha],'T',' ') AS DATE) \nFROM [stating].[VentaEnLinea_temp] ) ",
			"rawText": "delete from [stating].[VentaEnLinea]   \nwhere [Fecha] in (select distinct CAST(replace([Fecha],'T',' ') AS DATE) \nFROM [stating].[VentaEnLinea_temp] ) ",
			"fontSize": 20,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 67,
			"containerId": null,
			"originalText": "delete from [stating].[VentaEnLinea]   \nwhere [Fecha] in (select distinct CAST(replace([Fecha],'T',' ') AS DATE) \nFROM [stating].[VentaEnLinea_temp] ) ",
			"lineHeight": 1.2
		},
		{
			"id": "q_WxbkU5MLKpftAuA0pr4",
			"type": "arrow",
			"x": 362.2515458445773,
			"y": 670.708452564832,
			"width": 317.5,
			"height": 7.5,
			"angle": 0,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"seed": 967101512,
			"version": 93,
			"versionNonce": 1705940552,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1684537174416,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-317.5,
					7.5
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": {
				"elementId": "Y3sC4D7h",
				"focus": -0.6622662002012099,
				"gap": 2.5
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "i8sOnY04",
			"type": "text",
			"x": 2322.7515458445773,
			"y": 233.208452564832,
			"width": 14,
			"height": 35,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [],
			"roundness": null,
			"seed": 773951816,
			"version": 2,
			"versionNonce": 1802569528,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1684537254779,
			"link": null,
			"locked": false,
			"text": "",
			"rawText": "",
			"fontSize": 28,
			"fontFamily": 1,
			"textAlign": "center",
			"verticalAlign": "top",
			"baseline": 25,
			"containerId": null,
			"originalText": "",
			"lineHeight": 1.25
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#000000",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "hachure",
		"currentItemStrokeWidth": 1,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 0,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 28,
		"currentItemTextAlign": "center",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 1176.4984541554227,
		"scrollY": 658.080609935168,
		"zoom": {
			"value": 0.4
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