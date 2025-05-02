

Revit 2026 API

# RailingFlipped Property  
  
---  
  
Indicates if the railing is flipped. 

**Namespace:** [Autodesk.Revit.DB.Architecture](720f0c58-cb2b-4f13-374a-7348ed0a1cd3.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public bool Flipped { get; }
```
```vb
Public ReadOnly Property Flipped As Boolean
	Get
```
```cpp
public:
property bool Flipped {
	bool get ();
}
```
```fsharp
member Flipped : bool with get
```


#### Property Value

Boolean

| Exception | Condition |
| --- | --- |
| [InapplicableDataException](dc1a6d15-8923-a1fe-722a-4e976634a519.md) | The railing has incorrect internal data. |
  
#### Reference

[Railing Class](4af1265f-859e-123b-ada5-a479324f3dee.md)

[Autodesk.Revit.DB.Architecture Namespace](720f0c58-cb2b-4f13-374a-7348ed0a1cd3.md)