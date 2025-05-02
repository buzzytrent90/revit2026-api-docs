

Revit 2026 API

# TransactionGetStatus Method  
  
---  
  
Returns the current status of the transaction. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public TransactionStatus GetStatus()
```
```vb
Public Function GetStatus As TransactionStatus
```
```cpp
public:
TransactionStatus GetStatus()
```
```fsharp
member GetStatus : unit -> TransactionStatus 
```


#### Return Value

[TransactionStatus](29b9a7a8-6754-8310-e063-622b569bb6d5.md) The current status of the transaction. 

If the status was set to TransactionStatus.Pending as the result of calling Commit or RollBack, the status will be changed later to either 'Committed' or 'RolledBack' after failure handling is finished. That status change will be made asynchronously. 

#### Reference

[Transaction Class](308ebf8d-d96d-4643-cd1d-34fffcea53fd.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)