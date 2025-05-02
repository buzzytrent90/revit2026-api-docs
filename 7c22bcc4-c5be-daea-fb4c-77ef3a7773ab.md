

Revit 2026 API

# ScheduleDefinitionGetField(Int32) Method  
  
---  
  
Gets a field. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public ScheduleField GetField(
	int index
)
```
```vb
Public Function GetField ( 
	index As Integer
) As ScheduleField
```
```cpp
public:
ScheduleField^ GetField(
	int index
)
```
```fsharp
member GetField : 
        index : int -> ScheduleField 
```


#### Parameters

index Int32
     The index of the field. 

#### Return Value

[ScheduleField](3d6b0eb5-ed36-278d-a5df-38b6d600e876.md) The field. 

| Exception | Condition |
| --- | --- |
| [ArgumentOutOfRangeException](60f148c9-ece0-a6bb-4e12-bb4a9c8c8a24.md) | index is not a valid field index in this ScheduleDefinition. |
  
#### Reference

[ScheduleDefinition Class](420696e3-f3ec-1a1d-1205-36a8119d81e5.md)

[GetField Overload](6adf5d49-4644-1c45-7c01-573f061e9562.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)