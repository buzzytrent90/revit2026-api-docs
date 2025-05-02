

Revit 2026 API

# PrintManagerPrintOrderReverse Property  
  
---  
  
Indicates whether to reverse the print order of the current print. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public bool PrintOrderReverse { get; set; }
```
```vb
Public Property PrintOrderReverse As Boolean
	Get
	Set
```
```cpp
public:
property bool PrintOrderReverse {
	bool get ();
	void set (bool value);
}
```
```fsharp
member PrintOrderReverse : bool with get, set
```


#### Property Value

Boolean

The value of this property represents the global print setting property used for print operations on any document. In order to make a change to this property, after setting it call the Apply() method, or one of the SubmitPrint() methods, which save the local changes as modifications to the global print settings. 

#### Reference

[PrintManager Class](29599e18-cad8-813e-dc6e-04350fe37944.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)