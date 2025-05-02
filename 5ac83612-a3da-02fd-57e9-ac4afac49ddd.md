

Revit 2026 API

# EdgeEndPointEvaluate Method  
  
---  
  
Evaluate the end point of the edge in 3d coordinates. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public XYZ Evaluate()
```
```vb
Public Function Evaluate As XYZ
```
```cpp
public:
XYZ^ Evaluate()
```
```fsharp
member Evaluate : unit -> XYZ 
```


#### Return Value

[XYZ](c2fd995c-95c0-58fb-f5de-f3246cbc5600.md) The end point of the edge in 3d coordinates. 

| Exception | Condition |
| --- | --- |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | Failed to evaluate the end point of the edge. |
  
#### Reference

[EdgeEndPoint Class](3388e8f3-22d4-a411-a3da-450c16a31bc5.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)