

Revit 2026 API

# BuildingOperatingDayScheduleGetValueForHour Method  
  
---  
  
Gets the usage value for an hour. 

**Namespace:** [Autodesk.Revit.DB.Analysis](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public double GetValueForHour(
	int hour
)
```
```vb
Public Function GetValueForHour ( 
	hour As Integer
) As Double
```
```cpp
public:
double GetValueForHour(
	int hour
)
```
```fsharp
member GetValueForHour : 
        hour : int -> float 
```


#### Parameters

hour Int32
     The hour in the day, as an integer. For example: 0 is 12:00 midnight to 1:00 am, 6 is 6:00 am to 7:00 am, 12 is 12:00 noon to 1:00 pm, and 23 is 11:00 pm to midnight. To avoid issues around daylight savings times, these hours represent 1/24 of an earth rotation, and will not be exactly 60 minutes. 

#### Return Value

Double The usage as a fraction between 0 and 1 inclusive. For example: 0 in a lighting schedule means all lights are off, .5 means half of lights are on, 1 means all lights are on. 

| Exception | Condition |
| --- | --- |
| [ArgumentOutOfRangeException](60f148c9-ece0-a6bb-4e12-bb4a9c8c8a24.md) | hour must be from 0 to 23 inclusive. |
  
#### Reference

[BuildingOperatingDaySchedule Class](b9a7693c-e3ae-72d0-8d15-b377025b90b7.md)

[Autodesk.Revit.DB.Analysis Namespace](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)