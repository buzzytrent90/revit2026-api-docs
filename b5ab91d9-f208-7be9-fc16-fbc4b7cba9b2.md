

Revit 2026 API

# RuledFace Properties  
  
---  
  
The [RuledFace](1a973af7-5f14-26b4-25e8-af69fc6f0901.md) type exposes the following members.

|  | Name | Description |
| --- | --- | --- |
|  | [Area](e851e3f0-799f-c071-c3c6-18d7e50c9914.md) | The area of this face.(Inherited from [Face](e32b3b1f-66fc-57cb-6e1c-aa81d1bf3e63.md)) |
|  | [Curve](e1291b2c-73b2-09d0-09bd-082fe27fd27c.md) | Profile curves of the surface. |
|  | [EdgeLoops](2ccb511d-b5df-8d17-bd9e-3c9aff8cf234.md) | A collection of edge loops. Each edge loop represents one of the closed boundaries of the face.(Inherited from [Face](e32b3b1f-66fc-57cb-6e1c-aa81d1bf3e63.md)) |
|  | [GraphicsStyleId](4103f148-957e-3f44-9ccd-a5ed6702c689.md) | The ElementId of the GeometryObject's GraphicsStyle(Inherited from [GeometryObject](e0f15010-0e19-6216-e2f0-ab7978145daa.md)) |
|  | [HasRegions](b54848a3-e52c-618c-24ad-20fc3c7966bb.md) | Identifies if the face contains regions (which can be created, for example, by the Split Face command).(Inherited from [Face](e32b3b1f-66fc-57cb-6e1c-aa81d1bf3e63.md)) |
|  | [Id](abb781de-203f-4035-784b-713e65cca169.md) | A unique integer identifying the GeometryObject in its associated non view-specific GeometryElement.(Inherited from [GeometryObject](e0f15010-0e19-6216-e2f0-ab7978145daa.md)) |
|  | [IsCyclic](eca99f03-50e0-12bd-8e86-722759a5b612.md) | Indicates whether the underlying surface is periodic in the specified parametric direction.(Inherited from [Face](e32b3b1f-66fc-57cb-6e1c-aa81d1bf3e63.md)) |
|  | [IsElementGeometry](be3ad18d-a9d3-25ed-6200-4f71d3cd4754.md) | Indicates whether this geometry is obtained directly from an Element.(Inherited from [GeometryObject](e0f15010-0e19-6216-e2f0-ab7978145daa.md)) |
|  | [IsExtruded](cf640b08-f8ba-dcff-b4be-385ebff98ee2.md) | Determines if this is an extruded ruled surface. |
|  | [IsReadOnly](d516bcd2-a3fd-a578-58f6-f1add979bd07.md) | Identifies if the object is read-only or modifiable.(Inherited from [APIObject](beb86ef5-39ad-3f0d-0cd9-0c929387a2bb.md)) |
|  | [IsTwoSided](ac7f86fd-d6d6-918f-00f4-23d21e5e0c6f.md) | Determines if a face is two-sided (degenerate).(Inherited from [Face](e32b3b1f-66fc-57cb-6e1c-aa81d1bf3e63.md)) |
|  | [MaterialElementId](0f496bcd-fd05-f1dc-6cc7-d496541fd6ae.md) | The element ID of the material from which this face is composed.(Inherited from [Face](e32b3b1f-66fc-57cb-6e1c-aa81d1bf3e63.md)) |
|  | [OrientationMatchesSurfaceOrientation](1e6f8718-982a-c6fa-3b0f-bef04301a57e.md) | Returns true if this face's orientation matches the orientation of the face's surface, false if they have opposite orientations. (Inherited from [Face](e32b3b1f-66fc-57cb-6e1c-aa81d1bf3e63.md)) |
|  | [Period](4846f165-5347-a95d-649f-bb907019d28c.md) | The period of the underlying surface in the specified parametric direction.(Inherited from [Face](e32b3b1f-66fc-57cb-6e1c-aa81d1bf3e63.md)) |
|  | [Point](b4102dd4-581e-1c7a-857d-e3fe1c2e0f7e.md) | Profile points of the surface. |
|  | [Reference](f3d5d2fe-96bf-8528-4628-78d8d5e6705f.md) | Returns a stable reference to the face.(Inherited from [Face](e32b3b1f-66fc-57cb-6e1c-aa81d1bf3e63.md)) |
|  | [RulingsAreParallel](4ea772f5-7913-987c-78cb-c8f15eeadfa8.md) | Determines if the rulings of this ruled surface are parallel. |
|  | [Visibility](b504868c-1588-3488-8cdf-d8e45ef23fa0.md) | The visibility.(Inherited from [GeometryObject](e0f15010-0e19-6216-e2f0-ab7978145daa.md)) |
  
#### Reference

[RuledFace Class](1a973af7-5f14-26b4-25e8-af69fc6f0901.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)