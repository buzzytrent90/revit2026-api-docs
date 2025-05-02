

Revit 2026 API

# FilledRegionTypeIsValidLineWeight Method  
  
---  
  
Indicates whether the given line weight value is valid. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static bool IsValidLineWeight(
	int lineWeight
)
```
```vb
Public Shared Function IsValidLineWeight ( 
	lineWeight As Integer
) As Boolean
```
```cpp
public:
static bool IsValidLineWeight(
	int lineWeight
)
```
```fsharp
static member IsValidLineWeight : 
        lineWeight : int -> bool 
```


#### Parameters

lineWeight Int32
     The line weight. 

#### Return Value

Boolean True if it is a valid line weight value, false otherwise. 

#### Reference

[FilledRegionType Class](850ae173-379b-bfd6-7295-3950ccc229ca.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)