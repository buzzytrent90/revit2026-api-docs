

Revit 2026 API

# MEPNetworkIterator(Document, MEPAnalyticalSegment) Constructor  
  
---  
  
Creates an iterator to visit the connected segments on both sides. 

**Namespace:** [Autodesk.Revit.DB.Analysis](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public MEPNetworkIterator(
	Document pADoc,
	MEPAnalyticalSegment startSegment
)
```
```vb
Public Sub New ( 
	pADoc As Document,
	startSegment As MEPAnalyticalSegment
)
```
```cpp
public:
MEPNetworkIterator(
	Document^ pADoc, 
	MEPAnalyticalSegment^ startSegment
)
```
```fsharp
new : 
        pADoc : Document * 
        startSegment : MEPAnalyticalSegment -> MEPNetworkIterator
```


#### Parameters

pADoc [Document](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)
     The document of the analytical network. 
startSegment [MEPAnalyticalSegment](64b45968-97cf-a797-09a6-4583ad9069f7.md)
     The starting analytical segment. 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
#### Reference

[MEPNetworkIterator Class](ef919819-8e7e-7729-5994-096e56dfe420.md)

[MEPNetworkIterator Overload](306014f9-80ca-5367-abe1-a2fb7937531d.md)

[Autodesk.Revit.DB.Analysis Namespace](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)