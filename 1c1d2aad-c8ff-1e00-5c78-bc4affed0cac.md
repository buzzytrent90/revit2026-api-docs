

Revit 2026 API

# MEPBuildingConstructionSetIterator Class  
  
---  
  
An iterator to a MEPBuildingConstruction set.

SystemObject [Autodesk.Revit.DBAPIObject](beb86ef5-39ad-3f0d-0cd9-0c929387a2bb.md) Autodesk.Revit.DB.MechanicalMEPBuildingConstructionSetIterator

**Namespace:** [Autodesk.Revit.DB.Mechanical](0eafd899-5912-56fd-94b1-d286156e26fc.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public abstract class MEPBuildingConstructionSetIterator : APIObject, 
	IEnumerator
```
```vb
Public MustInherit Class MEPBuildingConstructionSetIterator
	Inherits APIObject
	Implements IEnumerator
```
```cpp
public ref class MEPBuildingConstructionSetIterator abstract : public APIObject, 
	IEnumerator
```
```fsharp
[<AbstractClassAttribute>]
type MEPBuildingConstructionSetIterator = 
    class
        inherit APIObject
        interface IEnumerator
    end
```


The MEPBuildingConstructionSetIterator type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [MEPBuildingConstructionSetIterator](e8eed8ad-8cf5-5caa-c6a8-33159d8e1020.md) | For Internal Use Only. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Current](0f8ee6bc-ec8b-79a5-f7f3-032b8acb27e7.md) | Retrieves the item that is the current focus of the iterator. |
|  | [IsReadOnly](d516bcd2-a3fd-a578-58f6-f1add979bd07.md) | Identifies if the object is read-only or modifiable.(Inherited from [APIObject](beb86ef5-39ad-3f0d-0cd9-0c929387a2bb.md)) |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Dispose](7c03212a-b587-1c89-3912-efea0d2619c5.md) | Causes the object to release immediately any resources it may be utilizing.(Inherited from [APIObject](beb86ef5-39ad-3f0d-0cd9-0c929387a2bb.md)) |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | [MoveNext](eead9cb8-f9e5-b382-6a92-99091b663cfa.md) | Move the iterator one item forward. |
|  | [Reset](a6246e09-4942-0c4d-a055-d20f16b0fff7.md) | Bring the iterator back to the start of the set. |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
#### Reference

[Autodesk.Revit.DB.Mechanical Namespace](0eafd899-5912-56fd-94b1-d286156e26fc.md)