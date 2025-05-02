

Revit 2026 API

# GroupTypeGetAvailableAttachedDetailGroupTypeIds Method  
  
---  
  
Returns the attached detail groups available for this element group type. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public ISet<ElementId> GetAvailableAttachedDetailGroupTypeIds()
```
```vb
Public Function GetAvailableAttachedDetailGroupTypeIds As ISet(Of ElementId)
```
```cpp
public:
ISet<ElementId^>^ GetAvailableAttachedDetailGroupTypeIds()
```
```fsharp
member GetAvailableAttachedDetailGroupTypeIds : unit -> ISet<ElementId> 
```


#### Return Value

ISet[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md) Returns the collection of attached detail group Ids that match this group's type. 

#### Reference

[GroupType Class](5ce7e921-2a43-d7f1-8ef9-8a397dd27b75.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)