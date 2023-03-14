# Java_Exercises
## Exercise 01
***1- Faça um algoritmo que receba dois números e exiba o resultado da sua soma***<br>
***1- Make an algorithm that takes two numbers and displays the result of their sum***
``` 
package ExercisesJava;

import java.util.Scanner;

public class App {

    public static void main(String[] args) {
         Scanner sc = new Scanner(System.in);
        
        int num1,num2,sum ;
        
        
        System.out.println("Enter the first number: ");
        num1 = sc.nextInt();
        System.out.println("Enter the second number: ");
        num2 = sc.nextInt();
        sum = num1+num2;
        System.out.print("The sum of the numbers is: "+sum);
    }
}

```

