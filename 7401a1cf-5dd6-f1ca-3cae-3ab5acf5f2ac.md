

Revit 2026 API

# TextBoxEnterPressed Event  
  
---  
  
Subscribe to this event to be notified when the Enter button is pressed in the text box. 

**Namespace:** [Autodesk.Revit.UI](e86fd90a-8957-02a6-da7f-ced248966e3e.md)**Assembly:** RevitAPIUI (in RevitAPIUI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public event EventHandler<TextBoxEnterPressedEventArgs> EnterPressed
```
```vb
Public Event EnterPressed As EventHandler(Of TextBoxEnterPressedEventArgs)
```
```cpp
public:
 event EventHandler<TextBoxEnterPressedEventArgs^>^ EnterPressed {
	void add (EventHandler<TextBoxEnterPressedEventArgs^>^ value);
	void remove (EventHandler<TextBoxEnterPressedEventArgs^>^ value);
}
```
```fsharp
member EnterPressed : IEvent<EventHandler<TextBoxEnterPressedEventArgs>,
    TextBoxEnterPressedEventArgs>
```


#### Value

EventHandler[TextBoxEnterPressedEventArgs](1e00abfd-8c82-f8ab-4231-6dca5f85af77.md)

#### Reference

[TextBox Class](5cfff6ff-3982-e8f7-a3c8-43d93204d41a.md)

[Autodesk.Revit.UI Namespace](e86fd90a-8957-02a6-da7f-ced248966e3e.md)