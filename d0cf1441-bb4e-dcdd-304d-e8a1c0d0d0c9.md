

Revit 2026 API

# PipeSettingsConnectorTolerance Property  
  
---  
  
The connector tolerance value. 

**Namespace:** [Autodesk.Revit.DB.Plumbing](cc553597-37c2-fcd9-6025-d904c129c80a.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public double ConnectorTolerance { get; set; }
```
```vb
Public Property ConnectorTolerance As Double
	Get
	Set
```
```cpp
public:
property double ConnectorTolerance {
	double get ();
	void set (double value);
}
```
```fsharp
member ConnectorTolerance : float with get, set
```


#### Property Value

Double

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | When setting this property: The given value for dValue is not finite |
  
#### Reference

[PipeSettings Class](2de0109b-0d0d-a0fe-2adf-6edec8bc1a06.md)

[Autodesk.Revit.DB.Plumbing Namespace](cc553597-37c2-fcd9-6025-d904c129c80a.md)