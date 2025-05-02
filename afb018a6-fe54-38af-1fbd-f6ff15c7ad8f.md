

Revit 2026 API

# LoadCaseNatureId Property  
  
---  
  
The nature ID of the load case. 

**Namespace:** [Autodesk.Revit.DB.Structure](d586b341-f687-9d90-e96d-255806b7d4fc.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public ElementId NatureId { get; set; }
```
```vb
Public Property NatureId As ElementId
	Get
	Set
```
```cpp
public:
property ElementId^ NatureId {
	ElementId^ get ();
	void set (ElementId^ value);
}
```
```fsharp
member NatureId : ElementId with get, set
```


#### Property Value

[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | When setting this property: the natureId does not refer to LoadNature element. |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | When setting this property: A non-optional argument was null |
  
#### Reference

[LoadCase Class](2a215599-9c4c-d817-e170-605fd705699d.md)

[Autodesk.Revit.DB.Structure Namespace](d586b341-f687-9d90-e96d-255806b7d4fc.md)