

Revit 2026 API

# RadialArrayCreate(Document, View, ICollectionElementId, Int32, Line, Double, ArrayAnchorMember) Method  
  
---  
**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static RadialArray Create(
	Document aDoc,
	View dBView,
	ICollection<ElementId> ids,
	int count,
	Line axis,
	double angle,
	ArrayAnchorMember anchorMember
)
```
```vb
Public Shared Function Create ( 
	aDoc As Document,
	dBView As View,
	ids As ICollection(Of ElementId),
	count As Integer,
	axis As Line,
	angle As Double,
	anchorMember As ArrayAnchorMember
) As RadialArray
```
```cpp
public:
static RadialArray^ Create(
	Document^ aDoc, 
	View^ dBView, 
	ICollection<ElementId^>^ ids, 
	int count, 
	Line^ axis, 
	double angle, 
	ArrayAnchorMember anchorMember
)
```
```fsharp
static member Create : 
        aDoc : Document * 
        dBView : View * 
        ids : ICollection<ElementId> * 
        count : int * 
        axis : Line * 
        angle : float * 
        anchorMember : ArrayAnchorMember -> RadialArray 
```


#### Parameters

aDoc [Document](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)
    
dBView [View](fb92a4e7-f3a7-ef14-e631-342179b18de9.md)
    
ids ICollection[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)
    
count Int32
    
axis [Line](e7329450-434a-918b-661c-65e15e0585a5.md)
    
angle Double
    
anchorMember [ArrayAnchorMember](4e138a54-bc03-a66f-831b-7ab88f15677e.md)
    

#### Return Value

[RadialArray](9264d95c-d206-a3c9-1759-b2eab38d3110.md)

#### Reference

[RadialArray Class](9264d95c-d206-a3c9-1759-b2eab38d3110.md)

[Create Overload](a9d1273c-e259-d459-613a-dfd13996728a.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)