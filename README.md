# Switch.java
com.java.basics

package com.java.basics;
import java.util.Scanner;
public class SwitchCases {

	public static void main(String[] args) {
		
		Scanner scanner = new Scanner(System.in);
		
		System.out.println("Enter your favourite drink:\n 1: coke \n 2: mountain deq \n 3:milk\n 4: mineral water");
		int kritikaChoice = scanner.nextInt();
		
		switch(kritikaChoice) {
		case 1:{
			System.out.println("Enjoy your coke");
			break;
		}
		case 2:{
			System.out.println("Enjoy your dew and darr ke aage jeet hai!");
			break;
		}
		case 3:{
			System.out.println("Enjoy your milk as its healthier option!");
			break;
		}
		case 4:{
			System.out.println("Just have your water!");
			break;
		}
		default:
			System.out.println("Invalid choice!");
			break;
		}

	}

}
