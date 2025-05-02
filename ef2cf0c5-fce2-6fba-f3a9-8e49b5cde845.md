

Revit 2026 API

# PrintSetupSave Method  
  
---  
  
Save the changes for the current print setting.

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public bool Save()
```
```vb
Public Function Save As Boolean
```
```cpp
public:
bool Save()
```
```fsharp
member Save : unit -> bool 
```


#### Return Value

BooleanFalse if save operation fails, otherwise True.

| Exception | Condition |
| --- | --- |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | Thrown when the current print setting is In-Session or the current print setting has not changed. |
  
#### Reference

[PrintSetup Class](9dc30afc-373c-a532-6c89-ff3fa2b3ceed.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)