

Revit 2026 API

# CategoriesContains Method  
  
---  
  
Identifies if a category which has the specified name is in the list of top-level categories.

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public override bool Contains(
	string name
)
```
```vb
Public Overrides Function Contains ( 
	name As String
) As Boolean
```
```cpp
public:
virtual bool Contains(
	String^ name
) override
```
```fsharp
abstract Contains : 
        name : string -> bool 
override Contains : 
        name : string -> bool 
```


#### Parameters

name String
    The name of the category to be retrieved.

#### Field Value

BooleanWhether the category exists in the list of top-level categories.

#### Reference

[Categories Class](6708af38-6a62-ead0-88ff-c68bedd88ffe.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)