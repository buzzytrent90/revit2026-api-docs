

Revit 2026 API

# FamilyManagerAddParameter(ExternalDefinition, ForgeTypeId, Boolean) Method  
  
---  
  
Add a new shared parameter to the family.

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public FamilyParameter AddParameter(
	ExternalDefinition familyDefinition,
	ForgeTypeId groupTypeId,
	bool isInstance
)
```
```vb
Public Function AddParameter ( 
	familyDefinition As ExternalDefinition,
	groupTypeId As ForgeTypeId,
	isInstance As Boolean
) As FamilyParameter
```
```cpp
public:
FamilyParameter^ AddParameter(
	ExternalDefinition^ familyDefinition, 
	ForgeTypeId^ groupTypeId, 
	bool isInstance
)
```
```fsharp
member AddParameter : 
        familyDefinition : ExternalDefinition * 
        groupTypeId : ForgeTypeId * 
        isInstance : bool -> FamilyParameter 
```


#### Parameters

familyDefinition [ExternalDefinition](a3e84415-b88e-a8e0-4e11-64795d92da0e.md)
    The definition of the loaded shared parameter.
groupTypeId [ForgeTypeId](d9fcf276-9566-de83-2b0b-d89b65ccc8af.md)
     The identifier of the parameter group to which the family parameter belongs. 
isInstance Boolean
    Indicates if the new parameter is instance or type.

#### Return Value

[FamilyParameter](6175e974-870e-7fbc-3df7-46105f937a6e.md)If creation was successful the new shared parameter is returned, otherwise an exception with failure information will be thrown.

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | Thrown when the input parameter group cannot be assigned to the new parameter. |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | Thrown when the shared family parameter creation is not supported. Or trying to add an instance parameter of image type. |
  
This method can work even without any family type, but it cannot be assigned the value via FamilyManager.Set methods when there is no current type.

#### Reference

[FamilyManager Class](1cc4fe6c-0e9f-7439-0021-32d2e06f4c33.md)

[AddParameter Overload](fb4f8475-440f-6454-768f-777388a7fdd4.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)