# Welcome to our GitHub classroom!

Do the following to Complete this assignment:

1. Begin editing this file by clicking the 'pen' symbol above.

2. Enter your First Name:

3. Enter your favourite animal:

4. Now click the green 'commit changes' button at the bottom.

5. Done!
Henry
Cat 

public class Rectangle
{
    private int width;
    private int height;
    
    public Rectangle(int rectWidth, int rectHeight)
    {
        width = rectWidth;
        height = rectHeight;
    }
    
    public int getArea()
    {
        return width * height;
    }
    
    public int getHeight()
    {
        return height;
    }
    
    public int getWidth()
    {
        return width;
    }
    
    public String toString()
    {
        return "Rectangle with width: " + width + " and height: " + height;
    }
    
    public class Circle
{
    private static final double PI = 3.14159265359;
    
    private double radius;
    
    public Circle(double theRadius)
    {
        radius = theRadius;
    }

    public double getArea()
    {
        double squared = Math.pow(radius, 2);
        return PI * squared;
    }
    
}
}
