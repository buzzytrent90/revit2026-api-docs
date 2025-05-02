

Revit 2026 API

# ElementTransformUtilsCopyElements(Document, ICollectionElementId, Document, Transform, CopyPasteOptions) Method  
  
---  
**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static ICollection<ElementId> CopyElements(
	Document sourceDocument,
	ICollection<ElementId> elementsToCopy,
	Document destinationDocument,
	Transform transform,
	CopyPasteOptions options
)
```
```vb
Public Shared Function CopyElements ( 
	sourceDocument As Document,
	elementsToCopy As ICollection(Of ElementId),
	destinationDocument As Document,
	transform As Transform,
	options As CopyPasteOptions
) As ICollection(Of ElementId)
```
```cpp
public:
static ICollection<ElementId^>^ CopyElements(
	Document^ sourceDocument, 
	ICollection<ElementId^>^ elementsToCopy, 
	Document^ destinationDocument, 
	Transform^ transform, 
	CopyPasteOptions^ options
)
```
```fsharp
static member CopyElements : 
        sourceDocument : Document * 
        elementsToCopy : ICollection<ElementId> * 
        destinationDocument : Document * 
        transform : Transform * 
        options : CopyPasteOptions -> ICollection<ElementId> 
```


#### Parameters

sourceDocument [Document](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)
    
elementsToCopy ICollection[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)
    
destinationDocument [Document](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)
    
transform [Transform](58dd01c8-b3fc-7142-e4f3-c524079a282d.md)
    
options [CopyPasteOptions](d8f58fd5-2106-7a88-6218-106a30415791.md)
    

#### Return Value

ICollection[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)

#### Reference

[ElementTransformUtils Class](82e737d5-fda4-bc10-6099-88999cd51300.md)

[CopyElements Overload](7b56b5c2-3aff-f42b-ab47-de1f89a1070f.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)