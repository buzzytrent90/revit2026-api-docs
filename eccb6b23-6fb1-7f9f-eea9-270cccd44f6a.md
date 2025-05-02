

Revit 2026 API

# AnalysisDisplayMarkersAndTextSettingsMarkerSize Property  
  
---  
  
Size of marker. 

**Namespace:** [Autodesk.Revit.DB.Analysis](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public double MarkerSize { get; set; }
```
```vb
Public Property MarkerSize As Double
	Get
	Set
```
```cpp
public:
property double MarkerSize {
	double get ();
	void set (double value);
}
```
```fsharp
member MarkerSize : float with get, set
```


#### Property Value

Double

| Exception | Condition |
| --- | --- |
| [ArgumentsInconsistentException](05972c68-fa6d-3a83-d720-ad84fbc4780f.md) | When setting this property: markerSize is negative |
  
#### Reference

[AnalysisDisplayMarkersAndTextSettings Class](bb940def-7483-32c6-01cb-1c79e6666290.md)

[Autodesk.Revit.DB.Analysis Namespace](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)