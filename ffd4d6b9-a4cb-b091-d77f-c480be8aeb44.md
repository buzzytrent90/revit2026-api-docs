

Revit 2026 API

# AdvancedLossFactorTemperatureLossFactor Property  
  
---  
  
The temperature loss factor. 

**Namespace:** [Autodesk.Revit.DB.Lighting](a6a04f07-7fd2-0a4e-12e7-01842ee6daaf.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public double TemperatureLossFactor { get; set; }
```
```vb
Public Property TemperatureLossFactor As Double
	Get
	Set
```
```cpp
public:
property double TemperatureLossFactor {
	double get ();
	void set (double value);
}
```
```fsharp
member TemperatureLossFactor : float with get, set
```


#### Property Value

Double The loss factor as a numerical value between 0.0 and 2.0 

| Exception | Condition |
| --- | --- |
| [ArgumentOutOfRangeException](60f148c9-ece0-a6bb-4e12-bb4a9c8c8a24.md) | When setting this property: The loss factor is not valid because it is not between 0.0 and 2.0. |
  
#### Reference

[AdvancedLossFactor Class](30e62a9d-eb01-8830-f897-dc8f32b486da.md)

[Autodesk.Revit.DB.Lighting Namespace](a6a04f07-7fd2-0a4e-12e7-01842ee6daaf.md)