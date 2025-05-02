

Revit 2026 API

# BoundingBoxXYZBounds Property  
  
---  
  
Indexed access for loops. Use 0 for Min and 1 for Max.

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public XYZ this[
	int bound
] { get; set; }
```
```vb
Public Property Bounds ( 
	bound As Integer
) As XYZ
	Get
	Set
```
```cpp
public:
property XYZ^ Bounds[int bound] {
	XYZ^ get (int bound);
	void set (int bound, XYZ^ value);
}
```
```fsharp
member Bounds : XYZ with get, set
```


#### Parameters

bound Int32
    

#### Property Value

[XYZ](c2fd995c-95c0-58fb-f5de-f3246cbc5600.md)

The bounds are defined in the coordinate space of the box.

#### Reference

[BoundingBoxXYZ Class](3c452286-57b1-40e2-2795-c90bff1fcec2.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)