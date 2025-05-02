

Revit 2026 API

# DetailElementOrderUtils Class  
  
---  
  
A utility class that arranges the draw order of the detail elements. 

SystemObject Autodesk.Revit.DBDetailElementOrderUtils

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static class DetailElementOrderUtils
```
```vb
Public NotInheritable Class DetailElementOrderUtils
```
```cpp
public ref class DetailElementOrderUtils abstract sealed
```
```fsharp
[<AbstractClassAttribute>]
[<SealedAttribute>]
type DetailElementOrderUtils = class end
```


The DetailElementOrderUtils type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [AreDetailElements](950de8f3-daa2-1023-eb83-cd0695ebb565.md) |  |
|  | [BringForward(Document, View, ElementId)](3110546a-c758-af2d-d5b1-2d5581f18555.md) | Moves the given detail instance one step closer to the front of all other detail instances in the view. |
|  | [BringForward(Document, View, ICollectionElementId)](fbf91f76-0c21-37dc-c69f-609c85753209.md) |  |
|  | [BringToFront(Document, View, ElementId)](734b7f03-6c46-b4b8-f3ed-c370df205e7b.md) | Places the given detail instance in the front of all other detail instances in the view. |
|  | [BringToFront(Document, View, ICollectionElementId)](b6cec4f5-c4ef-d4c6-cdb8-1e92997e019c.md) |  |
|  | [GetDrawOrderForDetails](686020d6-9ca3-c51f-47fc-a54438e3f608.md) |  |
|  | [IsDetailElement](8c7d0547-19ec-6ee0-5e96-02bbf717c54e.md) | Indicates if the element is a detail element that participates in detail draw ordering in the view. |
|  | [SendBackward(Document, View, ElementId)](9d2f8369-7929-06a9-98c2-cff426963ba2.md) | Moves the given detail instance one step closer to the back of all other detail instances in the view. |
|  | [SendBackward(Document, View, ICollectionElementId)](0d971884-a987-7ca9-6e13-e7c9fe030109.md) |  |
|  | [SendToBack(Document, View, ElementId)](28209b7b-e75e-36d9-f916-d1cdaebe051d.md) | Places the given detail instance behind all detail instances in the view. |
|  | [SendToBack(Document, View, ICollectionElementId)](edd4a515-1f60-c99f-09f5-865be893ea24.md) |  |
  
#### Reference

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)