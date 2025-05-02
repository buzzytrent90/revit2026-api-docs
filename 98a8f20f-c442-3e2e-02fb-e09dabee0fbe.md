

Revit 2026 API

# ViewScheduleCreateKeySchedule Method  
  
---  
  
Create a key schedule. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static ViewSchedule CreateKeySchedule(
	Document document,
	ElementId categoryId
)
```
```vb
Public Shared Function CreateKeySchedule ( 
	document As Document,
	categoryId As ElementId
) As ViewSchedule
```
```cpp
public:
static ViewSchedule^ CreateKeySchedule(
	Document^ document, 
	ElementId^ categoryId
)
```
```fsharp
static member CreateKeySchedule : 
        document : Document * 
        categoryId : ElementId -> ViewSchedule 
```


#### Parameters

document [Document](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)
     The document to which the new schedule will be added. 
categoryId [ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md)
     The ID of the category of elements that the schedule's keys will be associated with. 

#### Return Value

[ViewSchedule](0dae24ba-5dcb-9a34-cccc-0cf8cc52bcd3.md) The newly created schedule. 

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | document is not a project document. -or- categoryId is not a valid category for a key schedule. |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
| [ModificationForbiddenException](53205486-5917-7c33-8e67-e362106ddc97.md) | The document is in failure mode: an operation has failed, and Revit requires the user to either cancel the operation or fix the problem (usually by deleting certain elements). -or- The document is being loaded, or is in the midst of another sensitive process. |
| [ModificationOutsideTransactionException](8f025460-c283-ea99-aa8a-5a36e11528f4.md) | The document has no open transaction. |
  
A key schedule displays abstract "key" elements that can be used to populate parameters of ordinary model elements. 

#### Reference

[ViewSchedule Class](0dae24ba-5dcb-9a34-cccc-0cf8cc52bcd3.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)