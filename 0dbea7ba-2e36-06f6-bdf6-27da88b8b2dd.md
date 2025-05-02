

Revit 2026 API

# AirSystemDataIsValidObject Property  
  
---  
  
Specifies whether the .NET object represents a valid Revit entity. 

**Namespace:** [Autodesk.Revit.DB.Mechanical](0eafd899-5912-56fd-94b1-d286156e26fc.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public bool IsValidObject { get; }
```
```vb
Public ReadOnly Property IsValidObject As Boolean
	Get
```
```cpp
public:
property bool IsValidObject {
	bool get ();
}
```
```fsharp
member IsValidObject : bool with get
```


#### Return Value

Boolean True if the API object holds a valid Revit native object, false otherwise. 

If the corresponding Revit native object is destroyed, or creation of the corresponding object is undone, a managed API object containing it is no longer valid. API methods cannot be called on invalidated wrapper objects. 

#### Reference

[AirSystemData Class](4a7c39a1-cd35-4828-97b7-f70cbd3fdab8.md)

[Autodesk.Revit.DB.Mechanical Namespace](0eafd899-5912-56fd-94b1-d286156e26fc.md)