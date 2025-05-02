

Revit 2026 API

# DocumentSetInsert Method  
  
---  
  
Insert the specified item into the set.

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public virtual bool Insert(
	Document item
)
```
```vb
Public Overridable Function Insert ( 
	item As Document
) As Boolean
```
```cpp
public:
virtual bool Insert(
	Document^ item
)
```
```fsharp
abstract Insert : 
        item : Document -> bool 
override Insert : 
        item : Document -> bool 
```


#### Parameters

item [Document](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)
    The item to be inserted into the set.

#### Return Value

BooleanReturns whether the item was inserted into the set.

#### Reference

[DocumentSet Class](e1951076-29d2-4817-18d9-a01847fa812a.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)