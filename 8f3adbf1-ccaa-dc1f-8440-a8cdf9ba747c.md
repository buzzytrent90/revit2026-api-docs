

Revit 2026 API

# ElectricalAnalyticalNodeGetUpstreamNodeIds Method  
  
---  
  
Gets upstream node ids. 

**Namespace:** [Autodesk.Revit.DB.Electrical](212a1314-7843-2c6c-3322-363127e4059f.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public IList<ElementId> GetUpstreamNodeIds()
```
```vb
Public Function GetUpstreamNodeIds As IList(Of ElementId)
```
```cpp
public:
IList<ElementId^>^ GetUpstreamNodeIds()
```
```fsharp
member GetUpstreamNodeIds : unit -> IList<ElementId> 
```


#### Return Value

IList[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md) The array of upstream node ids. 

If node B supplies from node A, node B is the downstream node of node A, and node A is the upstream node of node B. Usually one node only has one upstream node, but TransferSwitch may have two upstream nodes. 

#### Reference

[ElectricalAnalyticalNode Class](562d1f7d-c9df-bee5-4659-4f8607ee4333.md)

[Autodesk.Revit.DB.Electrical Namespace](212a1314-7843-2c6c-3322-363127e4059f.md)