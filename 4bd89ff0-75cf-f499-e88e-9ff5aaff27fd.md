

Revit 2026 API

# Transform2DPostScale Method  
  
---  
  
Scales both the linear and translational parts of this transformation and returns the result. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public Transform2D PostScale(
	double scale
)
```
```vb
Public Function PostScale ( 
	scale As Double
) As Transform2D
```
```cpp
public:
Transform2D^ PostScale(
	double scale
)
```
```fsharp
member PostScale : 
        scale : float -> Transform2D 
```


#### Parameters

scale Double
     The scale value. 

#### Return Value

[Transform2D](49a13f08-08d7-95b1-d52e-65f90e6d4061.md) Returns a pointer to "this" [Transform2D](49a13f08-08d7-95b1-d52e-65f90e6d4061.md). 

The resulting transformation is equivalent to the application of this transformation and then the uniform scale, in this order. 

#### Reference

[Transform2D Class](49a13f08-08d7-95b1-d52e-65f90e6d4061.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)