

Revit 2026 API

# ExportLayerInfoCategoryType Property  
  
---  
  
The category type which this layer belongs to. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public LayerCategoryType CategoryType { get; set; }
```
```vb
Public Property CategoryType As LayerCategoryType
	Get
	Set
```
```cpp
public:
property LayerCategoryType CategoryType {
	LayerCategoryType get ();
	void set (LayerCategoryType value);
}
```
```fsharp
member CategoryType : LayerCategoryType with get, set
```


#### Property Value

[LayerCategoryType](7fc41293-ee24-a6cd-dc71-a5f9941cd0da.md)

| Exception | Condition |
| --- | --- |
| [ArgumentOutOfRangeException](60f148c9-ece0-a6bb-4e12-bb4a9c8c8a24.md) | When setting this property: A value passed for an enumeration argument is not a member of that enumeration |
  
#### Reference

[ExportLayerInfo Class](88a99694-968a-99f7-870a-f46737bd5927.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)