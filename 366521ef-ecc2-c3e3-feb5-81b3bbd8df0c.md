

Revit 2026 API

# ParameterValue Class  
  
---  
  
A class that holds a value of a parameter element. 

SystemObject Autodesk.Revit.DBParameterValue More

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class ParameterValue : IDisposable
```
```vb
Public Class ParameterValue
	Implements IDisposable
```
```cpp
public ref class ParameterValue : IDisposable
```
```fsharp
type ParameterValue = 
    class
        interface IDisposable
    end
```


The ParameterValue type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [IsValidObject](b3c38be8-8464-b650-b352-a917a4c13ddd.md) | Specifies whether the .NET object represents a valid Revit entity. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Copy](d2c6a380-8e4f-42fa-f698-77181259b347.md) | Makes an identical copy of the given parameter value. |
|  | [Dispose](8df3f1e5-ef6e-810e-61d2-bc383fc7fb69.md) | Releases all resources used by the ParameterValue |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | [IsEqual](561e8901-0ee7-2ff8-5ffa-d0397ca0b3c0.md) | Tests equality with another instance of the same class. |
|  | [IsSameType](b6d6c24a-28f4-f449-29ed-efba259c7054.md) | Tests another instance is of the same value type. |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
This is a non-instantiable base class. Classes that actually store a value of a certain type are all derived from this base class, once class per each value type. 

#### Reference

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)

SystemObject Autodesk.Revit.DBParameterValue [Autodesk.Revit.DBDoubleParameterValue](561ef32b-c3bc-3847-ef2a-27f4a011e650.md) [Autodesk.Revit.DBElementIdParameterValue](7de25c99-4f85-ef1d-7f64-74092f963c98.md) [Autodesk.Revit.DBIntegerParameterValue](14c16038-74bf-205b-ac93-6ffa6274c034.md) [Autodesk.Revit.DBNullParameterValue](fe10010f-e127-7248-1f17-8c1ee0d41ea0.md) [Autodesk.Revit.DBStringParameterValue](2f79fff4-9773-471a-83f8-5636459bdbe5.md)