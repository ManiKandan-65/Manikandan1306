# import java.util.Scanner;
public class hello {
    public static void main(String[] args) {
        Scanner mani = new Scanner(System.in);
        System.out.println("Enter first number");
        int num1 = mani.nextInt();
        System.out.println("Enter second number");
        int num2 = mani.nextInt();

 
        if (num1 % 2 == 0) {
            System.out.println(num1 + " is even");
        } else {
            System.out.println(num1 + " is odd");
        }

        if (num2 % 2 == 0) {
            System.out.println(num2 + " is even");
        } else {
            System.out.println(num2 + " is odd");
        }
    }
}

