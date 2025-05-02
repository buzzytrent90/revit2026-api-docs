

Revit 2026 API

# AnnotationMultipleAlignmentUtils Class  
  
---  
  
A helper providing functionality related to elements that can be aligned to one another. An element that wants to be able to align to other alignable elements using the Multiple Alignment buttons should implement this helper class. 

SystemObject Autodesk.Revit.DBAnnotationMultipleAlignmentUtils

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class AnnotationMultipleAlignmentUtils : IDisposable
```
```vb
Public Class AnnotationMultipleAlignmentUtils
	Implements IDisposable
```
```cpp
public ref class AnnotationMultipleAlignmentUtils : IDisposable
```
```fsharp
type AnnotationMultipleAlignmentUtils = 
    class
        interface IDisposable
    end
```


The AnnotationMultipleAlignmentUtils type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [IsValidObject](90193bfc-14d5-d50b-4c17-5ae6b69d7df3.md) | Specifies whether the .NET object represents a valid Revit entity. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Dispose](139653a9-5109-4350-f108-7270834cc648.md) | Releases all resources used by the AnnotationMultipleAlignmentUtils |
|  | [ElementSupportsMultiAlign](93240cc0-aed8-6862-6ae6-6b374d1961b8.md) | Returns true if element can be aligned to other similar elements. |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | [GetAnnotationOutlineWithoutLeaders](7685ede1-c115-abbc-ea40-44af7af99c5b.md) | Gets the four corners of the alignable element in model space without its leaders. |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | [MoveWithAnchoredLeaders](286eac71-1fee-7f99-037d-3eef2f1147e4.md) | Moves the element while keeping the leader end points anchored. |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
#### Reference

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)