

Revit 2026 API

# DocumentSetDefaultElementTypeId Method  
  
---  
  
Sets the default element type id of the given DefaultElementType id. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public void SetDefaultElementTypeId(
	ElementTypeGroup defaultTypeId,
	ElementId typeId
)
```
```vb
Public Sub SetDefaultElementTypeId ( 
	defaultTypeId As ElementTypeGroup,
	typeId As ElementId
)
```
```cpp
public:
void SetDefaultElementTypeId(
	ElementTypeGroup defaultTypeId, 
	ElementId^ typeId
)
```
```fsharp
member SetDefaultElementTypeId : 
        defaultTypeId : ElementTypeGroup * 
        typeId : ElementId -> unit 
```


#### Parameters

defaultTypeId [ElementTypeGroup](f5b57d98-c551-9693-9009-8eb17fef8a14.md)
     The default element type id. 
typeId [ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)
     The element type id. 

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | The element type id typeId is invalid for the give DefaultElementType id defaultTypeId. |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
| [ArgumentOutOfRangeException](60f148c9-ece0-a6bb-4e12-bb4a9c8c8a24.md) | A value passed for an enumeration argument is not a member of that enumeration |
  
#### Reference

[Document Class](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)