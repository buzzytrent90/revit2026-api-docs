

Revit 2026 API

# RebarSpliceTypeUtilsSetLapLengthMultiplier Method  
  
---  
  
Sets the lap length multiplier value. 

**Namespace:** [Autodesk.Revit.DB.Structure](d586b341-f687-9d90-e96d-255806b7d4fc.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static void SetLapLengthMultiplier(
	Document document,
	ElementId rebarSpliceTypeId,
	double lapLengthMultiplier
)
```
```vb
Public Shared Sub SetLapLengthMultiplier ( 
	document As Document,
	rebarSpliceTypeId As ElementId,
	lapLengthMultiplier As Double
)
```
```cpp
public:
static void SetLapLengthMultiplier(
	Document^ document, 
	ElementId^ rebarSpliceTypeId, 
	double lapLengthMultiplier
)
```
```fsharp
static member SetLapLengthMultiplier : 
        document : Document * 
        rebarSpliceTypeId : ElementId * 
        lapLengthMultiplier : float -> unit 
```


#### Parameters

document [Document](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)
     The document. 
rebarSpliceTypeId [ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)
     The Rebar Splice Type id. 
lapLengthMultiplier Double
     The lap length multiplier value. 

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | The rebarSpliceTypeId doesn't represent a valid Rebar Splice Type. It should be an ElementType of BuiltInCategory.OST_RebarSpliceType category. |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
| [ArgumentOutOfRangeException](60f148c9-ece0-a6bb-4e12-bb4a9c8c8a24.md) | The given value for lapLengthMultiplier must be non-negative. |
  
#### Reference

[RebarSpliceTypeUtils Class](98b9e51e-cd97-954d-4a31-a5189696b27e.md)

[Autodesk.Revit.DB.Structure Namespace](d586b341-f687-9d90-e96d-255806b7d4fc.md)