

Revit 2026 API

# IFCExportOptionsAssign Method  
  
---  
  
Assigns the values of the IFCExportOptions to this options object. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public void Assign(
	IFCExportOptions sourceOptions
)
```
```vb
Public Sub Assign ( 
	sourceOptions As IFCExportOptions
)
```
```cpp
public:
void Assign(
	IFCExportOptions^ sourceOptions
)
```
```fsharp
member Assign : 
        sourceOptions : IFCExportOptions -> unit 
```


#### Parameters

sourceOptions [IFCExportOptions](db8ed2bb-8949-7a7f-e09a-29f6c9916f42.md)
     The source IFCExportOptions. 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
#### Reference

[IFCExportOptions Class](db8ed2bb-8949-7a7f-e09a-29f6c9916f42.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)