

Revit 2026 API

# EntitySetFieldType(Field, FieldType) Method  
  
---  
  
Stores the value of the field in the entity. 

**Namespace:** [Autodesk.Revit.DB.ExtensibleStorage](79486a74-376c-9555-c873-45d5a750f051.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public void Set<FieldType>(
	Field field,
	FieldType value
)

```
```vb
Public Sub Set(Of FieldType) ( 
	field As Field,
	value As FieldType
)
```
```cpp
public:
generic<typename FieldType>
void Set(
	Field^ field, 
	FieldType value
)
```
```fsharp
member Set : 
        field : Field * 
        value : 'FieldType -> unit 
```


#### Parameters

field [Field](0aeabd09-5c61-0439-e4c7-e1d68d0e1a3b.md)
     The field to update. 
value FieldType
    

#### Type Parameters

FieldType
     The type of the field 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was NULL |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | The Field belongs to a different Schema from this Entity, or this Entity is invalid. |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | Requested type does not match the field type. |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | For floating-point fields, use the overload taking a ForgeTypeId parameter. |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | This field's subschema prevents writing. |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | Invalid floating-point value. |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | String is too long; exceeds max length of 16mb characters. |
  
The template parameter must match the type of the field (specified when creating the Schema) exactly; this method does not perform data type conversions. The types for containers are IList for arrays and IDictionary for maps. 

Note that when string values are specified as map keys, they are case-insensitive. 

This method only modifies your copy of the Entity. Store the Entity in an element or another Entity to save the new value. Write access check is not performed on each call to Set. Instead, write access is checked when you try to save the Entity in an Element or another Entity. 

#### Reference

[Entity Class](cf17f0e8-33bd-ef95-bf4b-e6298406f29b.md)

[Set Overload](ca7fbcad-94aa-40a0-f77d-1f78c5ecf705.md)

[Autodesk.Revit.DB.ExtensibleStorage Namespace](79486a74-376c-9555-c873-45d5a750f051.md)