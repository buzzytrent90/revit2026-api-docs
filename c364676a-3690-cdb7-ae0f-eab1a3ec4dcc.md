

Revit 2026 API

# PanelScheduleViewIsSpace Method  
  
---  
  
Check if the selected cell is a space 

**Namespace:** [Autodesk.Revit.DB.Electrical](212a1314-7843-2c6c-3322-363127e4059f.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public bool IsSpace(
	int nRow,
	int nCol
)
```
```vb
Public Function IsSpace ( 
	nRow As Integer,
	nCol As Integer
) As Boolean
```
```cpp
public:
bool IsSpace(
	int nRow, 
	int nCol
)
```
```fsharp
member IsSpace : 
        nRow : int * 
        nCol : int -> bool 
```


#### Parameters

nRow Int32
     Row Number 
nCol Int32
     Column Number 

#### Return Value

Boolean True if the selected cell is a space, false otherwise 

#### Reference

[PanelScheduleView Class](ef4390e8-5a93-fe7f-580b-c8ec297f6b52.md)

[Autodesk.Revit.DB.Electrical Namespace](212a1314-7843-2c6c-3322-363127e4059f.md)