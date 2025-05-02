

Revit 2026 API

# ViewDisplayDepthCueing Class  
  
---  
  
Represents the settings for depth cueing. 

SystemObject Autodesk.Revit.DBViewDisplayDepthCueing

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class ViewDisplayDepthCueing : IDisposable
```
```vb
Public Class ViewDisplayDepthCueing
	Implements IDisposable
```
```cpp
public ref class ViewDisplayDepthCueing : IDisposable
```
```fsharp
type ViewDisplayDepthCueing = 
    class
        interface IDisposable
    end
```


The ViewDisplayDepthCueing type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [EnableDepthCueing](4acfa60c-73f0-bc89-8f3e-f45a62d688d3.md) | True to enable depth cueing. False to disable it. |
|  | [EndPercentage](8b120fe1-09ab-d546-9eeb-71a3ddc6bc81.md) | The end percentage defines where depth cueing ends. Values between 0 and 100. |
|  | [FadeTo](9e113d92-3414-68ff-e0eb-61d934bb7110.md) | The fade to defines the maximum fading in per cent. Values between 0 and 100. |
|  | [IsValidObject](63284a76-88ca-cc3d-ebdc-762d472753ef.md) | Specifies whether the .NET object represents a valid Revit entity. |
|  | [StartPercentage](0aa4039d-4d7d-fc7c-224e-b09a3b853980.md) | The start percentage defines where depth cueing starts. Values between 0 and 100. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Dispose](aac6a985-6d34-45db-0b1e-6a01140306c7.md) | Releases all resources used by the ViewDisplayDepthCueing |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | [SetStartEndPercentages](031e725f-2572-ec64-b3dd-810dba3f5188.md) | Sets start and end percentages. |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
#### Reference

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)