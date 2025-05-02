

Revit 2026 API

# PipePressureDropDataFlowState Property  
  
---  
  
The flowState of the pipe. 

**Namespace:** [Autodesk.Revit.DB.Plumbing](cc553597-37c2-fcd9-6025-d904c129c80a.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public PipeFlowState FlowState { get; set; }
```
```vb
Public Property FlowState As PipeFlowState
	Get
	Set
```
```cpp
public:
property PipeFlowState FlowState {
	PipeFlowState get ();
	void set (PipeFlowState value);
}
```
```fsharp
member FlowState : PipeFlowState with get, set
```


#### Property Value

[PipeFlowState](7e8a8103-9ac3-c933-2c90-9892a2f27d4a.md)

| Exception | Condition |
| --- | --- |
| [ArgumentOutOfRangeException](60f148c9-ece0-a6bb-4e12-bb4a9c8c8a24.md) | When setting this property: A value passed for an enumeration argument is not a member of that enumeration |
  
#### Reference

[PipePressureDropData Class](d9c2df4c-512f-3f0c-4c04-2f5cc5afa7d8.md)

[Autodesk.Revit.DB.Plumbing Namespace](cc553597-37c2-fcd9-6025-d904c129c80a.md)