

Revit 2026 API

# TemperatureRatingTypeSetContains Method  
  
---  
  
Tests for the existence of a TemperatureRating type within the set.

**Namespace:** [Autodesk.Revit.DB.Electrical](212a1314-7843-2c6c-3322-363127e4059f.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public virtual bool Contains(
	TemperatureRatingType item
)
```
```vb
Public Overridable Function Contains ( 
	item As TemperatureRatingType
) As Boolean
```
```cpp
public:
virtual bool Contains(
	TemperatureRatingType^ item
)
```
```fsharp
abstract Contains : 
        item : TemperatureRatingType -> bool 
override Contains : 
        item : TemperatureRatingType -> bool 
```


#### Parameters

item [TemperatureRatingType](fe7e15d7-c31f-b24c-992f-332e54e9a5ba.md)
    The TemperatureRating type to be searched for.

#### Return Value

BooleanThe Contains method returns True if the TemperatureRating type is within the set, otherwise False.

#### Reference

[TemperatureRatingTypeSet Class](572d809d-fc08-6038-5279-b43903e9a6b8.md)

[Autodesk.Revit.DB.Electrical Namespace](212a1314-7843-2c6c-3322-363127e4059f.md)