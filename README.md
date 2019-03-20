# Lab-3
Class: Programming Fundamentals (COMP112) - Laboratory #3 - Scanner Class &amp; Methods + Math Class + Wrapper Classes in Java 

package lab3;

import java.util.Scanner;

import java.text.DecimalFormat;

import java.util.Random;

public class Main {

  public static void main(String[] args) {
  
   // TODO Auto-generated method stub

  Scanner scan = new Scanner (System.in);
  
  System.out.println("Enter integer");
	
  int num = scan.nextInt();
	
  System.out.println(Math.abs(num));
		
  Scanner scan2 = new Scanner (System.in);
	
  System.out.println("Enter integers");
	
  int num1 = scan2.nextInt();
	
  int num2 = scan2.nextInt();
	
  System.out.println(Math.min(num1, num2));
		
  Scanner scan3 = new Scanner (System.in);
	
  System.out.println("Enter integers");
	
  int num3 = scan3.nextInt();
	
  int num4 = scan3.nextInt();
	
  System.out.println(Math.max(num3, num4));
		
  Scanner scan4 = new Scanner (System.in);
	
  System.out.println("Enter doubles");
	
  double num5 = scan4.nextDouble();
	
  double num6 = scan4.nextDouble();
	
  System.out.println(Math.pow(num5, num6));
		
  Scanner scan5 = new Scanner (System.in);
	
  System.out.println("Enter double");
	
  double num7 = scan5.nextDouble();
	
  System.out.println(Math.round(num7));
		
  Scanner scan6 = new Scanner (System.in);
	
  System.out.println("Enter double");
	
  double num8 = scan6.nextDouble();
	
  System.out.println(Math.sqrt(num8));
		
  System.out.println("Calculadora de porciento");
	
  Random random = new Random();
	
  DecimalFormat averagePattern = new DecimalFormat("#0.0%");
	
  int start = 1, end = 50;
	
  double num9 = random.nextInt(50 - 1 + 1) + 1;
	
  double num10 = random.nextInt(50 - 1 + 1) + 1;
	
  double num11 = random.nextInt(50 - 1 + 1) + 1;
	
  double average;
	
  average = (double) ((num9 + num10 + num11)/3);
	
  System.out.println(num9);
	
  System.out.println(num10);
	
  System.out.println(num11);
	
  System.out.println("El porciento es: " + averagePattern.format(average/100));
	
  System.out.println("Calculadora de numero menor");
	
  Random random2 = new Random();
	
  int start2 = 0, end2 = 60;
	
  int num12 = random2.nextInt(100 - 60 + 1) + 60;
	
  int num13 = random2.nextInt(100 - 60 + 1) + 60;
	
  int num14 = random2.nextInt(100 - 60 + 1) + 60;
	
  int num15 = random2.nextInt(100 - 60 + 1) + 60;
	
  int num16 = random2.nextInt(100 - 60 + 1) + 60;
	
  System.out.println(num12);
	
  System.out.println(num13);
	
  System.out.println(num14);
	
  System.out.println(num15);
	
  System.out.println(num16);
	
  int num17 = Math.min(num12, num13);
	
  int num18 = Math.min(num17, num14);
	
  int num19 = Math.min(num18, num15);		
	
  int num20 = Math.min(num19, num16);
	
  System.out.println("El numero menor es: " + num20);
		
	}

}
