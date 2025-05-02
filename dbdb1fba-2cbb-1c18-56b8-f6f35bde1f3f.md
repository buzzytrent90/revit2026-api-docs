

Revit 2026 API

# ExporterIFCSetOwnerHistoryHandle Method  
  
---  
  
Sets the handle to the IfcOwnerHistory for the file. 

**Namespace:** [Autodesk.Revit.DB.IFC](b823fafb-1ba1-896b-4097-142c2817ce74.md)**Assembly:** RevitAPIIFC (in RevitAPIIFC.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public void SetOwnerHistoryHandle(
	IFCAnyHandle ownerHistory
)
```
```vb
Public Sub SetOwnerHistoryHandle ( 
	ownerHistory As IFCAnyHandle
)
```
```cpp
public:
void SetOwnerHistoryHandle(
	IFCAnyHandle^ ownerHistory
)
```
```fsharp
member SetOwnerHistoryHandle : 
        ownerHistory : IFCAnyHandle -> unit 
```


#### Parameters

ownerHistory [IFCAnyHandle](8b893943-70fa-94bf-90be-1523d516ecb3.md)
     The handle. 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
#### Reference

[ExporterIFC Class](c8697b81-e080-9202-14d3-ec883f951521.md)

[Autodesk.Revit.DB.IFC Namespace](b823fafb-1ba1-896b-4097-142c2817ce74.md)