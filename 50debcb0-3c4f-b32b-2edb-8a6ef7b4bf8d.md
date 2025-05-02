

Revit 2026 API

# DocumentEraseSchemaAndAllEntities Method  
  
---  
  
Erases Schema and all its Entities from the document. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public void EraseSchemaAndAllEntities(
	Schema schema
)
```
```vb
Public Sub EraseSchemaAndAllEntities ( 
	schema As Schema
)
```
```cpp
public:
void EraseSchemaAndAllEntities(
	Schema^ schema
)
```
```fsharp
member EraseSchemaAndAllEntities : 
        schema : Schema -> unit 
```


#### Parameters

schema [Schema](9817e7db-8367-ea4e-1769-0488f3faa37f.md)
     The Schema to erase. 

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | No write access to this Schema. |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
| [ModificationForbiddenException](53205486-5917-7c33-8e67-e362106ddc97.md) | The document is in failure mode: an operation has failed, and Revit requires the user to either cancel the operation or fix the problem (usually by deleting certain elements). -or- The document is being loaded, or is in the midst of another sensitive process. |
| [ModificationOutsideTransactionException](8f025460-c283-ea99-aa8a-5a36e11528f4.md) | The document has no open transaction. |
  
The Schema remains in memory. 

#### Reference

[Document Class](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)