

Revit 2026 API

# DocumentChangedEventArgsGetAddedElementIds(ElementFilter) Method  
  
---  
  
Returns set of newly added elements that pass the filter. 

**Namespace:** [Autodesk.Revit.DB.Events](b86712d6-83b3-e044-8016-f9881ecd3800.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public ICollection<ElementId> GetAddedElementIds(
	ElementFilter filter
)
```
```vb
Public Function GetAddedElementIds ( 
	filter As ElementFilter
) As ICollection(Of ElementId)
```
```cpp
public:
ICollection<ElementId^>^ GetAddedElementIds(
	ElementFilter^ filter
)
```
```fsharp
member GetAddedElementIds : 
        filter : ElementFilter -> ICollection<ElementId> 
```


#### Parameters

filter [ElementFilter](b8b46cbf-9ecc-0745-ec53-c3c3b6510113.md)
     The element filter to be applied. 

#### Return Value

ICollection[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md) The set of ElementId for newly added elements that pass the filter. Returns empty set if no elements are found which pass the filter. 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
#### Reference

[DocumentChangedEventArgs Class](8fd170b2-df48-209b-438e-54ec7b01b664.md)

[GetAddedElementIds Overload](1d71c512-2bf5-f329-cfe7-77af12a53e59.md)

[Autodesk.Revit.DB.Events Namespace](b86712d6-83b3-e044-8016-f9881ecd3800.md)