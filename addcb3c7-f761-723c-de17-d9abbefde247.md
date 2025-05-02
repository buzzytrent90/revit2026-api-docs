

Revit 2026 API

# EditScopeIsPermitted Property  
  
---  
  
Tells if the edit scope is permitted to start. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public bool IsPermitted { get; }
```
```vb
Public ReadOnly Property IsPermitted As Boolean
	Get
```
```cpp
public:
property bool IsPermitted {
	bool get ();
}
```
```fsharp
member IsPermitted : bool with get
```


#### Property Value

Boolean

The edit scope is not permitted to start for one of the following possible reasons: The document is in read-only state, or the document is currently modifiable, or there already is another edit mode active in the document. 

#### Reference

[EditScope Class](bac11282-3a3b-953e-8bc4-960c62da4946.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)