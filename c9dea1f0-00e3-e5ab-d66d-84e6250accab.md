

Revit 2026 API

# MultistoryStairsIsPinned Method  
  
---  
  
Checks if a stair is pinned. 

**Namespace:** [Autodesk.Revit.DB.Architecture](720f0c58-cb2b-4f13-374a-7348ed0a1cd3.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public bool IsPinned(
	Stairs stairs
)
```
```vb
Public Function IsPinned ( 
	stairs As Stairs
) As Boolean
```
```cpp
public:
bool IsPinned(
	Stairs^ stairs
)
```
```fsharp
member IsPinned : 
        stairs : Stairs -> bool 
```


#### Parameters

stairs [Stairs](45e2c068-7e52-c84a-cfb8-a53c531d28fa.md)
     A stairs element in this multistory stairs element. 

#### Return Value

Boolean Returns true if the stairs is pinned; otherwise returns false. 

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | The input stairs is not a member of this multistory stairs. |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
#### Reference

[MultistoryStairs Class](8b07cbff-013c-889f-8807-703e63a91923.md)

[Autodesk.Revit.DB.Architecture Namespace](720f0c58-cb2b-4f13-374a-7348ed0a1cd3.md)