

Revit 2026 API

# RectangleLightShape Class  
  
---  
  
This class encapsulates a rectangle light shape. 

SystemObject [Autodesk.Revit.DB.LightingLightShape](6fc9d0d9-21ac-9192-0178-115be3a48dc7.md) Autodesk.Revit.DB.LightingRectangleLightShape

**Namespace:** [Autodesk.Revit.DB.Lighting](a6a04f07-7fd2-0a4e-12e7-01842ee6daaf.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class RectangleLightShape : LightShape
```
```vb
Public Class RectangleLightShape
	Inherits LightShape
```
```cpp
public ref class RectangleLightShape : public LightShape
```
```fsharp
type RectangleLightShape = 
    class
        inherit LightShape
    end
```


The RectangleLightShape type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [RectangleLightShape](50b10199-177a-28cb-994d-515703bb1007.md) | Creates a rectangle light shape object with 4.0' emit length and a 2.0' emit width. |
|  | [RectangleLightShape(RectangleLightShape)](bdc695a2-882b-4ceb-df16-b1839a1e0db2.md) | Creates a copy of the given rectangle light shape |
|  | [RectangleLightShape(Double, Double)](a22d32f7-0b21-2f3d-c616-9852142859ef.md) | Creates a rectangle light shape object with the given emit length and width. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [EmitLength](40d4b78e-2da0-a0da-7d8d-7aae2a209fed.md) | The emit length. |
|  | [EmitWidth](ae514118-e9c0-ee49-68f6-891a50b42ebd.md) | The emit width. |
|  | [IsValidObject](114aa517-ec9d-25a8-7b03-213d1458ba95.md) | Specifies whether the .NET object represents a valid Revit entity. (Inherited from [LightShape](6fc9d0d9-21ac-9192-0178-115be3a48dc7.md)) |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Clone](189b18d1-2efc-49f7-da12-a157c6a745b6.md) | Creates a copy of the LightShape derived object. (Inherited from [LightShape](6fc9d0d9-21ac-9192-0178-115be3a48dc7.md)) |
|  | [Dispose](342f5f07-befa-c392-35ec-83ad48763628.md) | (Inherited from [LightShape](6fc9d0d9-21ac-9192-0178-115be3a48dc7.md)) |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
#### Reference

[Autodesk.Revit.DB.Lighting Namespace](a6a04f07-7fd2-0a4e-12e7-01842ee6daaf.md)