---
title: Tasks Object (Project)
ms.prod: PROJECTSERVER
ms.assetid: b7482b5a-7fac-531e-6793-610faca2f954
---


# Tasks Object (Project)

Contains a collection of  **[Task](task-object-project.md)** objects.


## Example

 **Using the Task Object**

Use  **Tasks** ( _Index_ ), where _Index_ is the task index number or task name, to return a single **Task** object. The following example prints the names of every resource assigned to every task in the active project.




```
Dim Temp As Long, A As Assignment 

Dim TaskName As String, Assigned As String, Results As String 

 

For Temp = 1 To ActiveProject.Tasks.Count 

 TaskName = "Task: " &amp; ActiveProject.Tasks(Temp).Name &amp; vbCrLf 

 For Each A In ActiveProject.Tasks(Temp).Assignments 

 Assigned = A.ResourceName &amp; ListSeparator &amp; " " &amp; Assigned 

 Next A 

 Results = Results &amp; TaskName &amp; "Resources: " &amp; _ 

 Left$(Assigned, Len(Assigned) - Len(ListSeparator &amp; " ")) &amp; vbCrLf &amp; vbCrLf 

 TaskName = "" 

 Assigned = "" 

Next Temp 

 

MsgBox Results
```

Use the  **[Tasks](http://msdn.microsoft.com/library/selection-tasks-property-project%28Office.15%29.aspx)** property to return a **Tasks** collection. The following example displays the name of every task in the selection.




```
Dim T As Task, Names As String 

 

For Each T In ActiveSelection.Tasks 

 Names = Names &amp; T.Name &amp; vbCrLf 

Next T 

 

MsgBox Names
```

Use the  **[Add](http://msdn.microsoft.com/library/tasks-add-method-project%28Office.15%29.aspx)** method to add a **Task** object to the **Tasks** collection. The following example adds a new task to the end of the task list.




```
ActiveProject.Tasks.Add "Hang clocks"
```


## Methods



|**Name**|
|:-----|
|[Add](http://msdn.microsoft.com/library/tasks-add-method-project%28Office.15%29.aspx)|

## Properties



|**Name**|
|:-----|
|[Application](http://msdn.microsoft.com/library/tasks-application-property-project%28Office.15%29.aspx)|
|[Count](http://msdn.microsoft.com/library/tasks-count-property-project%28Office.15%29.aspx)|
|[Item](http://msdn.microsoft.com/library/tasks-item-property-project%28Office.15%29.aspx)|
|[Parent](http://msdn.microsoft.com/library/tasks-parent-property-project%28Office.15%29.aspx)|
|[UniqueID](http://msdn.microsoft.com/library/tasks-uniqueid-property-project%28Office.15%29.aspx)|

## See also


#### Other resources


[Project Object Model](http://msdn.microsoft.com/library/project-object-model%28Office.15%29.aspx)
