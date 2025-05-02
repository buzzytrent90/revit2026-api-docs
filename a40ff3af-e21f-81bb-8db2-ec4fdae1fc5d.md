

Revit 2026 API

# IFCTransformSetterInitialize Method  
  
---  
  
Initializes the transformation in the transform setter. 

**Namespace:** [Autodesk.Revit.DB.IFC](b823fafb-1ba1-896b-4097-142c2817ce74.md)**Assembly:** RevitAPIIFC (in RevitAPIIFC.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public void Initialize(
	ExporterIFC exporterIFC,
	Transform transform
)
```
```vb
Public Sub Initialize ( 
	exporterIFC As ExporterIFC,
	transform As Transform
)
```
```cpp
public:
void Initialize(
	ExporterIFC^ exporterIFC, 
	Transform^ transform
)
```
```fsharp
member Initialize : 
        exporterIFC : ExporterIFC * 
        transform : Transform -> unit 
```


#### Parameters

exporterIFC [ExporterIFC](c8697b81-e080-9202-14d3-ec883f951521.md)
     The exporter. 
transform [Transform](58dd01c8-b3fc-7142-e4f3-c524079a282d.md)
     The transform. 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
#### Reference

[IFCTransformSetter Class](75b9525d-3b8d-70d8-55de-a193b9eb5e76.md)

[Autodesk.Revit.DB.IFC Namespace](b823fafb-1ba1-896b-4097-142c2817ce74.md)