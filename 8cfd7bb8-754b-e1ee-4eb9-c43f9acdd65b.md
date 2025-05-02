

Revit 2026 API

# SunAndShadowSettingsSharesSettings Property  
  
---  
  
Identifies whether settings are shared globally. 

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public bool SharesSettings { get; set; }
```
```vb
Public Property SharesSettings As Boolean
	Get
	Set
```
```cpp
public:
property bool SharesSettings {
	bool get ();
	void set (bool value);
}
```
```fsharp
member SharesSettings : bool with get, set
```


#### Property Value

Boolean

Identifies whether the per-view SunAndShadowSettings element shares global settings. Global settings are a special case that allows multiple views to be associated together in order that a change in one view affects that same change in other views. There cannot be multiple such groups, and a SunAndShadowSettings element is either a global setting or not. 

#### Reference

[SunAndShadowSettings Class](d616614b-a2ed-b0d0-4f11-f0a0b54a22e5.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)