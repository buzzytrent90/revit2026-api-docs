

Revit 2026 API

# CompoundStructureIsValidSegmentId Method  
  
---  
  
Determines whether the specified integer is actually the id of a segment in this CompoundStructure. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public bool IsValidSegmentId(
	int segmentId
)
```
```vb
Public Function IsValidSegmentId ( 
	segmentId As Integer
) As Boolean
```
```cpp
public:
bool IsValidSegmentId(
	int segmentId
)
```
```fsharp
member IsValidSegmentId : 
        segmentId : int -> bool 
```


#### Parameters

segmentId Int32
     The id of a segment in this CompoundStructure. 

#### Return Value

Boolean True if the specified segment is valid, false otherwise. 

| Exception | Condition |
| --- | --- |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | This operation is valid only for vertically compound structures. |
  
#### Reference

[CompoundStructure Class](dc1a081e-8dab-565f-145d-a429098d353c.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)