

Revit 2026 API

# RebarGetBendData Method  
  
---  
  
Gets the RebarBendData, containing bar and hook information, of the instance. 

**Namespace:** [Autodesk.Revit.DB.Structure](d586b341-f687-9d90-e96d-255806b7d4fc.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public RebarBendData GetBendData()
```
```vb
Public Function GetBendData As RebarBendData
```
```cpp
public:
RebarBendData^ GetBendData()
```
```fsharp
member GetBendData : unit -> RebarBendData 
```


#### Return Value

[RebarBendData](027b5619-ad82-74b3-1d78-efe86a1ef96b.md)

Internally, the bend data is used by many RebarShape methods to generate shape geometry. 

#### Reference

[Rebar Class](70fd7426-f4a4-591c-8c06-3c18dda45e7d.md)

[Autodesk.Revit.DB.Structure Namespace](d586b341-f687-9d90-e96d-255806b7d4fc.md)