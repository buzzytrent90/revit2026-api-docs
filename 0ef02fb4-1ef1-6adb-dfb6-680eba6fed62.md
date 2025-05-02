

Revit 2026 API

# NurbSplineCreateCurve(IListXYZ, IListDouble) Method  
  
---  
**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)**Assembly:** RevitAPI (in RevitAPI.dll) Version: 26.0.4.0 (26.0.4.0)

```csharp
public static Curve CreateCurve(
	IList<XYZ> controlPoints,
	IList<double> weights
)
```
```vb
Public Shared Function CreateCurve ( 
	controlPoints As IList(Of XYZ),
	weights As IList(Of Double)
) As Curve
```
```cpp
public:
static Curve^ CreateCurve(
	IList<XYZ^>^ controlPoints, 
	IList<double>^ weights
)
```
```fsharp
static member CreateCurve : 
        controlPoints : IList<XYZ> * 
        weights : IList<float> -> Curve 
```


#### Parameters

controlPoints IList[XYZ](c2fd995c-95c0-58fb-f5de-f3246cbc5600.md)
    
weights IListDouble
    

#### Return Value

[Curve](400cc9b6-9ff7-de85-6fd8-c20002209d25.md)

#### Reference

[NurbSpline Class](65c43ffe-3972-ae2b-4aa4-e2901cdbb3a8.md)

[CreateCurve Overload](774a9983-44a1-6cd9-36f2-0e40a819c5f7.md)

[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md)