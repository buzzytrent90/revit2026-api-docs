

Revit 2026 API

# ScheduleFieldMultipleValuesCustomText Property  
  
---  
  
The custom multiple values text to be used when the schedule field displays multiple element values, used when [MultipleValuesDisplayType](64592725-4f20-d2a0-010d-220a9315ff39.md) is set to [Custom](cc6f0e5f-958c-8062-2b8f-b443b0fae708.md). 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public string MultipleValuesCustomText { get; set; }
```
```vb
Public Property MultipleValuesCustomText As String
	Get
	Set
```
```cpp
public:
property String^ MultipleValuesCustomText {
	String^ get ();
	void set (String^ value);
}
```
```fsharp
member MultipleValuesCustomText : string with get, set
```


#### Property Value

String

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | When setting this property: A non-optional argument was null |
  
#### Reference

[ScheduleField Class](3d6b0eb5-ed36-278d-a5df-38b6d600e876.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)