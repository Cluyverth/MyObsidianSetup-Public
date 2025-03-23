---
tags:
  - "#MOC"
aliases:
---
## Table of Contents
### Scheduled
```dataview
TABLE Status, Priority, date as "Data Criação"
FROM #Activities/Work  
WHERE Status = "Scheduled"
Sort Priority ASC
```
### In-progress
```dataview
TABLE Status, Priority, date as "Data Criação"
FROM #Activities/Work  
WHERE Status = "In-progress"
Sort Priority ASC
```

### Paused
```dataview
TABLE Status, Priority, date as "Data Criação"
FROM #Activities/Work  
WHERE Status = "Paused"
Sort Priority ASC
```
