

Revit 2026 API

# SpecUtilsIsSpec Method  
  
---  
  
Checks whether a ForgeTypeId identifies a spec. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static bool IsSpec(
	ForgeTypeId specTypeId
)
```
```vb
Public Shared Function IsSpec ( 
	specTypeId As ForgeTypeId
) As Boolean
```
```cpp
public:
static bool IsSpec(
	ForgeTypeId^ specTypeId
)
```
```fsharp
static member IsSpec : 
        specTypeId : ForgeTypeId -> bool 
```


#### Parameters

specTypeId [ForgeTypeId](d9fcf276-9566-de83-2b0b-d89b65ccc8af.md)
     The identifier to check. 

#### Return Value

Boolean True if the ForgeTypeId identifies a spec, false otherwise. 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
#### Reference

[SpecUtils Class](21c660df-947f-4aa4-29f0-f3cd78f62d6c.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)