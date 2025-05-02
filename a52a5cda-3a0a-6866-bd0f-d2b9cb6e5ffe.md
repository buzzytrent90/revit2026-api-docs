

Revit 2026 API

# CustomFieldData Class  
  
---  
  
A class that offer access to the information about a custom field. 

SystemObject Autodesk.Revit.DBCustomFieldData

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class CustomFieldData : IDisposable
```
```vb
Public Class CustomFieldData
	Implements IDisposable
```
```cpp
public ref class CustomFieldData : IDisposable
```
```fsharp
type CustomFieldData = 
    class
        interface IDisposable
    end
```


The CustomFieldData type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [DefaultRowHeightOnSheet](76d96a8d-c4e1-2851-637a-a95623c391dd.md) | Identifies the default row height for this field. |
|  | [FieldName](eb99c50f-1be1-bffe-5939-e61c0a6a9772.md) | The name of this custom field. |
|  | [FieldTooltip](dd30e01e-28dc-11b9-4d46-44f5a38238b5.md) | The tooltip that will be shown in the schedule properties dialog for this custom field. |
|  | [IsValidObject](e64faaa7-4a8d-84a2-4c14-049b2687bc12.md) | Specifies whether the .NET object represents a valid Revit entity. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Dispose](24f965a9-7591-4629-e013-906495d884d6.md) | Releases all resources used by the CustomFieldData |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | [GetCustomFieldId](581bbb81-464e-3a69-3d31-49d1891199c7.md) | Gets an unique identifier of the custom field. |
|  | [GetCustomFieldProperties](9de9b290-c9f0-167c-ed37-952704c046c6.md) | Gets an instance of [ICustomFieldProperties](c468ee3f-5627-b99b-9219-cd807539e228.md) which represents the properties of this field. |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | [SetCustomFieldProperties](a13a0167-411a-3507-99e5-cca3f44d4feb.md) | Sets an instance of [ICustomFieldProperties](c468ee3f-5627-b99b-9219-cd807539e228.md) which represents the properties of this field. |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
|  | [ValidateCustomFieldProperties](e0298fd1-9ae5-584b-3d5b-aac318d93fd0.md) | Validates the custom field properties. |
  
#### Reference

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)