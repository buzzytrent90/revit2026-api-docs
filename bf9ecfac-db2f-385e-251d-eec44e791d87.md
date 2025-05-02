

Revit 2026 API

# ElectricalSystemCreate(Connector, ElectricalSystemType) Method  
  
---  
  
Creates a new MEP Electrical System element from an unused Connector. 

**Namespace:** [Autodesk.Revit.DB.Electrical](212a1314-7843-2c6c-3322-363127e4059f.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static ElectricalSystem Create(
	Connector connector,
	ElectricalSystemType elecSysType
)
```
```vb
Public Shared Function Create ( 
	connector As Connector,
	elecSysType As ElectricalSystemType
) As ElectricalSystem
```
```cpp
public:
static ElectricalSystem^ Create(
	Connector^ connector, 
	ElectricalSystemType elecSysType
)
```
```fsharp
static member Create : 
        connector : Connector * 
        elecSysType : ElectricalSystemType -> ElectricalSystem 
```


#### Parameters

connector [Connector](11e07082-b3f2-26a1-de79-16535f44716c.md)
     The Connector to create this Electrical System. 
elecSysType [ElectricalSystemType](90f62108-9cd1-a66a-a123-8372307f4e7f.md)
     The System Type of electrical system. 

#### Return Value

[ElectricalSystem](158b4be3-bbe5-11eb-cccc-788edd3a7590.md) If successful a new MEP Electrical System element within the project, otherwise . 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
| [ArgumentOutOfRangeException](60f148c9-ece0-a6bb-4e12-bb4a9c8c8a24.md) | A value passed for an enumeration argument is not a member of that enumeration |
  
#### Reference

[ElectricalSystem Class](158b4be3-bbe5-11eb-cccc-788edd3a7590.md)

[Create Overload](b3ea7251-7230-ac0a-d5cc-0806b0c0ec1e.md)

[Autodesk.Revit.DB.Electrical Namespace](212a1314-7843-2c6c-3322-363127e4059f.md)