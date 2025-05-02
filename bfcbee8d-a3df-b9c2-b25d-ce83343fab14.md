

Revit 2026 API

# INavisworksExporterValidateExportOptions Method  
  
---  
  
Determines if the inputs are valid, and returns an error message if not. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
bool ValidateExportOptions(
	Document document,
	string folder,
	string name,
	NavisworksExportOptions options,
	out string exceptionMessage
)
```
```vb
Function ValidateExportOptions ( 
	document As Document,
	folder As String,
	name As String,
	options As NavisworksExportOptions,
	<OutAttribute> ByRef exceptionMessage As String
) As Boolean
```
```cpp
bool ValidateExportOptions(
	Document^ document, 
	String^ folder, 
	String^ name, 
	NavisworksExportOptions^ options, 
	[OutAttribute] String^% exceptionMessage
)
```
```fsharp
abstract ValidateExportOptions : 
        document : Document * 
        folder : string * 
        name : string * 
        options : NavisworksExportOptions * 
        exceptionMessage : string byref -> bool 
```


#### Parameters

document [Document](db03274b-a107-aa32-9034-f3e0df4bb1ec.md)
     The document to export. 
folder String
     The folder path. 
name String
     The file name. 
options [NavisworksExportOptions](a58dbe71-1be7-dad6-51b6-5386c162cf87.md)
     The export options. 
exceptionMessage String
     The message to show in the exception thrown. This is not an end-user visible message, it is a developer message, and does not have to be localized. Ignored if the function returns true. 

#### Return Value

Boolean True if the options are valid, false otherwise. 

#### Reference

[INavisworksExporter Interface](b389017c-d7af-f0a4-7440-e9dc30f47718.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)