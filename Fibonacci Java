/*
------------------------------------------------------------------------------------------------
 * Seyon Krishnakumar - 0508305
 * COIS 2240 - Assignment 1
 ------------------------------------------------------------------------------------------------
 * Assignment Outline:
 * 
 * takes user input for integer n
 * calculates & prints Fibonacci Series up to the nth term
 * Fibonacci calculation & printing done twice - recursively & iteratively
 * recursive calculation done with fiboSeriesRec()
 * iterative calculation done with fiboSeriesIte()
 * runtime for each method is printed
 --------------------------------------------------------------------------------------------------
 * References:
 * https://www.sanfoundry.com/c-program-fibonacci-number-using-recursion/
 * http://www.java-fries.com/2014/11/nth-fibonacci-number-java/
---------------------------------------------------------------------------------------------------
 */
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

        // Introduce the Assignment Instruction.
        System.out.println("this is a fibonacci generator.");

        // Determining how many Fibonacci numbers to calculate.
        System.out.println("how many Fibonacci number we want to generate?");

        //initiating scanner for user input
        Scanner scanner = new Scanner(System.in);
        int input = scanner.nextInt();
        scanner.close();


        System.out.println(""); //blank line for formatting reasons
        System.out.println("");// blank line for formatting reasons


        //Please Display Recursive Fibnoacci results
        // Inform the user of calculation method
        System.out.println("Fibanacci number generation for Recursive");

        //Marking calculation start time for timing purposes
        long startTimeRec = System.nanoTime();

        //Run program
        for (int i = 0; i < input; i++) {

            System.out.print(""); //add space after each number

        }

        // Marking end time after each calculation
        long endtimerec = System.nanoTime();

        // Calculating time recorded for the purpose of recursive method results
        long timeelapsedrec = endtimerec - startTimeRec;

        System.out.println(""); //left blank for formatting reasons

        // Recording time to calculate lists of numbers using recursion
        System.out.println("Generating numbers took:" + timeelapsedrec + "nanoseconds" + "or" + timeelapsedrec / 1000000 + "milliseconds.");

        System.out.println(""); //left blank for formatting reasons


        // Displaying Iterative Fibonacci results
        // Inform user of calculation method
        System.out.println("Iterative Fibanocci Number Generation:");

        // Record Start Time Calculation for timing purposes
        long startTimeIte = System.nanoTime();

        for (int i = 0; i < input; i++) {

            System.out.print(""); // Inserting a space after each number

        }

        // Record calculation end time
        long endtimeIte = System.nanoTime();

        // calculating time for the results using Iterative method
        long timeelapsedIte = endtimeIte - startTimeIte;

        System.out.println(""); // left blank for formatting reasons

        // Recording time taken to calculate the list of numbers using iteration
        System.out.println("generating number took:" + timeelapsedIte + " nanoseconds" + "or" + timeelapsedIte / 1000000 + "milliseconds.");

        }

        // Recursive Fibonacci Number
    public static long fiboseriesRec(long number) {

        if (number == 0 || number == 1) {

            return number;

        }

        return fiboseriesRec(number - 1) + fiboseriesRec(number - 2);

    }


        //calculating fibonacci numbers
    public static long fiboSeriesIte(long number){

        //Initiating required variables
        long fib1 = 0;
        long fib2 = 1;
        long fibvalue = 0;

        for (int count =0; count <= number; count++) {

            fibvalue = fib1;
            fib1 = fib1 + fib2;
            fib2 = fibvalue;
            fib1 = fib1 + fib2; // calculating fibonacci
            fib2 = fibvalue; // current fibonacci value to fib2

        }

        return fibvalue;
    }


}
