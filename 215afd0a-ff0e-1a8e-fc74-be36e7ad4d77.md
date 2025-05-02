

Revit 2026 API

# AlignmentStationLabelOptionsStation Property  
  
---  
  
Specifies the station at which the label will be placed, in Revit internal model units (standard Imperial feet). The station determines the location of the label's origin: [Origin](df8b9dc6-9d36-ac2b-04cf-816d88f039b8.md) by setting it to the closest point on the alignment geometry which corresponds to this station. 

**Namespace:** [Autodesk.Revit.DB.Infrastructure](cedea963-42a0-acf8-0f0e-5477c4212ae9.md)**Assembly:** Autodesk.CivilAlignments.DBApplication (in Autodesk.CivilAlignments.DBApplication.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public double Station { get; set; }
```
```vb
Public Property Station As Double
	Get
	Set
```
```cpp
public:
property double Station {
	double get ();
	void set (double value);
}
```
```fsharp
member Station : float with get, set
```


#### Property Value

Double

#### Reference

[AlignmentStationLabelOptions Class](65682466-07b4-766b-a215-fefcdcfd32ce.md)

[Autodesk.Revit.DB.Infrastructure Namespace](cedea963-42a0-acf8-0f0e-5477c4212ae9.md)