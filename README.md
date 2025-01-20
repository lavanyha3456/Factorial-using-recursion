# Factorial-using-recursion
public class FactorialRecursion {

// Recursive method to calculate factorial

public static int factorial(int n) {

if (n == 0 || n == 1) { // Base case

return 1;

} else {

return n * factorial(n - 1); // Recursive call

}

}

public static void main(String[] args) {

int number = 5; // Input number defined here

if (number < 0) {

System.out.println("Factorial is not defined for negative numbers.");

} else {

System.out.println("The factorial of " + number + " is " + factorial(number) + ".");
}
}
}
OUTPUT:

The factorial of 5 is 120.
