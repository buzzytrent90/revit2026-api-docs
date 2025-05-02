

Revit 2026 API

# ApplicationWriteJournalComment Method  
  
---  
  
Writes a comment to the Revit journal file. 

**Namespace:** [Autodesk.Revit.ApplicationServices](91957e18-2935-006c-83ab-3b5b9dbb5928.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public void WriteJournalComment(
	string comment,
	bool timeStamp
)
```
```vb
Public Sub WriteJournalComment ( 
	comment As String,
	timeStamp As Boolean
)
```
```cpp
public:
void WriteJournalComment(
	String^ comment, 
	bool timeStamp
)
```
```fsharp
member WriteJournalComment : 
        comment : string * 
        timeStamp : bool -> unit 
```


#### Parameters

comment String
     Text for journal comment. 
timeStamp Boolean
     If a time stamp should be included in the journal comment. 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
  
#### Reference

[Application Class](94db8ea8-d2c3-5e71-8030-466bcb8e4426.md)

[Autodesk.Revit.ApplicationServices Namespace](91957e18-2935-006c-83ab-3b5b9dbb5928.md)