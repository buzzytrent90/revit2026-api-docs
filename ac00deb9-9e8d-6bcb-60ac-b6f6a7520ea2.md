

Revit 2026 API

# CurveComputeRawParameter Method  
  
---  
  
Computes the raw parameter from the normalized parameter.

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public double ComputeRawParameter(
	double normalizedParameter
)
```
```vb
Public Function ComputeRawParameter ( 
	normalizedParameter As Double
) As Double
```
```cpp
public:
double ComputeRawParameter(
	double normalizedParameter
)
```
```fsharp
member ComputeRawParameter : 
        normalizedParameter : float -> float 
```


#### Parameters

normalizedParameter Double
    The normalized parameter.

#### Return Value

DoubleThe real number equal to the raw curve parameter.

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | Thrown when normalizedParameter is infinite. |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | Thrown when the curve is unbound. |
  
#### Reference

[Curve Class](400cc9b6-9ff7-de85-6fd8-c20002209d25.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)