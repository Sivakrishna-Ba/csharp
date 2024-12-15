using System;
class Circle
{
    static float _PI=3.14F;
    int _Radius;

    public Circle(int Radius)
    {
        this._Radius=Radius;

    }
    public float CalculateArea()
    {
        return Circle._PI*_Radius*_Radius;


    }
}

class program
{
    public static void Main()
    {
        Circle C1= new Circle(5);
        float Area=C1.CalculateArea();
        Console.WriteLine("Area={0}",Area);
    }
}

