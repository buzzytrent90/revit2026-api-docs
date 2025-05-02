

Revit 2026 API

# DividedPathIsValidSpacingRuleLayout Method  
  
---  
  
Checks that the spacing rule layout enumeration value is valid 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public bool IsValidSpacingRuleLayout(
	SpacingRuleLayout layout
)
```
```vb
Public Function IsValidSpacingRuleLayout ( 
	layout As SpacingRuleLayout
) As Boolean
```
```cpp
public:
bool IsValidSpacingRuleLayout(
	SpacingRuleLayout layout
)
```
```fsharp
member IsValidSpacingRuleLayout : 
        layout : SpacingRuleLayout -> bool 
```


#### Parameters

layout [SpacingRuleLayout](163b0cc7-31f0-68b4-ced5-bea6d3c5abcc.md)
    

#### Return Value

Boolean

| Exception | Condition |
| --- | --- |
| [ArgumentOutOfRangeException](60f148c9-ece0-a6bb-4e12-bb4a9c8c8a24.md) | A value passed for an enumeration argument is not a member of that enumeration |
  
#### Reference

[DividedPath Class](8043b21a-7c78-e0cb-f7b3-495ace05de87.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)