

Revit 2026 API

# ElectricalLoadClassificationDemandFactorId Property  
  
---  
  
The demand factor definition this load classification element uses. 

**Namespace:** [Autodesk.Revit.DB.Electrical](212a1314-7843-2c6c-3322-363127e4059f.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public ElementId DemandFactorId { get; set; }
```
```vb
Public Property DemandFactorId As ElementId
	Get
	Set
```
```cpp
public:
property ElementId^ DemandFactorId {
	ElementId^ get ();
	void set (ElementId^ value);
}
```
```fsharp
member DemandFactorId : ElementId with get, set
```


#### Property Value

[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | When setting this property: The element id elemId is not a valid ElectricalDemandFactorDefinition element. |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | When setting this property: A non-optional argument was null |
  
#### Reference

[ElectricalLoadClassification Class](c8aeb888-f4dd-4b93-063e-6aa118c0e471.md)

[Autodesk.Revit.DB.Electrical Namespace](212a1314-7843-2c6c-3322-363127e4059f.md)