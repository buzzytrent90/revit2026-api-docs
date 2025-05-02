

Revit 2026 API

# ElectricalSystemRating Property  
  
---  
  
The Rating value of the Electrical System. 

**Namespace:** [Autodesk.Revit.DB.Electrical](212a1314-7843-2c6c-3322-363127e4059f.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public double Rating { get; set; }
```
```vb
Public Property Rating As Double
	Get
	Set
```
```cpp
public:
property double Rating {
	double get ();
	void set (double value);
}
```
```fsharp
member Rating : float with get, set
```


#### Property Value

Double

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | When setting this property: The given value for rating is not a number -or- When setting this property: The given value for rating is not finite |
| [ArgumentOutOfRangeException](60f148c9-ece0-a6bb-4e12-bb4a9c8c8a24.md) | When setting this property: The given value for rating must be non-negative. |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | This property only available when System Type is Power! |
  
This property is used to retrieve the Rating value of the Electrical System. 

#### Reference

[ElectricalSystem Class](158b4be3-bbe5-11eb-cccc-788edd3a7590.md)

[Autodesk.Revit.DB.Electrical Namespace](212a1314-7843-2c6c-3322-363127e4059f.md)