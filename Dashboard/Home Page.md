---
tags: []
cssclasses:
  - dash
  - dashboard
aliases:
---
### Statistics
> [!LifeData]+ Vault Data
> 🗃️ `$=dv.pages().length` **Vault Notes**
> ⏳`$=dv.pages('#Note/Fleeting').length` **Fleeting Notes**
>🌡️ `$=dv.pages('#Activities/Work').length` **Activities Notes**
>🎴`$=dv.pages('#Backlog/Card').length` **Backlog Cards**
> 🧭 `$=dv.pages('"Atlas/Notes"').length` **Atlas Notes**
> 🗓️ `$=dv.pages('"Calendar/Notes"').length` **Calendar Notes**
> 🗺️ `$=dv.pages('"Atlas/MOCs"').length` **MOCs**
> ⚙️ `$=dv.pages('"Settigns/Templates"').length` **Templates**
### Tree of Knowledge
> [!TreeofKnowledge]+ Tree of Knowledge
> ```dataview
> LIST
>FROM #MOC  
>SORT file.name ASC
>```
### Tasks
>[!TasksManager]+  Work Tasks
>```tasks
>not done
>heading includes Work
>path does not include Templates
>```
### Fleeting Notes

> [!LifeData]+ Fleeting Notes 
>```dataview
>LIST
>FROM #Note/Fleeting 
>WHERE file.name != "Fleeting_Note_Template"
>SORT file.name ASC
>```
