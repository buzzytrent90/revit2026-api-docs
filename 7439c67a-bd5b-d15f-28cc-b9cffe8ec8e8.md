

Revit 2026 API

# ParameterFilterElementElementFilterIsAcceptableForParameterFilterElement(Document, ISetElementId, ElementFilter) Method  
  
---  
**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static bool ElementFilterIsAcceptableForParameterFilterElement(
	Document aDocument,
	ISet<ElementId> categories,
	ElementFilter elementFilter
)
```
```vb
Public Shared Function ElementFilterIsAcceptableForParameterFilterElement ( 
	aDocument As Document,
	categories As ISet(Of ElementId),
	elementFilter As ElementFilter
) As Boolean
```
```cpp
public:
static bool ElementFilterIsAcceptableForParameterFilterElement(
	Document^ aDocument, 
	ISet<ElementId^>^ categories, 
	ElementFilter^ elementFilter
)
```
```fsharp
static member ElementFilterIsAcceptableForParameterFilterElement : 
        aDocument : Document * 
        categories : ISet<ElementId> * 
        elementFilter : ElementFilter -> bool 
```


#### Parameters

aDocument [Document](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)
    
categories ISet[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)
    
elementFilter [ElementFilter](b8b46cbf-9ecc-0745-ec53-c3c3b6510113.md)
    

#### Return Value

Boolean

#### Reference

[ParameterFilterElement Class](b231dc85-516a-5e75-c634-c6cd81b43fc5.md)

[ElementFilterIsAcceptableForParameterFilterElement Overload](1ea4b742-414d-a165-1306-aed309bbb1ef.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)