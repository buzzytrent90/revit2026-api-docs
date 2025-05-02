

Revit 2026 API

# VertexPositionColored Class  
  
---  
  
A geometry vertex specified as a position in space with a color. 

SystemObject [Autodesk.Revit.DB.DirectContext3DVertex](0434973b-559d-a27f-25f9-f6bf6ef4f750.md) Autodesk.Revit.DB.DirectContext3DVertexPositionColored

**Namespace:** [Autodesk.Revit.DB.DirectContext3D](f4ba10f0-55ea-5344-173b-688405391794.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class VertexPositionColored : Vertex
```
```vb
Public Class VertexPositionColored
	Inherits Vertex
```
```cpp
public ref class VertexPositionColored : public Vertex
```
```fsharp
type VertexPositionColored = 
    class
        inherit Vertex
    end
```


The VertexPositionColored type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [VertexPositionColored](75b056bc-5893-d9a8-0fc5-89c52d79cfab.md) | Constructs the vertex from a point and a color. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [IsValidObject](42be4518-ac75-2386-7874-cc2e95f93d39.md) | Specifies whether the .NET object represents a valid Revit entity. (Inherited from [Vertex](0434973b-559d-a27f-25f9-f6bf6ef4f750.md)) |
|  | [Position](22dfd306-606b-4922-d373-4325f1b2e89f.md) | The vertex's position. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Dispose](b008eaa1-66a2-8e56-34e5-82b879047a97.md) | (Inherited from [Vertex](0434973b-559d-a27f-25f9-f6bf6ef4f750.md)) |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | [GetColor](0f6e7ddf-e1f7-42f3-56b5-9979ebf39563.md) | Gets the vertex's color. |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | [GetSizeInFloats](9e13ae0f-ea74-b708-4617-9a62f1cbced0.md) | Gets the amount of storage that the vertex takes up in a buffer, measured in floats. |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | [SetColor](5b90c02e-8b63-cd76-5951-fbb60327a420.md) | Sets the vertex's color. |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
The color of these vertices includes a transparency component In order to render them as transparent they must be rendered in the transparent pass See the 'IsTransparentPass' method of [DrawContext](b9244325-08c8-8bbd-a9f3-5d91d638d85d.md)

#### Reference

[Autodesk.Revit.DB.DirectContext3D Namespace](f4ba10f0-55ea-5344-173b-688405391794.md)