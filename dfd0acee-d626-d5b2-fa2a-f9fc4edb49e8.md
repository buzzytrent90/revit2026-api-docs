

Revit 2026 API

# FilteredElementIdIterator Class  
  
---  
  
An iterator to a set of element ids filtered by the settings of a FilteredElementCollector. 

SystemObject Autodesk.Revit.DBFilteredElementIdIterator

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class FilteredElementIdIterator : IEnumerator<ElementId>
```
```vb
Public Class FilteredElementIdIterator
	Implements IEnumerator(Of ElementId)
```
```cpp
public ref class FilteredElementIdIterator : IEnumerator<ElementId^>
```
```fsharp
type FilteredElementIdIterator = 
    class
        interface IEnumerator<ElementId>
    end
```


The FilteredElementIdIterator type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [Current](d37acf89-a76e-f310-ff9e-056c5857172f.md) | Gets the item at the current position of the iterator. |
|  | [CurrentObject](ca23ad34-a750-7156-f0c1-5295ccf4a582.md) |  |
|  | [IsValidObject](3f6d5b54-979e-fe9f-9a8d-c124fd15c411.md) | Specifies whether the .NET object represents a valid Revit entity. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Dispose](3b640fff-8676-9a8e-d541-083e5b0ddd31.md) | Releases all resources used by the FilteredElementIdIterator |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | [GetCurrent](4622b4be-e533-d633-26e8-2c4ea5d63742.md) | The current element id found by the iterator. |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | [IsDone](d97c9f2b-33a3-128b-fad4-00fba014c1a6.md) | Identifies if the iteration has completed. |
|  | [MoveNext](ef73f3f0-2049-2ebf-fccd-84a2c85949b7.md) | Increments the iterator to the next element id passing the filter. |
|  | [Reset](e478208b-3d1c-9ce1-1592-0faa8462469d.md) | Resets the iterator to the beginning. |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
#### Reference

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)