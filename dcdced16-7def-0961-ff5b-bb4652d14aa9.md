

Revit 2026 API

# FabricationPartSpecification Property  
  
---  
  
The fabrication part specification identifier. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public int Specification { get; set; }
```
```vb
Public Property Specification As Integer
	Get
	Set
```
```cpp
public:
property int Specification {
	int get ();
	void set (int value);
}
```
```fsharp
member Specification : int with get, set
```


#### Property Value

Int32

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | When setting this property: the specification is invalid for the fabrication part. |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | When setting this property: the specification is not able to be modified. -or- When setting this property: the fabrication part is connected to more than one item. -or- When setting this property: the specification fails to be set by identifier: specId. |
  
A value of 0 indicates the specification is set to undefined. 

#### Reference

[FabricationPart Class](c9b86162-c105-696a-a919-49a7a7938cc4.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)