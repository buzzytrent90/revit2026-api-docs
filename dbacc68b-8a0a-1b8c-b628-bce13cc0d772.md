

Revit 2026 API

# TemperatureRatingGetTemperatureRatingIdByName Method  
  
---  
  
Gets the Conductor Temperature Rating id by given Conductor Temperature Rating name. 

**Namespace:** [Autodesk.Revit.DB.Electrical](212a1314-7843-2c6c-3322-363127e4059f.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static ElementId GetTemperatureRatingIdByName(
	Document document,
	string name
)
```
```vb
Public Shared Function GetTemperatureRatingIdByName ( 
	document As Document,
	name As String
) As ElementId
```
```cpp
public:
static ElementId^ GetTemperatureRatingIdByName(
	Document^ document, 
	String^ name
)
```
```fsharp
static member GetTemperatureRatingIdByName : 
        document : Document * 
        name : string -> ElementId 
```


#### Parameters

document [Document](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)
     The document. 
name String
     The Conductor Temperature Rating name. 

#### Return Value

[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md) The Conductor Temperature Rating id. 

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | document is not a project document. -or- name cannot include prohibited characters, such as "{, }, [, ], | , ;, less-than sign, greater-than sign, ?, `, ~". -or- name is an empty string. |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | The document is in failure mode: an operation has failed, and Revit requires the user to either cancel the operation or fix the problem (usually by deleting certain elements). |
  
#### Reference

[TemperatureRating Class](e631810b-d26b-b58e-3e0e-4a413b175305.md)

[Autodesk.Revit.DB.Electrical Namespace](212a1314-7843-2c6c-3322-363127e4059f.md)