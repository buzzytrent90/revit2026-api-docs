

Revit 2026 API

# SubMenuItem Class  
  
---  
  
A class representing a menu flyout. 

SystemObject [Autodesk.Revit.UIMenuItem](7c67e3b0-5649-1705-6522-109ea3703327.md) Autodesk.Revit.UISubMenuItem

**Namespace:** [Autodesk.Revit.UI](e86fd90a-8957-02a6-da7f-ced248966e3e.md)**Assembly:** RevitAPIUI (in RevitAPIUI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class SubMenuItem : MenuItem
```
```vb
Public Class SubMenuItem
	Inherits MenuItem
```
```cpp
public ref class SubMenuItem : public MenuItem
```
```fsharp
type SubMenuItem = 
    class
        inherit MenuItem
    end
```


The SubMenuItem type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [SubMenuItem](529c7a21-19d8-2498-7c53-c25bac2d47d1.md) | Initialize the item data. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [IsValidObject](33600c83-398a-ce60-d63a-5b5728d6a5e1.md) | Specifies whether the .NET object represents a valid Revit entity. (Inherited from [MenuItem](7c67e3b0-5649-1705-6522-109ea3703327.md)) |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Dispose](4b424e0d-48e1-db0f-50ab-3a9318d8ef9f.md) | (Inherited from [MenuItem](7c67e3b0-5649-1705-6522-109ea3703327.md)) |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
To add a child menu, create a new [ContextMenu](a47515a8-389d-ac38-852f-600948ba63e6.md) object and add MenuItem on it, pass the child ContextMenu object to SubMenuItem constructor and create SubMenuItem object, use AddItem() method to add the SubMenuItem object to parent ContextMenu. 

#### Reference

[Autodesk.Revit.UI Namespace](e86fd90a-8957-02a6-da7f-ced248966e3e.md)