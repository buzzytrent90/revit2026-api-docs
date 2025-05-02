

Revit 2026 API

# PathReinforcementGetCurveElementIds Method  
  
---  
  
Retrieves the set of ElementIds of curves forming the boundary of the Path Reinforcement. 

**Namespace:** [Autodesk.Revit.DB.Structure](d586b341-f687-9d90-e96d-255806b7d4fc.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public IList<ElementId> GetCurveElementIds()
```
```vb
Public Function GetCurveElementIds As IList(Of ElementId)
```
```cpp
public:
IList<ElementId^>^ GetCurveElementIds()
```
```fsharp
member GetCurveElementIds : unit -> IList<ElementId> 
```


#### Return Value

IList[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md) A collection of ElementIds of ModelCurve elements. 

Each ElementId in the collection is an Id of an Element of type ModelCurve. 

#### Reference

[PathReinforcement Class](1593a849-b883-73d4-7c02-a2522877d71d.md)

[Autodesk.Revit.DB.Structure Namespace](d586b341-f687-9d90-e96d-255806b7d4fc.md)