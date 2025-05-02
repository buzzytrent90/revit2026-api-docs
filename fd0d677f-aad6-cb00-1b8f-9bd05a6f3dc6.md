

Revit 2026 API

# RebarShapeDefinitionBySegmentsMajorSegmentIndex Property  
  
---  
  
Index of a segment that can be considered the most important. Revit attempts to preserve the orientation of this segment when a Rebar instance changes its RebarShape to one with a different number of segments. 

**Namespace:** [Autodesk.Revit.DB.Structure](d586b341-f687-9d90-e96d-255806b7d4fc.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public int MajorSegmentIndex { get; set; }
```
```vb
Public Property MajorSegmentIndex As Integer
	Get
	Set
```
```cpp
public:
property int MajorSegmentIndex {
	int get ();
	void set (int value);
}
```
```fsharp
member MajorSegmentIndex : int with get, set
```


#### Property Value

Int32

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | When setting this property: majorSegmentIndex is not between 0 and NumberOfSegments. |
  
#### Reference

[RebarShapeDefinitionBySegments Class](7229fdba-1e8f-6cb7-e72e-0933e495ad62.md)

[Autodesk.Revit.DB.Structure Namespace](d586b341-f687-9d90-e96d-255806b7d4fc.md)