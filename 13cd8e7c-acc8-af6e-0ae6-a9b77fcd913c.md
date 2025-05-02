

Revit 2026 API

# FieldBuilder Class  
  
---  
  
This class is used to create Fields in the Extensible Storage framework. 

SystemObject Autodesk.Revit.DB.ExtensibleStorageFieldBuilder

**Namespace:** [Autodesk.Revit.DB.ExtensibleStorage](79486a74-376c-9555-c873-45d5a750f051.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class FieldBuilder : IDisposable
```
```vb
Public Class FieldBuilder
	Implements IDisposable
```
```cpp
public ref class FieldBuilder : IDisposable
```
```fsharp
type FieldBuilder = 
    class
        interface IDisposable
    end
```


The FieldBuilder type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [FieldBuilder(FieldBuilder)](ee0ee042-7252-3e7c-88e8-e0d12709497c.md) | Constructs a new copy of the input ESFieldBuilder object. |
|  | [FieldBuilder(Field, SchemaBuilder)](933ec291-d085-aed9-8a97-ddd5156d74e2.md) | Constructs a new FieldBuilder using the field and associated SchemaBuilder object. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [IsValidObject](b749ab6a-805c-598f-680c-7a6befc14512.md) | Specifies whether the .NET object represents a valid Revit entity. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Dispose](04868aec-2b5b-1d9e-39ae-d534deb885f7.md) | Releases all resources used by the FieldBuilder |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | [NeedsSubSchemaGUID](a528302b-2597-d7e2-4282-71c23eeba4d9.md) | Checks whether the SubSchema GUID needs to be explicitly specified for this field type. |
|  | [NeedsUnits](97243405-0f5b-1465-5e4c-847153e455df.md) | Checks whether the field type requires explicit unit conversions. |
|  | [Ready](f137ea2f-b359-b285-331b-1eb72447015a.md) | Checks whether the builder may be used. |
|  | [SetDocumentation](d50b90de-a117-f069-6bff-dbf10520b1e2.md) | Sets the documentation string for the Field. |
|  | [SetSpec](d801562b-ca4b-740f-07ed-7aa2ac336174.md) | Sets the spec describing the field's values. |
|  | [SetSubSchemaGUID](bac5b4c3-e3b5-a06c-c94c-4a72e074a653.md) | Sets the GUID of the Schema of the Entities that are intended to be stored in this field. |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
#### Reference

[Autodesk.Revit.DB.ExtensibleStorage Namespace](79486a74-376c-9555-c873-45d5a750f051.md)