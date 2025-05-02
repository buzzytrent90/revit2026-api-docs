

Revit 2026 API

# InitialWattageIntensityEfficacy Property  
  
---  
  
The efficacy value. 

**Namespace:** [Autodesk.Revit.DB.Lighting](a6a04f07-7fd2-0a4e-12e7-01842ee6daaf.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public double Efficacy { get; set; }
```
```vb
Public Property Efficacy As Double
	Get
	Set
```
```cpp
public:
property double Efficacy {
	double get ();
	void set (double value);
}
```
```fsharp
member Efficacy : float with get, set
```


#### Property Value

Double The efficacy value in lm/W as a numerical value greater than 0.0 and less than 1.0e+10. 

| Exception | Condition |
| --- | --- |
| [ArgumentOutOfRangeException](60f148c9-ece0-a6bb-4e12-bb4a9c8c8a24.md) | When setting this property: The efficacy value is not valid because it is not between 0 and 1e+30. |
  
#### Reference

[InitialWattageIntensity Class](2bcbaf81-375c-2732-d67a-563d8302cd1e.md)

[Autodesk.Revit.DB.Lighting Namespace](a6a04f07-7fd2-0a4e-12e7-01842ee6daaf.md)