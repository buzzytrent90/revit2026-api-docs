

Revit 2026 API

# ViewSectionIsParentViewValidForCallout Method  
  
---  
  
This validator checks that the parent view is appropriate for callout views. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static bool IsParentViewValidForCallout(
	Document document,
	ElementId parentViewId
)
```
```vb
Public Shared Function IsParentViewValidForCallout ( 
	document As Document,
	parentViewId As ElementId
) As Boolean
```
```cpp
public:
static bool IsParentViewValidForCallout(
	Document^ document, 
	ElementId^ parentViewId
)
```
```fsharp
static member IsParentViewValidForCallout : 
        document : Document * 
        parentViewId : ElementId -> bool 
```


#### Parameters

document [Document](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)
     The document which contains the ViewFamilyType and parent view. 
parentViewId [ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)
     The view in which the new callout will appear. Callouts can be created in FloorPlan, CeilingPlan, StructuralPlan, Section, Elevation, and Detail views. 

#### Return Value

Boolean True if the ViewFamilyType can be used for callout views in the parent view, false otherwise. 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
#### Reference

[ViewSection Class](fcc75682-bd99-a97d-5a4d-0f8eb9e92ab5.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)