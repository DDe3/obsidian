
[Proceso](obsidian://open?vault=Obsidian%20Vault&file=Excalidraw%2FVMI-Telcel-InventarioWorkflow.excalidraw)

## Carga de archivos .txt


| Origen                     | Destino                | Reemplazo                    |
| -------------------------- | ---------------------- | ---------------------------- |
| Carpeta: **01_Inventario** | stating.DailyInventory | preprocessing.DailyInventory |


## Carga de tabla facts

| Origen                       | Destino      | Reemplazo |
| ---------------------------- | ------------ | --------- |
| preprocessing.DailyInventory | dw.FactSales | No        |
| dw.dimMaterial               |              |           |
| dw.dimStore                             |              |           |




