

Revit 2026 API

# CriticalPathCollectorGetCalculatedPressureDrop Method  
  
---  
  
Gets the calculated pressure drop of the network. 

**Namespace:** [Autodesk.Revit.DB.Analysis](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public double GetCalculatedPressureDrop()
```
```vb
Public Function GetCalculatedPressureDrop As Double
```
```cpp
public:
double GetCalculatedPressureDrop()
```
```fsharp
member GetCalculatedPressureDrop : unit -> float 
```


#### Return Value

Double The pressure drop value in the internal Revit unit kg/(ft*s^2). 

The calculated pressure drop is the total pressure loss value of all analytical segment on the critical path. The value is often used to select the equipment. 

#### Reference

[CriticalPathCollector Class](a152f21d-fd43-94dc-f52d-ece283f47c8a.md)

[Autodesk.Revit.DB.Analysis Namespace](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)