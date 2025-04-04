# DSA-Basic-code-Java

# Factorial Recursive Approach 

public class Main {
    public static void main(String[] args) {
        int n = 5;
        System.out.println("The value is: " + fact(n));
    }

    // Recursive factorial function with base case
    public static long fact(int num) {
        if (num <= 1) { // ✅ Base case to stop recursion
            return 1;
        }
        return num * fact(num - 1); // Recursive case
    }
}



