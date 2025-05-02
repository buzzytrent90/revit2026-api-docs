

Revit 2026 API

# IndexStreamTriangle Class  
  
---  
  
A stream that can be used to write [IndexTriangle](96cdfb77-c6e0-7866-c1f7-799f3dda0ad5.md) primitives into an [IndexBuffer](186f6b15-38c7-cee7-6163-396cfdea43ee.md)

SystemObject [Autodesk.Revit.DB.DirectContext3DIndexStream](9c300586-7f1f-41db-270b-797d6ad967d8.md) Autodesk.Revit.DB.DirectContext3DIndexStreamTriangle

**Namespace:** [Autodesk.Revit.DB.DirectContext3D](f4ba10f0-55ea-5344-173b-688405391794.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class IndexStreamTriangle : IndexStream
```
```vb
Public Class IndexStreamTriangle
	Inherits IndexStream
```
```cpp
public ref class IndexStreamTriangle : public IndexStream
```
```fsharp
type IndexStreamTriangle = 
    class
        inherit IndexStream
    end
```


The IndexStreamTriangle type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [IsValidObject](ea6dfcb2-87f3-1f91-4ecf-effbfd2fbcb8.md) | Specifies whether the .NET object represents a valid Revit entity. (Inherited from [IndexStream](9c300586-7f1f-41db-270b-797d6ad967d8.md)) |
  
|  | Name | Description |
| --- | --- | --- |
|  | [AddTriangle](59ae57c9-3b92-182d-74c6-7f1ac2ec1cb9.md) | Inserts a [IndexTriangle](96cdfb77-c6e0-7866-c1f7-799f3dda0ad5.md) into the stream and associated buffer. |
|  | [AddTriangles](a0803821-c418-02d0-ec3f-030a77734d9e.md) |  |
|  | [Dispose](1a7b2093-a251-21ae-a225-1a456da5d73b.md) | (Inherited from [IndexStream](9c300586-7f1f-41db-270b-797d6ad967d8.md)) |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
#### Reference

[Autodesk.Revit.DB.DirectContext3D Namespace](f4ba10f0-55ea-5344-173b-688405391794.md)