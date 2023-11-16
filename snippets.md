```
public class MyClass {
  public static void main(String[] args) {
  System.out.print("a");
    try {
               System.out.print("b");
               throw new IllegalArgumentException();
         }catch (RuntimeException e) {
                System.out.print(“c");
                return;
         } catch (Exception e) {
                System.out.print(“d");
        } finally {
                System.out.print("f");
      }
 System.out.print(“e");
    }
}


A)    abdf
 
B)    abdfe
 
C)    abfe
 
D)    abcfe
 
e)    abcf

f)    Code does not compile

 

 What is the output of the following program?

1: public class WaterBottle {
2: private String brand;
3: private boolean empty;
4: public static void main(String[] args) {
5: WaterBottle wb = new WaterBottle();
6: System.out.print("Empty = " + wb.empty);
7: System.out.print(", Brand = " + wb.brand);
8: } 
} 


A. Line 6 generates a compiler error. 
B. Line 7 generates a compiler error. 
C. There is no output.
D. Empty = false, Brand = null
E. Empty = false, Brand = 
F. Empty = null, Brand = null


Which of the following lambda expressions can fill in the blank? (Choose all that apply)
List<String> list = new ArrayList<>();
list.removeIf(__________);

A. s -> s.isEmpty()
B. s -> {s.isEmpty()}
C. s -> {s.isEmpty();}
D. s -> {return s.isEmpty();}
E. String s -> s.isEmpty()


```