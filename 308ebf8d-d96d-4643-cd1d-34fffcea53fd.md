

Revit 2026 API

# Transaction Class  
  
---  
  
Transactions are context-like objects that guard any changes made to a Revit model 

SystemObject Autodesk.Revit.DBTransaction

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class Transaction : IDisposable
```
```vb
Public Class Transaction
	Implements IDisposable
```
```cpp
public ref class Transaction : IDisposable
```
```fsharp
type Transaction = 
    class
        interface IDisposable
    end
```


The Transaction type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [Transaction(Document)](36a9e161-5943-3a7d-b022-a2779185d02c.md) | Instantiates a transaction object. |
|  | [Transaction(Document, String)](8ac32652-a440-7f01-81b8-d6a7f2dc7791.md) | Instantiates a transaction object |
  
|  | Name | Description |
| --- | --- | --- |
|  | [IsValidObject](80f24fab-a66b-7bf9-949c-1fbaa360c79d.md) | Specifies whether the .NET object represents a valid Revit entity. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Commit](32714010-7138-f64f-8fde-a310354448e3.md) | Commits all changes made to the model during the transaction. |
|  | [Commit(FailureHandlingOptions)](9e9983d1-bd0d-b476-2dc4-021c56eb2bd7.md) | Commits all changes made to the model during the transaction. |
|  | [Dispose](58d38d85-06cb-58ad-3631-8c2301240c94.md) | Releases all resources used by the Transaction |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | [GetFailureHandlingOptions](f306f808-a753-1585-18ef-57d65e76fad4.md) | Returns the current failure handling options. |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | [GetName](efc9e55a-1457-db92-66ec-84fcfc688552.md) | Returns the transaction's name. |
|  | [GetStatus](fdf98941-eee4-d8af-e3f7-5b6c7ccc3c74.md) | Returns the current status of the transaction. |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | [HasEnded](0287f338-0d0c-aff2-c75b-0aefe452969d.md) | Determines whether the transaction has ended already. |
|  | [HasStarted](425a8103-a11b-4c45-f002-0e7bc602d074.md) | Determines whether the transaction has been started yet. |
|  | [RollBack](bd1e69e9-961e-1c07-f70a-a29b90c6eb97.md) | Rolls back all changes made to the model during the transaction. |
|  | [RollBack(FailureHandlingOptions)](d99de9ee-168e-a114-1255-0cea9f317efb.md) | Rolls back all changes made to the model during the transaction. |
|  | [SetFailureHandlingOptions](1e913cca-f75b-8dfb-b172-5a04f3732b85.md) | Sets options for handling failures to be used when the transaction is being committed or rolled back. |
|  | [SetName](c0283e7f-d261-6016-724c-31ae5cde96a7.md) | Sets the transaction's name. |
|  | [Start](1146fa87-127d-c432-0f51-79a5eb102031.md) | Starts the transaction. |
|  | [Start(String)](5fb266f4-5eca-049f-6a30-f3ed76687409.md) | Starts the transaction with an assigned name. |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
Any change to a document can only be made while there is an active transaction open for that document. Changes do not become part of the document until the active transaction is [committed](32714010-7138-f64f-8fde-a310354448e3.md). Consequently, all changes made in a transaction can be [rolled back](bd1e69e9-961e-1c07-f70a-a29b90c6eb97.md) either explicitly or implicitly by the transaction's destructor.

A document can have only one transaction open at any given time.

Transactions cannot be started when the document is in read-only mode, either permanently or temporarily. See the Document class methods IsReadOnly and IsModifiable for more details.

Transactions in linked documents are not permitted, for linked documents are not allowed to be modified.

If a transaction was started and not finished yet by the time the Transaction object is about to be disposed, the default destructor will roll it back automatically, thus all changes made to the document while this transaction was open will be discarded. It is not recommended to rely on this default behavior though. Instead, it is advised to always call either [Commit](32714010-7138-f64f-8fde-a310354448e3.md) or [RollBack](bd1e69e9-961e-1c07-f70a-a29b90c6eb97.md) explicitly before the transaction object gets disposed. Please note that unless invoked explicitly the actual destruction of an object in managed code might not happen until the object is collected by the garbage collector.

#### Reference

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)