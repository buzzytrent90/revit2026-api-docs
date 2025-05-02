

Revit 2026 API

# IFCImportOptions Class  
  
---  
  
IFC Import options. 

SystemObject Autodesk.Revit.DB.IFCIFCImportOptions

**Namespace:** [Autodesk.Revit.DB.IFC](b823fafb-1ba1-896b-4097-142c2817ce74.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class IFCImportOptions : IDisposable
```
```vb
Public Class IFCImportOptions
	Implements IDisposable
```
```cpp
public ref class IFCImportOptions : IDisposable
```
```fsharp
type IFCImportOptions = 
    class
        interface IDisposable
    end
```


The IFCImportOptions type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [IFCImportOptions](303d5cc5-8885-e5ad-fd84-304abda7ee5b.md) | Constructs a new IFCImportOptions using default settings. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Action](070af608-cb1e-43d5-f3ca-6d53150f9dbb.md) | The action of the import. |
|  | [AutocorrectOffAxisLines](7c134ff4-e2e3-c74e-e828-079963d773a8.md) | Enable or disable correcting lines that are slight off-axis. |
|  | [AutoJoin](abf3e142-3f21-9161-e799-7a6b6e3c30b0.md) | Enable or disable auto-join at the end of import. |
|  | [CreateLinkInstanceOnly](47219405-9a1f-3e60-1c1c-bc88586d487e.md) | Determines whether to create a linked symbol element or not. |
|  | [ForceImport](f9fcc2e6-4e4e-94bd-2646-801f7f487612.md) | Force the IFC file to be imported regardless of an existing corresponding Revit file. |
|  | [Intent](6200e560-88d8-d10d-0cf9-ceb18ca15f3f.md) | The intent of the import. |
|  | [IsValidObject](a4e4a737-c53c-62e5-a9c2-c424f1f80951.md) | Specifies whether the .NET object represents a valid Revit entity. |
|  | [LinkOrientation](6eeeeb82-c769-ac1e-ea46-e4cb320df9f1.md) | The orientation of the Linked IFC File in the Host Document. |
|  | [LinkPosition](e1eee09c-2f35-e140-beb8-8f367fd336f5.md) | The position of the Linked IFC File in the Host Document. |
|  | [RevitLinkFileName](34cbbeb3-4be9-42c9-bc0c-9e411c2d3184.md) | The full path of the intermediate Revit file created during a previous link action. This is used during "Reload From" to determine the path to the previous generated Revit file. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Dispose](fc622f9f-c5df-7755-e519-71d663b2ae40.md) | Releases all resources used by the IFCImportOptions |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | [GetConversionData](e4cd397e-8e29-ca75-4a92-ab8efd557ea1.md) | Get the data used in the creation of the associated Revit file for an IFC link operation, if it exists. |
|  | [GetExtraOptions](b47a34ec-ea49-7f3d-ce78-782222abf96e.md) | Get the list of extra options to be passed into the importer. Each entry in the map is a pair of option name and value. |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | [SetExtraOptions](a2800b08-bb26-a9c7-0cdf-c995c9e2be63.md) |  |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
#### Reference

[Autodesk.Revit.DB.IFC Namespace](b823fafb-1ba1-896b-4097-142c2817ce74.md)