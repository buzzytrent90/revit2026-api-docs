

Revit 2026 API

# CentralModelVersionArchivedException Class  
  
---  
  
Exception is thrown when last central version merged into the local model has been archived in the central model. Reload Latest or Synchronized with Central needs to be conducted before the current failed operation is retried. 

SystemObject SystemException [Autodesk.Revit.ExceptionsApplicationException](05012a96-16ea-ace7-6115-b45406dacead.md) [Autodesk.Revit.ExceptionsCentralModelException](0e2ac15f-ca64-42c3-b3ef-e6f7ca1cb59a.md) Autodesk.Revit.ExceptionsCentralModelVersionArchivedException

**Namespace:** [Autodesk.Revit.Exceptions](e3bbc463-dccb-6964-e8ef-697c9ed07a27.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
[SerializableAttribute]
public class CentralModelVersionArchivedException : CentralModelException
```
```vb
<SerializableAttribute>
Public Class CentralModelVersionArchivedException
	Inherits CentralModelException
```
```cpp
[SerializableAttribute]
public ref class CentralModelVersionArchivedException : public CentralModelException
```
```fsharp
[<SerializableAttribute>]
type CentralModelVersionArchivedException = 
    class
        inherit CentralModelException
    end
```


The CentralModelVersionArchivedException type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | Data | Gets a collection of key/value pairs that provide additional user-defined information about the exception.(Inherited from Exception) |
|  | [FunctionId](84bd650f-9f87-dccb-4dd4-b23ca890b8b9.md) | The information of the function throwing the exception.(Inherited from [ApplicationException](05012a96-16ea-ace7-6115-b45406dacead.md)) |
|  | HelpLink | Gets or sets a link to the help file associated with this exception.(Inherited from Exception) |
|  | HResult | Gets or sets HRESULT, a coded numerical value that is assigned to a specific exception.(Inherited from Exception) |
|  | InnerException | Gets the Exception instance that caused the current exception.(Inherited from Exception) |
|  | Message | Gets a message that describes the current exception.(Inherited from Exception) |
|  | Source | Gets or sets the name of the application or the object that causes the error.(Inherited from Exception) |
|  | StackTrace | Gets a string representation of the immediate frames on the call stack.(Inherited from Exception) |
|  | TargetSite | Gets the method that throws the current exception.(Inherited from Exception) |
  
|  | Name | Description |
| --- | --- | --- |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | GetBaseException | When overridden in a derived class, returns the Exception that is the root cause of one or more subsequent exceptions.(Inherited from Exception) |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | [GetObjectData](656ad575-f049-fe8c-644a-d6f65a3058c0.md) | Retrieves data needed to serialize the target object.(Overrides [CentralModelExceptionGetObjectData(SerializationInfo, StreamingContext)](3f70774d-39db-827d-1571-ed5dfd5de9f1.md)) |
|  | GetType | Gets the runtime type of the current instance.(Inherited from Exception) |
|  | ToString | Creates and returns a string representation of the current exception.(Inherited from Exception) |
  
#### Reference

[Autodesk.Revit.Exceptions Namespace](e3bbc463-dccb-6964-e8ef-697c9ed07a27.md)