

Revit 2026 API

# MassLevelDataIsValidConceptualConstructionTypeElement Method  
  
---  
  
Checks if the ElementId is an acceptable conceptual construction type ElementId for the MassLevelData (Mass Floor). 

**Namespace:** [Autodesk.Revit.DB.Analysis](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public bool IsValidConceptualConstructionTypeElement(
	ElementId id
)
```
```vb
Public Function IsValidConceptualConstructionTypeElement ( 
	id As ElementId
) As Boolean
```
```cpp
public:
bool IsValidConceptualConstructionTypeElement(
	ElementId^ id
)
```
```fsharp
member IsValidConceptualConstructionTypeElement : 
        id : ElementId -> bool 
```


#### Parameters

id [ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)
     The ElementId to be checked. 

#### Return Value

Boolean True if the ElementId is an acceptable conceptual construction type ElementId, false otherwise. 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
In the case that 'conceptualConstructionIsByEnergyData' is true, invalidElementId is also acceptable input. 

#### Reference

[MassLevelData Class](c1e62aaf-b7af-ad0c-60d5-4a1a9c1bed79.md)

[Autodesk.Revit.DB.Analysis Namespace](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)