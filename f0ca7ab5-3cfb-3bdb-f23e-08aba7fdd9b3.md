

Revit 2026 API

# FilteredWorksetIteratorGetCurrent Method  
  
---  
  
The current workset found by the iterator. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public Workset GetCurrent()
```
```vb
Public Function GetCurrent As Workset
```
```cpp
public:
Workset^ GetCurrent()
```
```fsharp
member GetCurrent : unit -> Workset 
```


#### Return Value

[Workset](aa8f7f05-16c7-2fbf-5004-d819a1fd0b6d.md) The workset. 

| Exception | Condition |
| --- | --- |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | There are no more worksets in the iterator. -or- The FilteredWorksetCollector that yielded this iterator has been reset by another operation. No further iteration is permitted with this iterator. |
  
#### Reference

[FilteredWorksetIterator Class](c80ff08f-7511-ebed-dc44-233d18ad8e87.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)