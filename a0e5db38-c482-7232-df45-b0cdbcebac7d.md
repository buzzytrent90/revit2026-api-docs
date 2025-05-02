

Revit 2026 API

# RebarContainerParameterManager Class  
  
---  
  
Provides implementation of RebarContainer parameters overrides. 

SystemObject Autodesk.Revit.DB.StructureRebarContainerParameterManager

**Namespace:** [Autodesk.Revit.DB.Structure](d586b341-f687-9d90-e96d-255806b7d4fc.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class RebarContainerParameterManager : IDisposable
```
```vb
Public Class RebarContainerParameterManager
	Implements IDisposable
```
```cpp
public ref class RebarContainerParameterManager : IDisposable
```
```fsharp
type RebarContainerParameterManager = 
    class
        interface IDisposable
    end
```


The RebarContainerParameterManager type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [IsValidObject](e400c49b-bdc6-3bc6-5db2-2fe16fe956bf.md) | Specifies whether the .NET object represents a valid Revit entity. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [AddOverride(ElementId, ElementId)](162cbdc9-f640-ca81-fb77-f7456993951f.md) | Adds an override for the given parameter as its value will be displayed for the Rebar Container element. |
|  | [AddOverride(ElementId, Double)](37cdef48-c22a-633f-7047-33f9d170f641.md) | Adds an override for the given parameter as its value will be displayed for the Rebar Container element. |
|  | [AddOverride(ElementId, Int32)](1a855734-c230-30ee-8d74-33617eb7bc3f.md) | Adds an override for the given parameter as its value will be displayed for the Rebar Container element. |
|  | [AddOverride(ElementId, String)](b9cfaccb-15c0-d12c-470a-8ec9f1419979.md) | Adds an override for the given parameter as its value will be displayed for the Rebar Container element. |
|  | [AddSharedParameterAsOverride](0e4551e0-d6c6-3c71-812b-8ea6a82a9ea9.md) | Adds a shared parameter as one of the parameter overrides stored by this Rebar Container element. |
|  | [ClearOverrides](997a68cf-1530-13a1-91d3-484beefa51a3.md) | Clears any overridden values from all parameters of the associated RebarContainer element. |
|  | [Dispose](37f9ed71-f3fa-9ce0-db64-aba29212386b.md) | Releases all resources used by the RebarContainerParameterManager |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | [GetDoubleOverrideValue](269b5ffa-a173-d34a-20ce-b3d98ca793f6.md) | Get the double value for an overriden parameter. |
|  | [GetElementIdOverrideValue](5c9dca6a-77dd-9631-47f8-b0f02c8ca905.md) | Get the ElementId value for an overriden parameter. |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | [GetIntOverrideValue](fa4716f0-ba7b-5d2f-6005-1a6be9e4ddd3.md) | Get the integer value for an overriden parameter. |
|  | [GetStringOverrideValue](bdd0c7ed-421a-fc24-05d0-5cc727c4c013.md) | Get the string value for an overriden parameter. |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | [IsOverriddenParameterModifiable](7d3b99fe-2028-3309-52cd-a3c8d4319d08.md) | Checks if overridden parameter is modifiable. |
|  | [IsParameterOverridden](329a5321-cfa1-3924-e05b-6a51fcc08b81.md) | Checks if the parameter has an override |
|  | [IsRebarContainerParameter](f1af9db7-e66c-f8db-8526-1e52833cb830.md) | Checks if the parameter is a Rebar Container parameter |
|  | [RemoveOverride](936573d9-88a4-ed15-233b-6508a9c88a64.md) | Removes an overridden value from the given parameter. |
|  | [SetOverriddenParameterModifiable](0b91fcec-09b4-8e89-01cf-24272512395f.md) | Sets this overridden parameter to be modifiable. |
|  | [SetOverriddenParameterReadonly](13dfe73c-aa3c-767d-c939-45feab28cd21.md) | Sets this overridden parameter to be readonly. |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
When a new override is created, by default, the parameter will show the overridden value as read-only. You can control whether or not the parameter is modifiable using [SetOverriddenParameterReadonly(ElementId)](13dfe73c-aa3c-767d-c939-45feab28cd21.md) and [SetOverriddenParameterModifiable(ElementId)](0b91fcec-09b4-8e89-01cf-24272512395f.md).a 

#### Reference

[Autodesk.Revit.DB.Structure Namespace](d586b341-f687-9d90-e96d-255806b7d4fc.md)