

Revit 2026 API

# ExporterIFCSet3DContextHandle Method  
  
---  
  
Sets the IfcRepresentationContext or IfcRepresentationSubContext handle to be used for 3D entities (Model entities). 

**Namespace:** [Autodesk.Revit.DB.IFC](b823fafb-1ba1-896b-4097-142c2817ce74.md)**Assembly:** RevitAPIIFC (in RevitAPIIFC.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public void Set3DContextHandle(
	IFCAnyHandle contextHandle,
	string subContextName
)
```
```vb
Public Sub Set3DContextHandle ( 
	contextHandle As IFCAnyHandle,
	subContextName As String
)
```
```cpp
public:
void Set3DContextHandle(
	IFCAnyHandle^ contextHandle, 
	String^ subContextName
)
```
```fsharp
member Set3DContextHandle : 
        contextHandle : IFCAnyHandle * 
        subContextName : string -> unit 
```


#### Parameters

contextHandle [IFCAnyHandle](8b893943-70fa-94bf-90be-1523d516ecb3.md)
     The IfcRepresentationContext for 3D entities. 
subContextName String
     The name of the IfcRepresentationSubContext, or the IfcRepresentationContext if the string is empty, for 3D entities. 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
#### Reference

[ExporterIFC Class](c8697b81-e080-9202-14d3-ec883f951521.md)

[Autodesk.Revit.DB.IFC Namespace](b823fafb-1ba1-896b-4097-142c2817ce74.md)