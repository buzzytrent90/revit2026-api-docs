

Revit 2026 API

# GlobalParametersManagerFindByName Method  
  
---  
  
Finds whether a global parameter with the given name exists in the input document. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static ElementId FindByName(
	Document document,
	string name
)
```
```vb
Public Shared Function FindByName ( 
	document As Document,
	name As String
) As ElementId
```
```cpp
public:
static ElementId^ FindByName(
	Document^ document, 
	String^ name
)
```
```fsharp
static member FindByName : 
        document : Document * 
        name : string -> ElementId 
```


#### Parameters

document [Document](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)
     The document expected to contain the global parameter. 
name String
     Name of the global parameter 

#### Return Value

[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md) ElementId of the parameter element, or InvalidElementId if it was not found. 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
No exception is thrown when no parameter with such a name exists in the document; instead, the method returns an ElementId.InvalidElementId. 

#### Reference

[GlobalParametersManager Class](f3af05ec-1f0c-fe86-6708-0a211a40bcda.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)