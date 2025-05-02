

Revit 2026 API

# MultiReferenceAnnotationOptionsDimensionLineOrigin Property  
  
---  
  
The origin point for the dimension line. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public XYZ DimensionLineOrigin { get; set; }
```
```vb
Public Property DimensionLineOrigin As XYZ
	Get
	Set
```
```cpp
public:
property XYZ^ DimensionLineOrigin {
	XYZ^ get ();
	void set (XYZ^ value);
}
```
```fsharp
member DimensionLineOrigin : XYZ with get, set
```


#### Property Value

[XYZ](c2fd995c-95c0-58fb-f5de-f3246cbc5600.md)

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | When setting this property: A non-optional argument was null |
  
#### Reference

[MultiReferenceAnnotationOptions Class](2e081b6c-38fd-4f03-a372-0dfa841e6248.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)