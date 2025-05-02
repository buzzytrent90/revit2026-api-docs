

Revit 2026 API

# IFCImportOptionsLinkOrientation Property  
  
---  
  
The orientation of the Linked IFC File in the Host Document. 

**Namespace:** [Autodesk.Revit.DB.IFC](b823fafb-1ba1-896b-4097-142c2817ce74.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public IFCLinkOrientation LinkOrientation { get; set; }
```
```vb
Public Property LinkOrientation As IFCLinkOrientation
	Get
	Set
```
```cpp
public:
property IFCLinkOrientation LinkOrientation {
	IFCLinkOrientation get ();
	void set (IFCLinkOrientation value);
}
```
```fsharp
member LinkOrientation : IFCLinkOrientation with get, set
```


#### Property Value

[IFCLinkOrientation](95081cfc-ae14-6716-aa80-e65251ca2683.md)

| Exception | Condition |
| --- | --- |
| [ArgumentOutOfRangeException](60f148c9-ece0-a6bb-4e12-bb4a9c8c8a24.md) | When setting this property: A value passed for an enumeration argument is not a member of that enumeration |
  
#### Reference

[IFCImportOptions Class](f98f40e2-dbab-4b4c-7fcb-36df9b35cad5.md)

[Autodesk.Revit.DB.IFC Namespace](b823fafb-1ba1-896b-4097-142c2817ce74.md)