

Revit 2026 API

# AnalysisDisplayDiagramSettingsRounding Property  
  
---  
  
Increment to which numeric values of analysis results are rounded in diagram. 

**Namespace:** [Autodesk.Revit.DB.Analysis](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public double Rounding { get; set; }
```
```vb
Public Property Rounding As Double
	Get
	Set
```
```cpp
public:
property double Rounding {
	double get ();
	void set (double value);
}
```
```fsharp
member Rounding : float with get, set
```


#### Property Value

Double

| Exception | Condition |
| --- | --- |
| [ArgumentsInconsistentException](05972c68-fa6d-3a83-d720-ad84fbc4780f.md) | When setting this property: rounding is not positive |
  
#### Reference

[AnalysisDisplayDiagramSettings Class](57e0c5ff-555c-7345-ac24-3592207a4d70.md)

[Autodesk.Revit.DB.Analysis Namespace](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)