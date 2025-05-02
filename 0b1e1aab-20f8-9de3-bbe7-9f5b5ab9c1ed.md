

Revit 2026 API

# FabricationNetworkChangeServiceChangeSize Method  
  
---  
**Namespace:** [Autodesk.Revit.DB.Fabrication](49e74a25-7ea1-efa6-548a-a3c3d0655e43.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public FabricationNetworkChangeServiceResult ChangeSize(
	ISet<ElementId> selection,
	ISet<FabricationPartSizeMap> fabricationPartSizeMaps
)
```
```vb
Public Function ChangeSize ( 
	selection As ISet(Of ElementId),
	fabricationPartSizeMaps As ISet(Of FabricationPartSizeMap)
) As FabricationNetworkChangeServiceResult
```
```cpp
public:
FabricationNetworkChangeServiceResult ChangeSize(
	ISet<ElementId^>^ selection, 
	ISet<FabricationPartSizeMap^>^ fabricationPartSizeMaps
)
```
```fsharp
member ChangeSize : 
        selection : ISet<ElementId> * 
        fabricationPartSizeMaps : ISet<FabricationPartSizeMap> -> FabricationNetworkChangeServiceResult 
```


#### Parameters

selection ISet[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)
    
fabricationPartSizeMaps ISet[FabricationPartSizeMap](b4be4ccc-ac6d-bb65-ef61-a41713b2916f.md)
    

#### Return Value

[FabricationNetworkChangeServiceResult](d637e2e7-215c-ac8e-7c9a-9311a07d68ba.md)

#### Reference

[FabricationNetworkChangeService Class](ddd58cb0-54bc-a864-9688-b890a7140112.md)

[Autodesk.Revit.DB.Fabrication Namespace](49e74a25-7ea1-efa6-548a-a3c3d0655e43.md)