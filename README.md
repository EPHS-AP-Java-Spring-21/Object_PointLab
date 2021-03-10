# Object_PointLab


## Creating Point Objects && Methods in the Point.java class

### Instance Variables
You will find some comments in the Point.java class, thinking about a two dimensional point that contains an x and a y.

### Constructors
1. Create a default constructor that takes in no parameters and creates a point at the origin.
1. Create another constructor that takes in 2 parameters, and creates a point given those inputs.

## Object Methods

### Quadrant
Returns which quadrant of the x/y plane this Point object falls in. 
* Quadrant 1 contains all points whose x and y values are both positive. 
* Quadrant 2 contains all points with negative x but positive y. 
* Quadrant 3 contains all points with negative x and y values.
* Quadrant 4 contains all points with positive x but negative y.
* If the point lies directly on the x and/or y axis, return 0.
* bob.quadrant(); --> 2 

### Swap
Negates and swaps the x/y coordinates of the Point object.
For example, if an object pt initially represents the point (5, -3), after a call of pt.flip(); , the object should represent (3, -5). If the same object initially represents the point (4, 17), after a call to pt.flip(); the object should represent (-17, -4).

### toString
Modify the toString method in the Point class.
Make it return a string in the following format.
For example, if a Point object stored in a variable pt represents the point (5, -17), return the string: x.toString() Point(x=5,y=-17)
If the client code were to call System.out.println(pt); , that text would be shown on the console.

## PointMain.java
This client program uses Point objects.Expected output:
	 
	p1(81,21) quadrant=1 
	p2(-52,32) quadrant=2 
	p3(-93,-13) quadrant=3 
	p4(64,-44) quadrant=4 
	p0(0,0) quadrant=0
	 
	p1 after flip=(-21,-81)
	p2 after flip=(-32,52)
	p3 after flip=(13,93)
	p4 after flip=(44,-64)
	p0 after flip=(0,0)
