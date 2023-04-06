# array01
//Write a program that takes an array of integers as input and outputs the sum of all the even numbers in the array.
package mypackage;

import java.util.Scanner;

public class PrimeNumber {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
//		System.out.println("Enter values ");
		Scanner sc=new Scanner(System.in);
		System.out.println("Enter array size ");
        int size=sc.nextInt();
    	System.out.println("Enter value ");
        int[] array=new int[size];
        int sum=0;
    	
        for(int i=0;i<array.length;i++) {
        	array[i]=sc.nextInt();
        	
        	}for(int i=0;i<array.length;i++) {
        		if(array[i]%2==0) {
            		sum=sum+array[i];
            		
        }
        
        		
	}
        	System.out.println(sum);
	}
}
