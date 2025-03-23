---
tags:
  - MOC
aliases:
---
## Overview


### In-progress
```dataview
TABLE Card, Environment, Status, Priority, date as "Data Criação", Data_R as "Data Ready", Data_D as "Done", Autor
FROM #GameDev 
WHERE Status = "In-progress"
Sort Priority ASC
```
### Scheduled
```dataview
TABLE Card, Environment, Status, Priority, date as "Data Criação", Data_R as "Data Ready", Data_D as "Done", Autor
FROM #GameDev 
WHERE Status = "Scheduled" OR Status = "Paused"
Sort Priority ASC
```
### Completed
```dataview
TABLE Card, Environment, Status, Priority, date as "Data Criação", Data_R as "Data Ready", Data_D as "Done", Autor
FROM #GameDev 
WHERE Status = "Done"
Sort date Desc
```
