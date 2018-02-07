import java.io.*;
import java.util.*;
import java.text.*;
import java.math.*;
import java.util.regex.*;

public class Solution {

    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        double meal_cost = scan.nextDouble();
        int tip_percent = scan.nextInt();
        int tax_percent = scan.nextInt();
        
        scan.close();
        
        double tip = (meal_cost * (tip_percent))/100.0;
        double tax = (meal_cost * (tax_percent/100.0));
        double totalCost = (meal_cost + tax + tip);
        int roundTotal = (int) Math.round(totalCost);
        
        System.out.println("The total meal cost is " + roundTotal + " dollars.");
    }
        
}
