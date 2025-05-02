

Revit 2026 API

# CompoundStructureLayerDeckProfileId Property  
  
---  
  
The ElementId of the structural deck profile - only for a layer whose function is StructuralDeck. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public ElementId DeckProfileId { get; set; }
```
```vb
Public Property DeckProfileId As ElementId
	Get
	Set
```
```cpp
public:
property ElementId^ DeckProfileId {
	ElementId^ get ();
	void set (ElementId^ value);
}
```
```fsharp
member DeckProfileId : ElementId with get, set
```


#### Property Value

[ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md) The default is InvalidElementId. 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | When setting this property: A non-optional argument was null |
  
#### Reference

[CompoundStructureLayer Class](faece83a-6d49-41b0-2713-fe6cfaa5a3b5.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)