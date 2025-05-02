

Revit 2026 API

# AlignmentStationLabelCreateSet Method  
  
---  
  
Creates a collection of [AlignmentStationLabel](5c51c34b-8b34-99fe-d8c6-b6f1ba7caba7.md) objects along with their underlying [SpotDimension](f3c633ac-1595-cb8d-5c1b-66eb3eefb433.md) elements. 

**Namespace:** [Autodesk.Revit.DB.Infrastructure](cedea963-42a0-acf8-0f0e-5477c4212ae9.md)**Assembly:** Autodesk.CivilAlignments.DBApplication (in Autodesk.CivilAlignments.DBApplication.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static ICollection<AlignmentStationLabel> CreateSet(
	Alignment alignment,
	View view,
	AlignmentStationLabelSetOptions options
)
```
```vb
Public Shared Function CreateSet ( 
	alignment As Alignment,
	view As View,
	options As AlignmentStationLabelSetOptions
) As ICollection(Of AlignmentStationLabel)
```
```cpp
public:
static ICollection<AlignmentStationLabel^>^ CreateSet(
	Alignment^ alignment, 
	View^ view, 
	AlignmentStationLabelSetOptions^ options
)
```
```fsharp
static member CreateSet : 
        alignment : Alignment * 
        view : View * 
        options : AlignmentStationLabelSetOptions -> ICollection<AlignmentStationLabel> 
```


#### Parameters

alignment [Alignment](6594712d-3b22-9b08-ab4c-782df88f36d1.md)
    The alignment on which the alignment station label is placed.
view [View](fb92a4e7-f3a7-ef14-e631-342179b18de9.md)
    The view for which the alignment station label is created.
options [AlignmentStationLabelSetOptions](15f4337d-738d-ec32-e7bc-4f2c569f4c59.md)
    The alignment station options of the label set to be created.

#### Return Value

ICollection[AlignmentStationLabel](5c51c34b-8b34-99fe-d8c6-b6f1ba7caba7.md)

#### Reference

[AlignmentStationLabel Class](5c51c34b-8b34-99fe-d8c6-b6f1ba7caba7.md)

[Autodesk.Revit.DB.Infrastructure Namespace](cedea963-42a0-acf8-0f0e-5477c4212ae9.md)