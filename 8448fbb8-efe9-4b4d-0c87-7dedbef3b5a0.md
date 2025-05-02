

Revit 2026 API

# ViewScheduleExportOptionsTextQualifier Property  
  
---  
  
How to qualify text fields. Default is DoubleQuote. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public ExportTextQualifier TextQualifier { get; set; }
```
```vb
Public Property TextQualifier As ExportTextQualifier
	Get
	Set
```
```cpp
public:
property ExportTextQualifier TextQualifier {
	ExportTextQualifier get ();
	void set (ExportTextQualifier value);
}
```
```fsharp
member TextQualifier : ExportTextQualifier with get, set
```


#### Property Value

[ExportTextQualifier](21d248e0-364a-8e01-3a43-dfc34fb979bc.md)

| Exception | Condition |
| --- | --- |
| [ArgumentOutOfRangeException](60f148c9-ece0-a6bb-4e12-bb4a9c8c8a24.md) | When setting this property: A value passed for an enumeration argument is not a member of that enumeration |
  
#### Reference

[ViewScheduleExportOptions Class](f0bde7ea-ceab-820d-7c55-b09819f21607.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)