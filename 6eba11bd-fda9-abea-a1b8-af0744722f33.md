

Revit 2026 API

# AreaLoadCreate(Document, ElementId, IListCurveLoop, XYZ, AreaLoadType) Method  
  
---  
**Namespace:** [Autodesk.Revit.DB.Structure](d586b341-f687-9d90-e96d-255806b7d4fc.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static AreaLoad Create(
	Document document,
	ElementId hostElemId,
	IList<CurveLoop> loops,
	XYZ forceVector,
	AreaLoadType symbol
)
```
```vb
Public Shared Function Create ( 
	document As Document,
	hostElemId As ElementId,
	loops As IList(Of CurveLoop),
	forceVector As XYZ,
	symbol As AreaLoadType
) As AreaLoad
```
```cpp
public:
static AreaLoad^ Create(
	Document^ document, 
	ElementId^ hostElemId, 
	IList<CurveLoop^>^ loops, 
	XYZ^ forceVector, 
	AreaLoadType^ symbol
)
```
```fsharp
static member Create : 
        document : Document * 
        hostElemId : ElementId * 
        loops : IList<CurveLoop> * 
        forceVector : XYZ * 
        symbol : AreaLoadType -> AreaLoad 
```


#### Parameters

document [Document](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)
    
hostElemId [ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)
    
loops IList[CurveLoop](84824924-cb89-9e20-de6e-3461f429dfd6.md)
    
forceVector [XYZ](c2fd995c-95c0-58fb-f5de-f3246cbc5600.md)
    
symbol [AreaLoadType](eb4b548c-059a-d0d7-2431-8203c29dfebd.md)
    

#### Return Value

[AreaLoad](5dc205a9-cafd-911b-6a56-26f2e8bfcdc1.md)

#### Reference

[AreaLoad Class](5dc205a9-cafd-911b-6a56-26f2e8bfcdc1.md)

[Create Overload](ad04ec26-96a4-ddc4-305a-e6316cdb6a70.md)

[Autodesk.Revit.DB.Structure Namespace](d586b341-f687-9d90-e96d-255806b7d4fc.md)