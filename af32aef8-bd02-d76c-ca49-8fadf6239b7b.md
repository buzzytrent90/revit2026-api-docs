

Revit 2026 API

# BuiltInFailuresCuttingFailures Class  
  
---  
  
Failures about Cutting. 

SystemObject Autodesk.Revit.DBBuiltInFailuresCuttingFailures

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static class CuttingFailures
```
```vb
Public NotInheritable Class CuttingFailures
```
```cpp
public ref class CuttingFailures abstract sealed
```
```fsharp
[<AbstractClassAttribute>]
[<SealedAttribute>]
type CuttingFailures = class end
```


The BuiltInFailuresCuttingFailures type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [CannotCopyFromMultipleLinks](17c6e2c0-c863-141e-000c-5f68c34af25d.md) | Elements cannot be copied from multiple links at the same time. |
|  | [ElementsWithNotCopiedParentsDeleted](358dc8fd-50c2-a30d-d065-56929e74f70e.md) | Some elements were deleted because elements that they require for references were not copied. |
|  | [NoFileSaved](186f52f3-2410-9ca9-5926-6226a6ad00a6.md) | No file has been saved. |
|  | [NoSupported2DElementsToCopyFromView](e16ac190-df60-3559-c9e1-dbd6b069958d.md) | None of the elements in the view you have selected are supported for the insert 2D operation. |
|  | [UnableToCopyElementsFromFile](d9b20b41-fdca-4744-37b2-1932bd5825e7.md) | Unable to copy elements from file. |
|  | [UnableToPasteToFile](a321f6d8-bf46-21f6-9b84-83da7db79808.md) | Unable to paste current clipboard contents to file. |
|  | [UnableToReplaceWithLink](e3d9eeb7-f89a-eb2c-ee42-f89835722dd5.md) | Selected elements were copied to new file but Revit was unable to replace them with link to that file. |
  
#### Reference

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)