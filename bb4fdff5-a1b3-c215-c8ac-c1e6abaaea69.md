

Revit 2026 API

# AssetPropertyAddConnectedAsset Method  
  
---  
  
Adds a new connected asset attached to this asset property, if it allows it. 

**Namespace:** [Autodesk.Revit.DB.Visual](f5a10581-6ac2-be19-0e32-f87d05bc8b83.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public void AddConnectedAsset(
	string schema
)
```
```vb
Public Sub AddConnectedAsset ( 
	schema As String
)
```
```cpp
public:
void AddConnectedAsset(
	String^ schema
)
```
```fsharp
member AddConnectedAsset : 
        schema : string -> unit 
```


#### Parameters

schema String
     The schema name. 

| Exception | Condition |
| --- | --- |
| [ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md) | The schema name is not valid. |
| [ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md) | A non-optional argument was null |
| [InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md) | The asset property is not editable. -or- Cannot check validity for a property not being edited in AppearanceAssetEditScope. -or- Asset property is already connected to one asset. |
  
Cannot add a connected asset if one is already connected. Use RemoveConnectedAsset() to avoid an exception being thrown. A new preset asset is created and connected to the property. For "UnifiedBitmap", it contains an empty property unifiedbitmap_Bitmap. 

#### Reference

[AssetProperty Class](7be89499-d011-ab43-4715-0ee6f9335970.md)

[Autodesk.Revit.DB.Visual Namespace](f5a10581-6ac2-be19-0e32-f87d05bc8b83.md)