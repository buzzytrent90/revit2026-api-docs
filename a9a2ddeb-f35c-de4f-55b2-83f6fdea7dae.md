

Revit 2026 API

# UIApplicationCreateAddInCommandBinding Method  
  
---  
  
Creates a new AddInCommandBinding.

**Namespace:** [Autodesk.Revit.UI](e86fd90a-8957-02a6-da7f-ced248966e3e.md)**Assembly:** RevitAPIUI (in RevitAPIUI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public AddInCommandBinding CreateAddInCommandBinding(
	RevitCommandId revitCommandId
)
```
```vb
Public Function CreateAddInCommandBinding ( 
	revitCommandId As RevitCommandId
) As AddInCommandBinding
```
```cpp
public:
AddInCommandBinding^ CreateAddInCommandBinding(
	RevitCommandId^ revitCommandId
)
```
```fsharp
member CreateAddInCommandBinding : 
        revitCommandId : RevitCommandId -> AddInCommandBinding 
```


#### Parameters

revitCommandId [RevitCommandId](0fb2f851-f469-f739-d6ee-89b40b25c4a2.md)
    The Revit command id to identify the command handler you want to replace. 

#### Return Value

[AddInCommandBinding](a457ac93-b849-d962-8719-2b3910358b04.md)

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | Thrown when uiApplication or revitCommandId is . |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | Thrown when the given command already has been bound. |
  
#### Reference

[UIApplication Class](51ca80e2-3e5f-7dd2-9d95-f210950c72ae.md)

[Autodesk.Revit.UI Namespace](e86fd90a-8957-02a6-da7f-ced248966e3e.md)