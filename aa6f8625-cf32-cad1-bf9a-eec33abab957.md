

Revit 2026 API

# WorksetTableRenameWorkset Method  
  
---  
  
Renames the workset. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static void RenameWorkset(
	Document aDoc,
	WorksetId worksetId,
	string name
)
```
```vb
Public Shared Sub RenameWorkset ( 
	aDoc As Document,
	worksetId As WorksetId,
	name As String
)
```
```cpp
public:
static void RenameWorkset(
	Document^ aDoc, 
	WorksetId^ worksetId, 
	String^ name
)
```
```fsharp
static member RenameWorkset : 
        aDoc : Document * 
        worksetId : WorksetId * 
        name : string -> unit 
```


#### Parameters

aDoc [Document](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)
     The document in which the workset is accessed. 
worksetId [WorksetId](8bece327-c269-8101-b4c2-38632f593fe6.md)
     The workset Id. 
name String
     The workset name. 

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | aDoc is not a workshared document. -or- name is an empty string or contains only whitespace. -or- name cannot include prohibited characters, such as "{, }, [, ], | , ;, less-than sign, greater-than sign, ?, `, ~". -or- The given workset name is already in use. -or- There is no workset in the document with this id. |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
| [ModificationForbiddenException](53205486-5917-7c33-8e67-e362106ddc97.md) | The document is in failure mode: an operation has failed, and Revit requires the user to either cancel the operation or fix the problem (usually by deleting certain elements). -or- The document is being loaded, or is in the midst of another sensitive process. |
| [ModificationOutsideTransactionException](8f025460-c283-ea99-aa8a-5a36e11528f4.md) | The document has no open transaction. |
  
#### Reference

[WorksetTable Class](9ffa5fc8-e6a5-17d6-590e-8ecbfd7b85fb.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)