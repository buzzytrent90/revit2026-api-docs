

Revit 2026 API

# DocumentPreviewSettingsIsViewIdValidForPreview Method  
  
---  
  
Identifies if the view id is valid as a preview view id. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public bool IsViewIdValidForPreview(
	ElementId viewId
)
```
```vb
Public Function IsViewIdValidForPreview ( 
	viewId As ElementId
) As Boolean
```
```cpp
public:
bool IsViewIdValidForPreview(
	ElementId^ viewId
)
```
```fsharp
member IsViewIdValidForPreview : 
        viewId : ElementId -> bool 
```


#### Parameters

viewId [ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)
     The view id. 

#### Return Value

Boolean True if the view id is valid for preview, false otherwise. 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
Only graphical views (3d or 2d) are valid for use as a preview view. Other views (such as view templates) will not pass this method. InvalidElementId is accepted by this method as this id means that no special view is set for the preview. 

#### Reference

[DocumentPreviewSettings Class](e38ea350-9951-ee05-5e3d-ab7f31815fb3.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)