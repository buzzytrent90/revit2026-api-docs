

Revit 2026 API

# ExportIFCCategoryInfoIFCPresentationLayerName Property  
  
---  
  
The name of the presentation layer mapped to a particular Revit category. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public string IFCPresentationLayerName { get; set; }
```
```vb
Public Property IFCPresentationLayerName As String
	Get
	Set
```
```cpp
public:
property String^ IFCPresentationLayerName {
	String^ get ();
	void set (String^ value);
}
```
```fsharp
member IFCPresentationLayerName : string with get, set
```


#### Property Value

String

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | When setting this property: A non-optional argument was null |
  
#### Reference

[ExportIFCCategoryInfo Class](5da998a3-e973-3b76-5f5d-ed4769fef46e.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)