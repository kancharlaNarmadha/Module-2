

# EX 2A Static Method
## DATE:
## AIM:
To write a java program for calculate cube of a number using static method.





## Algorithm

1.Create a class named CalculateCube and define a static method Cube() to perform the cube calculation.

2.Inside the Cube() method, create a Scanner object to accept an integer input from the user.

3.Read an integer value and compute its cube using the formula x * x * x.

4.Display the result of the cube using System.out.println().

5.Call the Cube() method from the main() method to execute the logic.




## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
import java.util.*;
public class CalculateCube{
    static void Cube(){
        Scanner sc=new Scanner(System.in);
        int x=sc.nextInt();
        int y=x*x*x;
        System.out.println("Cube is: "+y);
    }
    public static void main(String args[]){
        Cube();
    }
}

```

## Output:
![image](https://github.com/user-attachments/assets/d543d5f0-c9f1-425c-a4e1-38bdced83648)


## Result:
The program successfully accepts an integer input from the user and calculates its cube using a static method. The result is then displayed on the screen.

