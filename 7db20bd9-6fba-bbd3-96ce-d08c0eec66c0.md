

Revit 2026 API

# DuctFittingAndAccessoryData Class  
  
---  
  
The input data used by external servers for calculation of the duct fitting and duct accessory coefficient. 

SystemObject Autodesk.Revit.DB.MechanicalDuctFittingAndAccessoryData

**Namespace:** [Autodesk.Revit.DB.Mechanical](0eafd899-5912-56fd-94b1-d286156e26fc.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class DuctFittingAndAccessoryData : IDisposable
```
```vb
Public Class DuctFittingAndAccessoryData
	Implements IDisposable
```
```cpp
public ref class DuctFittingAndAccessoryData : IDisposable
```
```fsharp
type DuctFittingAndAccessoryData = 
    class
        interface IDisposable
    end
```


The DuctFittingAndAccessoryData type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [Density](39bfde86-cd51-d76c-49c5-2eda2ff7a2aa.md) | The air density for the duct fitting or duct accessory, Units: kg/ft^3. |
|  | [DynamicViscosity](fd65feaa-bf6d-3f17-c278-01648880a9e4.md) | The dynamic viscosity of air for the duct fitting or duct accessory, Units: (kg/(ftÂ·s)). |
|  | [IsValidObject](fd6dd959-097d-38ce-2ce4-7295cb9f03bb.md) | Specifies whether the .NET object represents a valid Revit entity. |
|  | [Origin](e861b86d-b8ef-6978-3c78-1ff297e512ff.md) | The origin position of the duct fitting or duct accessory. |
|  | [PartType](798cb715-a76a-1a2e-7162-abba4f773337.md) | The part type of the duct fitting or duct accessory. |
|  | [ServerGUID](94277b06-9ddc-a15a-032e-984176ddbd44.md) | The GUID of the duct fitting or duct accessory. |
|  | [SystemClassification](b6c60ee8-b012-b506-dc42-a47c82ee9e7c.md) | The system classification of the duct fitting or duct accessory. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Dispose](a637738b-5a16-7783-de47-0829610e360d.md) | Releases all resources used by the DuctFittingAndAccessoryData |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | [GetAllConnectorData](6a6fd6cc-325d-4d44-6e08-309cdc81ef42.md) | Gets the connector data of the pipe fitting or pipe accessory. |
|  | [GetEntity](c1e1344a-74d7-fd84-877f-e4513270e61c.md) | Returns an Entity of the Schema of the serverGUID. or an invalid entity otherwise. |
|  | [GetFamilyInstanceId](b219f66a-497c-b7ca-a1fa-6cf36287b7a4.md) | Gets the Id of the fiting or accessory instance |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
A FamilyInstance is the input data for the calculation, 

#### Reference

[Autodesk.Revit.DB.Mechanical Namespace](0eafd899-5912-56fd-94b1-d286156e26fc.md)