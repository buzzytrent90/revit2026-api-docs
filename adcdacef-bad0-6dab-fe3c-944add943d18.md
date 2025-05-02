

Revit 2026 API

# ConnectorWidth Property  
  
---  
  
The width of the connector.

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public virtual double Width { get; set; }
```
```vb
Public Overridable Property Width As Double
	Get
	Set
```
```cpp
public:
virtual property double Width {
	double get ();
	void set (double value);
}
```
```fsharp
abstract Width : float with get, set
override Width : float with get, set
```


#### Property Value

Double

#### Implements

[IConnectorWidth](92181844-bac8-96ab-eeac-bf4e62339f82.md)

| Exception | Condition |
| --- | --- |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | Thrown when the connector's shape is not rectangular. |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | Thrown when the argument is invalid. |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | Thrown on failure to set width. |
  
In order to set this property, it must be mapped to a writable instance parameter in the family definition.

#### Reference

[Connector Class](11e07082-b3f2-26a1-de79-16535f44716c.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)