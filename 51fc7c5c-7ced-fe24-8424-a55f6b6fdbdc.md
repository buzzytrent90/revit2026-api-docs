

Revit 2026 API

# DuctSizes Class  
  
---  
  
Class RbsDuctSizes being used to store the duct sizes 

SystemObject Autodesk.Revit.DB.MechanicalDuctSizes

**Namespace:** [Autodesk.Revit.DB.Mechanical](0eafd899-5912-56fd-94b1-d286156e26fc.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class DuctSizes : IEnumerable<MEPSize>, 
	IDisposable
```
```vb
Public Class DuctSizes
	Implements IEnumerable(Of MEPSize), IDisposable
```
```cpp
public ref class DuctSizes : IEnumerable<MEPSize^>, 
	IDisposable
```
```fsharp
type DuctSizes = 
    class
        interface IEnumerable<MEPSize>
        interface IDisposable
    end
```


The DuctSizes type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [Count](e85868ab-9c7d-3db3-3b84-9756a81f1abc.md) | Count of the items contained in the collection. |
|  | [IsValidObject](94be6a69-f822-1d7f-feb9-318061fa765e.md) | Specifies whether the .NET object represents a valid Revit entity. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Contains](5e387d9d-c99a-ac14-30d5-8918a1772585.md) | Checks whether a duct size with the nominal diameter exists. |
|  | [Dispose](c1984717-dba2-91c7-7974-83248a3e58e7.md) | Releases all resources used by the DuctSizes |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | [GetBasicIEnumerator](99e82d00-de56-f5b4-348e-9e0cea6daa46.md) | Returns an enumerator that iterates through a collection. |
|  | [GetDuctSizeIterator](af6c24af-10d9-6ad7-19f9-7bac13bbc9e2.md) | Returns a DuctSizeIterator that iterates through the collection. |
|  | [GetEnumerator](02063365-6e18-677d-cf0d-9241dc01e681.md) | Returns an enumerator that iterates through a collection. |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
#### Reference

[Autodesk.Revit.DB.Mechanical Namespace](0eafd899-5912-56fd-94b1-d286156e26fc.md)