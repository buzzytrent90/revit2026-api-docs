

Revit 2026 API

# HVACLoadSpaceTypeCreate Method  
  
---  
  
Creates a space type. 

**Namespace:** [Autodesk.Revit.DB.Analysis](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static HVACLoadSpaceType Create(
	Document document,
	string name
)
```
```vb
Public Shared Function Create ( 
	document As Document,
	name As String
) As HVACLoadSpaceType
```
```cpp
public:
static HVACLoadSpaceType^ Create(
	Document^ document, 
	String^ name
)
```
```fsharp
static member Create : 
        document : Document * 
        name : string -> HVACLoadSpaceType 
```


#### Parameters

document [Document](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)
     The document. 
name String
     The space type name. 

#### Return Value

[HVACLoadSpaceType](0fcf26fe-8542-3dc7-b9e8-8c89eda1a48d.md) The new space type. 

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | name is an empty string or contains only whitespace. -or- name cannot include prohibited characters, such as "{, }, [, ], | , ;, less-than sign, greater-than sign, ?, `, ~". -or- The given value for name is already in use as a space type name. |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
#### Reference

[HVACLoadSpaceType Class](0fcf26fe-8542-3dc7-b9e8-8c89eda1a48d.md)

[Autodesk.Revit.DB.Analysis Namespace](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)