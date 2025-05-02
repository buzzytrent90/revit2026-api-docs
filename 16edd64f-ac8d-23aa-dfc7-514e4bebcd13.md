

Revit 2026 API

# CameraInfoFarDistance Property  
  
---  
  
Distance from eye point to far plane of view frustum along the view direction. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public double FarDistance { get; }
```
```vb
Public ReadOnly Property FarDistance As Double
	Get
```
```cpp
public:
property double FarDistance {
	double get ();
}
```
```fsharp
member FarDistance : float with get
```


#### Property Value

Double

This property together with NearDistance determines the depth restrictions of a view frustum. 

#### Reference

[CameraInfo Class](facf52cc-bc82-0008-9e4c-60e6a335ef40.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)