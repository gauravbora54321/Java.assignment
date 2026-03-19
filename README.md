# Java.assignment
Assignment 1
Q1 //write a program to performance sum of three number in Java 
import java.util.Scanner;

public class SumThree {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int a, b, c, sum;

        System.out.println("Enter three numbers:");
        a = sc.nextInt();
        b = sc.nextInt();
        c = sc.nextInt();

        sum = a + b + c;

        System.out.println("Sum of three numbers = " + sum);
    }
}


Q2 //write a program to calculate the CGPA using a marks of three subject out of 100 

import java.util.Scanner;

public class CGPA {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.println("Enter marks of 3 subjects:");
        double m1 = sc.nextDouble();
        double m2 = sc.nextDouble();
        double m3 = sc.nextDouble();

        double cgpa = (m1 + m2 + m3) / 30;

        System.out.println("CGPA = " + cgpa);

        
    }
}

Q3 // Question:

Write a Java program that asks the user to enter their name using the Scanner class and displays a greeting message:
"Hello <name>, have a good day!"

import java.util.Scanner;

public class Greeting {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter your name: ");
        String name = sc.nextLine();

        System.out.println("Hello " + name + ", have a good day!");

    }
}

Q4 // write a program to convert kilometres to mile


import java.util.Scanner;

public class KmToMile {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter distance in kilometers: ");
        double km = sc.nextDouble();

        double miles = km * 0.621371;

        System.out.println("Distance in miles = " + miles);

    }
}

Q5 // write a program to detect whether the number entered by the user is integer or not

import java.util.Scanner;

public class CheckInteger {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a value: ");

        if (sc.hasNextInt()) {
            int num = sc.nextInt();
            System.out.println("It is an integer: " + num);
        } else {
            System.out.println("It is not an integer.");
        }
    }
}
