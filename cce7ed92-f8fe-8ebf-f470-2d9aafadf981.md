

Revit 2026 API

# CeilingGetCeilingGridLines Method  
  
---  
  
Get the geometric representation of the ceiling grid, optionally including the ceiling boundary. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public IList<Curve> GetCeilingGridLines(
	bool includeBoundary
)
```
```vb
Public Function GetCeilingGridLines ( 
	includeBoundary As Boolean
) As IList(Of Curve)
```
```cpp
public:
IList<Curve^>^ GetCeilingGridLines(
	bool includeBoundary
)
```
```fsharp
member GetCeilingGridLines : 
        includeBoundary : bool -> IList<Curve> 
```


#### Parameters

includeBoundary Boolean
     Include the boundary of the ceiling with the grid lines. 

#### Return Value

IList[Curve](400cc9b6-9ff7-de85-6fd8-c20002209d25.md) The curves representing the ceiling grid, optionally including the ceiling boundary. 

#### Reference

[Ceiling Class](14d7698a-ab61-2211-2315-3ae1434c582c.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)