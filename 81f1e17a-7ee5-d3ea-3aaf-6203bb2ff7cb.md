

Revit 2026 API

# BendingDetailCustomFieldPropertiesDiameterDimensionTypeId Property  
  
---  
  
Identifies the Id of the diameter dimension type which is used to show dimensions. 

**Namespace:** [Autodesk.Revit.DB.Structure](d586b341-f687-9d90-e96d-255806b7d4fc.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public ElementId DiameterDimensionTypeId { get; set; }
```
```vb
Public Property DiameterDimensionTypeId As ElementId
	Get
	Set
```
```cpp
public:
property ElementId^ DiameterDimensionTypeId {
	ElementId^ get ();
	void set (ElementId^ value);
}
```
```fsharp
member DiameterDimensionTypeId : ElementId with get, set
```


#### Property Value

[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | When setting this property: The diameterDimensionTypeId should be an id of a diameter dimension type. |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | When setting this property: A non-optional argument was null |
  
#### Reference

[BendingDetailCustomFieldProperties Class](fca17725-1925-31a4-1a9b-c773c4329e46.md)

[Autodesk.Revit.DB.Structure Namespace](d586b341-f687-9d90-e96d-255806b7d4fc.md)