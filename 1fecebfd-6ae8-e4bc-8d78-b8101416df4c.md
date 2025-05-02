

Revit 2026 API

# VertexPositionNormalColoredSetColor Method  
  
---  
  
Sets the vertex's color. 

**Namespace:** [Autodesk.Revit.DB.DirectContext3D](f4ba10f0-55ea-5344-173b-688405391794.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public void SetColor(
	ColorWithTransparency color
)
```
```vb
Public Sub SetColor ( 
	color As ColorWithTransparency
)
```
```cpp
public:
void SetColor(
	ColorWithTransparency^ color
)
```
```fsharp
member SetColor : 
        color : ColorWithTransparency -> unit 
```


#### Parameters

color [ColorWithTransparency](b68f80e1-5ea0-a485-ec3e-7dd077043230.md)
     The vertex's color. 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
#### Reference

[VertexPositionNormalColored Class](aa354e03-2b25-b5a4-5634-c3518518c0d3.md)

[Autodesk.Revit.DB.DirectContext3D Namespace](f4ba10f0-55ea-5344-173b-688405391794.md)