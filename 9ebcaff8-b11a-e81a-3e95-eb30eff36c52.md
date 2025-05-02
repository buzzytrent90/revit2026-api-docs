

Revit 2026 API

# MEPAnalyticalModelDataGetNodeByIndex Method  
  
---  
  
Gets the specified analytical node. 

**Namespace:** [Autodesk.Revit.DB.Analysis](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public MEPAnalyticalNode GetNodeByIndex(
	int index
)
```
```vb
Public Function GetNodeByIndex ( 
	index As Integer
) As MEPAnalyticalNode
```
```cpp
public:
MEPAnalyticalNode^ GetNodeByIndex(
	int index
)
```
```fsharp
member GetNodeByIndex : 
        index : int -> MEPAnalyticalNode 
```


#### Parameters

index Int32
     The node index number by their storing sequence, starting from 0. 

#### Return Value

[MEPAnalyticalNode](d542aa13-f6a7-087c-9660-b0698d303a0c.md) The returned analytical node. 

| Exception | Condition |
| --- | --- |
| [ArgumentOutOfRangeException](60f148c9-ece0-a6bb-4e12-bb4a9c8c8a24.md) | The index must range from 0 to GetNumberOfNodes()-1. |
  
#### Reference

[MEPAnalyticalModelData Class](9bb95365-04a3-6c28-5f72-477facd80cbc.md)

[Autodesk.Revit.DB.Analysis Namespace](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)