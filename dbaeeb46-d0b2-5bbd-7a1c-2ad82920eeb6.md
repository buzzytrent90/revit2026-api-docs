

Revit 2026 API

# PointRelativeToPoint Class  
  
---  
  
Represents a point placed relative to another point.

SystemObject [Autodesk.Revit.DBPointElementReference](f1548185-45ba-c1c6-8bde-4f9bb0669026.md) Autodesk.Revit.DBPointRelativeToPoint

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class PointRelativeToPoint : PointElementReference
```
```vb
Public Class PointRelativeToPoint
	Inherits PointElementReference
```
```cpp
public ref class PointRelativeToPoint : public PointElementReference
```
```fsharp
type PointRelativeToPoint = 
    class
        inherit PointElementReference
    end
```


The PointRelativeToPoint type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | [GetHostPointReference](609ac007-f461-f815-2ec1-2c4e14a457ba.md) | Get a copy of the host point reference. |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | [SetHostPointReference](68d232d3-f67f-4c19-79e6-e7ceed0407f2.md) | Change the host point reference. |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
For this release, the only workflow supported is that the point is placed coincident with the referenced host (a relative transformation of Transform.Identity). 

#### Reference

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)