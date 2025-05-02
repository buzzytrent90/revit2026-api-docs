

Revit 2026 API

# ViewSetSketchyLines Method  
  
---  
  
Sets the sketchy lines settings for the view. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public void SetSketchyLines(
	ViewDisplaySketchyLines sketchyLines
)
```
```vb
Public Sub SetSketchyLines ( 
	sketchyLines As ViewDisplaySketchyLines
)
```
```cpp
public:
void SetSketchyLines(
	ViewDisplaySketchyLines^ sketchyLines
)
```
```fsharp
member SetSketchyLines : 
        sketchyLines : ViewDisplaySketchyLines -> unit 
```


#### Parameters

sketchyLines [ViewDisplaySketchyLines](c92b463b-1b59-695d-f06b-a76dacfaf2f0.md)
     Sketchy Lines settings to set. 

| Exception | Condition |
| --- | --- |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | This view does not contain display-related properties. |
  
#### Reference

[View Class](fb92a4e7-f3a7-ef14-e631-342179b18de9.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)