

Revit 2026 API

# ViewActivatedEventArgs Class  
  
---  
  
The event arguments used by the ViewActivated event. 

SystemObject SystemEventArgs [Autodesk.Revit.DB.EventsRevitAPIEventArgs](7c98499c-e345-cfda-ef89-48eccd3c9992.md) [Autodesk.Revit.DB.EventsRevitAPIPostEventArgs](93554f52-0145-3454-5697-3f1015e46434.md) [Autodesk.Revit.DB.EventsRevitAPIPostDocEventArgs](7d3fba7a-5efb-6a4c-a49c-16c25f972830.md) Autodesk.Revit.UI.EventsViewActivatedEventArgs

**Namespace:** [Autodesk.Revit.UI.Events](21d3e79a-2484-60b0-b4c6-5cf65cd96039.md)**Assembly:** RevitAPIUI (in RevitAPIUI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class ViewActivatedEventArgs : RevitAPIPostDocEventArgs
```
```vb
Public Class ViewActivatedEventArgs
	Inherits RevitAPIPostDocEventArgs
```
```cpp
public ref class ViewActivatedEventArgs : public RevitAPIPostDocEventArgs
```
```fsharp
type ViewActivatedEventArgs = 
    class
        inherit RevitAPIPostDocEventArgs
    end
```


The ViewActivatedEventArgs type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [Cancellable](a393138a-34b5-1724-aa69-92cef651482b.md) | Indicates whether an event may be cancelled by an event delegate. (Inherited from [RevitAPIEventArgs](7c98499c-e345-cfda-ef89-48eccd3c9992.md)) |
|  | [CurrentActiveView](5e105bf3-a62b-9998-f1b7-32c393f138b1.md) | The view that has just become active. |
|  | [Document](b0a5235e-b2b3-0a29-799c-2ef535a51909.md) | The document associated with the event. (Inherited from [RevitAPIPostDocEventArgs](7d3fba7a-5efb-6a4c-a49c-16c25f972830.md)) |
|  | [IsValidObject](35c0066a-b3dc-9d37-c79e-c29f90713b2d.md) | Specifies whether the .NET object represents a valid Revit entity. (Inherited from [RevitAPIEventArgs](7c98499c-e345-cfda-ef89-48eccd3c9992.md)) |
|  | [PreviousActiveView](1417a2d1-a1cc-8e24-7ee3-7c411d9142ca.md) | The previously active view. |
|  | [Status](01c1c4b6-fc91-0651-3312-4d988073433a.md) | Indicates whether the action associated with this event succeeded, failed, or was cancelled (by an API event handler). (Inherited from [RevitAPIPostEventArgs](93554f52-0145-3454-5697-3f1015e46434.md)) |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Dispose](697794d0-db4b-41ee-90a3-388296ffeefb.md) | (Inherited from [RevitAPIEventArgs](7c98499c-e345-cfda-ef89-48eccd3c9992.md)) |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | [IsCancelled](5627aeaa-9d9c-dcbe-b34f-db40f1c025be.md) | Indicates whether the event is being cancelled. (Inherited from [RevitAPIEventArgs](7c98499c-e345-cfda-ef89-48eccd3c9992.md)) |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
#### Reference

[Autodesk.Revit.UI.Events Namespace](21d3e79a-2484-60b0-b4c6-5cf65cd96039.md)