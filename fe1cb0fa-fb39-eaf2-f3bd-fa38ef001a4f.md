

Revit 2026 API

# ColorOptionsPreselectionColor Property  
  
---  
  
The color of the current canvas theme used to highlight candidates for selection before they are selected. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public Color PreselectionColor { get; set; }
```
```vb
Public Property PreselectionColor As Color
	Get
	Set
```
```cpp
public:
property Color^ PreselectionColor {
	Color^ get ();
	void set (Color^ value);
}
```
```fsharp
member PreselectionColor : Color with get, set
```


#### Property Value

[Color](3735f9b9-d477-09ea-25bd-67f34134595f.md)

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | When setting this property: A non-optional argument was null |
  
#### Reference

[ColorOptions Class](1ca57d8c-b970-83b4-c5ce-9e39464e5cc2.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)