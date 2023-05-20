---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
brightcell-nonprod-vmi-telcel
 ^4PljDSvt

preprocessing.dailyInventory ^hKori0fi

Brightcell-VMI-load-inventory-files ^pOtoZu0G

Brightcell-VMI-FactInventory ^mRshoyeX

dw.dimMaterial ^c7ih8hKG

dw.dimStore ^NQLFfa34

Consulta información de: ^F3xsQS71

Carga información en: ^JdxFb2Km

Se carga archivo .txt en
directorio 02_Inventario/unprocessed ^Hm82BKT4

dw.factInventory ^UO6Kxrjf

Limpiar tabla ^AAH374TF

Verificar archivos ^VzTre5sz

Notificación de proceso
fallido ^x8TGHSiC

Evento ^5TYddIld

AWS Step Functions: Inventario ^YDNkIOX2

El archivo es correcto? ^0dZA6q3V

Flujo principal ^xxa9yaOB

No ^aZWmVcIT

Si ^SZosf4q1

El proceso limpia
la tabla en caso
de que se tenga
que reprocesar ^v3O3ve8g

Consultar fecha ^baEV8zYt

Keys ^V7BfNFI4

DELETE 
FROM dw.FactInventory
WHERE date IN
(
        SELECT MAX(CAST(Fecha AS DATE)) FROM stating.DailyInventory
)  ^6Q7Qq6t2

Llama a un SP: DeleteFactInventory ^XTUZCDYK

