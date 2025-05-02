

Revit 2026 API

# RenderingSettingsSetRenderingQualitySettings Method  
  
---  
  
Change rendering quality settings. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public void SetRenderingQualitySettings(
	RenderingQualitySettings settings
)
```
```vb
Public Sub SetRenderingQualitySettings ( 
	settings As RenderingQualitySettings
)
```
```cpp
public:
void SetRenderingQualitySettings(
	RenderingQualitySettings^ settings
)
```
```fsharp
member SetRenderingQualitySettings : 
        settings : RenderingQualitySettings -> unit 
```


#### Parameters

settings [RenderingQualitySettings](400738fc-3791-666c-10f3-ec46c771d6d5.md)
     An instance of the new rendering quality settings. 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
#### Reference

[RenderingSettings Class](7ba669f3-bd38-464b-f3f7-8a0b4e513a0a.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)