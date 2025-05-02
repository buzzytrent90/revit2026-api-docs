

Revit 2026 API

# TableDataIsEqual Method  
  
---  
  
Checks if this element is equal in value to the other element. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public bool IsEqual(
	TableData OtherElem
)
```
```vb
Public Function IsEqual ( 
	OtherElem As TableData
) As Boolean
```
```cpp
public:
bool IsEqual(
	TableData^ OtherElem
)
```
```fsharp
member IsEqual : 
        OtherElem : TableData -> bool 
```


#### Parameters

OtherElem [TableData](ab967e17-822e-fd5f-760a-4810e2e7eb61.md)
    

#### Return Value

Boolean

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
#### Reference

[TableData Class](ab967e17-822e-fd5f-760a-4810e2e7eb61.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)