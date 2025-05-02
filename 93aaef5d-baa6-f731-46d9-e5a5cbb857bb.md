

Revit 2026 API

# WireMaterialTypeName Property  
  
---  
  
Get name of wire material type. 

**Namespace:** [Autodesk.Revit.DB.Electrical](212a1314-7843-2c6c-3322-363127e4059f.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public override string Name { set; }
```
```vb
Public Overrides WriteOnly Property Name As String
	Set
```
```cpp
public:
virtual property String^ Name {
	void set (String^ value) override;
}
```
```fsharp
abstract Name : string with set
override Name : string with set
```


#### Property Value

String

| Exception | Condition |
| --- | --- |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | Set name can't be supported. |
  
#### Reference

[WireMaterialType Class](3d05ec79-0289-c6d1-2a13-7e6b07241afd.md)

[Autodesk.Revit.DB.Electrical Namespace](212a1314-7843-2c6c-3322-363127e4059f.md)