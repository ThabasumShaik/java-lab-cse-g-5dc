## EXPERIMENT-2
# 2a)title Implement class mechanism im java.create a class,methods and invoke them inside method.
# SORCE CODE:
``` java
public class Rectangle{
   double length;
   double breadth;
 double area(){
   return length*breadth;
 }
  double perimeter(){
    return 2*(length+breadth);
 }
}
class Main {
    public static void main (String args[]){
    Rectangle rect = new Rectangle();
     rect.length = 10;
     rect.breadth = 5;
   double area = rect.area();
   double perimeter = rect.perimeter();
   System.out.println("area of given rectangle: "+area);
   System.out.println("perimeter of given rectangle: "+perimeter);
   }
 }
```
 ## output:
 [experiment2output](mechanism.png)
