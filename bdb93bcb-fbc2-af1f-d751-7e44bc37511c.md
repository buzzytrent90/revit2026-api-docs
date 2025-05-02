

Revit 2026 API

# FabricAreaDistributionOfWiresAtCover Property  
  
---  
  
The distribution of wires that is closest to the cover. 

**Namespace:** [Autodesk.Revit.DB.Structure](d586b341-f687-9d90-e96d-255806b7d4fc.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public WireDistributionDirection DistributionOfWiresAtCover { get; set; }
```
```vb
Public Property DistributionOfWiresAtCover As WireDistributionDirection
	Get
	Set
```
```cpp
public:
property WireDistributionDirection DistributionOfWiresAtCover {
	WireDistributionDirection get ();
	void set (WireDistributionDirection value);
}
```
```fsharp
member DistributionOfWiresAtCover : WireDistributionDirection with get, set
```


#### Property Value

[WireDistributionDirection](2c5558b4-57d4-1b81-e843-e79c5c1bbc21.md)

| Exception | Condition |
| --- | --- |
| [ArgumentOutOfRangeException](60f148c9-ece0-a6bb-4e12-bb4a9c8c8a24.md) | When setting this property: A value passed for an enumeration argument is not a member of that enumeration |
  
#### Reference

[FabricArea Class](b8e6a637-e069-500d-b7d3-3500e1728681.md)

[Autodesk.Revit.DB.Structure Namespace](d586b341-f687-9d90-e96d-255806b7d4fc.md)