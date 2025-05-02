

Revit 2026 API

# RebarShapeDefinitionBySegmentsGetSegment Method  
  
---  
  
Return a reference to one of the segments in the definition. 

**Namespace:** [Autodesk.Revit.DB.Structure](d586b341-f687-9d90-e96d-255806b7d4fc.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public RebarShapeSegment GetSegment(
	int segmentIndex
)
```
```vb
Public Function GetSegment ( 
	segmentIndex As Integer
) As RebarShapeSegment
```
```cpp
public:
RebarShapeSegment^ GetSegment(
	int segmentIndex
)
```
```fsharp
member GetSegment : 
        segmentIndex : int -> RebarShapeSegment 
```


#### Parameters

segmentIndex Int32
     Index of the segment (0 to NumberOfSegments - 1). 

#### Return Value

[RebarShapeSegment](4fd9ba08-b5a3-39c8-9666-fc0a105615c6.md) The requested segment. 

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | segmentIndex is not between 0 and NumberOfSegments. |
  
#### Reference

[RebarShapeDefinitionBySegments Class](7229fdba-1e8f-6cb7-e72e-0933e495ad62.md)

[Autodesk.Revit.DB.Structure Namespace](d586b341-f687-9d90-e96d-255806b7d4fc.md)