

Revit 2026 API

# OverrideGraphicSettingsSetSurfaceTransparency Method  
  
---  
  
Sets the projection surface transparency. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public OverrideGraphicSettings SetSurfaceTransparency(
	int transparency
)
```
```vb
Public Function SetSurfaceTransparency ( 
	transparency As Integer
) As OverrideGraphicSettings
```
```cpp
public:
OverrideGraphicSettings^ SetSurfaceTransparency(
	int transparency
)
```
```fsharp
member SetSurfaceTransparency : 
        transparency : int -> OverrideGraphicSettings 
```


#### Parameters

transparency Int32
     Value of the transparency of the projection surface (0 = opaque, 100 = fully transparent). 

#### Return Value

[OverrideGraphicSettings](eb2bd6b6-b7b2-5452-2070-2dbadb9e068a.md) Reference to the changed object. 

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | Transparency must be greater than 0 and less than 100. |
  
#### Reference

[OverrideGraphicSettings Class](eb2bd6b6-b7b2-5452-2070-2dbadb9e068a.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)