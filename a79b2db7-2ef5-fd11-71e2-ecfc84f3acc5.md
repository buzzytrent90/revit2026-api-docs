

Revit 2026 API

# ExternalResourceReferenceHasValidDisplayPath Method  
  
---  
  
Checks whether this external Resource has a valid display path. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public bool HasValidDisplayPath()
```
```vb
Public Function HasValidDisplayPath As Boolean
```
```cpp
public:
bool HasValidDisplayPath()
```
```fsharp
member HasValidDisplayPath : unit -> bool 
```


#### Return Value

Boolean True if the this external Resource has a valid display path. False otherwise. 

For an external resource, such as a Revit link loaded from an external server, the valid display path should be like "My Server://Nested/Nested_1.rvt". For an external resource, such as a Revit link loaded from the "built-in" server, the valid display path should be like "c:\LocalLinks\Link_1.rvt". 

#### Reference

[ExternalResourceReference Class](ffad9c15-8fc9-fbfd-f328-101533f4cf74.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)