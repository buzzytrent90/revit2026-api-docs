

Revit 2026 API

# ExportPatternTableAdd Method  
  
---  
  
Inserts a (key,info) pair into Export pattern table. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public void Add(
	ExportPatternKey exportPatternKey,
	ExportPatternInfo exportPatternInfo
)
```
```vb
Public Sub Add ( 
	exportPatternKey As ExportPatternKey,
	exportPatternInfo As ExportPatternInfo
)
```
```cpp
public:
void Add(
	ExportPatternKey^ exportPatternKey, 
	ExportPatternInfo^ exportPatternInfo
)
```
```fsharp
member Add : 
        exportPatternKey : ExportPatternKey * 
        exportPatternInfo : ExportPatternInfo -> unit 
```


#### Parameters

exportPatternKey [ExportPatternKey](8e55a491-0886-37f5-b867-e4eea95276eb.md)
     The export pattern key to be added. 
exportPatternInfo [ExportPatternInfo](17621c1b-5f57-2a25-6ff9-73dfc67d5024.md)
     The export pattern info to be added. 

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | The key already exists in the table. |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
#### Reference

[ExportPatternTable Class](3e87bc0e-e04b-f76a-2b06-82e951b5aec2.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)