Mover archivos a directorio processed ^y6MjXAug

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
			"version": 1500,
			"versionNonce": 252210232,
			"isDeleted": false,
			"id": "laxh7uGSv06vb_kQpr05b",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1262.502937304876,
			"y": -913.0589964177847,
			"strokeColor": "#000000",
			"backgroundColor": "#40c05788",
			"width": 77.00500621045215,
			"height": 77.00500621045215,
			"seed": 754733865,
			"groupIds": [
				"-cQLPCzFSMvM7TLvWg04c",
				"HrMXy-671yU1wzqpfrfjg",
				"i6Y9UnhUVKiIwh_wxY-gs",
				"nf_iPZ4pn7rw5fNyiA-oW"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "o-nLp3HiCIxcFVnyVCYBh",
					"type": "arrow"
				},
				{
					"id": "gIiuQF2JT4V4GceRBAg5V",
					"type": "arrow"
				},
				{
					"id": "g1EatTZ5K-Pth2tr9fFs_",
					"type": "arrow"
				}
			],
			"updated": 1684508324130,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1274,
			"versionNonce": 355308360,
			"isDeleted": false,
			"id": "zsJH1hB1-vquXo0KURWTf",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1246.3959236223168,
			"y": -899.9641779698716,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 46.27059743037148,
			"height": 12.724351334011057,
			"seed": 1845792743,
			"groupIds": [
				"i6Y9UnhUVKiIwh_wxY-gs",
				"nf_iPZ4pn7rw5fNyiA-oW"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"id": "gIiuQF2JT4V4GceRBAg5V",
					"type": "arrow"
				}
			],
			"updated": 1684508324131,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1891,
			"versionNonce": 1285432632,
			"isDeleted": false,
			"id": "eECPsU8e4WahDvwjgw_2M",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1245.9724294663315,
			"y": -893.008652177518,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 45.312356259233844,
			"height": 47.90461342961858,
			"seed": 1312425481,
			"groupIds": [
				"i6Y9UnhUVKiIwh_wxY-gs",
				"nf_iPZ4pn7rw5fNyiA-oW"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324131,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1283,
			"versionNonce": 1873537608,
			"isDeleted": false,
			"id": "7JgficXNUEXqFGlbVs8kX",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1226.129475425068,
			"y": -880.8658494718388,
			"strokeColor": "#000000",
			"backgroundColor": "#000",
			"width": 5.558985761351276,
			"height": 5.558985761351276,
			"seed": 1322777351,
			"groupIds": [
				"i6Y9UnhUVKiIwh_wxY-gs",
				"nf_iPZ4pn7rw5fNyiA-oW"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324131,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1969,
			"versionNonce": 555007544,
			"isDeleted": false,
			"id": "h0P_p140E4d069er49GRX",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1223.1831154771608,
			"y": -877.8214336370573,
			"strokeColor": "#000000",
			"backgroundColor": "#000",
			"width": 27.506237081118297,
			"height": 13.643881491353264,
			"seed": 654204137,
			"groupIds": [
				"i6Y9UnhUVKiIwh_wxY-gs",
				"nf_iPZ4pn7rw5fNyiA-oW"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324131,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1786,
			"versionNonce": 910647624,
			"isDeleted": false,
			"id": "4PljDSvt",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1355.2103035844157,
			"y": -815.861117384166,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 262.41973876953125,
			"height": 48,
			"seed": 340853287,
			"groupIds": [
				"nf_iPZ4pn7rw5fNyiA-oW"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "b3fYGBXunSACHv_1-lmi-",
					"type": "arrow"
				}
			],
			"updated": 1684508324131,
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
			"version": 2576,
			"versionNonce": 1028667192,
			"isDeleted": false,
			"id": "hKori0fi",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 317.8208283541669,
			"y": -623.4254600338286,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 265.93975830078125,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"YM0tshGOK7sjPU6q6Yogz"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "OPvVe6-LfhbieNY0XD2wp",
					"type": "arrow"
				},
				{
					"id": "0f3zZlOzJFkxpOLEWqKk0",
					"type": "arrow"
				},
				{
					"id": "fVg0mPlzz4axLOQnyaLXo",
					"type": "arrow"
				}
			],
			"updated": 1684508324131,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "preprocessing.dailyInventory",
			"rawText": "preprocessing.dailyInventory",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "preprocessing.dailyInventory",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 3710,
			"versionNonce": 677115976,
			"isDeleted": false,
			"id": "kfg9uospInV9fs_CgBtTq",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 406.5902521716887,
			"y": -692.8925975947558,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"9w11IxQM6Ao2xAa8HfKD4",
				"P4FnsdZ-Gdx90_P5MVP7k",
				"DJR4aQs900E9YBLEdpauS",
				"AnKFP42cu3TQUGWyfuuVU",
				"YM0tshGOK7sjPU6q6Yogz"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "OPvVe6-LfhbieNY0XD2wp",
					"type": "arrow"
				},
				{
					"id": "0f3zZlOzJFkxpOLEWqKk0",
					"type": "arrow"
				}
			],
			"updated": 1684508324131,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2148,
			"versionNonce": 364154936,
			"isDeleted": false,
			"id": "K02AbQFIrJ3dW2lca1YAr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 427.63092427473816,
			"y": -669.6083093723463,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"1G9IyQkOG5JUT9JSoP7kx",
				"QDSOCKUpF3FHRdFd0M_kU",
				"AnKFP42cu3TQUGWyfuuVU",
				"YM0tshGOK7sjPU6q6Yogz"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324131,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2290,
			"versionNonce": 969256776,
			"isDeleted": false,
			"id": "h7-zJiX7Gj-RfQsQlM-4o",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 428.61622327888995,
			"y": -665.4236649162466,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"1G9IyQkOG5JUT9JSoP7kx",
				"QDSOCKUpF3FHRdFd0M_kU",
				"AnKFP42cu3TQUGWyfuuVU",
				"YM0tshGOK7sjPU6q6Yogz"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324131,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 2996,
			"versionNonce": 1915078968,
			"isDeleted": false,
			"id": "1M4mQIezNKxU5G8ZJmgHr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 459.2733379209146,
			"y": -675.7364926056097,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"SY8y6YImasKIJ1vtm3mZi",
				"QDSOCKUpF3FHRdFd0M_kU",
				"AnKFP42cu3TQUGWyfuuVU",
				"YM0tshGOK7sjPU6q6Yogz"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324131,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3087,
			"versionNonce": 48268872,
			"isDeleted": false,
			"id": "dlr8v7IpHwRFLd4uXYYKX",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 424.95362450728703,
			"y": -677.2307574227528,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"Pe185J_9wzUdNhBwzdmP9",
				"QDSOCKUpF3FHRdFd0M_kU",
				"AnKFP42cu3TQUGWyfuuVU",
				"YM0tshGOK7sjPU6q6Yogz"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324131,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3197,
			"versionNonce": 2114445880,
			"isDeleted": false,
			"id": "GvYX3B2cNnZIfB7e6W7kB",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 444.2840575697908,
			"y": -682.1049381295305,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"Pe185J_9wzUdNhBwzdmP9",
				"QDSOCKUpF3FHRdFd0M_kU",
				"AnKFP42cu3TQUGWyfuuVU",
				"YM0tshGOK7sjPU6q6Yogz"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324131,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3110,
			"versionNonce": 814251336,
			"isDeleted": false,
			"id": "w3qb39jMvS45LRbAa_ht2",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 425.24951015210354,
			"y": -681.8787481921576,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"Pe185J_9wzUdNhBwzdmP9",
				"QDSOCKUpF3FHRdFd0M_kU",
				"AnKFP42cu3TQUGWyfuuVU",
				"YM0tshGOK7sjPU6q6Yogz"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324131,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3305,
			"versionNonce": 1480514360,
			"isDeleted": false,
			"id": "NmMcSdLKrF13edC0nA8vW",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 443.32269606508703,
			"y": -638.3618104271508,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"QDSOCKUpF3FHRdFd0M_kU",
				"AnKFP42cu3TQUGWyfuuVU",
				"YM0tshGOK7sjPU6q6Yogz"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324131,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3263,
			"versionNonce": 1947833416,
			"isDeleted": false,
			"id": "wQ_MIO8FvDhWPHBMMlDUn",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 424.2881486474,
			"y": -638.1356204897778,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"QDSOCKUpF3FHRdFd0M_kU",
				"AnKFP42cu3TQUGWyfuuVU",
				"YM0tshGOK7sjPU6q6Yogz"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324131,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 2221,
			"versionNonce": 590263352,
			"isDeleted": false,
			"id": "pOtoZu0G",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -116.88636363636334,
			"y": -608.0822117931294,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 326.69970703125,
			"height": 24,
			"seed": 1245685479,
			"groupIds": [
				"2tPTw0Tc2NF91gM9FjTYl"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "Nqc-k-SzgtdiW1AV4FuKZ",
					"type": "arrow"
				}
			],
			"updated": 1684508324131,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Brightcell-VMI-load-inventory-files",
			"rawText": "Brightcell-VMI-load-inventory-files",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Brightcell-VMI-load-inventory-files",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4205,
			"versionNonce": 1936706376,
			"isDeleted": false,
			"id": "YVXumhUA9dF82s72x-A2n",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -10.757886409635205,
			"y": -730.3112541159613,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 107.76604983800789,
			"height": 107.66285368525563,
			"seed": 941612809,
			"groupIds": [
				"oTxCUB15NRMVfYfqTNka9",
				"MjL9V2bU3ULQom6f2bfp6",
				"8s0vEfj1RHMJmsJJ0Xtqv",
				"Y0K9hNNRkgInZXwPUokqI",
				"2tPTw0Tc2NF91gM9FjTYl"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "OPvVe6-LfhbieNY0XD2wp",
					"type": "arrow"
				},
				{
					"id": "c_BC4Cv4wDibovIg6hTvH",
					"type": "arrow"
				},
				{
					"id": "b3fYGBXunSACHv_1-lmi-",
					"type": "arrow"
				}
			],
			"updated": 1684508324131,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2064,
			"versionNonce": 347827512,
			"isDeleted": false,
			"id": "9CPy4DqmS3A_9wM5ktwJb",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 47.920898408414075,
			"y": -660.612586938399,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 17.21171637693966,
			"height": 30.981089478491384,
			"seed": 1100493319,
			"groupIds": [
				"ZDRwU8-vxrtyjSUl8pTKf",
				"Y0K9hNNRkgInZXwPUokqI",
				"2tPTw0Tc2NF91gM9FjTYl"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324131,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 2144,
			"versionNonce": 954671688,
			"isDeleted": false,
			"id": "FE1v35hSHMFl5gizfLuP7",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 38.841718019576604,
			"y": -660.612586938399,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 17.21171637693966,
			"height": 30.981089478491384,
			"seed": 1757484521,
			"groupIds": [
				"ZDRwU8-vxrtyjSUl8pTKf",
				"Y0K9hNNRkgInZXwPUokqI",
				"2tPTw0Tc2NF91gM9FjTYl"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324131,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1944,
			"versionNonce": 105449016,
			"isDeleted": false,
			"id": "vK2AsZayXLzCsGEE4RyKC",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 39.31504021994391,
			"y": -660.1822940289829,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 7.745272369622733,
			"height": 0,
			"seed": 1341282599,
			"groupIds": [
				"ZDRwU8-vxrtyjSUl8pTKf",
				"Y0K9hNNRkgInZXwPUokqI",
				"2tPTw0Tc2NF91gM9FjTYl"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324132,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 2058,
			"versionNonce": 593205576,
			"isDeleted": false,
			"id": "m83jMgOz_OSEEIdGZ11FM",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 22.963909661851176,
			"y": -692.144451340959,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 42.168705123502164,
			"height": 7.314979460199344,
			"seed": 567832777,
			"groupIds": [
				"ZDRwU8-vxrtyjSUl8pTKf",
				"Y0K9hNNRkgInZXwPUokqI",
				"2tPTw0Tc2NF91gM9FjTYl"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324132,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1948,
			"versionNonce": 79396664,
			"isDeleted": false,
			"id": "og0ZHaK4YTm_N80zWBiT5",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 22.017265261120087,
			"y": -692.4542622357352,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 16.35113055809267,
			"height": 2.581757456540929,
			"seed": 1522179143,
			"groupIds": [
				"ZDRwU8-vxrtyjSUl8pTKf",
				"Y0K9hNNRkgInZXwPUokqI",
				"2tPTw0Tc2NF91gM9FjTYl"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324132,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1902,
			"versionNonce": 1445539912,
			"isDeleted": false,
			"id": "GRWnkZg0UzgySBmIP4Ugo",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 43.660998605122586,
			"y": -713.0652925971312,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 956395433,
			"groupIds": [
				"ZDRwU8-vxrtyjSUl8pTKf",
				"Y0K9hNNRkgInZXwPUokqI",
				"2tPTw0Tc2NF91gM9FjTYl"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324132,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1902,
			"versionNonce": 1618401336,
			"isDeleted": false,
			"id": "cQTPRnD0WkY8clp1eQaw4",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 32.043090050688875,
			"y": -704.545492990546,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 1707965287,
			"groupIds": [
				"ZDRwU8-vxrtyjSUl8pTKf",
				"Y0K9hNNRkgInZXwPUokqI",
				"2tPTw0Tc2NF91gM9FjTYl"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324132,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1903,
			"versionNonce": 690743112,
			"isDeleted": false,
			"id": "d2LJJVcUF4YKht2VWOglX",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 45.812463152237854,
			"y": -699.7692416959422,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 1147638409,
			"groupIds": [
				"ZDRwU8-vxrtyjSUl8pTKf",
				"Y0K9hNNRkgInZXwPUokqI",
				"2tPTw0Tc2NF91gM9FjTYl"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324132,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1400,
			"versionNonce": 1029640504,
			"isDeleted": false,
			"id": "Q5bRngWV62TfKeMG4Cyt6",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 45.6516306315267,
			"y": -656.275159521028,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 18.44546425611026,
			"height": 14.81684833687558,
			"seed": 1165457031,
			"groupIds": [
				"Y0K9hNNRkgInZXwPUokqI",
				"2tPTw0Tc2NF91gM9FjTYl"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324132,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1695,
			"versionNonce": 415219272,
			"isDeleted": false,
			"id": "OPvVe6-LfhbieNY0XD2wp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 111.52277200245913,
			"y": -674.0757071550163,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 288.3117692414972,
			"height": 0.8192192618206491,
			"seed": 46375535,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324132,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "YVXumhUA9dF82s72x-A2n",
				"focus": 0.048109612346724014,
				"gap": 14.514608574086438
			},
			"endBinding": {
				"elementId": "kfg9uospInV9fs_CgBtTq",
				"focus": 0.4432407831404789,
				"gap": 6.755710927732366
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
					288.3117692414972,
					-0.8192192618206491
				]
			]
		},
		{
			"type": "text",
			"version": 2396,
			"versionNonce": 1807541560,
			"isDeleted": false,
			"id": "mRshoyeX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -84.85009331830338,
			"y": -75.00536461262072,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 280.71978759765625,
			"height": 24,
			"seed": 1245685479,
			"groupIds": [
				"8rxMVPBnu1JrQemTtWSpC"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "7A5vC-mmjri9DHhOsS7xe",
					"type": "arrow"
				}
			],
			"updated": 1684508340472,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Brightcell-VMI-FactInventory",
			"rawText": "Brightcell-VMI-FactInventory",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Brightcell-VMI-FactInventory",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 4359,
			"versionNonce": 901821768,
			"isDeleted": false,
			"id": "BWPU9Xn2_S8v5EGjTZzUc",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -3.456749043767104,
			"y": -194.48605882965353,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 107.76604983800789,
			"height": 107.66285368525563,
			"seed": 941612809,
			"groupIds": [
				"ipuTHxqDtVZIJXBf91Zo4",
				"w7qUzrYwJPEPRlfD2dem8",
				"TYgN6nIc4-pkixiK7fM20",
				"D2RDSeZICb_wylnSjP2C3",
				"8rxMVPBnu1JrQemTtWSpC"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "Gs9ePMR2DXE_XZYsRQm_p",
					"type": "arrow"
				},
				{
					"id": "89bltkxTvvlBoT147gqN9",
					"type": "arrow"
				},
				{
					"id": "0f3zZlOzJFkxpOLEWqKk0",
					"type": "arrow"
				},
				{
					"id": "nrleZpkNNrOn80ZC-ftlO",
					"type": "arrow"
				},
				{
					"id": "0juGu8sAojCiaFM-TaKd9",
					"type": "arrow"
				}
			],
			"updated": 1684508324132,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2214,
			"versionNonce": 197534520,
			"isDeleted": false,
			"id": "5F14LnivW6zyap8sZxwni",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 55.222035774282176,
			"y": -124.78739165209117,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 17.21171637693966,
			"height": 30.981089478491384,
			"seed": 1100493319,
			"groupIds": [
				"YaIKku9ARCt6vjDaSFPAN",
				"D2RDSeZICb_wylnSjP2C3",
				"8rxMVPBnu1JrQemTtWSpC"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324132,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 2294,
			"versionNonce": 361417800,
			"isDeleted": false,
			"id": "uopZ1nOVkz2doMT4o9dkx",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 46.142855385444705,
			"y": -124.78739165209117,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 17.21171637693966,
			"height": 30.981089478491384,
			"seed": 1757484521,
			"groupIds": [
				"YaIKku9ARCt6vjDaSFPAN",
				"D2RDSeZICb_wylnSjP2C3",
				"8rxMVPBnu1JrQemTtWSpC"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324132,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 2094,
			"versionNonce": 1988951096,
			"isDeleted": false,
			"id": "BfU2x4TllKerWMvXy0Q5L",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 46.61617758581201,
			"y": -124.35709874267513,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 7.745272369622733,
			"height": 0,
			"seed": 1341282599,
			"groupIds": [
				"YaIKku9ARCt6vjDaSFPAN",
				"D2RDSeZICb_wylnSjP2C3",
				"8rxMVPBnu1JrQemTtWSpC"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324132,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 2208,
			"versionNonce": 1106903880,
			"isDeleted": false,
			"id": "O-tU06kpxe7d7fDzQeBz7",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 30.265047027719277,
			"y": -156.3192560546513,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 42.168705123502164,
			"height": 7.314979460199344,
			"seed": 567832777,
			"groupIds": [
				"YaIKku9ARCt6vjDaSFPAN",
				"D2RDSeZICb_wylnSjP2C3",
				"8rxMVPBnu1JrQemTtWSpC"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324132,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 2098,
			"versionNonce": 1964029240,
			"isDeleted": false,
			"id": "YRNBWqxBNAD1HsY3GGqzs",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 29.31840262698819,
			"y": -156.6290669494274,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 16.35113055809267,
			"height": 2.581757456540929,
			"seed": 1522179143,
			"groupIds": [
				"YaIKku9ARCt6vjDaSFPAN",
				"D2RDSeZICb_wylnSjP2C3",
				"8rxMVPBnu1JrQemTtWSpC"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324132,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 2052,
			"versionNonce": 694835784,
			"isDeleted": false,
			"id": "xDn_RQlgVe7ypcsZgqHsz",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 50.96213597099069,
			"y": -177.24009731082333,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 956395433,
			"groupIds": [
				"YaIKku9ARCt6vjDaSFPAN",
				"D2RDSeZICb_wylnSjP2C3",
				"8rxMVPBnu1JrQemTtWSpC"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324132,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 2052,
			"versionNonce": 1018515000,
			"isDeleted": false,
			"id": "XjaXXpBB47fcyoEmhvlOL",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 39.344227416556976,
			"y": -168.7202977042382,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 1707965287,
			"groupIds": [
				"YaIKku9ARCt6vjDaSFPAN",
				"D2RDSeZICb_wylnSjP2C3",
				"8rxMVPBnu1JrQemTtWSpC"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324132,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 2053,
			"versionNonce": 246927688,
			"isDeleted": false,
			"id": "xSNAr4mQGvicxV896VxeI",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 53.113600518105955,
			"y": -163.94404640963444,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 6.024100731928854,
			"height": 6.024100731928854,
			"seed": 1147638409,
			"groupIds": [
				"YaIKku9ARCt6vjDaSFPAN",
				"D2RDSeZICb_wylnSjP2C3",
				"8rxMVPBnu1JrQemTtWSpC"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324132,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1522,
			"versionNonce": 912181048,
			"isDeleted": false,
			"id": "YmFUqIV3TBa7JVmWEhHX3",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 52.9527679973948,
			"y": -120.44996423472003,
			"strokeColor": "#000000",
			"backgroundColor": "#ffffff",
			"width": 18.44546425611026,
			"height": 14.81684833687558,
			"seed": 1165457031,
			"groupIds": [
				"D2RDSeZICb_wylnSjP2C3",
				"8rxMVPBnu1JrQemTtWSpC"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324132,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 2640,
			"versionNonce": 2034133064,
			"isDeleted": false,
			"id": "c7ih8hKG",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 348.43461227417333,
			"y": -255.1520703893264,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 195.91590881347656,
			"height": 33.6,
			"seed": 1885428937,
			"groupIds": [
				"XrQvEXSwgnyNcineR4ApF"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324132,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "dw.dimMaterial",
			"rawText": "dw.dimMaterial",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dw.dimMaterial",
			"lineHeight": 1.2,
			"baseline": 24
		},
		{
			"type": "rectangle",
			"version": 3773,
			"versionNonce": 242294840,
			"isDeleted": false,
			"id": "MGjWzcJEFP0VzeDTIsK4n",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 411.8113297183395,
			"y": -319.8192079502538,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"okF6RtgJnwx58FS6W1lBg",
				"T5JwaQPLNdM81nooylgNh",
				"eS-Y1mRAEnjZF4dPkbJo-",
				"kyRLPzWpEk-fMrz19tB1f",
				"XrQvEXSwgnyNcineR4ApF"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "Gs9ePMR2DXE_XZYsRQm_p",
					"type": "arrow"
				}
			],
			"updated": 1684508324132,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2209,
			"versionNonce": 618274632,
			"isDeleted": false,
			"id": "tZXOvNWjn9DYryh_EOJAt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 432.85200182138897,
			"y": -296.53491972784434,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"Q4aeVf_ZowVygIbikPXFT",
				"O8kApOLJmY80u08HRwoek",
				"kyRLPzWpEk-fMrz19tB1f",
				"XrQvEXSwgnyNcineR4ApF"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324132,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2351,
			"versionNonce": 1154505016,
			"isDeleted": false,
			"id": "w1-SpcoThuPWtDahq_ffj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 433.83730082554075,
			"y": -292.35027527174464,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"Q4aeVf_ZowVygIbikPXFT",
				"O8kApOLJmY80u08HRwoek",
				"kyRLPzWpEk-fMrz19tB1f",
				"XrQvEXSwgnyNcineR4ApF"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324133,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3057,
			"versionNonce": 1910961736,
			"isDeleted": false,
			"id": "W736SICjUBX90x2YrfJJv",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 464.49441546756543,
			"y": -302.6631029611077,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"UpjVyU577UOh4dEeNzbd8",
				"O8kApOLJmY80u08HRwoek",
				"kyRLPzWpEk-fMrz19tB1f",
				"XrQvEXSwgnyNcineR4ApF"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324133,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3148,
			"versionNonce": 1021342264,
			"isDeleted": false,
			"id": "2W-n-Bk7FQxqnMULtdw5o",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 430.17470205393784,
			"y": -304.1573677782509,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"-4AGuHopVqpL1Nmu75fok",
				"O8kApOLJmY80u08HRwoek",
				"kyRLPzWpEk-fMrz19tB1f",
				"XrQvEXSwgnyNcineR4ApF"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324133,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3258,
			"versionNonce": 1430318408,
			"isDeleted": false,
			"id": "t_sechxAaGu2WX-Gp9XIG",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 449.5051351164416,
			"y": -309.03154848502857,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"-4AGuHopVqpL1Nmu75fok",
				"O8kApOLJmY80u08HRwoek",
				"kyRLPzWpEk-fMrz19tB1f",
				"XrQvEXSwgnyNcineR4ApF"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324133,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3171,
			"versionNonce": 1300589368,
			"isDeleted": false,
			"id": "7t9mJ8L6ndG2tWZnhW8Th",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 430.47058769875434,
			"y": -308.8053585476556,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"-4AGuHopVqpL1Nmu75fok",
				"O8kApOLJmY80u08HRwoek",
				"kyRLPzWpEk-fMrz19tB1f",
				"XrQvEXSwgnyNcineR4ApF"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324133,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3366,
			"versionNonce": 1212417096,
			"isDeleted": false,
			"id": "NMf3AtxmAneAyLKJ7mntT",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 448.54377361173783,
			"y": -265.2884207826488,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"O8kApOLJmY80u08HRwoek",
				"kyRLPzWpEk-fMrz19tB1f",
				"XrQvEXSwgnyNcineR4ApF"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324133,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3324,
			"versionNonce": 1361265720,
			"isDeleted": false,
			"id": "8XHW4_JfMJ1LTZQULMG06",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 429.5092261940508,
			"y": -265.06223084527585,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"O8kApOLJmY80u08HRwoek",
				"kyRLPzWpEk-fMrz19tB1f",
				"XrQvEXSwgnyNcineR4ApF"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324133,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 2650,
			"versionNonce": 952908616,
			"isDeleted": false,
			"id": "NQLFfa34",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 373.28299645980167,
			"y": -65.01417211701649,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 156.15591430664062,
			"height": 33.6,
			"seed": 1885428937,
			"groupIds": [
				"d5vwe1vETu43YqwQEzGMq"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324133,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "dw.dimStore",
			"rawText": "dw.dimStore",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dw.dimStore",
			"lineHeight": 1.2,
			"baseline": 24
		},
		{
			"type": "rectangle",
			"version": 3787,
			"versionNonce": 899546424,
			"isDeleted": false,
			"id": "PSw_nqXpYanp_kcg-GGUP",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 418.1538907034494,
			"y": -129.6813096779439,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"FuVgYQNFQyq4MA6M1TsQ9",
				"YmxY_olCeDJrbCgC4S8zz",
				"YPpjV09Sgavg_-ZS3RSDl",
				"QgKw4kPs23Vcz73M4p8E3",
				"d5vwe1vETu43YqwQEzGMq"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "89bltkxTvvlBoT147gqN9",
					"type": "arrow"
				}
			],
			"updated": 1684508324133,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2223,
			"versionNonce": 2033553992,
			"isDeleted": false,
			"id": "1BP5wO6SHgCELLEkBXukb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 439.1945628064989,
			"y": -106.3970214555344,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"Op3Ji0IgG_VuzBWovPUOc",
				"JnKFEyaV5MulKUZK4Ytzw",
				"QgKw4kPs23Vcz73M4p8E3",
				"d5vwe1vETu43YqwQEzGMq"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324133,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2365,
			"versionNonce": 207197752,
			"isDeleted": false,
			"id": "odXyPEDkMu7-kjkDsZ7V5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 440.17986181065066,
			"y": -102.2123769994347,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"Op3Ji0IgG_VuzBWovPUOc",
				"JnKFEyaV5MulKUZK4Ytzw",
				"QgKw4kPs23Vcz73M4p8E3",
				"d5vwe1vETu43YqwQEzGMq"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324133,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3071,
			"versionNonce": 811338056,
			"isDeleted": false,
			"id": "JzKcc4cbGCIImeJw14qy2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 470.83697645267534,
			"y": -112.52520468879777,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"8y6b_LSVrvp0894UQBozA",
				"JnKFEyaV5MulKUZK4Ytzw",
				"QgKw4kPs23Vcz73M4p8E3",
				"d5vwe1vETu43YqwQEzGMq"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324133,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3162,
			"versionNonce": 440012600,
			"isDeleted": false,
			"id": "vyJNS82UWfywJtyBYL6EH",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 436.51726303904775,
			"y": -114.01946950594095,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"l_jFvFW2oi7OyrurepB8t",
				"JnKFEyaV5MulKUZK4Ytzw",
				"QgKw4kPs23Vcz73M4p8E3",
				"d5vwe1vETu43YqwQEzGMq"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324133,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3272,
			"versionNonce": 1234935880,
			"isDeleted": false,
			"id": "AI-Vyltruc3sQgbmjH0P8",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 455.8476961015515,
			"y": -118.89365021271863,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"l_jFvFW2oi7OyrurepB8t",
				"JnKFEyaV5MulKUZK4Ytzw",
				"QgKw4kPs23Vcz73M4p8E3",
				"d5vwe1vETu43YqwQEzGMq"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324133,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3185,
			"versionNonce": 1738762296,
			"isDeleted": false,
			"id": "0N-pabxflAt8vyx95d-34",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 436.81314868386426,
			"y": -118.66746027534566,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"l_jFvFW2oi7OyrurepB8t",
				"JnKFEyaV5MulKUZK4Ytzw",
				"QgKw4kPs23Vcz73M4p8E3",
				"d5vwe1vETu43YqwQEzGMq"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324133,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3380,
			"versionNonce": 1691375432,
			"isDeleted": false,
			"id": "WMS2IDOOJT21qYQXrGnXF",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 454.88633459684775,
			"y": -75.15052251033887,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"JnKFEyaV5MulKUZK4Ytzw",
				"QgKw4kPs23Vcz73M4p8E3",
				"d5vwe1vETu43YqwQEzGMq"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324133,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3338,
			"versionNonce": 1350148408,
			"isDeleted": false,
			"id": "3wbuAeEor1VMKOBl-sKv8",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 435.85178717916074,
			"y": -74.92433257296591,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"JnKFEyaV5MulKUZK4Ytzw",
				"QgKw4kPs23Vcz73M4p8E3",
				"d5vwe1vETu43YqwQEzGMq"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324133,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 431,
			"versionNonce": 1180053064,
			"isDeleted": false,
			"id": "595OqfDh8YrZxDPVtnlCv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 80,
			"angle": 0,
			"x": -1539.1443326913304,
			"y": -107.53012659820592,
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
			"updated": 1684508324133,
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
			"version": 454,
			"versionNonce": 337689144,
			"isDeleted": false,
			"id": "F3xsQS71",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 80,
			"angle": 0,
			"x": -1124.0100717758764,
			"y": -208.8629136007173,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 341.9183349609375,
			"height": 36.14748415627665,
			"seed": 1664452687,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324133,
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
			"version": 504,
			"versionNonce": 1191781704,
			"isDeleted": false,
			"id": "JdxFb2Km",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 80,
			"angle": 0,
			"x": -1096.8813868538593,
			"y": -133.5515382451687,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 299.5941467285156,
			"height": 36.14748415627665,
			"seed": 1664452687,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324134,
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
			"type": "text",
			"version": 527,
			"versionNonce": 1702671160,
			"isDeleted": false,
			"id": "Hm82BKT4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1777.476148017258,
			"y": -915.9689345981838,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 371.23968505859375,
			"height": 50,
			"seed": 376765871,
			"groupIds": [],
			"roundness": null,
			"boundElements": [
				{
					"id": "o-nLp3HiCIxcFVnyVCYBh",
					"type": "arrow"
				}
			],
			"updated": 1684508324134,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Se carga archivo .txt en\ndirectorio 02_Inventario/unprocessed",
			"rawText": "Se carga archivo .txt en\ndirectorio 02_Inventario/unprocessed",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Se carga archivo .txt en\ndirectorio 02_Inventario/unprocessed",
			"lineHeight": 1.25,
			"baseline": 43
		},
		{
			"type": "arrow",
			"version": 789,
			"versionNonce": 1145388104,
			"isDeleted": false,
			"id": "Gs9ePMR2DXE_XZYsRQm_p",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 80,
			"angle": 0,
			"x": 400.08524190403483,
			"y": -297.747372406092,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 282.00819168673354,
			"height": 154.42122064878885,
			"seed": 1061913313,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324134,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "MGjWzcJEFP0VzeDTIsK4n",
				"focus": 0.6860303025288188,
				"gap": 11.726087814304663
			},
			"endBinding": {
				"elementId": "BWPU9Xn2_S8v5EGjTZzUc",
				"focus": 0.4124540686951108,
				"gap": 13.767749423060508
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
					-282.00819168673354,
					154.42122064878885
				]
			]
		},
		{
			"type": "arrow",
			"version": 691,
			"versionNonce": 2062650424,
			"isDeleted": false,
			"id": "89bltkxTvvlBoT147gqN9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 80,
			"angle": 0,
			"x": 415.0536288362452,
			"y": -105.89777762455296,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 298.0053497917232,
			"height": 3.839987146107376,
			"seed": 422660719,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324134,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "PSw_nqXpYanp_kcg-GGUP",
				"focus": 0.27200472268685133,
				"gap": 3.1002618672042104
			},
			"endBinding": {
				"elementId": "BWPU9Xn2_S8v5EGjTZzUc",
				"focus": 0.7236088030211772,
				"gap": 12.738978250281235
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
					-298.0053497917232,
					3.839987146107376
				]
			]
		},
		{
			"type": "arrow",
			"version": 777,
			"versionNonce": 266761032,
			"isDeleted": false,
			"id": "0f3zZlOzJFkxpOLEWqKk0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 80,
			"angle": 0,
			"x": 449.95817318118065,
			"y": -597.0490507881592,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 337.10406166137045,
			"height": 423.759533401645,
			"seed": 886914735,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324134,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "hKori0fi",
				"focus": -0.09300722174734627,
				"gap": 4.776409245669242
			},
			"endBinding": {
				"elementId": "BWPU9Xn2_S8v5EGjTZzUc",
				"focus": 0.37708512172049746,
				"gap": 8.54481072556942
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
					-337.10406166137045,
					423.759533401645
				]
			]
		},
		{
			"type": "text",
			"version": 2745,
			"versionNonce": 509822264,
			"isDeleted": false,
			"id": "UO6Kxrjf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -421.875138750391,
			"y": -373.57370620008,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 164.7798614501953,
			"height": 24,
			"seed": 1885428937,
			"groupIds": [
				"e3Htb9Df7LKN87gz0IV70"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "0juGu8sAojCiaFM-TaKd9",
					"type": "arrow"
				}
			],
			"updated": 1684508324134,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "dw.factInventory",
			"rawText": "dw.factInventory",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "dw.factInventory",
			"lineHeight": 1.2,
			"baseline": 17
		},
		{
			"type": "rectangle",
			"version": 3826,
			"versionNonce": 1615383112,
			"isDeleted": false,
			"id": "BshMmtQGaKqnIPZVY7Opm",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -369.9439228291667,
			"y": -451.28588807840447,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f288",
			"width": 64.46115236495699,
			"height": 64.39942473426015,
			"seed": 1183215687,
			"groupIds": [
				"dYZXxp9qZrNXfUMDHihZH",
				"UEJgZwF-3yMoXsVyDU97l",
				"xg2y1si2SKmgrPjj1DhOI",
				"Q3fripkfoEA0Rka_br6p3",
				"e3Htb9Df7LKN87gz0IV70"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "n15t6yg9Ri0Nx7SslEd5a",
					"type": "arrow"
				}
			],
			"updated": 1684508324134,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2262,
			"versionNonce": 1026940472,
			"isDeleted": false,
			"id": "OW5kVigL4b-U6TxyLaMxc",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -348.9032507261172,
			"y": -428.001599855995,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.914827876275105,
			"height": 6.301101843599194,
			"seed": 529324969,
			"groupIds": [
				"gLYKAwjKF5RLcaXy3BsSL",
				"tHslKxEALnAeSAyfGZ57S",
				"Q3fripkfoEA0Rka_br6p3",
				"e3Htb9Df7LKN87gz0IV70"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324134,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2404,
			"versionNonce": 1078477128,
			"isDeleted": false,
			"id": "o8XpZvhoA-xJImQAbws3U",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -347.91795172196544,
			"y": -423.8169553998953,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.57156398053291,
			"height": 21.72622429910385,
			"seed": 285134695,
			"groupIds": [
				"gLYKAwjKF5RLcaXy3BsSL",
				"tHslKxEALnAeSAyfGZ57S",
				"Q3fripkfoEA0Rka_br6p3",
				"e3Htb9Df7LKN87gz0IV70"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324134,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3110,
			"versionNonce": 2018334520,
			"isDeleted": false,
			"id": "L9B70PyqNh-Rn3gACQ3fr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -317.26083707994076,
			"y": -434.12978308925835,
			"strokeColor": "#000",
			"backgroundColor": "#ff00",
			"width": 42.14824103070528,
			"height": 52.441486153113395,
			"seed": 514162313,
			"groupIds": [
				"P6mKgLXcGbiGlTX1Nrebz",
				"tHslKxEALnAeSAyfGZ57S",
				"Q3fripkfoEA0Rka_br6p3",
				"e3Htb9Df7LKN87gz0IV70"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324134,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3201,
			"versionNonce": 2134956104,
			"isDeleted": false,
			"id": "6BQuleFGSq1hRu5_cKNO5",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -351.58055049356835,
			"y": -435.62404790640153,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 29.931807646605147,
			"height": 0.034763199846892336,
			"seed": 660490887,
			"groupIds": [
				"N51dgaCizt-Mnu9zBZMby",
				"tHslKxEALnAeSAyfGZ57S",
				"Q3fripkfoEA0Rka_br6p3",
				"e3Htb9Df7LKN87gz0IV70"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324134,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3311,
			"versionNonce": 873312312,
			"isDeleted": false,
			"id": "HaF7q5NkYHnwdmAPaYgDT",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -332.2501174310646,
			"y": -440.4982286131792,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1013368169,
			"groupIds": [
				"N51dgaCizt-Mnu9zBZMby",
				"tHslKxEALnAeSAyfGZ57S",
				"Q3fripkfoEA0Rka_br6p3",
				"e3Htb9Df7LKN87gz0IV70"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324134,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3224,
			"versionNonce": 554602312,
			"isDeleted": false,
			"id": "iSU5pvmEz57FRj4ktdII3",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -351.28466484875185,
			"y": -440.27203867580624,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 912351655,
			"groupIds": [
				"N51dgaCizt-Mnu9zBZMby",
				"tHslKxEALnAeSAyfGZ57S",
				"Q3fripkfoEA0Rka_br6p3",
				"e3Htb9Df7LKN87gz0IV70"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324134,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3419,
			"versionNonce": 677046584,
			"isDeleted": false,
			"id": "Cwm37Q3lkC1OCNzR4QEPE",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -333.21147893576835,
			"y": -396.75510091079946,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 9.124279794031136,
			"height": 0,
			"seed": 1679568969,
			"groupIds": [
				"tHslKxEALnAeSAyfGZ57S",
				"Q3fripkfoEA0Rka_br6p3",
				"e3Htb9Df7LKN87gz0IV70"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324134,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 3377,
			"versionNonce": 1309501000,
			"isDeleted": false,
			"id": "wgkUBlz1XiCsk8iXxVJrm",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -352.24602635345536,
			"y": -396.5289109734265,
			"strokeColor": "#000000",
			"backgroundColor": "#fa525288",
			"width": 15.487284381001047,
			"height": 0.03476319984691851,
			"seed": 523539655,
			"groupIds": [
				"tHslKxEALnAeSAyfGZ57S",
				"Q3fripkfoEA0Rka_br6p3",
				"e3Htb9Df7LKN87gz0IV70"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324134,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 743,
			"versionNonce": 1889075768,
			"isDeleted": false,
			"id": "o-nLp3HiCIxcFVnyVCYBh",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1396.2354987520284,
			"y": -879.7356077629659,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 129.93469858449998,
			"height": 3.4895146134263086,
			"seed": 230571777,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324134,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "Hm82BKT4",
				"focus": 0.11314870186121179,
				"gap": 10.000964206635786
			},
			"endBinding": {
				"elementId": "laxh7uGSv06vb_kQpr05b",
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
					129.93469858449998,
					3.4895146134263086
				]
			]
		},
		{
			"type": "rectangle",
			"version": 2014,
			"versionNonce": 1125735752,
			"isDeleted": false,
			"id": "8mWppJ7rItok_2tdstwCy",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 6.037009071252385,
			"y": -451.40530374454534,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e1488",
			"width": 85.17426249185807,
			"height": 85.09270010541165,
			"seed": 1087403015,
			"groupIds": [
				"aQn9_0yIDL1onm3gxWYCQ",
				"XYfY8-JMbfhS6WjiZ6qnc",
				"lj77H-S5LGaDWNiLfUcAo"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "Nqc-k-SzgtdiW1AV4FuKZ",
					"type": "arrow"
				},
				{
					"id": "n15t6yg9Ri0Nx7SslEd5a",
					"type": "arrow"
				},
				{
					"id": "fVg0mPlzz4axLOQnyaLXo",
					"type": "arrow"
				}
			],
			"updated": 1684508324134,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1175,
			"versionNonce": 464255800,
			"isDeleted": false,
			"id": "n8YR7Mk5O1YZyBS9qaAFY",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 39.05856692114685,
			"y": -416.0763677017403,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.51105029288197,
			"height": 35.539732911894475,
			"seed": 1235612649,
			"groupIds": [
				"3jBolSUBdKAp1mUQh0CYm",
				"XYfY8-JMbfhS6WjiZ6qnc",
				"lj77H-S5LGaDWNiLfUcAo"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324134,
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
			"version": 1175,
			"versionNonce": 1099854920,
			"isDeleted": false,
			"id": "185XjbKBeadccSrm4nn_b",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 71.41353200261665,
			"y": -395.07123203232055,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 46.066480238311605,
			"height": 58.1383889698984,
			"seed": 47340327,
			"groupIds": [
				"3jBolSUBdKAp1mUQh0CYm",
				"XYfY8-JMbfhS6WjiZ6qnc",
				"lj77H-S5LGaDWNiLfUcAo"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324134,
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
			"version": 1518,
			"versionNonce": 1006097464,
			"isDeleted": false,
			"id": "AAH374TF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -36.33712066608689,
			"y": -359.75432268879786,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 169.8804931640625,
			"height": 31.71184852903549,
			"seed": 242323145,
			"groupIds": [
				"lj77H-S5LGaDWNiLfUcAo"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "n15t6yg9Ri0Nx7SslEd5a",
					"type": "arrow"
				},
				{
					"id": "nrleZpkNNrOn80ZC-ftlO",
					"type": "arrow"
				}
			],
			"updated": 1684508324134,
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
			"version": 548,
			"versionNonce": 2135468872,
			"isDeleted": false,
			"id": "Nqc-k-SzgtdiW1AV4FuKZ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 46.53489287511953,
			"y": -578.3602525885175,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 0.6646019146130939,
			"height": 115.63636363636363,
			"seed": 667923137,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324135,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "pOtoZu0G",
				"focus": -0.0010681160156277936,
				"gap": 5.721959204611949
			},
			"endBinding": {
				"elementId": "8mWppJ7rItok_2tdstwCy",
				"focus": -0.07152255285844385,
				"gap": 11.31858520760855
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
					-0.6646019146130939,
					115.63636363636363
				]
			]
		},
		{
			"type": "arrow",
			"version": 422,
			"versionNonce": 2002816312,
			"isDeleted": false,
			"id": "n15t6yg9Ri0Nx7SslEd5a",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -4.764443747363515,
			"y": -421.21247602478775,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 299.4545454545454,
			"height": 2.247169790693988,
			"seed": 1003567247,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324135,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "8mWppJ7rItok_2tdstwCy",
				"focus": 0.2780949428719064,
				"gap": 10.8014528186159
			},
			"endBinding": {
				"elementId": "BshMmtQGaKqnIPZVY7Opm",
				"focus": -0.1425583824687287,
				"gap": 1.2637812623008244
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
					-299.4545454545454,
					-2.247169790693988
				]
			]
		},
		{
			"type": "arrow",
			"version": 355,
			"versionNonce": 379847240,
			"isDeleted": false,
			"id": "nrleZpkNNrOn80ZC-ftlO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 45.76672231174649,
			"y": -320.17843440669935,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 0.6983228524409668,
			"height": 114.90909090909088,
			"seed": 1780587553,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324135,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "AAH374TF",
				"focus": 0.03165107911336743,
				"gap": 7.864039753063025
			},
			"endBinding": {
				"elementId": "BWPU9Xn2_S8v5EGjTZzUc",
				"focus": -0.1060788344216402,
				"gap": 10.783284667954952
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
					-0.6983228524409668,
					114.90909090909088
				]
			]
		},
		{
			"type": "rectangle",
			"version": 2556,
			"versionNonce": 390735416,
			"isDeleted": false,
			"id": "Gwx6IoVByK1QXFhlWYOmY",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -281.22784225389523,
			"y": -1082.024937582929,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e1488",
			"width": 66.53246337764709,
			"height": 66.4687522713753,
			"seed": 1087403015,
			"groupIds": [
				"eotoQlBWu7zW1Tl8qn2Io",
				"5ZB2swleppY_QKYA4PW5_",
				"vihLL58YOqpPFZuy9l-M3"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "ERw7XKmwhDR6_e1oNUu7F",
					"type": "arrow"
				},
				{
					"id": "CrOFH9_krpPUaBmlFMbEo",
					"type": "arrow"
				}
			],
			"updated": 1684508324135,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1716,
			"versionNonce": 1987869000,
			"isDeleted": false,
			"id": "cl-ckH_rDnD6MusT4bCpE",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -255.4335996735034,
			"y": -1054.4283247720596,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.927534089288194,
			"height": 27.761273291189447,
			"seed": 1235612649,
			"groupIds": [
				"Jrio85ibyAKMqteN1eUJp",
				"5ZB2swleppY_QKYA4PW5_",
				"vihLL58YOqpPFZuy9l-M3"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324135,
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
			"version": 1716,
			"versionNonce": 412655416,
			"isDeleted": false,
			"id": "BHmtAvL-IUZVI4VWomU_r",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -230.1600549853564,
			"y": -1038.0205112051178,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 35.98406748383116,
			"height": 45.41383889698984,
			"seed": 47340327,
			"groupIds": [
				"Jrio85ibyAKMqteN1eUJp",
				"5ZB2swleppY_QKYA4PW5_",
				"vihLL58YOqpPFZuy9l-M3"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324135,
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
			"version": 2065,
			"versionNonce": 1378750536,
			"isDeleted": false,
			"id": "VzTre5sz",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -335.1600903531928,
			"y": -1010.4332928510494,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 174.3872528076172,
			"height": 24.77118485290355,
			"seed": 242323145,
			"groupIds": [
				"vihLL58YOqpPFZuy9l-M3"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "g1EatTZ5K-Pth2tr9fFs_",
					"type": "arrow"
				}
			],
			"updated": 1684508324135,
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
			"type": "arrow",
			"version": 805,
			"versionNonce": 1001388088,
			"isDeleted": false,
			"id": "b3fYGBXunSACHv_1-lmi-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -24.188686171605923,
			"y": -661.8733180373993,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1197.8097713648415,
			"height": 96.63687141980495,
			"seed": 1557954575,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324135,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "YVXumhUA9dF82s72x-A2n",
				"focus": -0.2792539373502846,
				"gap": 13.430799761970718
			},
			"endBinding": {
				"elementId": "4PljDSvt",
				"focus": 0.2986960991413859,
				"gap": 9.350927926961845
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
					-1059.3547880344627,
					-8.636871419804947
				],
				[
					-1197.8097713648415,
					-96.63687141980495
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1421,
			"versionNonce": 294963016,
			"isDeleted": false,
			"id": "WGMwO7U7qdE12O6WEtXXw",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 388.82644885172306,
			"y": -1091.464062841031,
			"strokeColor": "#000000",
			"backgroundColor": "#e6498088",
			"width": 65.08084106445301,
			"height": 65.08084106445301,
			"seed": 1898935145,
			"groupIds": [
				"9-OJA-HTTWjV5FYd0CgGl",
				"dcMJdIHxvkpZqQFRFEkbp",
				"iBWtOIr3ye_4xUxvOQdAE",
				"ej9kRlHCBc2EVG8IEfUcl",
				"zNwhrgkpXLZv7RxQDdZFC",
				"4Y6kdsp17pbFIxYOeLpBg"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "QmsGv5AeFLBrKcG-djHMS",
					"type": "arrow"
				}
			],
			"updated": 1684508324135,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1188,
			"versionNonce": 343159096,
			"isDeleted": false,
			"id": "tGJNamC5MleVaqA_O6iP1",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 398.51094395588336,
			"y": -1061.501953097208,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.935660646660656,
			"height": 5.935660646660656,
			"seed": 306353063,
			"groupIds": [
				"DPU7MaI9lM5zWgTPLIh8L",
				"zNwhrgkpXLZv7RxQDdZFC",
				"4Y6kdsp17pbFIxYOeLpBg"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324135,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1281,
			"versionNonce": 1091345992,
			"isDeleted": false,
			"id": "lCXqIIannKNKJSgF2MLBR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 438.56848186693526,
			"y": -1061.5526650158138,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.935660646660656,
			"height": 5.935660646660656,
			"seed": 396303945,
			"groupIds": [
				"DPU7MaI9lM5zWgTPLIh8L",
				"zNwhrgkpXLZv7RxQDdZFC",
				"4Y6kdsp17pbFIxYOeLpBg"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324135,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1326,
			"versionNonce": 441010744,
			"isDeleted": false,
			"id": "5S8pxtKbYCcgY8lR_Nt-h",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 435.3993658573987,
			"y": -1072.1697677341792,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.935660646660656,
			"height": 5.935660646660656,
			"seed": 203392711,
			"groupIds": [
				"DPU7MaI9lM5zWgTPLIh8L",
				"zNwhrgkpXLZv7RxQDdZFC",
				"4Y6kdsp17pbFIxYOeLpBg"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324135,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1400,
			"versionNonce": 24221000,
			"isDeleted": false,
			"id": "JbbRE63-yRAg8lU2Bxoww",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 435.43072788275833,
			"y": -1049.8663781965354,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.935660646660656,
			"height": 5.935660646660656,
			"seed": 1821797673,
			"groupIds": [
				"DPU7MaI9lM5zWgTPLIh8L",
				"zNwhrgkpXLZv7RxQDdZFC",
				"4Y6kdsp17pbFIxYOeLpBg"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324135,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1306,
			"versionNonce": 940786488,
			"isDeleted": false,
			"id": "H5wZy8OIeJnj_cpRn9LG0",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 423.1406103542032,
			"y": -1058.4982771466969,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15.738770407595338,
			"height": 0,
			"seed": 540087783,
			"groupIds": [
				"DPU7MaI9lM5zWgTPLIh8L",
				"zNwhrgkpXLZv7RxQDdZFC",
				"4Y6kdsp17pbFIxYOeLpBg"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324135,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1228,
			"versionNonce": 2015341640,
			"isDeleted": false,
			"id": "PakA6mtbbOi-FX6bg_0U9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 431.0369561914373,
			"y": -1069.619912600988,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 23.436189350564298,
			"seed": 125886473,
			"groupIds": [
				"DPU7MaI9lM5zWgTPLIh8L",
				"zNwhrgkpXLZv7RxQDdZFC",
				"4Y6kdsp17pbFIxYOeLpBg"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324135,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1176,
			"versionNonce": 1547050040,
			"isDeleted": false,
			"id": "Nz2RRGHMgiX8UU10KMFAT",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 435.5756597320229,
			"y": -1069.1042878515234,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.278540805703472,
			"height": 0,
			"seed": 1434697991,
			"groupIds": [
				"DPU7MaI9lM5zWgTPLIh8L",
				"zNwhrgkpXLZv7RxQDdZFC",
				"4Y6kdsp17pbFIxYOeLpBg"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324135,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1188,
			"versionNonce": 1056105288,
			"isDeleted": false,
			"id": "lRTbAvWO_37VMieP00uRV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 435.54161639894903,
			"y": -1046.6669204076663,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 4.278540805703472,
			"height": 0,
			"seed": 106559209,
			"groupIds": [
				"DPU7MaI9lM5zWgTPLIh8L",
				"zNwhrgkpXLZv7RxQDdZFC",
				"4Y6kdsp17pbFIxYOeLpBg"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324135,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1358,
			"versionNonce": 144037176,
			"isDeleted": false,
			"id": "SHnsejlY6Vxe2PeOMcim1",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 410.08273029294935,
			"y": -1066.5996605055227,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13.538770570677526,
			"height": 4.283701206606613,
			"seed": 496240679,
			"groupIds": [
				"DPU7MaI9lM5zWgTPLIh8L",
				"zNwhrgkpXLZv7RxQDdZFC",
				"4Y6kdsp17pbFIxYOeLpBg"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324135,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1493,
			"versionNonce": 1413954120,
			"isDeleted": false,
			"id": "NPu0BHU6ldThZXUi6kdre",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 410.4636483908099,
			"y": -1063.7371597619738,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13.305408215826999,
			"height": 14.770218853011942,
			"seed": 1001206217,
			"groupIds": [
				"DPU7MaI9lM5zWgTPLIh8L",
				"zNwhrgkpXLZv7RxQDdZFC",
				"4Y6kdsp17pbFIxYOeLpBg"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324135,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1365,
			"versionNonce": 1654025784,
			"isDeleted": false,
			"id": "QYcYQD4yyCCgnsrhzsR01",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 404.54046618233326,
			"y": -1058.5986396329365,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.229181632062791,
			"height": 0,
			"seed": 105802567,
			"groupIds": [
				"DPU7MaI9lM5zWgTPLIh8L",
				"zNwhrgkpXLZv7RxQDdZFC",
				"4Y6kdsp17pbFIxYOeLpBg"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324136,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1334,
			"versionNonce": 184070472,
			"isDeleted": false,
			"id": "DpGnrVbCTG9JEshbgCgmi",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 401.6992443848809,
			"y": -1061.50459856984,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 32.796640923919526,
			"height": 16.800743224146107,
			"seed": 479596713,
			"groupIds": [
				"DPU7MaI9lM5zWgTPLIh8L",
				"zNwhrgkpXLZv7RxQDdZFC",
				"4Y6kdsp17pbFIxYOeLpBg"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324136,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1469,
			"versionNonce": 1125902136,
			"isDeleted": false,
			"id": "dA0_rvi2_UJkHII9mHEJR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 401.28595070935955,
			"y": -1055.431691646196,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.72406610309211,
			"height": 17.27583554628456,
			"seed": 739207783,
			"groupIds": [
				"DPU7MaI9lM5zWgTPLIh8L",
				"zNwhrgkpXLZv7RxQDdZFC",
				"4Y6kdsp17pbFIxYOeLpBg"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324136,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1638,
			"versionNonce": 2053326920,
			"isDeleted": false,
			"id": "x8TGHSiC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 302.3668693839496,
			"y": -1022.0007605178218,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 226.73977661132812,
			"height": 48,
			"seed": 1858081673,
			"groupIds": [
				"4Y6kdsp17pbFIxYOeLpBg"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "QmsGv5AeFLBrKcG-djHMS",
					"type": "arrow"
				}
			],
			"updated": 1684508324136,
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
			"version": 1137,
			"versionNonce": 1183465528,
			"isDeleted": false,
			"id": "xzQI1rMxmnyzICDXQO21y",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -816.6735709847027,
			"y": -1084.8571237756846,
			"strokeColor": "#000000",
			"backgroundColor": "#e6498088",
			"width": 64.70089111328099,
			"height": 64.70089111328099,
			"seed": 1932782313,
			"groupIds": [
				"fiYBfqYCmec6NafoRlDB_",
				"fX7A25mvtG0RmVypZ5yTf"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "gIiuQF2JT4V4GceRBAg5V",
					"type": "arrow"
				},
				{
					"id": "ERw7XKmwhDR6_e1oNUu7F",
					"type": "arrow"
				}
			],
			"updated": 1684508324136,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1347,
			"versionNonce": 1851981640,
			"isDeleted": false,
			"id": "bpkKeCkJq1fyllAdrxSFZ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -798.5234506790285,
			"y": -1052.2750896096022,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.0965264804551,
			"height": 25.394020168765657,
			"seed": 2055427111,
			"groupIds": [
				"quotIZrOGVgXEFkoNqilH",
				"fiYBfqYCmec6NafoRlDB_",
				"fX7A25mvtG0RmVypZ5yTf"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324136,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1131,
			"versionNonce": 1556445496,
			"isDeleted": false,
			"id": "ZwHvRb9yp8Y-NDSISv8yv",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -798.7900808220357,
			"y": -1075.4621679095076,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.527048406442323,
			"height": 6.527048406442323,
			"seed": 1630053833,
			"groupIds": [
				"quotIZrOGVgXEFkoNqilH",
				"fiYBfqYCmec6NafoRlDB_",
				"fX7A25mvtG0RmVypZ5yTf"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324136,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1192,
			"versionNonce": 1465112136,
			"isDeleted": false,
			"id": "_TPOU5zeBAZV-C-NdG7N4",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -793.7049293258511,
			"y": -1069.3033588804356,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.4300394358401154,
			"height": 4.165241568829386,
			"seed": 527710023,
			"groupIds": [
				"quotIZrOGVgXEFkoNqilH",
				"fiYBfqYCmec6NafoRlDB_",
				"fX7A25mvtG0RmVypZ5yTf"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324136,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1253,
			"versionNonce": 1496420920,
			"isDeleted": false,
			"id": "gcPzL5GKPi5-zkkkI0P3f",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.141592653589793,
			"x": -775.7122837926973,
			"y": -1036.0782369350231,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.527048406442323,
			"height": 6.527048406442323,
			"seed": 1786971305,
			"groupIds": [
				"quotIZrOGVgXEFkoNqilH",
				"fiYBfqYCmec6NafoRlDB_",
				"fX7A25mvtG0RmVypZ5yTf"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324136,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1321,
			"versionNonce": 974245192,
			"isDeleted": false,
			"id": "I9iR6iERc0j_TRQ0U6yAz",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.141592653589793,
			"x": -776.7004263182813,
			"y": -1039.875239126482,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.4300394358401154,
			"height": 4.165241568829386,
			"seed": 916174439,
			"groupIds": [
				"quotIZrOGVgXEFkoNqilH",
				"fiYBfqYCmec6NafoRlDB_",
				"fX7A25mvtG0RmVypZ5yTf"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324136,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1264,
			"versionNonce": 45255480,
			"isDeleted": false,
			"id": "s2DMtp_Me14U-oYYCmD3V",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -770.084316718912,
			"y": -1065.899870507667,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.527048406442323,
			"height": 6.527048406442323,
			"seed": 1525581705,
			"groupIds": [
				"quotIZrOGVgXEFkoNqilH",
				"fiYBfqYCmec6NafoRlDB_",
				"fX7A25mvtG0RmVypZ5yTf"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324136,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1352,
			"versionNonce": 536405064,
			"isDeleted": false,
			"id": "TtpopyQQDTLkaY8p3MrAc",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -804.8599178374062,
			"y": -1045.4969387368465,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.527048406442323,
			"height": 6.527048406442323,
			"seed": 1992708487,
			"groupIds": [
				"quotIZrOGVgXEFkoNqilH",
				"fiYBfqYCmec6NafoRlDB_",
				"fX7A25mvtG0RmVypZ5yTf"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324136,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1158,
			"versionNonce": 598500408,
			"isDeleted": false,
			"id": "vfmoruRJJ2ZV33ekFOXex",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -783.9028735796056,
			"y": -1071.0653357640476,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14.881064367630502,
			"height": 5.819316836931806,
			"seed": 2091298409,
			"groupIds": [
				"quotIZrOGVgXEFkoNqilH",
				"fiYBfqYCmec6NafoRlDB_",
				"fX7A25mvtG0RmVypZ5yTf"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324136,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1146,
			"versionNonce": 115678024,
			"isDeleted": false,
			"id": "o-462C8dNyMosJM88p__W",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -767.1068689754221,
			"y": -1042.4711191329538,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.359881211089217,
			"height": 17.609098804231238,
			"seed": 154175655,
			"groupIds": [
				"quotIZrOGVgXEFkoNqilH",
				"fiYBfqYCmec6NafoRlDB_",
				"fX7A25mvtG0RmVypZ5yTf"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324136,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1331,
			"versionNonce": 436411704,
			"isDeleted": false,
			"id": "WSG2UqllIoFxnFI_vdeB4",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.141592653589793,
			"x": -799.6244416441497,
			"y": -1039.5814840732514,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14.881064367630502,
			"height": 5.819316836931806,
			"seed": 1182202185,
			"groupIds": [
				"quotIZrOGVgXEFkoNqilH",
				"fiYBfqYCmec6NafoRlDB_",
				"fX7A25mvtG0RmVypZ5yTf"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324136,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1316,
			"versionNonce": 1362260552,
			"isDeleted": false,
			"id": "4c7DPy7cuO4jKkI3kMNQ2",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.141592653589793,
			"x": -806.8992630917916,
			"y": -1044.8251437717918,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.359881211089217,
			"height": 17.609098804231238,
			"seed": 998693831,
			"groupIds": [
				"quotIZrOGVgXEFkoNqilH",
				"fiYBfqYCmec6NafoRlDB_",
				"fX7A25mvtG0RmVypZ5yTf"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324136,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 2070,
			"versionNonce": 1729803832,
			"isDeleted": false,
			"id": "5TYddIld",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -817.8786809836179,
			"y": -1016.6076995831681,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.59994506835938,
			"height": 24,
			"seed": 1236985897,
			"groupIds": [
				"fX7A25mvtG0RmVypZ5yTf"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324136,
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
			"version": 385,
			"versionNonce": 901572936,
			"isDeleted": false,
			"id": "gIiuQF2JT4V4GceRBAg5V",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1219.855582275852,
			"y": -925.2271590453483,
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
			"updated": 1684508324136,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "laxh7uGSv06vb_kQpr05b",
				"focus": -0.3386597489482006,
				"gap": 12.168162627563675
			},
			"endBinding": {
				"elementId": "xzQI1rMxmnyzICDXQO21y",
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
					392.77800721535675,
					-125.28349161994038
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1809,
			"versionNonce": 1071066936,
			"isDeleted": false,
			"id": "W8muu5hOUOio0dbn7H3Xm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -452.66796314633643,
			"y": -1305.4027092885603,
			"strokeColor": "#e64980",
			"backgroundColor": "transparent",
			"width": 1070.625220616127,
			"height": 1553.9606610077406,
			"seed": 1073359495,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324136,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1611,
			"versionNonce": 803242056,
			"isDeleted": false,
			"id": "CCShLrHS0Lh6da0Odf8gN",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -430.1316211140347,
			"y": -1284.6936315662294,
			"strokeColor": "#e64980",
			"backgroundColor": "#e6498088",
			"width": 113.8653583445497,
			"height": 113.8653583445497,
			"seed": 1259971911,
			"groupIds": [
				"ci41UmsoICVchdU9jqCX7",
				"gAgarKHJiktfdu-dnYx2R",
				"G7hCQBuHaIXinTDRNWu32"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324136,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1111,
			"versionNonce": 480020536,
			"isDeleted": false,
			"id": "DJsBU8nRAIhYa7Fqsl7x-",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -379.2083029524674,
			"y": -1270.8319130090233,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.131091700161791,
			"height": 10.131091700161791,
			"seed": 1219720873,
			"groupIds": [
				"ZpfcBcTjweg8vgYxmiGuQ",
				"gAgarKHJiktfdu-dnYx2R",
				"G7hCQBuHaIXinTDRNWu32"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324136,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1218,
			"versionNonce": 1870214984,
			"isDeleted": false,
			"id": "qP7Kcmalgazr7vjURKBH2",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -379.10295375981923,
			"y": -1194.8210834790482,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.131091700161791,
			"height": 10.131091700161791,
			"seed": 1734567015,
			"groupIds": [
				"ZpfcBcTjweg8vgYxmiGuQ",
				"gAgarKHJiktfdu-dnYx2R",
				"G7hCQBuHaIXinTDRNWu32"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324136,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1077,
			"versionNonce": 1229898040,
			"isDeleted": false,
			"id": "co2Hmy5T2IMdCJ__75qyi",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -418.2718839775862,
			"y": -1243.8525197769607,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.37948548155744,
			"height": 10.986936652204236,
			"seed": 1044429193,
			"groupIds": [
				"ZpfcBcTjweg8vgYxmiGuQ",
				"gAgarKHJiktfdu-dnYx2R",
				"G7hCQBuHaIXinTDRNWu32"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324136,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1126,
			"versionNonce": 1222839880,
			"isDeleted": false,
			"id": "ONG_yUid7Sexi_-CQMKpT",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -418.1261784484659,
			"y": -1222.3650427042069,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.37948548155744,
			"height": 10.986936652204236,
			"seed": 1315454855,
			"groupIds": [
				"ZpfcBcTjweg8vgYxmiGuQ",
				"gAgarKHJiktfdu-dnYx2R",
				"G7hCQBuHaIXinTDRNWu32"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324136,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1194,
			"versionNonce": 1968298552,
			"isDeleted": false,
			"id": "cG8rBL2gGoWVG5vvJqtVB",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -361.50548538748853,
			"y": -1234.833222029706,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.37948548155744,
			"height": 14.914612147334124,
			"seed": 1524801641,
			"groupIds": [
				"ZpfcBcTjweg8vgYxmiGuQ",
				"gAgarKHJiktfdu-dnYx2R",
				"G7hCQBuHaIXinTDRNWu32"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324137,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1097,
			"versionNonce": 620365128,
			"isDeleted": false,
			"id": "CbcUfrFW-65ubPkeYkWnB",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -401.10933141827445,
			"y": -1231.939111281369,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.917422766232455,
			"seed": 845461159,
			"groupIds": [
				"ZpfcBcTjweg8vgYxmiGuQ",
				"gAgarKHJiktfdu-dnYx2R",
				"G7hCQBuHaIXinTDRNWu32"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324137,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1144,
			"versionNonce": 1133105976,
			"isDeleted": false,
			"id": "0Vc4fbPbGXa-6gWW4OtAi",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -400.87728578593124,
			"y": -1251.3024778269998,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 57.71378835781129,
			"height": 0,
			"seed": 476359497,
			"groupIds": [
				"ZpfcBcTjweg8vgYxmiGuQ",
				"gAgarKHJiktfdu-dnYx2R",
				"G7hCQBuHaIXinTDRNWu32"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324137,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1159,
			"versionNonce": 1897536584,
			"isDeleted": false,
			"id": "8bLe88z-IWfiqqEQbD6Ai",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -401.9019272249434,
			"y": -1252.999712765061,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.917422766232455,
			"seed": 1241860551,
			"groupIds": [
				"ZpfcBcTjweg8vgYxmiGuQ",
				"gAgarKHJiktfdu-dnYx2R",
				"G7hCQBuHaIXinTDRNWu32"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324137,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1261,
			"versionNonce": 1515891768,
			"isDeleted": false,
			"id": "sjQ4TAws0M2PwuFAKg22c",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -344.7284461445606,
			"y": -1251.662682898789,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 10.488988336663578,
			"seed": 992107049,
			"groupIds": [
				"ZpfcBcTjweg8vgYxmiGuQ",
				"gAgarKHJiktfdu-dnYx2R",
				"G7hCQBuHaIXinTDRNWu32"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324137,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1309,
			"versionNonce": 253711176,
			"isDeleted": false,
			"id": "K4ElKTW_n1LZt0jd03gOj",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -374.11029502013207,
			"y": -1259.8206172456955,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.010963966968777,
			"seed": 1114011879,
			"groupIds": [
				"ZpfcBcTjweg8vgYxmiGuQ",
				"gAgarKHJiktfdu-dnYx2R",
				"G7hCQBuHaIXinTDRNWu32"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324137,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1179,
			"versionNonce": 1940415800,
			"isDeleted": false,
			"id": "AMl2FDz3ivk9UjhV75Qn2",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -400.8412570225478,
			"y": -1203.1015531376604,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 57.71378835781129,
			"height": 0,
			"seed": 1476865289,
			"groupIds": [
				"ZpfcBcTjweg8vgYxmiGuQ",
				"gAgarKHJiktfdu-dnYx2R",
				"G7hCQBuHaIXinTDRNWu32"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324137,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1352,
			"versionNonce": 1164290632,
			"isDeleted": false,
			"id": "61hiOP31AbHi4RJGuCGCt",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -374.07426625674225,
			"y": -1204.5433760585158,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.480946860464432,
			"seed": 1897186311,
			"groupIds": [
				"ZpfcBcTjweg8vgYxmiGuQ",
				"gAgarKHJiktfdu-dnYx2R",
				"G7hCQBuHaIXinTDRNWu32"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324137,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1194,
			"versionNonce": 1826029112,
			"isDeleted": false,
			"id": "R9q66c62WrbTrinnpxWU-",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -400.93651911255483,
			"y": -1210.4399797477824,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 8.917422766232455,
			"seed": 1787732969,
			"groupIds": [
				"ZpfcBcTjweg8vgYxmiGuQ",
				"gAgarKHJiktfdu-dnYx2R",
				"G7hCQBuHaIXinTDRNWu32"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324137,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1352,
			"versionNonce": 784933192,
			"isDeleted": false,
			"id": "JA3f7BkRutBF0QblNVenr",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -344.8024534570177,
			"y": -1212.4296891434674,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 10.488988336663578,
			"seed": 1175235367,
			"groupIds": [
				"ZpfcBcTjweg8vgYxmiGuQ",
				"gAgarKHJiktfdu-dnYx2R",
				"G7hCQBuHaIXinTDRNWu32"
			],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324137,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
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
			"version": 1923,
			"versionNonce": 1456109368,
			"isDeleted": false,
			"id": "YDNkIOX2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -291.2480861611516,
			"y": -1260.8000385167354,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 554.6878051757812,
			"height": 43.199999999999996,
			"seed": 1017614857,
			"groupIds": [
				"cBU9dbkeR4COA7PB9lf0h",
				"G7hCQBuHaIXinTDRNWu32"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324137,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "AWS Step Functions: Inventario",
			"rawText": "AWS Step Functions: Inventario",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "AWS Step Functions: Inventario",
			"lineHeight": 1.2,
			"baseline": 31
		},
		{
			"type": "arrow",
			"version": 78,
			"versionNonce": 715503688,
			"isDeleted": false,
			"id": "ERw7XKmwhDR6_e1oNUu7F",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -744.138081805213,
			"y": -1054.4635635684742,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 460.0000000000002,
			"height": 4,
			"seed": 1359218369,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324137,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "xzQI1rMxmnyzICDXQO21y",
				"focus": -0.07067718538808795,
				"gap": 7.8345980662086845
			},
			"endBinding": {
				"elementId": "Gwx6IoVByK1QXFhlWYOmY",
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
					460.0000000000002,
					4
				]
			]
		},
		{
			"type": "diamond",
			"version": 284,
			"versionNonce": 99012664,
			"isDeleted": false,
			"id": "c4XZskgfkQ-1RmaHr25R6",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -40.13808180521255,
			"y": -1134.463563568474,
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
					"id": "0dZA6q3V"
				},
				{
					"id": "CrOFH9_krpPUaBmlFMbEo",
					"type": "arrow"
				},
				{
					"id": "QmsGv5AeFLBrKcG-djHMS",
					"type": "arrow"
				},
				{
					"id": "c_BC4Cv4wDibovIg6hTvH",
					"type": "arrow"
				}
			],
			"updated": 1684508324137,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 257,
			"versionNonce": 1289187144,
			"isDeleted": false,
			"id": "0dZA6q3V",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 11.253939373986668,
			"y": -1082.463563568474,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 77.21595764160156,
			"height": 60,
			"seed": 1620544207,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324137,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "El archivo\nes \ncorrecto?",
			"rawText": "El archivo es correcto?",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "c4XZskgfkQ-1RmaHr25R6",
			"originalText": "El archivo es correcto?",
			"lineHeight": 1.25,
			"baseline": 54
		},
		{
			"type": "arrow",
			"version": 111,
			"versionNonce": 271835448,
			"isDeleted": false,
			"id": "CrOFH9_krpPUaBmlFMbEo",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -204.13808180521255,
			"y": -1046.5281119994797,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 164.89158360037834,
			"height": 3.770299288185015,
			"seed": 485934383,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508681251,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "Gwx6IoVByK1QXFhlWYOmY",
				"gap": 10.557297071035578,
				"focus": 0.09602843741616263
			},
			"endBinding": {
				"elementId": "c4XZskgfkQ-1RmaHr25R6",
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
					164.89158360037834,
					-3.770299288185015
				]
			]
		},
		{
			"type": "arrow",
			"version": 324,
			"versionNonce": 1653799480,
			"isDeleted": false,
			"id": "QmsGv5AeFLBrKcG-djHMS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 143.79081066814493,
			"y": -1052.0832350374867,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 235.62115582991166,
			"height": 2.01086894511468,
			"seed": 45550529,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "aZWmVcIT"
				}
			],
			"updated": 1684508681251,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "c4XZskgfkQ-1RmaHr25R6",
				"gap": 3.9472580177495473,
				"focus": 0.014414009683752425
			},
			"endBinding": {
				"elementId": "WGMwO7U7qdE12O6WEtXXw",
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
					235.62115582991166,
					-2.01086894511468
				]
			]
		},
		{
			"type": "text",
			"version": 23,
			"versionNonce": 917119544,
			"isDeleted": false,
			"id": "aZWmVcIT",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 249.6214004849562,
			"y": -1065.588669510044,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.959976196289062,
			"height": 25,
			"seed": 1226593793,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324137,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "No",
			"rawText": "No",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "QmsGv5AeFLBrKcG-djHMS",
			"originalText": "No",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 195,
			"versionNonce": 2049588552,
			"isDeleted": false,
			"id": "g1EatTZ5K-Pth2tr9fFs_",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -246.13808180521278,
			"y": -972.4635635684741,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 928.0000000000005,
			"height": 106,
			"seed": 349728975,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324137,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "VzTre5sz",
				"focus": -0.31790732783103054,
				"gap": 13.198544429671813
			},
			"endBinding": {
				"elementId": "laxh7uGSv06vb_kQpr05b",
				"focus": 0.2155495832370154,
				"gap": 11.359849289210729
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
					102
				],
				[
					-928.0000000000005,
					106
				]
			]
		},
		{
			"type": "arrow",
			"version": 142,
			"versionNonce": 1117330232,
			"isDeleted": false,
			"id": "bSiLlP42JzIBg_DE6pwzo",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1535.0298574243843,
			"y": -263.76852592657843,
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
			"updated": 1684508324137,
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
			"version": 537,
			"versionNonce": 595809352,
			"isDeleted": false,
			"id": "xxa9yaOB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 80,
			"angle": 0,
			"x": -1094.8401736135252,
			"y": -291.9635635684742,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 264.7391357421875,
			"height": 50.60647781878732,
			"seed": 1664452687,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324137,
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
			"version": 101,
			"versionNonce": 732361528,
			"isDeleted": false,
			"id": "c_BC4Cv4wDibovIg6hTvH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 49.86191819478745,
			"y": -966.0283855448251,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 233.56482197635125,
			"seed": 1002414529,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "SZosf4q1"
				}
			],
			"updated": 1684508681253,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "c4XZskgfkQ-1RmaHr25R6",
				"gap": 4.435178023648788,
				"focus": 0
			},
			"endBinding": {
				"elementId": "YVXumhUA9dF82s72x-A2n",
				"gap": 2.1523094525125543,
				"focus": 0.1250260113559943
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
					233.56482197635125
				]
			]
		},
		{
			"type": "text",
			"version": 21,
			"versionNonce": 262245192,
			"isDeleted": false,
			"id": "SZosf4q1",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 41.591929181115574,
			"y": -861.7459745566496,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.53997802734375,
			"height": 25,
			"seed": 324324737,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324138,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Si",
			"rawText": "Si",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "c_BC4Cv4wDibovIg6hTvH",
			"originalText": "Si",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 143,
			"versionNonce": 1569041720,
			"isDeleted": false,
			"id": "oM7RKtE4N3ae8x2rWWKKB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1532.3135380541034,
			"y": -185.77230511488523,
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
			"updated": 1684508324138,
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
			"type": "text",
			"version": 230,
			"versionNonce": 1759568456,
			"isDeleted": false,
			"id": "v3O3ve8g",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 70,
			"angle": 0,
			"x": -147.29941567168316,
			"y": -548.5205142579803,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 134.07994079589844,
			"height": 80,
			"seed": 399369505,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324138,
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
			"type": "arrow",
			"version": 112,
			"versionNonce": 1003177528,
			"isDeleted": false,
			"id": "0juGu8sAojCiaFM-TaKd9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 70,
			"angle": 0,
			"x": -10.259445273733945,
			"y": -128.52051425798027,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 333.99172549934144,
			"height": 210,
			"seed": 519747119,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324138,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "BWPU9Xn2_S8v5EGjTZzUc",
				"focus": -0.33335946895590346,
				"gap": 6.802696229966841
			},
			"endBinding": {
				"elementId": "UO6Kxrjf",
				"focus": 0.14020860830876195,
				"gap": 11.053191942099716
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
					-279.3767263610843,
					-38
				],
				[
					-333.99172549934144,
					-210
				]
			]
		},
		{
			"type": "arrow",
			"version": 117,
			"versionNonce": 773675336,
			"isDeleted": false,
			"id": "fVg0mPlzz4axLOQnyaLXo",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 70,
			"angle": 0,
			"x": 99.74055472626605,
			"y": -418.52051425798027,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 270,
			"height": 170,
			"seed": 1446991041,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "baEV8zYt"
				}
			],
			"updated": 1684508324138,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "8mWppJ7rItok_2tdstwCy",
				"focus": 0.3247216836217705,
				"gap": 8.529283163155597
			},
			"endBinding": {
				"elementId": "hKori0fi",
				"focus": 0.29383733926431166,
				"gap": 10.904945775848319
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
					270,
					-170
				]
			]
		},
		{
			"type": "text",
			"version": 34,
			"versionNonce": 1341505336,
			"isDeleted": false,
			"id": "baEV8zYt",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 70,
			"angle": 0,
			"x": 171.56459800019184,
			"y": -513.5205142579803,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 126.35191345214844,
			"height": 20,
			"seed": 585867649,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324138,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Consultar fecha",
			"rawText": "Consultar fecha",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "fVg0mPlzz4axLOQnyaLXo",
			"originalText": "Consultar fecha",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "rectangle",
			"version": 631,
			"versionNonce": 582152264,
			"isDeleted": false,
			"id": "gotp9FW_UCb2DaCrM90OD",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -1707.0165000262414,
			"y": -512.793242422669,
			"strokeColor": "#0091e2",
			"backgroundColor": "transparent",
			"width": 965.5141095050149,
			"height": 589.4717721188509,
			"seed": 302519605,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324138,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 2518,
			"versionNonce": 1248401464,
			"isDeleted": false,
			"id": "V7BfNFI4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1685.9866629195649,
			"y": -490.63289655672276,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 158.51254272460938,
			"height": 91.22729405629221,
			"seed": 35046555,
			"groupIds": [
				"D6LmCZVQeqUeD3miQULY_"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324138,
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
			"type": "text",
			"version": 227,
			"versionNonce": 1048422216,
			"isDeleted": false,
			"id": "6Q7Qq6t2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 70,
			"angle": 0,
			"x": 851.4905547262656,
			"y": -462.15935795135715,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 605.2821044921875,
			"height": 127.06666666666652,
			"seed": 1548343563,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324138,
			"link": null,
			"locked": false,
			"fontSize": 18.415458937198046,
			"fontFamily": 2,
			"text": "DELETE \nFROM dw.FactInventory\nWHERE date IN\n(\n        SELECT MAX(CAST(Fecha AS DATE)) FROM stating.DailyInventory\n) ",
			"rawText": "DELETE \nFROM dw.FactInventory\nWHERE date IN\n(\n        SELECT MAX(CAST(Fecha AS DATE)) FROM stating.DailyInventory\n) ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "DELETE \nFROM dw.FactInventory\nWHERE date IN\n(\n        SELECT MAX(CAST(Fecha AS DATE)) FROM stating.DailyInventory\n) ",
			"lineHeight": 1.15,
			"baseline": 123
		},
		{
			"type": "arrow",
			"version": 108,
			"versionNonce": 789139768,
			"isDeleted": false,
			"id": "tEUsuS4DEs50eL5C8ldis",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 70,
			"angle": 0,
			"x": 113.15722139293297,
			"y": -397.15935795135704,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 683.333333333333,
			"height": 3.3333333333333712,
			"seed": 809668139,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508324138,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "yEgoqimHyTQx0Q5jCHyw5",
				"focus": 0.07865225298040046,
				"gap": 9.999999999999773
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
					683.333333333333,
					-3.3333333333333712
				]
			]
		},
		{
			"type": "rectangle",
			"version": 72,
			"versionNonce": 500792904,
			"isDeleted": false,
			"id": "yEgoqimHyTQx0Q5jCHyw5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 70,
			"angle": 0,
			"x": 806.4905547262658,
			"y": -548.8260246180237,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 728.333333333333,
			"height": 318.33333333333326,
			"seed": 970163141,
			"groupIds": [],
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "tEUsuS4DEs50eL5C8ldis",
					"type": "arrow"
				}
			],
			"updated": 1684508324138,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 28,
			"versionNonce": 1698327096,
			"isDeleted": false,
			"id": "XTUZCDYK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 70,
			"angle": 0,
			"x": 894.8238880595995,
			"y": -613.8260246180237,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 290.6558837890625,
			"height": 20,
			"seed": 1518206347,
			"groupIds": [],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508324138,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Llama a un SP: DeleteFactInventory",
			"rawText": "Llama a un SP: DeleteFactInventory",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Llama a un SP: DeleteFactInventory",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "rectangle",
			"version": 2114,
			"versionNonce": 486784056,
			"isDeleted": false,
			"id": "e1NlIkCwoH5N0CN2DGGn5",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2.218864287589497,
			"y": 76.02467864514097,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e1488",
			"width": 85.17426249185807,
			"height": 85.09270010541165,
			"seed": 1087403015,
			"groupIds": [
				"OvCSOa5MJdNbCoyAtGwC9",
				"VedbI7ZReXANBHK91sMLj",
				"9fvBnwcDPXGK7NFoTSMuS"
			],
			"roundness": null,
			"boundElements": [
				{
					"id": "7A5vC-mmjri9DHhOsS7xe",
					"type": "arrow"
				}
			],
			"updated": 1684508343160,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1272,
			"versionNonce": 2000284472,
			"isDeleted": false,
			"id": "KTp8rXlSIBQj30DZn-h-y",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 35.24042213748396,
			"y": 111.35361468794599,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.51105029288197,
			"height": 35.539732911894475,
			"seed": 1235612649,
			"groupIds": [
				"NcqmJuEB_Ouj2b2qjcm1d",
				"VedbI7ZReXANBHK91sMLj",
				"9fvBnwcDPXGK7NFoTSMuS"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508329314,
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
			"version": 1272,
			"versionNonce": 571966536,
			"isDeleted": false,
			"id": "bjFKFbwlaG6KU9fYikghv",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 67.59538721895376,
			"y": 132.35875035736575,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 46.066480238311605,
			"height": 58.1383889698984,
			"seed": 47340327,
			"groupIds": [
				"NcqmJuEB_Ouj2b2qjcm1d",
				"VedbI7ZReXANBHK91sMLj",
				"9fvBnwcDPXGK7NFoTSMuS"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508329314,
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
			"version": 1674,
			"versionNonce": 1724630344,
			"isDeleted": false,
			"id": "y6MjXAug",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -202.71746027396853,
			"y": 167.67565970088845,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 495.0048828125,
			"height": 31.71184852903549,
			"seed": 242323145,
			"groupIds": [
				"9fvBnwcDPXGK7NFoTSMuS"
			],
			"roundness": null,
			"boundElements": [],
			"updated": 1684508694170,
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
			"version": 421,
			"versionNonce": 1148980792,
			"isDeleted": false,
			"id": "7A5vC-mmjri9DHhOsS7xe",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 51.549511601383614,
			"y": -42.137894435093415,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 0.69832285244118,
			"height": 103.79797979797979,
			"seed": 1780587553,
			"groupIds": [],
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1684508343707,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "mRshoyeX",
				"focus": 0.027199384264467465,
				"gap": 8.86747017752731
			},
			"endBinding": {
				"elementId": "e1NlIkCwoH5N0CN2DGGn5",
				"focus": 0.13207062346357365,
				"gap": 14.364593282254589
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
					-0.69832285244118,
					103.79797979797979
				]
			]
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
		"currentItemRoughness": 1,
		"currentItemOpacity": 70,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 16,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 1976.3261299788296,
		"scrollY": 1587.8841843402456,
		"zoom": {
			"value": 0.45
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