

Revit 2026 API

# AnalyticalLinkIsValidHub Method  
  
---  
  
Checks whether input hub is valid for an AnalyticalLink. 

**Namespace:** [Autodesk.Revit.DB.Structure](d586b341-f687-9d90-e96d-255806b7d4fc.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static bool IsValidHub(
	Document doc,
	ElementId hubId
)
```
```vb
Public Shared Function IsValidHub ( 
	doc As Document,
	hubId As ElementId
) As Boolean
```
```cpp
public:
static bool IsValidHub(
	Document^ doc, 
	ElementId^ hubId
)
```
```fsharp
static member IsValidHub : 
        doc : Document * 
        hubId : ElementId -> bool 
```


#### Parameters

doc [Document](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)
     Hubs's document. 
hubId [ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)
     Hub to test for validity. 

#### Return Value

Boolean True is returned when provided hubId points hub that is valid for AnalyticalLink, false otherwise. 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
#### Reference

[AnalyticalLink Class](b552fb54-8dff-6690-e16e-cc46cbc46d6b.md)

[Autodesk.Revit.DB.Structure Namespace](d586b341-f687-9d90-e96d-255806b7d4fc.md)