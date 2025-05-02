

Revit 2026 API

# BuiltInFailuresCopyMonitorFailures Class  
  
---  
  
Failures about CopyWatch. 

SystemObject Autodesk.Revit.DBBuiltInFailuresCopyMonitorFailures

**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static class CopyMonitorFailures
```
```vb
Public NotInheritable Class CopyMonitorFailures
```
```cpp
public ref class CopyMonitorFailures abstract sealed
```
```fsharp
[<AbstractClassAttribute>]
[<SealedAttribute>]
type CopyMonitorFailures = class end
```


The BuiltInFailuresCopyMonitorFailures type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [AlreadyCopiedAndStopWatch](3fd113fa-9e28-9155-9917-75589a3bb675.md) | Element has already been copied. Stop existing monitoring to copy again. |
|  | [AlreadyWatched](bbef8a98-d525-0a37-57a4-87d8536d6dfc.md) | Elements already monitored. |
|  | [CannotCopyCuttingInsert](ca401dd8-eb6b-bc7d-25b4-5f1b2ce32346.md) | Copy/Monitor does not support cutting inserts in floors. Some openings were not copied. |
|  | [CannotMoveHostedFixtureViaCopyMonitor](3f5916f1-0f50-e16e-fa3a-6044d5877e38.md) | The fixture is hosted and cannot be moved. Use the Move command to relocate the fixture in the host file as required. |
|  | [CopyWatchAlert](62dc3a39-e072-264a-fffe-b2a07c25a9c7.md) | Coordination Monitor alert : [Description] |
|  | [GridDeletedSameName](e6153c00-cf20-1d4f-3ade-b73a0cfb16b7.md) | Grid cannot be copied because grid with desired name '[Name]' already exist in a target document. |
|  | [LevelDeletedSameName](4f5c27d1-b4a7-11ba-6f3f-25ec6e2cfb78.md) | Level cannot be copied because level with desired name '[Name]' already exist in a target document. |
  
#### Reference

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)