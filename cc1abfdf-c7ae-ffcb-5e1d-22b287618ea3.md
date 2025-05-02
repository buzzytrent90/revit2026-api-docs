

Revit 2026 API

# AssetPropertyDoubleArray3dIsValidValue Method  
  
---  
  
Checks that the value is a valid value for this property. 

**Namespace:** [Autodesk.Revit.DB.Visual](f5a10581-6ac2-be19-0e32-f87d05bc8b83.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public bool IsValidValue(
	XYZ xyz
)
```
```vb
Public Function IsValidValue ( 
	xyz As XYZ
) As Boolean
```
```cpp
public:
bool IsValidValue(
	XYZ^ xyz
)
```
```fsharp
member IsValidValue : 
        xyz : XYZ -> bool 
```


#### Parameters

xyz [XYZ](c2fd995c-95c0-58fb-f5de-f3246cbc5600.md)
     The value to be checked. 

#### Return Value

Boolean True if the value is valid for the property. 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | Cannot check validity for a property not being edited in AppearanceAssetEditScope. |
  
#### Reference

[AssetPropertyDoubleArray3d Class](f0623332-e4b1-3b6f-7247-8ee16a27251c.md)

[Autodesk.Revit.DB.Visual Namespace](f5a10581-6ac2-be19-0e32-f87d05bc8b83.md)