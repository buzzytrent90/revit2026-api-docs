

Revit 2026 API

# MechanicalSystemGetFlow Method  
  
---  
  
Gets the flow of this mechanical system. 

**Namespace:** [Autodesk.Revit.DB.Mechanical](0eafd899-5912-56fd-94b1-d286156e26fc.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public double GetFlow()
```
```vb
Public Function GetFlow As Double
```
```cpp
public:
double GetFlow()
```
```fsharp
member GetFlow : unit -> float 
```


#### Return Value

Double

| Exception | Condition |
| --- | --- |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | The flow can not be calculated for this system. |
  
The system flow is calculated in the non-blocking evaluation framework. The caller may set up callbacks that react to the asynchronous calculation results. If no callback is set up (e.g, called from third-party applications), the calculation is automatically switched to synchronous calculation so the caller can access the up-to-date result. Similarly, the public method get_ParameterValue(BuiltInParameter.RBS_DUCT_FLOW_PARAM) has the same behavior. Due to this change, the parameter RBS_DUCT_FLOW_PARAM no longer supports dynamic model update. 

#### Reference

[MechanicalSystem Class](ef83dd58-07d6-4f9a-8dc6-f4b1fd8246d2.md)

[Autodesk.Revit.DB.Mechanical Namespace](0eafd899-5912-56fd-94b1-d286156e26fc.md)