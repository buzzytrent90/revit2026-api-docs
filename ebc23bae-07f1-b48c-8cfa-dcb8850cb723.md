

Revit 2026 API

# CompoundStructureMergeRegionsAdjacentToSegment Method  
  
---  
  
Merges the two regions which share the specified segment. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public int MergeRegionsAdjacentToSegment(
	int segmentId,
	int layerIdxForMergedRegion
)
```
```vb
Public Function MergeRegionsAdjacentToSegment ( 
	segmentId As Integer,
	layerIdxForMergedRegion As Integer
) As Integer
```
```cpp
public:
int MergeRegionsAdjacentToSegment(
	int segmentId, 
	int layerIdxForMergedRegion
)
```
```fsharp
member MergeRegionsAdjacentToSegment : 
        segmentId : int * 
        layerIdxForMergedRegion : int -> int 
```


#### Parameters

segmentId Int32
     The id of a segment in the underlying grid. 
layerIdxForMergedRegion Int32
     The index of the layer to which the resulting region will be associated. 

#### Return Value

Int32 The id of the resulting region. If -1 is returned, then the operation would have produced an invalid region and was not performed. 

| Exception | Condition |
| --- | --- |
| [ArgumentOutOfRangeException](60f148c9-ece0-a6bb-4e12-bb4a9c8c8a24.md) | The layer index is out of range. |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | Split and merge regions operations can be used only for vertically compound structures without variable thickness layers. -or- The segment is not shared by adjacent regions. |
  
#### Reference

[CompoundStructure Class](dc1a081e-8dab-565f-145d-a429098d353c.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)