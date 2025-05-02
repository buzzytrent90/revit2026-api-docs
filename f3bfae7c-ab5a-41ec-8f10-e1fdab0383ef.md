

Revit 2026 API

# KeyBasedTreeEntryGetChildrenKeys Method  
  
---  
  
Gets a collection containing the keys of all children entry objects from this entry. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public IList<string> GetChildrenKeys()
```
```vb
Public Function GetChildrenKeys As IList(Of String)
```
```cpp
public:
IList<String^>^ GetChildrenKeys()
```
```fsharp
member GetChildrenKeys : unit -> IList<string> 
```


#### Return Value

IListString The collection containing the keys of all children entry objects from this entry. 

To look up the entry object corresponding to the child keys using KeyBasedTreeEntries.FindEntry(). 

#### Reference

[KeyBasedTreeEntry Class](119355ca-f9b6-3d6a-b315-6977ac95edbe.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)