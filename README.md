# recursion
public class FactorialRecursion {
public static int factorial(int n) {
if (n == 0 || n == 1) { 
return 1;
} else {
return n * factorial(n - 1); 
}
}
public static void main(String[] args) {
int number = 5; 
 if (number < 0) {
System.out.println("Factorial is not defined for negative numbers.");
} else {
 System.out.println("The factorial of " + number + " is " + factorial(number) + ".");
        }
    }
}

OUTPUT:
The factorial of 5 is 120.
