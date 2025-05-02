

Revit 2026 API

# FailureDefinitionId Class  
  
---  
  
The unique identifier of a FailureDefinition. 

SystemObject [Autodesk.Revit.DBGuidEnum](36623d19-ba65-63c0-337a-f43c593a9931.md) Autodesk.Revit.DBFailureDefinitionId

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class FailureDefinitionId : GuidEnum
```
```vb
Public Class FailureDefinitionId
	Inherits GuidEnum
```
```cpp
public ref class FailureDefinitionId : public GuidEnum
```
```fsharp
type FailureDefinitionId = 
    class
        inherit GuidEnum
    end
```


The FailureDefinitionId type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [FailureDefinitionId](d8c33d58-de02-1ca4-3d3b-57a806b6dc33.md) | Creates a new FailureDefinitionId instance. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Guid](bc40d585-4c79-959e-5de2-0fe093c89bd1.md) | The Guid of GUID-based enum object. (Inherited from [GuidEnum](36623d19-ba65-63c0-337a-f43c593a9931.md)) |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Equals](7e78b321-b3c8-4283-875c-499d7de34acb.md) | Compares two Guid-based enum object based on their concrete class and GUID value. (Inherited from [GuidEnum](36623d19-ba65-63c0-337a-f43c593a9931.md)) |
|  | [GetHashCode](ac66f072-e558-0e10-b7ed-4cec874b0e0d.md) | Generates a hash code for this Guid-based enum object. (Inherited from [GuidEnum](36623d19-ba65-63c0-337a-f43c593a9931.md)) |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Equality(FailureDefinitionId, FailureDefinitionId)](a1872570-45a1-b596-b9b0-3a649efd8eaa.md) | Compares two FailureDefinitionId instances. |
|  | [Inequality(FailureDefinitionId, FailureDefinitionId)](2c1212ac-b498-db33-a5f2-e9eccd71cdc8.md) | Compares two FailureDefinitionId instances. |
  
Each possible failure in Revit must be defined and registered during Revit application startup by creating a FailureDefinition object. Unique FailureDefinitionId must be used as a key to register FailureDefinition. Those unique FailureDefinitionId should be created using GUID generation tool. Later FailureDefinitionId can be used to lookup FailureDefinition in FailureDefinitionRegistry, and create and post FailureMessages. 

#### Reference

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)