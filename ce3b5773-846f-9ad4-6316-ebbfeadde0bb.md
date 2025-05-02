

Revit 2026 API

# EdgeGetCurveUV(Int32, Transform2D) Method  
  
---  
  
Calculate and transform a 2D curve that represents the edge in the uv-parameter plane of one of the edge's faces. The output curve's direction will follow the parametric direction of the edge, not the topological direction of the edge on the given face. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public CurveUV GetCurveUV(
	int index,
	Transform2D transform
)
```
```vb
Public Function GetCurveUV ( 
	index As Integer,
	transform As Transform2D
) As CurveUV
```
```cpp
public:
CurveUV^ GetCurveUV(
	int index, 
	Transform2D^ transform
)
```
```fsharp
member GetCurveUV : 
        index : int * 
        transform : Transform2D -> CurveUV 
```


#### Parameters

index Int32
    The index of the face (0 or 1).
transform [Transform2D](49a13f08-08d7-95b1-d52e-65f90e6d4061.md)
    Transformation to apply to the curve.

#### Return Value

[CurveUV](2d1d9c1f-afb6-fc09-f461-54cf0d511bf0.md)If successful, returns the calculated and transformed CurveUV,  otherwise.

| Exception | Condition |
| --- | --- |
| [ArgumentOutOfRangeException](60f148c9-ece0-a6bb-4e12-bb4a9c8c8a24.md) | Thrown when the specified index is not 0 or 1. |
  
Use of this function is preferred over using GetCurveUV(int index) and then transforming the curve, as the latter approach may yield a less accurate result. 

#### Reference

[Edge Class](7155ef49-fcd9-c80a-6232-70189a617bcc.md)

[GetCurveUV Overload](fa95b450-4354-00d7-f02c-f5319086f63f.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)