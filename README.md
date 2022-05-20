# weeks-day-by-using-if-else-condition-
package com.javaAssigment;

import java.util.Scanner;

public class Weekends {

	public static void main(String[] args) {
		Scanner days = new Scanner(System.in);
		System.out.println("Enter The day ");
		String day = days.nextLine();
		if(day.equals("Monday") || day.equals("Tuesday") || day.equals("Wednesday")|| day.equals("Thusday") || day.equals("Friday")) {
			System.out.println("Uff, it's week day");
		}else {
			System.out.println("Heyy, it's week end");
		}days.close();

	}

}
