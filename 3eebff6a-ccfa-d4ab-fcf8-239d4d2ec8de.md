

Revit 2026 API

# FloorGetDefaultFloorType Method  
  
---  
  
Returns id of default floor type. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static ElementId GetDefaultFloorType(
	Document document,
	bool isFoundation
)
```
```vb
Public Shared Function GetDefaultFloorType ( 
	document As Document,
	isFoundation As Boolean
) As ElementId
```
```cpp
public:
static ElementId^ GetDefaultFloorType(
	Document^ document, 
	bool isFoundation
)
```
```fsharp
static member GetDefaultFloorType : 
        document : Document * 
        isFoundation : bool -> ElementId 
```


#### Parameters

document [Document](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)
     The document. 
isFoundation Boolean
     True to return id of foundation floor type. 

#### Return Value

[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
#### Reference

[Floor Class](96cc6685-003d-ff90-1c5b-c25a4830f0f7.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)