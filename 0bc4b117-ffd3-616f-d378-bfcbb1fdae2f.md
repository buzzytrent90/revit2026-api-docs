

Revit 2026 API

# DocumentSaveToProjectAsImage Method  
  
---  
  
Creates an image view from the currently active view. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public ElementId SaveToProjectAsImage(
	ImageExportOptions options
)
```
```vb
Public Function SaveToProjectAsImage ( 
	options As ImageExportOptions
) As ElementId
```
```cpp
public:
ElementId^ SaveToProjectAsImage(
	ImageExportOptions^ options
)
```
```fsharp
member SaveToProjectAsImage : 
        options : ImageExportOptions -> ElementId 
```


#### Parameters

options [ImageExportOptions](c2e823a1-6eb0-2bf3-f07b-ed46d8f7b70a.md)
     The options which govern the image creation. 

#### Return Value

[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md) Id of the newly created view if the operation succeeded, invalid element id otherwise. 

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | options object is invalid: the ExportRange is invalid, must be CurrentView or VisibleRegionOfCurrentView, or the ViewName is invalid, must be non-empty, unique and should not contain prohibited characters. -or- The current view cannot be exported as an image |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
#### Reference

[Document Class](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)