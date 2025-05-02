

Revit 2026 API

# ElementGetParameters Method  
  
---  
  
Retrieves the parameters from the element via the given name.

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public IList<Parameter> GetParameters(
	string name
)
```
```vb
Public Function GetParameters ( 
	name As String
) As IList(Of Parameter)
```
```cpp
public:
IList<Parameter^>^ GetParameters(
	String^ name
)
```
```fsharp
member GetParameters : 
        name : string -> IList<Parameter> 
```


#### Parameters

name String
    The name of the parameter to be retrieved.

#### Return Value

IList[Parameter](333ff41b-e6a7-d959-60bf-c3bfae495581.md) A collection containing the parameters having the same given parameter name. 

Multiple matches of parameters with the same name can occur because shared parameters or project parameters can be bound to an element category even if there is a built-in parameter with the same name already. 

If this method is used to find built-in parameters the code will not be portable to other languages of Revit (because built-in parameter names are translated, and this method matches the translation).

For the reasons above this method should be used sparingly and when portability across multiple languages is not a requirement.

Safer approaches include:

  * get_Parameter(Guid) to get a shared parameter by stored guid.
  * get_Parameter(BuiltInParameter) to find a built-in parameter in a language-independent way.



#### Reference

[Element Class](eb16114f-69ea-f4de-0d0d-f7388b105a16.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)