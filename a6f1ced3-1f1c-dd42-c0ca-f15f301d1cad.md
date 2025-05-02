

Revit 2026 API

# ViewSetElementOverrides Method  
  
---  
  
Sets graphic overrides for an element in the view. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public void SetElementOverrides(
	ElementId elementId,
	OverrideGraphicSettings overrideGraphicSettings
)
```
```vb
Public Sub SetElementOverrides ( 
	elementId As ElementId,
	overrideGraphicSettings As OverrideGraphicSettings
)
```
```cpp
public:
void SetElementOverrides(
	ElementId^ elementId, 
	OverrideGraphicSettings^ overrideGraphicSettings
)
```
```fsharp
member SetElementOverrides : 
        elementId : ElementId * 
        overrideGraphicSettings : OverrideGraphicSettings -> unit 
```


#### Parameters

elementId [ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)
     Element to override. 
overrideGraphicSettings [OverrideGraphicSettings](eb2bd6b6-b7b2-5452-2070-2dbadb9e068a.md)
     An object representing all graphic overrides of the element in view. 

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | elementId is not a valid Element identifier. -or- Fill pattern must be a drafting pattern. -or- Fill pattern Id must be invalidElementId or point to a LinePattern element. |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | The element "this View" does not belong to a project document. -or- The view type does not support Visibility/Graphics Overriddes. |
  
#### Reference

[View Class](fb92a4e7-f3a7-ef14-e631-342179b18de9.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)