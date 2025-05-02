

Revit 2026 API

# RebarShapeGetEndTreatmentTypeId Method  
  
---  
  
**Note: This API is now obsolete.**

Gets the id of the EndTreatmentType at the specified rebar shape end. 

**Namespace:** [Autodesk.Revit.DB.Structure](d586b341-f687-9d90-e96d-255806b7d4fc.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
[ObsoleteAttribute("This method is deprecated in Revit 2026 and may be removed in a later version of Revit. Please use RebarShape.GetTerminationsData().EndTreatmentTypeIdAtStart or RebarShape.GetTerminationsData().EndTreatmentTypeIdAtEnd instead.")]
public ElementId GetEndTreatmentTypeId(
	int end
)
```
```vb
<ObsoleteAttribute("This method is deprecated in Revit 2026 and may be removed in a later version of Revit. Please use RebarShape.GetTerminationsData().EndTreatmentTypeIdAtStart or RebarShape.GetTerminationsData().EndTreatmentTypeIdAtEnd instead.")>
Public Function GetEndTreatmentTypeId ( 
	end As Integer
) As ElementId
```
```cpp
public:
[ObsoleteAttribute(L"This method is deprecated in Revit 2026 and may be removed in a later version of Revit. Please use RebarShape.GetTerminationsData().EndTreatmentTypeIdAtStart or RebarShape.GetTerminationsData().EndTreatmentTypeIdAtEnd instead.")]
ElementId^ GetEndTreatmentTypeId(
	int end
)
```
```fsharp
[<ObsoleteAttribute("This method is deprecated in Revit 2026 and may be removed in a later version of Revit. Please use RebarShape.GetTerminationsData().EndTreatmentTypeIdAtStart or RebarShape.GetTerminationsData().EndTreatmentTypeIdAtEnd instead.")>]
member GetEndTreatmentTypeId : 
        end : int -> ElementId 
```


#### Parameters

end Int32
     0 for the start end treatment, 1 for the end end treatment. 

#### Return Value

[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md) Returns the id of an EndTreatmentType, or invalidElementId if the rebar shape has no end treatment at the specified end. 

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | end not a valid shape end |
  
#### Reference

[RebarShape Class](0a370e32-eaba-785e-7e1f-9330929525fc.md)

[Autodesk.Revit.DB.Structure Namespace](d586b341-f687-9d90-e96d-255806b7d4fc.md)