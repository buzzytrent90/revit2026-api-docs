

Revit 2026 API

# CustomExporterExport2DGeometricObjectsIncludingPatternLines Property  
  
---  
  
This flag sets the exporter of 2D views to either include or exclude output of face pattern lines as part of geometric objects when the model is being processed by the export context. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public bool Export2DGeometricObjectsIncludingPatternLines { get; set; }
```
```vb
Public Property Export2DGeometricObjectsIncludingPatternLines As Boolean
	Get
	Set
```
```cpp
public:
property bool Export2DGeometricObjectsIncludingPatternLines {
	bool get ();
	void set (bool value);
}
```
```fsharp
member Export2DGeometricObjectsIncludingPatternLines : bool with get, set
```


#### Property Value

Boolean

This flag is ignored if view has Wireframe display style. This flag is ignored unless property "IncludeGeometricObjects" is set to true. 

#### Reference

[CustomExporter Class](d2437433-9183-cbb1-1c67-dedd86db5b5a.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)