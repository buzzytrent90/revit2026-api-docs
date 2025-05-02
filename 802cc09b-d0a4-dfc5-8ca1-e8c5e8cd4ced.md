

Revit 2026 API

# SurfaceProject Method  
  
---  
  
Project a 3D point orthogonally onto a surface (to find the nearest point). Throws InvalidOperationException if the projection fails. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public void Project(
	XYZ point,
	out UV uv,
	out double distance
)
```
```vb
Public Sub Project ( 
	point As XYZ,
	<OutAttribute> ByRef uv As UV,
	<OutAttribute> ByRef distance As Double
)
```
```cpp
public:
void Project(
	XYZ^ point, 
	[OutAttribute] UV^% uv, 
	[OutAttribute] double% distance
)
```
```fsharp
member Project : 
        point : XYZ * 
        uv : UV byref * 
        distance : float byref -> unit 
```


#### Parameters

point [XYZ](c2fd995c-95c0-58fb-f5de-f3246cbc5600.md)
     The point to project. 
uv [UV](1724be37-059b-91ff-aa74-d1508082f76d.md)
     The surface coordinates of the projected point. 
distance Double
     Holds the distance from input point to its projection. 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | The projection failed. |
  
#### Reference

[Surface Class](bb391358-5ca0-578d-e8e2-6d1b30c472d8.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)