

Revit 2026 API

# RebarShapeMultiplanarDefinitionOutOfPlaneBendDiameter Property  
  
---  
  
Bend diameter to be applied to the connector segments. 

**Namespace:** [Autodesk.Revit.DB.Structure](d586b341-f687-9d90-e96d-255806b7d4fc.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public double OutOfPlaneBendDiameter { get; set; }
```
```vb
Public Property OutOfPlaneBendDiameter As Double
	Get
	Set
```
```cpp
public:
property double OutOfPlaneBendDiameter {
	double get ();
	void set (double value);
}
```
```fsharp
member OutOfPlaneBendDiameter : float with get, set
```


#### Property Value

Double

| Exception | Condition |
| --- | --- |
| [ArgumentOutOfRangeException](60f148c9-ece0-a6bb-4e12-bb4a9c8c8a24.md) | When setting this property: The given value for outOfPlaneBendDiameter must be greater than 0 and no more than 30000 feet. |
  
#### Reference

[RebarShapeMultiplanarDefinition Class](47a3135c-ce53-c041-f551-0795767eaa41.md)

[Autodesk.Revit.DB.Structure Namespace](d586b341-f687-9d90-e96d-255806b7d4fc.md)