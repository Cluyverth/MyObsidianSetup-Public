---
tags:
  - MOC
aliases:
  - Backlog
  - backlog
  - histórias
  - cards
  - Cards
  - Histórias
---
## Overview
- Tudo relacionado ao backlog.
## Table of Contents
### In-progress
```dataview
TABLE Card, Environment, Status, Priority, date as "Data Criação", Data_R as "Data Ready", Data_D as "Done", Autor
FROM #Backlog/Card 
WHERE Status = "In-progress"
Sort Priority ASC
```
### Scheduled
```dataview
TABLE Card, Environment, Status, Priority, date as "Data Criação", Data_R as "Data Ready", Data_D as "Done", Autor
FROM #Backlog/Card
WHERE Status = "Scheduled" OR Status = "Paused"
Sort Priority ASC
Sort Card Desc
```
### Completed
```dataview
TABLE Card, Environment, Status, Priority, date as "Data Criação", Data_R as "Data Ready", Data_D as "Done", Autor
FROM #Backlog/Card
WHERE Status = "Done"
Sort date Desc
```
