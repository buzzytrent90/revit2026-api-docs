

Revit 2026 API

# ReinforcementAbbreviationTag Constructor  
  
---  
  
Constructs a new ReinforcementAbbreviationTag. 

**Namespace:** [Autodesk.Revit.DB.Structure](d586b341-f687-9d90-e96d-255806b7d4fc.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public ReinforcementAbbreviationTag(
	ReinforcementAbbreviationTagType typeTag,
	string abbreviationTag
)
```
```vb
Public Sub New ( 
	typeTag As ReinforcementAbbreviationTagType,
	abbreviationTag As String
)
```
```cpp
public:
ReinforcementAbbreviationTag(
	ReinforcementAbbreviationTagType typeTag, 
	String^ abbreviationTag
)
```
```fsharp
new : 
        typeTag : ReinforcementAbbreviationTagType * 
        abbreviationTag : string -> ReinforcementAbbreviationTag
```


#### Parameters

typeTag [ReinforcementAbbreviationTagType](55ba9a83-6ce5-c4ec-67dd-52943a87e6f7.md)
     Defines the type of abbreviation tag. 
abbreviationTag String
     Defines the abbreviation tag value. 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
| [ArgumentOutOfRangeException](60f148c9-ece0-a6bb-4e12-bb4a9c8c8a24.md) | A value passed for an enumeration argument is not a member of that enumeration |
  
#### Reference

[ReinforcementAbbreviationTag Class](bf71dcbf-bb5b-07db-9711-e901b109b8e2.md)

[Autodesk.Revit.DB.Structure Namespace](d586b341-f687-9d90-e96d-255806b7d4fc.md)