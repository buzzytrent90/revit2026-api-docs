

Revit 2026 API

# DetailCurveArrayIterator Class  
  
---  
  
An iterator to a array.

SystemObject [Autodesk.Revit.DBAPIObject](beb86ef5-39ad-3f0d-0cd9-0c929387a2bb.md) Autodesk.Revit.DBDetailCurveArrayIterator

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public abstract class DetailCurveArrayIterator : APIObject, 
	IEnumerator
```
```vb
Public MustInherit Class DetailCurveArrayIterator
	Inherits APIObject
	Implements IEnumerator
```
```cpp
public ref class DetailCurveArrayIterator abstract : public APIObject, 
	IEnumerator
```
```fsharp
[<AbstractClassAttribute>]
type DetailCurveArrayIterator = 
    class
        inherit APIObject
        interface IEnumerator
    end
```


The DetailCurveArrayIterator type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [DetailCurveArrayIterator](ba40f774-3c8d-b430-80e9-a03ed219c5c4.md) | For Internal Use Only. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Current](b97affd1-b1dd-00ee-b3fb-bc02c3ba67f7.md) | Retrieves the item that is the current focus of the iterator. |
|  | [IsReadOnly](d516bcd2-a3fd-a578-58f6-f1add979bd07.md) | Identifies if the object is read-only or modifiable.(Inherited from [APIObject](beb86ef5-39ad-3f0d-0cd9-0c929387a2bb.md)) |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Dispose](7c03212a-b587-1c89-3912-efea0d2619c5.md) | Causes the object to release immediately any resources it may be utilizing.(Inherited from [APIObject](beb86ef5-39ad-3f0d-0cd9-0c929387a2bb.md)) |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | [MoveNext](29297560-59a9-d591-dddc-364131fcbeb5.md) | Move the iterator one item forward. |
|  | [Reset](7962ea29-2421-5bbf-f50c-d56480fea5cb.md) | Bring the iterator back to the start of the array. |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
#### Reference

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)