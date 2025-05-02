

Revit 2026 API

# RadioButtonGroupData Constructor  
  
---  
  
Constructs a new instance of RadioButtonGroupData.

**Namespace:** [Autodesk.Revit.UI](e86fd90a-8957-02a6-da7f-ced248966e3e.md)**Assembly:** RevitAPIUI (in RevitAPIUI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public RadioButtonGroupData(
	string name
)
```
```vb
Public Sub New ( 
	name As String
)
```
```cpp
public:
RadioButtonGroupData(
	String^ name
)
```
```fsharp
new : 
        name : string -> RadioButtonGroupData
```


#### Parameters

name String
    The internal name of the RadioButtonGroup.

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | Thrown when  is passed for name. |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | Thrown when an empty string is passed for name. |
  
#### Reference

[RadioButtonGroupData Class](eeda7b4e-226f-b9a2-12d8-6768d295ca4a.md)

[Autodesk.Revit.UI Namespace](e86fd90a-8957-02a6-da7f-ced248966e3e.md)