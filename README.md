# Java-Tel-
package com.company;

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Enter the number in \"$\"");
        double euro = scanner.nextDouble();
        double usd = euro/1.2;
        System.out.println("“for the payment "+euro+" "+"you need "+usd+" "+"€");
        double commission = usd*1.5/100;
        System.out.println("Commission is "+commission+" "+"€");
    }

}
