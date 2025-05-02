

Revit 2026 API

# FormUtilsDissolveForms(Document, ICollectionElementId, ICollectionElementId) Method  
  
---  
**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static ICollection<ElementId> DissolveForms(
	Document ADoc,
	ICollection<ElementId> elements,
	out ICollection<ElementId> ProfileOriginPointSet
)
```
```vb
Public Shared Function DissolveForms ( 
	ADoc As Document,
	elements As ICollection(Of ElementId),
	<OutAttribute> ByRef ProfileOriginPointSet As ICollection(Of ElementId)
) As ICollection(Of ElementId)
```
```cpp
public:
static ICollection<ElementId^>^ DissolveForms(
	Document^ ADoc, 
	ICollection<ElementId^>^ elements, 
	[OutAttribute] ICollection<ElementId^>^% ProfileOriginPointSet
)
```
```fsharp
static member DissolveForms : 
        ADoc : Document * 
        elements : ICollection<ElementId> * 
        ProfileOriginPointSet : ICollection<ElementId> byref -> ICollection<ElementId> 
```


#### Parameters

ADoc [Document](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)
    
elements ICollection[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)
    
ProfileOriginPointSet ICollection[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)
    

#### Return Value

ICollection[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)

#### Reference

[FormUtils Class](fe80084f-2b75-cc39-bf64-866bc2c27bb1.md)

[DissolveForms Overload](9a152dc3-04f7-aaf2-91a3-2715652ed95d.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)