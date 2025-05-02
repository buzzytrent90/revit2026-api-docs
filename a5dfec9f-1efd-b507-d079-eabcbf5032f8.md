

Revit 2026 API

# ScheduleFilter Class  
  
---  
  
A filter in a schedule. 

SystemObject Autodesk.Revit.DBScheduleFilter

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class ScheduleFilter : IDisposable
```
```vb
Public Class ScheduleFilter
	Implements IDisposable
```
```cpp
public ref class ScheduleFilter : IDisposable
```
```fsharp
type ScheduleFilter = 
    class
        interface IDisposable
    end
```


The ScheduleFilter type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [ScheduleFilter](aa3c48a1-94c7-a3dd-1b20-faa87fe1a23e.md) | Creates a new ScheduleFilter. |
|  | [ScheduleFilter(ScheduleFieldId, ScheduleFilterType)](cdde2306-7abe-15d5-dc37-39b23f916dbd.md) | Creates a new ScheduleFilter. |
|  | [ScheduleFilter(ScheduleFieldId, ScheduleFilterType, ElementId)](4ac7ace5-54dd-ef66-3e7d-b9503c5a7f75.md) | Creates a new ScheduleFilter. |
|  | [ScheduleFilter(ScheduleFieldId, ScheduleFilterType, Double)](1eedd87b-7ab3-e586-411d-241c5fa15eca.md) | Creates a new ScheduleFilter. |
|  | [ScheduleFilter(ScheduleFieldId, ScheduleFilterType, Int32)](979e8984-99f3-587c-648d-9dd21db7ef90.md) | Creates a new ScheduleFilter. |
|  | [ScheduleFilter(ScheduleFieldId, ScheduleFilterType, String)](6ec07804-d396-ad9b-d0b8-08b37b3b9ae7.md) | Creates a new ScheduleFilter. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [FieldId](c11c4781-9acd-baf9-692d-93bf4ab9c86e.md) | The ID of the field used to filter the schedule. |
|  | [FilterType](bbf3558f-d6a6-1f19-1f89-d51e68072baa.md) | The filter type. |
|  | [IsDoubleValue](27d2efc3-39f8-ba90-06e3-454c7889284c.md) | Indicates if the filter has a double value. |
|  | [IsElementIdValue](e96b8bef-b3e3-1a77-f2f5-4ec524f9fcd6.md) | Indicates if the filter has an ElementId value. |
|  | [IsIntegerValue](7e3e7135-4c1a-2c8b-1e77-15dcf80ec72e.md) | Indicates if the filter has an integer value. |
|  | [IsNullValue](40a03966-e5bd-237c-121c-23e9b28b5a82.md) | Indicates if the filter has no specified value. |
|  | [IsStringValue](6f4ef6ca-b44c-dd64-32e1-dd1bc236f89a.md) | Indicates if the filter has a string value. |
|  | [IsValidObject](eb738886-34c0-5603-c330-e94a88927381.md) | Specifies whether the .NET object represents a valid Revit entity. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Dispose](6830e4c4-13dc-5e85-5d0c-715de0a52bf1.md) | Releases all resources used by the ScheduleFilter |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | [GetDoubleValue](9c1cce12-0cf2-35d6-0a3d-fe9caff8faf0.md) | Gets the filter value for a filter using a double value. |
|  | [GetElementIdValue](3ee4da28-2a21-f9a3-0b58-03286ec21bfc.md) | Gets the filter value for a filter using an ElementId value. |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | [GetIntegerValue](f2fc20ab-05c6-2b2c-80dd-86a93d0ddd4c.md) | Gets the filter value for a filter using an integer value. |
|  | [GetStringValue](1bd344af-4984-367d-f8a6-769f7fb0d093.md) | Gets the filter value for a filter using a string value. |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | [SetNullValue](2c193a4c-37fd-0b4d-a026-d9dfd773c16b.md) | Sets the filter to have no specified value (used for HasParameter filters). |
|  | [SetValue(Double)](c510b2ca-b22d-789f-b329-58efd5713da0.md) | Set the filter value to a double. |
|  | [SetValue(ElementId)](768e344c-4e15-866f-4cb1-84fe74d549d3.md) | Set the filter value to an ElementId. |
|  | [SetValue(Int32)](2f52924c-8851-6512-c2b0-28205a799c21.md) | Set the filter value to an integer. |
|  | [SetValue(String)](9556c7a1-1bf9-2844-3357-ada1c0f653de.md) | Set the filter value to a string. |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
The ScheduleFilter class represents a single filter in a schedule. A filter is a condition that must be satisfied for an element to appear in the schedule. All filters must be satisfied for an element to appear in the schedule.

A schedule can be filtered by data that is not displayed in the schedule by marking the field used for filtering as hidden using the ScheduleField.IsHidden property.

#### Reference

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)