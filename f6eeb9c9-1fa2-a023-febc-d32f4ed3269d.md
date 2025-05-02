

Revit 2026 API

# CurtainGridSetIteratorReset Method  
  
---  
  
Bring the iterator back to the start of the set.

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public virtual void Reset()
```
```vb
Public Overridable Sub Reset
```
```cpp
public:
virtual void Reset()
```
```fsharp
abstract Reset : unit -> unit 
override Reset : unit -> unit 
```


#### Implements

IEnumeratorReset

The Reset method will return the iterator back to the start of the set in line with the definition of IEnumerator. Note that you must call MoveNext before the first item can be accessed via the Current property.

#### Reference

[CurtainGridSetIterator Class](b8aa3f5a-d84c-a10b-34a0-4562c2fc2ed3.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)