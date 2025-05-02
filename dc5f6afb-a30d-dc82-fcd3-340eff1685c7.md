

Revit 2026 API

# CombinableElementArray Class  
  
---  
  
An array that contains CombinableElement objects.

SystemObject [Autodesk.Revit.DBAPIObject](beb86ef5-39ad-3f0d-0cd9-0c929387a2bb.md) Autodesk.Revit.DBCombinableElementArray

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class CombinableElementArray : APIObject, 
	IEnumerable
```
```vb
Public Class CombinableElementArray
	Inherits APIObject
	Implements IEnumerable
```
```cpp
public ref class CombinableElementArray : public APIObject, 
	IEnumerable
```
```fsharp
type CombinableElementArray = 
    class
        inherit APIObject
        interface IEnumerable
    end
```


The CombinableElementArray type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [CombinableElementArray](4aaefe03-1efa-1a7c-a043-340cec1097bf.md) | Initializes a new instance of the CombinableElementArray class |
  
|  | Name | Description |
| --- | --- | --- |
|  | [IsEmpty](2d4e7268-af37-4771-ba49-34d7c90ae39f.md) | Test to see if the array is empty. |
|  | [IsReadOnly](d516bcd2-a3fd-a578-58f6-f1add979bd07.md) | Identifies if the object is read-only or modifiable.(Inherited from [APIObject](beb86ef5-39ad-3f0d-0cd9-0c929387a2bb.md)) |
|  | [Item](5a1fd0a8-c11d-ee5a-d2c1-c31d3cb0e160.md) | Gets or sets a CombinableElement at a specified index within the array. |
|  | [Size](3e89356a-f974-728b-9e94-ac267b7c2d76.md) | Returns the number of CombinableElements that are in the array. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Append](8b82eaa7-102a-2839-d602-ccd81df40a40.md) | Add the element to the end of the array. |
|  | [Clear](f21fff3a-7a61-915d-037e-ea6fd6fbd53f.md) | Removes every CombinableElement from the array, rendering it empty. |
|  | [Dispose](7c03212a-b587-1c89-3912-efea0d2619c5.md) | Causes the object to release immediately any resources it may be utilizing.(Inherited from [APIObject](beb86ef5-39ad-3f0d-0cd9-0c929387a2bb.md)) |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | [ForwardIterator](1b12b26e-d988-4115-c2b7-eb7a582a8dbe.md) | Retrieve a forward moving iterator to the array. |
|  | [GetEnumerator](7ec1dc27-5043-9807-a0a1-c2ee1eb79e3f.md) | Retrieve a forward moving iterator to the array. |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | [Insert](e14202d8-9f3e-04d3-3bd8-9b38fdcdda2f.md) | Insert the specified element into the array. |
|  | [ReverseIterator](ee2becce-dc57-383c-620c-26c9f5d6c379.md) | Retrieve a backward moving iterator to the array. |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
#### Reference

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)