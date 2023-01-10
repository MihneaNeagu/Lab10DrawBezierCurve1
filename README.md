# Lab10DrawBezierCurve1

Write a Python program to determine a point on a rational Bézier cubic curve, in the plane, using de Casteljau's rational algorithm.
The input data will be:

• the 4 control points;

• the 4 weights;

• t∈[0,1],

Then take control points and weights and graphically represent the resulting curve (using geomdl, see file model1.py).
Attention, in geomdl control points and weights are entered simultaneously, with the help of homogeneous control points.
For example, if the control point is (2,2), with weight 0.5, then the homogeneous control point will be (0.5·2,0.5·2,0.5) = (1,1,0.5).
