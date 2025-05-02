

Revit 2026 API

# UIApplicationFabricationPartBrowserChanged Event  
  
---  
  
Subscribe to MEP Fabrication part browser changed event to be notified when MEP Fabrication part browser is updated. 

**Namespace:** [Autodesk.Revit.UI](e86fd90a-8957-02a6-da7f-ced248966e3e.md)**Assembly:** RevitAPIUI (in RevitAPIUI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public event EventHandler<FabricationPartBrowserChangedEventArgs> FabricationPartBrowserChanged
```
```vb
Public Event FabricationPartBrowserChanged As EventHandler(Of FabricationPartBrowserChangedEventArgs)
```
```cpp
public:
 event EventHandler<FabricationPartBrowserChangedEventArgs^>^ FabricationPartBrowserChanged {
	void add (EventHandler<FabricationPartBrowserChangedEventArgs^>^ value);
	void remove (EventHandler<FabricationPartBrowserChangedEventArgs^>^ value);
}
```
```fsharp
member FabricationPartBrowserChanged : IEvent<EventHandler<FabricationPartBrowserChangedEventArgs>,
    FabricationPartBrowserChangedEventArgs>
```


#### Value

EventHandler[FabricationPartBrowserChangedEventArgs](2af49738-a0c3-0e9b-f344-0f39d15dbd49.md)

More docs about the different conditions goes here

#### Reference

[UIApplication Class](51ca80e2-3e5f-7dd2-9d95-f210950c72ae.md)

[Autodesk.Revit.UI Namespace](e86fd90a-8957-02a6-da7f-ced248966e3e.md)