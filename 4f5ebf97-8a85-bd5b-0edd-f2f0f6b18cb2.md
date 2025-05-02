

Revit 2026 API

# DatumPlaneGetLeader Method  
  
---  
  
Gets a copy of the leader applied to the indicated end of the datum plane. This method does not apply to Reference planes (which do not support leaders). 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public Leader GetLeader(
	DatumEnds datumEnd,
	View view
)
```
```vb
Public Function GetLeader ( 
	datumEnd As DatumEnds,
	view As View
) As Leader
```
```cpp
public:
Leader^ GetLeader(
	DatumEnds datumEnd, 
	View^ view
)
```
```fsharp
member GetLeader : 
        datumEnd : DatumEnds * 
        view : View -> Leader 
```


#### Parameters

datumEnd [DatumEnds](60cdd5d4-8c6c-320b-7b8b-1cc4487edd9c.md)
     The end of the datum plane. 
view [View](fb92a4e7-f3a7-ef14-e631-342179b18de9.md)
     The view on which the DatumPlane shows. 

#### Return Value

[Leader](66228564-d8b8-fc81-454c-e175528f7188.md) The Leader of the datum plane. Null will return if no leader applied. 

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | The datum plane cannot be visible in the view. |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
| [ArgumentOutOfRangeException](60f148c9-ece0-a6bb-4e12-bb4a9c8c8a24.md) | A value passed for an enumeration argument is not a member of that enumeration |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | This datum plane has no leaders. |
  
#### Reference

[DatumPlane Class](3e0a6725-ee40-c4d5-839f-b7720c1fe2af.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)