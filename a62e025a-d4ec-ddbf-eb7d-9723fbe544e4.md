

Revit 2026 API

# FilledRegionCreateMaskingRegion(Document, SketchPlane, IListCurveLoop) Method  
  
---  
**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static FilledRegion CreateMaskingRegion(
	Document document,
	SketchPlane sketchPlane,
	IList<CurveLoop> boundaries
)
```
```vb
Public Shared Function CreateMaskingRegion ( 
	document As Document,
	sketchPlane As SketchPlane,
	boundaries As IList(Of CurveLoop)
) As FilledRegion
```
```cpp
public:
static FilledRegion^ CreateMaskingRegion(
	Document^ document, 
	SketchPlane^ sketchPlane, 
	IList<CurveLoop^>^ boundaries
)
```
```fsharp
static member CreateMaskingRegion : 
        document : Document * 
        sketchPlane : SketchPlane * 
        boundaries : IList<CurveLoop> -> FilledRegion 
```


#### Parameters

document [Document](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)
    
sketchPlane [SketchPlane](ba104029-d175-7e75-caef-667a4281f4af.md)
    
boundaries IList[CurveLoop](84824924-cb89-9e20-de6e-3461f429dfd6.md)
    

#### Return Value

[FilledRegion](3685651c-a789-3550-f6bb-7c1decc29079.md)

#### Reference

[FilledRegion Class](3685651c-a789-3550-f6bb-7c1decc29079.md)

[CreateMaskingRegion Overload](0b90c4da-38ea-c126-3147-b47bc450695d.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)