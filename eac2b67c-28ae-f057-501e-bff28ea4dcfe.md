

Revit 2026 API

# SelectionPickObjects(ObjectType, ISelectionFilter, String, IListReference) Method  
  
---  
**Namespace:** [Autodesk.Revit.UI.Selection](11785869-cc9e-03fc-97db-767a59af10a1.md)**Assembly:** RevitAPIUI (in RevitAPIUI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public IList<Reference> PickObjects(
	ObjectType objectType,
	ISelectionFilter selectionFilter,
	string statusPrompt,
	IList<Reference> pPreSelected
)
```
```vb
Public Function PickObjects ( 
	objectType As ObjectType,
	selectionFilter As ISelectionFilter,
	statusPrompt As String,
	pPreSelected As IList(Of Reference)
) As IList(Of Reference)
```
```cpp
public:
IList<Reference^>^ PickObjects(
	ObjectType objectType, 
	ISelectionFilter^ selectionFilter, 
	String^ statusPrompt, 
	IList<Reference^>^ pPreSelected
)
```
```fsharp
member PickObjects : 
        objectType : ObjectType * 
        selectionFilter : ISelectionFilter * 
        statusPrompt : string * 
        pPreSelected : IList<Reference> -> IList<Reference> 
```


#### Parameters

objectType [ObjectType](2d0cbbba-d4ab-84b7-b081-36c14769d82c.md)
    
selectionFilter [ISelectionFilter](d552f44b-221c-0ecd-d001-41a5099b2f9f.md)
    
statusPrompt String
    
pPreSelected IList[Reference](d28155ae-817b-1f31-9c3f-c9c6a28acc0d.md)
    

#### Return Value

IList[Reference](d28155ae-817b-1f31-9c3f-c9c6a28acc0d.md)

#### Reference

[Selection Class](31b73d46-7d67-5dbb-4dad-80aa597c9afc.md)

[PickObjects Overload](e5a547a2-3cf5-7638-2daa-ea85b4d3de2d.md)

[Autodesk.Revit.UI.Selection Namespace](11785869-cc9e-03fc-97db-767a59af10a1.md)