

Revit 2026 API

# PrintSetup Class  
  
---  
  
Represents the Print Setup (Application Menu->Print->Print Setup) within Autodesk Revit.

SystemObject [Autodesk.Revit.DBAPIObject](beb86ef5-39ad-3f0d-0cd9-0c929387a2bb.md) Autodesk.Revit.DBPrintSetup

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class PrintSetup : APIObject
```
```vb
Public Class PrintSetup
	Inherits APIObject
```
```cpp
public ref class PrintSetup : public APIObject
```
```fsharp
type PrintSetup = 
    class
        inherit APIObject
    end
```


The PrintSetup type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [CurrentPrintSetting](64b832f9-8c68-70eb-1ade-a20a6344525e.md) | The current Print Setting of Print Setup. |
|  | [InSession](8fa68bd4-9e97-f772-629b-25ef129939e3.md) | The in-session Print Setting of Print Setup. |
|  | [IsReadOnly](d516bcd2-a3fd-a578-58f6-f1add979bd07.md) | Identifies if the object is read-only or modifiable.(Inherited from [APIObject](beb86ef5-39ad-3f0d-0cd9-0c929387a2bb.md)) |
  
|  | Name | Description |
| --- | --- | --- |
|  | [Delete](8748eb34-b067-f058-1451-51eb342680ac.md) | Delete the current print setting, and make the In-Session setting as the current one. |
|  | [Dispose](7c03212a-b587-1c89-3912-efea0d2619c5.md) | Causes the object to release immediately any resources it may be utilizing.(Inherited from [APIObject](beb86ef5-39ad-3f0d-0cd9-0c929387a2bb.md)) |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | [Rename](ce2e12e0-8875-7238-26d4-3fd323142899.md) | Rename the current print setting with the specified name. |
|  | [Revert](ddea247a-625d-18e9-660f-eee28615018c.md) | Revert the current print setting. |
|  | [Save](ef2cf0c5-fce2-6fba-f3a9-8e49b5cde845.md) | Save the changes for the current print setting. |
|  | [SaveAs](b2ff4be8-70c5-ea87-a9d4-e0b7c4af39c6.md) | Save the current print setting to another print setting with the specified name. |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
The Print Setup object can only get from PrintManager object. 

#### Reference

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)