

Revit 2026 API

# RebarConstrainedHandleGetEdgeNumber Method  
  
---  
  
If the RebarConstrainedHandle's RebarHandleType is 'Edge', then this function will return the number of the edge that is driven by the handle. 

**Namespace:** [Autodesk.Revit.DB.Structure](d586b341-f687-9d90-e96d-255806b7d4fc.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public int GetEdgeNumber()
```
```vb
Public Function GetEdgeNumber As Integer
```
```cpp
public:
int GetEdgeNumber()
```
```fsharp
member GetEdgeNumber : unit -> int 
```


#### Return Value

Int32

| Exception | Condition |
| --- | --- |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | RebarConstrainedHandle is no longer valid. -or- The RebarConstrainedHandle is not of RebarHandleType 'Edge'. |
  
#### Reference

[RebarConstrainedHandle Class](08b4c4a3-3bb9-0801-9cc8-cd5420a306d9.md)

[Autodesk.Revit.DB.Structure Namespace](d586b341-f687-9d90-e96d-255806b7d4fc.md)