

Revit 2026 API

# MassSurfaceDataGetFaceReferences Method  
  
---  
  
Gets References to the faces that the MassSurfaceData provides properties for. 

**Namespace:** [Autodesk.Revit.DB.Analysis](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public IList<Reference> GetFaceReferences()
```
```vb
Public Function GetFaceReferences As IList(Of Reference)
```
```cpp
public:
IList<Reference^>^ GetFaceReferences()
```
```fsharp
member GetFaceReferences : unit -> IList<Reference> 
```


#### Return Value

IList[Reference](d28155ae-817b-1f31-9c3f-c9c6a28acc0d.md) Returns an array of References to Faces that the MassSurfaceData provides properties for. 

The results are always references to Faces. The Reference Type should be REFERENCE_TYPE_SURFACE. Currently Revit improperly reports it as REFERENCE_TYPE_NONE. 

#### Reference

[MassSurfaceData Class](69fcb13c-6443-d1c2-29d5-08adc1261afd.md)

[Autodesk.Revit.DB.Analysis Namespace](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)