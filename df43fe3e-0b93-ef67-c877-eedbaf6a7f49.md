

Revit 2026 API

# ColorFillSchemeIsValidParameterDefinitionId Method  
  
---  
  
Checks whether the input parameter id can be applied to the scheme. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public bool IsValidParameterDefinitionId(
	ElementId parameterId
)
```
```vb
Public Function IsValidParameterDefinitionId ( 
	parameterId As ElementId
) As Boolean
```
```cpp
public:
bool IsValidParameterDefinitionId(
	ElementId^ parameterId
)
```
```fsharp
member IsValidParameterDefinitionId : 
        parameterId : ElementId -> bool 
```


#### Parameters

parameterId [ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)
    

#### Return Value

Boolean Returns true if the input parameter id can be set to this scheme, false otherwise. 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
#### Reference

[ColorFillScheme Class](c405eb5b-14fa-0fea-a750-dcd9925a90b0.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)