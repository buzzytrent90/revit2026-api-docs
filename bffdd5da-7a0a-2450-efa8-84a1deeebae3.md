

Revit 2026 API

# FileArgumentAlreadyExistsException Class  
  
---  
  
The exception that is thrown when the specified file exists.

SystemObject SystemException [Autodesk.Revit.ExceptionsApplicationException](05012a96-16ea-ace7-6115-b45406dacead.md) [Autodesk.Revit.ExceptionsArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) Autodesk.Revit.ExceptionsFileArgumentAlreadyExistsException

**Namespace:** [Autodesk.Revit.Exceptions](e3bbc463-dccb-6964-e8ef-697c9ed07a27.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
[SerializableAttribute]
public class FileArgumentAlreadyExistsException : ArgumentException
```
```vb
<SerializableAttribute>
Public Class FileArgumentAlreadyExistsException
	Inherits ArgumentException
```
```cpp
[SerializableAttribute]
public ref class FileArgumentAlreadyExistsException : public ArgumentException
```
```fsharp
[<SerializableAttribute>]
type FileArgumentAlreadyExistsException = 
    class
        inherit ArgumentException
    end
```


The FileArgumentAlreadyExistsException type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | Data | Gets a collection of key/value pairs that provide additional user-defined information about the exception.(Inherited from Exception) |
|  | [FunctionId](84bd650f-9f87-dccb-4dd4-b23ca890b8b9.md) | The information of the function throwing the exception.(Inherited from [ApplicationException](05012a96-16ea-ace7-6115-b45406dacead.md)) |
|  | HelpLink | Gets or sets a link to the help file associated with this exception.(Inherited from Exception) |
|  | HResult | Gets or sets HRESULT, a coded numerical value that is assigned to a specific exception.(Inherited from Exception) |
|  | InnerException | Gets the Exception instance that caused the current exception.(Inherited from Exception) |
|  | [Message](c2498b95-ccc5-95cc-d5c2-7e732615e940.md) | Gets the error message and the parameter name, or only the error message if no parameter name is set.(Inherited from [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md)) |
|  | [ParamName](cf17c2e6-aa4a-3d6a-6fd2-fad6395336df.md) | Gets the name of the parameter that causes this exception.(Inherited from [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md)) |
|  | Source | Gets or sets the name of the application or the object that causes the error.(Inherited from Exception) |
|  | StackTrace | Gets a string representation of the immediate frames on the call stack.(Inherited from Exception) |
|  | TargetSite | Gets the method that throws the current exception.(Inherited from Exception) |
  
|  | Name | Description |
| --- | --- | --- |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | GetBaseException | When overridden in a derived class, returns the Exception that is the root cause of one or more subsequent exceptions.(Inherited from Exception) |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | [GetObjectData](d01390ec-78c9-cdd3-3b0a-2964be908358.md) | Retrieves data needed to serialize the target object.(Overrides [ArgumentExceptionGetObjectData(SerializationInfo, StreamingContext)](ffd259c2-53ec-f232-02e1-135ba0a6ccfd.md)) |
|  | GetType | Gets the runtime type of the current instance.(Inherited from Exception) |
|  | ToString | Creates and returns a string representation of the current exception.(Inherited from Exception) |
  
#### Reference

[Autodesk.Revit.Exceptions Namespace](e3bbc463-dccb-6964-e8ef-697c9ed07a27.md)