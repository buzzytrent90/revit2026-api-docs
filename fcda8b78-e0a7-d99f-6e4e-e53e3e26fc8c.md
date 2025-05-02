

Revit 2026 API

# VectorAtPoint Class  
  
---  
  
Stores vectors at one domain point. Each vector corresponds to a "measurement" for which this vector was calculated. 

SystemObject [Autodesk.Revit.DBValueAtPointBase](67c49547-b5b9-59ad-8106-65d90886a381.md) Autodesk.Revit.DB.AnalysisVectorAtPoint

**Namespace:** [Autodesk.Revit.DB.Analysis](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public class VectorAtPoint : ValueAtPointBase
```
```vb
Public Class VectorAtPoint
	Inherits ValueAtPointBase
```
```cpp
public ref class VectorAtPoint : public ValueAtPointBase
```
```fsharp
type VectorAtPoint = 
    class
        inherit ValueAtPointBase
    end
```


The VectorAtPoint type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [VectorAtPoint(IListXYZ)](02d307b6-9e0b-692f-1325-346d314b94e8.md) | Initializes a new instance of the VectorAtPoint class |
|  | [VectorAtPoint(VectorAtPoint)](9fae67e6-79af-edfc-f295-6733b0481892.md) | Creates a copy of the given VectorAtPoint instance. |
  
|  | Name | Description |
| --- | --- | --- |
|  | [IsValidObject](586e4bc0-785e-8c96-0801-480dd86f096c.md) | Specifies whether the .NET object represents a valid Revit entity. (Inherited from [ValueAtPointBase](67c49547-b5b9-59ad-8106-65d90886a381.md)) |
  
|  | Name | Description |
| --- | --- | --- |
|  | [ClearAllFlags](95bc440a-e3dd-6b17-3843-e8cf451347b1.md) | Sets flags for all measurements to ValueAtPointFlags::None. (Inherited from [ValueAtPointBase](67c49547-b5b9-59ad-8106-65d90886a381.md)) |
|  | [ClearFlagsAt](031eb89d-71e5-f986-cf5b-e586f8d11f67.md) | Sets flags for the given measurement to ValueAtPointFlags::None. (Inherited from [ValueAtPointBase](67c49547-b5b9-59ad-8106-65d90886a381.md)) |
|  | [Dispose](634fe4ca-cc7a-f91f-41ea-cd3795a6a63a.md) | (Inherited from [ValueAtPointBase](67c49547-b5b9-59ad-8106-65d90886a381.md)) |
|  | Equals | Determines whether the specified object is equal to the current object.(Inherited from Object) |
|  | [GetFlags](140ca529-26a6-4a19-f5d9-9fe199aa89a8.md) | Returns flags for the given measurement. (Inherited from [ValueAtPointBase](67c49547-b5b9-59ad-8106-65d90886a381.md)) |
|  | GetHashCode | Serves as the default hash function.(Inherited from Object) |
|  | GetType | Gets the Type of the current instance.(Inherited from Object) |
|  | [SetFlags(IListInt32)](91abfaff-2abe-225d-ab00-f8b301b81392.md) | (Inherited from [ValueAtPointBase](67c49547-b5b9-59ad-8106-65d90886a381.md)) |
|  | [SetFlags(Int32)](80ea41b0-f274-8e7f-25f8-79f9fdeddb33.md) | Sets the flags associated to all measurements to the same value. (Inherited from [ValueAtPointBase](67c49547-b5b9-59ad-8106-65d90886a381.md)) |
|  | [SetFlags(Int32, Int32)](6d1e3b3e-bfce-3a5b-a31e-55ba6c408635.md) | Sets the flags associated to a given measurement. (Inherited from [ValueAtPointBase](67c49547-b5b9-59ad-8106-65d90886a381.md)) |
|  | ToString | Returns a string that represents the current object.(Inherited from Object) |
  
#### Reference

[Autodesk.Revit.DB.Analysis Namespace](958e2e12-587d-f188-5d7b-f13d7dbfdf48.md)