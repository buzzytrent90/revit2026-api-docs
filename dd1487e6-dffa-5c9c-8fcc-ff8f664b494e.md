

Revit 2026 API

# ViewSheetGetAllRevisionCloudIds Method  
  
---  
  
Gets the ids of the revision clouds which appear on the sheet's revision schedules. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public ISet<ElementId> GetAllRevisionCloudIds()
```
```vb
Public Function GetAllRevisionCloudIds As ISet(Of ElementId)
```
```cpp
public:
ISet<ElementId^>^ GetAllRevisionCloudIds()
```
```fsharp
member GetAllRevisionCloudIds : unit -> ISet<ElementId> 
```


#### Return Value

ISet[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md) The ids of the revisions clouds which appear on the sheet's revision schedules. 

The sheet's revision schedules include the revisions that are associated with revision clouds that are visible on the sheet. Revision schedules may also include revisions that have been additionally added to the sheet via the Revisions On Sheets parameter. Use [GetAdditionalRevisionIds](6d852f22-cf1b-3bcb-c255-184998d1334c.md) to get the additionally added revisions. 

#### Reference

[ViewSheet Class](af2ee879-173d-df3a-9793-8d5750a17b49.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)