

Revit 2026 API

# MassLevelDataIsEmpty Method  
  
---  
  
Indicates if the MassLevelData (Mass Floor) has a geometrical representation. May not if the level does not intersect the mass geometry. 

**Namespace:** [Autodesk.Revit.DB.Analysis](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public bool IsEmpty()
```
```vb
Public Function IsEmpty As Boolean
```
```cpp
public:
bool IsEmpty()
```
```fsharp
member IsEmpty : unit -> bool 
```


#### Return Value

Boolean Returns True if MassLevelData is dimensionless, False otherwise. 

#### Reference

[MassLevelData Class](c1e62aaf-b7af-ad0c-60d5-4a1a9c1bed79.md)

[Autodesk.Revit.DB.Analysis Namespace](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)