# Receptionist-program
I have done a program in receptionist program using JAVA programming language


import java.util.*;
public class Main
{
	public static void main(String[] args) {
	int n=9875;
	int k=4;
	int sum=0;
	while(n!=0){
	   int rem=n%10;
	   sum=sum+rem;
	   n=n/10;
	}sum=sum*k;
	System.out.println(sum);
	
	if(sum<=9)	
	    {
	        System.out.println(sum);
	    }
	    
	 else{
	     int temp=sum;
	     while(sum>9){
	       int  sum1=0;
	       while(sum!=0){
	           int rem1=sum%10;
	           sum1=sum1+rem1;
	           sum=sum/10;
	       }sum=sum1;
	     }
	     System.out.println(sum);
	 }
	}
}
