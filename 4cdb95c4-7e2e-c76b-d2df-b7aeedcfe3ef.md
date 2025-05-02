

Revit 2026 API

# ScheduleSortGroupFieldShowHeader Property  
  
---  
  
Indicates if a header row should be displayed before each group. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public bool ShowHeader { get; set; }
```
```vb
Public Property ShowHeader As Boolean
	Get
	Set
```
```cpp
public:
property bool ShowHeader {
	bool get ();
	void set (bool value);
}
```
```fsharp
member ShowHeader : bool with get, set
```


#### Property Value

Boolean True if a header row should be displayed, false otherwise. 

The header row displays a title consisting of the value of the field that the schedule is grouped by. 

#### Reference

[ScheduleSortGroupField Class](526680eb-ea68-35a7-b0c5-d63459fac04d.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)