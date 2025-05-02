

Revit 2026 API

# ViewShapeBuilderAddCurve Method  
  
---  
  
Add a curve to the GRep associated to this ViewShapeBuilder. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public void AddCurve(
	Curve GCurve
)
```
```vb
Public Sub AddCurve ( 
	GCurve As Curve
)
```
```cpp
public:
void AddCurve(
	Curve^ GCurve
)
```
```fsharp
member AddCurve : 
        GCurve : Curve -> unit 
```


#### Parameters

GCurve [Curve](400cc9b6-9ff7-de85-6fd8-c20002209d25.md)
     The curve to be added. 

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | GCurve is not acceptable for view-specific shape representation that is currently being built. |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
#### Reference

[ViewShapeBuilder Class](f99edd24-4519-56d5-a5d6-aa1565a893af.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)