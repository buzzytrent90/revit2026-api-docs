

Revit 2026 API

# AnalyticalTransformerData Class  
  
---  
  
Represents the data and parameters of analytical transformer node. 

SystemObject [Autodesk.Revit.DB.ElectricalAnalyticalDistributionNodePropertyData](08a43b98-428c-2bd4-d1c3-fc425563d67e.md) [Autodesk.Revit.DB.ElectricalAnalyticalPowerDistributableNodeData](b04e3319-ced8-0ffb-5816-9f2be112ad6b.md) Autodesk.Revit.DB.ElectricalAnalyticalTransformerData

**Namespace:** [Autodesk.Revit.DB.Electrical](212a1314-7843-2c6c-3322-363127e4059f.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class AnalyticalTransformerData : AnalyticalPowerDistributableNodeData
```
```vb
Public Class AnalyticalTransformerData
	Inherits AnalyticalPowerDistributableNodeData
```
```cpp
public ref class AnalyticalTransformerData : public AnalyticalPowerDistributableNodeData
```
```fsharp
type AnalyticalTransformerData = 
    class
        inherit AnalyticalPowerDistributableNodeData
    end
```


The AnalyticalTransformerData type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [ApparentPowerRating](d7965632-fd13-476c-5a38-5bf3a6ac8e51.md) | The apparent power rating value of the analytical transformer. |
|  | [AssignedPhasesNumber](9d6d49c1-91b4-8ef4-26c0-b044938d2824.md) | The number of electrical phases assigned through the distribution system of the power distributable node. (Inherited from [AnalyticalPowerDistributableNodeData](b04e3319-ced8-0ffb-5816-9f2be112ad6b.md)) |
|  | [AssignedVoltage](10ee95c6-68b3-5fc0-6219-573180244db9.md) | The voltage assigned through the distribution system of the power distributable node. (Inherited from [AnalyticalPowerDistributableNodeData](b04e3319-ced8-0ffb-5816-9f2be112ad6b.md)) |
|  | [ConnectedPhases](bcb78144-2b99-cb70-7172-bfca78e2c27c.md) | The electrical connected phases of the electrical analytical node to its upstream node. (Inherited from [AnalyticalDistributionNodePropertyData](08a43b98-428c-2bd4-d1c3-fc425563d67e.md)) |
|  | [DistributionSystem](a271a35f-d65a-b22e-9579-c3038854f0bb.md) | The distribution system of the power distributable node. (Inherited from [AnalyticalPowerDistributableNodeData](b04e3319-ced8-0ffb-5816-9f2be112ad6b.md)) |
|  | [IsValidObject](d3767f0c-ecb2-e6bc-3b6f-0a65f71204b2.md) | Specifies whether the .NET object represents a valid Revit entity. (Inherited from [AnalyticalDistributionNodePropertyData](08a43b98-428c-2bd4-d1c3-fc425563d67e.md)) |
|  | [SecondaryDistributionSystem](df6261db-4ad4-7d00-9fd2-d3ebdc988351.md) | The secondary distribution system of the analytical transformer. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Dispose](f7dfe5ca-7afd-202a-cce0-8d4e0ce3a8fb.md) | (Inherited from [AnalyticalDistributionNodePropertyData](08a43b98-428c-2bd4-d1c3-fc425563d67e.md)) |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | [GetAllAvailableConnectedPhasesOnDownstream](3937cb9b-34c1-9f9f-7043-309ace9887ec.md) | Get all the available electrical connected phases that this power distributable node can provide to the downstream node. (Inherited from [AnalyticalPowerDistributableNodeData](b04e3319-ced8-0ffb-5816-9f2be112ad6b.md)) |
|  | [GetApparentPerPhaseResults](2cdf8943-793a-1fcb-880a-c2dbd303012b.md) | Get an ElectricalPerPhaseData which contains each electrical phase's apparent load and apprent current of the power distributable node. (Inherited from [AnalyticalPowerDistributableNodeData](b04e3319-ced8-0ffb-5816-9f2be112ad6b.md)) |
|  | [GetConnectedPhasesOnDownstream](def48076-10be-2d07-29f1-d5eb02f46f94.md) | Get the electrical connected phases of the downstream node. (Inherited from [AnalyticalPowerDistributableNodeData](b04e3319-ced8-0ffb-5816-9f2be112ad6b.md)) |
|  | [GetDemandPerPhaseResults](039649ce-c681-a1a2-569f-c6facd2245de.md) | Get an ElectricalPerPhaseData which contains each electrical phase's demand load and demand current of the power distributable node. (Inherited from [AnalyticalPowerDistributableNodeData](b04e3319-ced8-0ffb-5816-9f2be112ad6b.md)) |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | [SetConnectedPhasesOnDownstream](2e8c09ca-d8b6-d586-a8b0-b221d84ef593.md) | Set the electrical connected phases of the downstream node. (Inherited from [AnalyticalPowerDistributableNodeData](b04e3319-ced8-0ffb-5816-9f2be112ad6b.md)) |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
#### Reference

[Autodesk.Revit.DB.Electrical Namespace](212a1314-7843-2c6c-3322-363127e4059f.md)