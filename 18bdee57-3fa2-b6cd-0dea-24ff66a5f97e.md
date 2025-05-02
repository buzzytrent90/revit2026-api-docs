

Revit 2026 API

# EnergyModelType Enumeration  
  
---  
  
This enum is used to define if the energy model is based on rooms/spaces, building elements or analysis mode in EnergyDataSettings. 

**Namespace:** [Autodesk.Revit.DB.Analysis](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public enum EnergyModelType
```
```vb
Public Enumeration EnergyModelType
```
```cpp
public enum class EnergyModelType
```
```fsharp
type EnergyModelType
```


| Member name | Value | Description |
| --- | --- | --- |
| AnalysisMode | 2 | Energy model based on analysis mode in EnergyDataSettings. |
| BuildingElement | 1 | The building element based energy analytical model. |
| SpatialElement | 0 | Energy model based on rooms or spaces. |
  
#### Reference

[Autodesk.Revit.DB.Analysis Namespace](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)