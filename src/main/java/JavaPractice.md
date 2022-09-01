Q1. Welcome to the world of Java! In this challenge, we practice printing to stdout.

The code stubs in your editor declare a Solution class and a main method. Complete the main method by copying the two lines of code below and pasting them inside the body of your main method.

System.out.println("Hello, World.");
System.out.println("Hello, Java.");

#Answer

	public class Solution {
	 public static void main(String[] args) {
       System.out.println("Hello, World.");
       System.out.println("Hello, Java.");
    }
	}
	
Q2. Task
In this challenge, you must read 3 integers from stdin and then print them to stdout. Each integer must be printed on a new line. To make the problem a little easier, a portion of the code is provided for you in the editor below.

Input Format

There are 3 lines of input, and each line contains a single integer.

# Answer

	import java.util.*;
	public class Solution {
	public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        int a = scan.nextInt();
        int b =scan.nextInt();
        int c =scan.nextInt();
        scan.close();
        System.out.println(a);
        System.out.println(b);
        System.out.println(c);
    }
	}
	
Q3. Task
Given an integer,n, perform the following conditional actions:

If  n is odd, print Weird
If  is even and in the inclusive range of 2 to 5, print Not Weird
If  is even and in the inclusive range of  6 to 20, print Weird
If  is even and greater than 20 , print Not Weird
Complete the stub code provided in your editor to print whether or not  is weird.


	import java.io.*;
	import java.util.*;
	public class Solution {
	 public static void main(String[] args) {
      Scanner sc =new Scanner(System.in);
      int n =sc.nextInt();
      if(n%2!=0)
          System.out.println("Weird");
      else if (n%2==0 && n>=2 && n<=5)
        System.out.println("Not Weird");
      else if(n%2==0 && n>6 && n<=20)
      System.out.println("Weird");
      else if(n%2==0 && n>20)
      System.out.println("Not Weird");
      }
	}