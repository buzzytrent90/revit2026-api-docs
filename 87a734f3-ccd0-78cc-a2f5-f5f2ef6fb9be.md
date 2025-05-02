

Revit 2026 API

# TopographySurfaceAssociatedBuildingPadId Property  
  
---  
  
The element id of the building pad which causes this topography surface to be formed. 

**Namespace:** [Autodesk.Revit.DB.Architecture](720f0c58-cb2b-4f13-374a-7348ed0a1cd3.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public ElementId AssociatedBuildingPadId { get; }
```
```vb
Public ReadOnly Property AssociatedBuildingPadId As ElementId
	Get
```
```cpp
public:
property ElementId^ AssociatedBuildingPadId {
	ElementId^ get ();
}
```
```fsharp
member AssociatedBuildingPadId : ElementId with get
```


#### Property Value

[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)

InvalidElementId returned signals that there is no associated building pad. 

#### Reference

[TopographySurface Class](64242f41-69e1-84be-f21b-84783e81364a.md)

[Autodesk.Revit.DB.Architecture Namespace](720f0c58-cb2b-4f13-374a-7348ed0a1cd3.md)