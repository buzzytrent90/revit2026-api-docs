

Revit 2026 API

# FilterStringEndsWith Class  
  
---  
  
Tests whether string values from the document end with a certain string. 

SystemObject [Autodesk.Revit.DBFilterStringRuleEvaluator](ba8dad25-3f85-1fbb-a164-323c3750018c.md) Autodesk.Revit.DBFilterStringEndsWith

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class FilterStringEndsWith : FilterStringRuleEvaluator
```
```vb
Public Class FilterStringEndsWith
	Inherits FilterStringRuleEvaluator
```
```cpp
public ref class FilterStringEndsWith : public FilterStringRuleEvaluator
```
```fsharp
type FilterStringEndsWith = 
    class
        inherit FilterStringRuleEvaluator
    end
```


The FilterStringEndsWith type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [FilterStringEndsWith](155a65a7-2d98-4127-1e7e-bc24ec26517f.md) | Constructs an instance of FilterStringEndsWith. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [IsValidObject](2681c5c1-e859-f664-316a-e3d9d3e6d6b1.md) | Specifies whether the .NET object represents a valid Revit entity. (Inherited from [FilterStringRuleEvaluator](ba8dad25-3f85-1fbb-a164-323c3750018c.md)) |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Dispose](852de747-8837-d13a-5141-fdbbdd66fdce.md) | (Inherited from [FilterStringRuleEvaluator](ba8dad25-3f85-1fbb-a164-323c3750018c.md)) |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | [Evaluate](fcbe6f51-9a2e-10bc-36bb-7705f554bd14.md) | Derived classes override this method to implement the test that determines whether the two given string values satisfy the desired condition or not. (Inherited from [FilterStringRuleEvaluator](ba8dad25-3f85-1fbb-a164-323c3750018c.md)) |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
All string comparisons in this class are performed in the case-insensitive manner. 

#### Reference

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)