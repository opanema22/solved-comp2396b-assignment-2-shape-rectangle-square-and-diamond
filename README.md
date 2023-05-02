Download Link: https://assignmentchef.com/product/solved-comp2396b-assignment-2-shape-rectangle-square-and-diamond
<br>
This assignment tests your understanding of basic inheritance in Java.You are asked to write a number of Java classes to model basic shapes: <strong><em>Shape</em></strong>, <strong><em>Rectangle</em></strong>, <strong><em>Square</em></strong> and <strong><em>Diamond</em></strong>. <strong><em>Rectangle</em></strong> and <strong><em>Diamond</em></strong> are the subclasses of <strong><em>Shape</em></strong>, and <strong><em>Square</em></strong> is the subclass of <strong><em>Rectangle.</em></strong>You are also required to write <strong>JavaDoc</strong> for all non-private classes and non-private class members.

<em> </em>Implementation

The <strong><em>Shape</em></strong> class:

<strong>Methods </strong>   Shape()

Constructor, create an empty shape. A shape is typically a 2D array of pixels (boolean values).

String toString()

Return a drawing of the shape as a String. Each pixel should be represented by the character * and each empty space should be represented by the space character. Newlines are represented by newline character 
.

int getArea()

Return the area, i.e., the number of pixels in the shape.

Shape intersect(Shape s)

Return a new Shape object representing the intersection of this Shape object and s.

Shape union(Shape s)

Return a new Shape object representing the union of this Shape object and s.




The <strong><em>Rectangle</em></strong> class, a subclass of the <strong><em>Shape</em></strong> class:

<strong>Methods </strong>

Rectangle(int width, int height)

Constructor, create a rectangle with the specific width and height. For example, if width = 5 and height = 3, a drawing of this shape will look like this:

*****

***** *****







The Diamond class, a subclass of the <em>Shape</em> class:

<strong>Methods</strong>

Diamond(int size)

Constructor, create a diamond shape with the specific size. For example, if size = 3, a drawing of this shape will look like this (the empty area is represented by space characters and each newline is represented by the newline character 
.):




The <em>Square</em> class, a subclass of the <em>Rectangle</em> class:

<strong>Methods </strong>

Square(int size)

Constructor, create a square with the specific size. For example, if size = 3, a drawing of this shape will look like this:

***

*** ***