Task 1:
CODE:
using System;
class pro
{
 private int salary =+200000;
 public int salaryac 
 {
 get { return salary; }
 set { salary = value; }
 
 }
 }
 
 class Program
 {
 static void Main(string[] args)
 {
 int a;
 pro pr = new pro();
 pr.salaryac = 24235;
 a = pr.salaryac / 100*8;
 Console.WriteLine(a);
 Console.ReadKey();
 
 
 }
 }
Task 2:
CODE:
using System;
 class factorial
 {
 static double fac()
 {
 int i, num, fact = 1;
 Console.WriteLine("Enter Any Number: ");
 num = Convert.ToInt32(Console.ReadLine());
 for (i = num; i >= 1; i--)
 {
 fact = fact * i;
 }
 Console.WriteLine("\nFactorial of given Number is : " + fact);
 
 
 }
 public int faca
 {
 get { return fac; }
 
 }
 }
 class Program
 {
 static void Main(string[] args)
 {
 int a;
 factorial f=new factorial();
 a = f.faca;
 Console.WriteLine(a);
 Console.ReadKey();
 }
 }
Task 3:
CODE:
using System;
namespace Lab4
{
 class car
 {
 private string car_name;
 private int car_paint;
 private double car_model;
 public car()
 {
 name = car_name;
 paint = car_paint;
 model = car_model;
 }
 public string name
 {
 get { return car_name; }
 set { car_name = value; }
 }
 public double model
 {
 get { return car_model; }
 set { car_model = value; }
 }
 public Int32 paint
 {
 get { return car_paint; }
 set { car_paint = value; }
 }
 public void display()
 {
 Console.WriteLine("CAR Name : " + name);
 Console.WriteLine("CAR model: " + model);
 Console.WriteLine("PAINT : " + paint);
 }
 class program
 {
 static void Main(string[] args)
 {
 car c = new car();
 Console.WriteLine("Enter car name: ");
 c.name = Console.ReadLine();
 Console.WriteLine("Enter car model: ");
 c.model = Convert.ToDouble(Console.ReadLine());
 Console.WriteLine("Enter car paint: ");
 c.paint = Convert.ToInt32(Console.ReadLine());
 c.display();
 Console.WriteLine(" ");
 }
 }
 }
}
Task 4:
CODE:
using System;
class Rectangle
{
private double field_length = 1;
private double field_width = 1;
public Rectangle(double Length, double Width)
{
 length = Length;
 width = Width;
}
public double length
{
 get { return field_length; }
 set { if((length>=0)&&(length<=20))
 field_length = value; }
}
public double width
{
 get { return field_width; }
 set { if((width>=0)&&(width<=20))
 field_width = value; }
}
public double Perimeter
{
 get { return 2 * field_width + 2 * field_length; ;}
 set { Perimeter = 2 * field_width + 2 * field_length; }
}
public double Area
{
 get { return field_length * field_width; }
 set { Area = field_width * field_length; }
}
}
class Program
{
 static void Main(string[] args)
 {
 Rectangle rect1 = new Rectangle(5, 6);
 Console.WriteLine(rect1.length);
 Console.WriteLine(rect1.width);
 Console.WriteLine(rect1.Perimeter);
 Console.WriteLine(rect1.Area);
 Console.ReadLine();
 }
}
using System;
class Rectangle
{
private double field_length = 1;
private double field_width = 1;
public Rectangle(double Length, double Width)
{
 length = Length;
 width = Width;
}
public double length
{
 get { return field_length; }
 set { if((length>=0)&&(length<=20))
 field_length = value; }
}
public double width
{
 get { return field_width; }
 set { if((width>=0)&&(width<=20))
 field_width = value; }
}
public double Perimeter
{
 get { return 2 * field_width + 2 * field_length; ;}
 set { Perimeter = 2 * field_width + 2 * field_length; }
}
public double Area
{
 get { return field_length * field_width; }
 set { Area = field_width * field_length; }
}
}
class Program
{
 static void Main(string[] args)
 {
 Rectangle rect1 = new Rectangle(5, 6);
 Console.WriteLine(rect1.length);
 Console.WriteLine(rect1.width);
 Console.WriteLine(rect1.Perimeter);
 Console.WriteLine(rect1.Area);
 Console.ReadLine();
 }

