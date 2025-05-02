

Revit 2026 API

# PlanCircuitSetInsert Method  
  
---  
  
Insert the specified item into the set.

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public virtual bool Insert(
	PlanCircuit item
)
```
```vb
Public Overridable Function Insert ( 
	item As PlanCircuit
) As Boolean
```
```cpp
public:
virtual bool Insert(
	PlanCircuit^ item
)
```
```fsharp
abstract Insert : 
        item : PlanCircuit -> bool 
override Insert : 
        item : PlanCircuit -> bool 
```


#### Parameters

item [PlanCircuit](9fdb77cb-c579-1cbd-71de-01f06a18ea3a.md)
    The item to be inserted into the set.

#### Return Value

BooleanReturns whether the item was inserted into the set.

#### Reference

[PlanCircuitSet Class](8398c79d-1108-6846-cc0c-b7b2b5c1d026.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)