

Revit 2026 API

# LineLightShape Class  
  
---  
  
This class encapsulates a line light shape. 

SystemObject [Autodesk.Revit.DB.LightingLightShape](6fc9d0d9-21ac-9192-0178-115be3a48dc7.md) Autodesk.Revit.DB.LightingLineLightShape

**Namespace:** [Autodesk.Revit.DB.Lighting](a6a04f07-7fd2-0a4e-12e7-01842ee6daaf.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class LineLightShape : LightShape
```
```vb
Public Class LineLightShape
	Inherits LightShape
```
```cpp
public ref class LineLightShape : public LightShape
```
```fsharp
type LineLightShape = 
    class
        inherit LightShape
    end
```


The LineLightShape type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [LineLightShape](266127e4-df48-7068-4bbf-d009d313a005.md) | Creates a line light shape object with 2.0' emit length. |
|  | [LineLightShape(Double)](1fdbec29-e0ca-ed2e-7bac-56b61e96b0a4.md) | Creates a line light shape object with the given emit length. |
|  | [LineLightShape(LineLightShape)](02cb7d90-f274-2bb9-6933-7053e9cab49e.md) | Creates a copy of the given line light shape |
  
|  | Name | Description |
| --- | --- | --- |
|  | [EmitLength](ab565bc6-7ad8-cbdd-cfe3-442f1f344804.md) | The emit length. |
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