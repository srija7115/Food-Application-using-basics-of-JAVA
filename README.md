# Food-Application-using-basics-of-JAVA
My first personal project. This is password protected food application. Through this we can order food from the given menu.

import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
		System.out.println("Welcome to the foodhog");
		Scanner scan=new Scanner(System.in);
		System.out.println("Please create a password: ");
		String pass1=scan.next();
		System.out.println("Your password now is:"+pass1);
		
		System.out.println("Please enter your password: ");
		String pass2=scan.next();
		
		while(!pass2.equals(pass1))
		{
		    System.out.println("The enter password do not match\nkindly enter correct password:");
		    pass2 =scan.next();
		}
		
		System.out.println("Access Granted! ");
		
		System.out.println("Are you hungry? (Answer in yes/no)");
		String ans1=scan.next();
		
		if(ans1.equals("yes"))
		{
		    System.out.println("Choose what you want to eat between pizza and burger");
		    String ans2=scan.next();
		    
		    if(ans2.equals("pizza"))
		    {
		        System.out.println("Please choose between veg and nonveg: ");
		        String ans3=scan.next();
		        if(ans3.equals("veg"))
		        {
		         System.out.println("Your order is placed.\n To confirm the order kindly enter your password: ");
		         String pass3=scan.next();
		         
		         	while(!pass3.equals(pass1))
		{
		    System.out.println("The enter password do not match\nkindly enter correct password:");
		    pass3 =scan.next();
		}
		
		System.out.println("Your order is confirmed\n Kindly wait till we process your order.");
		        }
		        else
		        {
		           System.out.println("Your order is placed.\n To confirm the order kindly enter your password: ");
		         String pass4=scan.next();
		         
		         	while(!pass4.equals(pass1))
		{
		    System.out.println("The enter password do not match\nkindly enter correct password:");
		    pass4 =scan.next();
		}
		
		System.out.println("Your order is confirmed\n Kindly wait till we process your order."); 
		        }
		    }
		    else{
		        System.out.println("Please choose between veg and nonveg: ");
		        String ans4=scan.next();
		        if(ans4.equals("veg"))
		        {
		         System.out.println("Your order is placed.\n To confirm the order kindly enter your password: ");
		         String pass5=scan.next();
		         
		         	while(!pass5.equals(pass1))
		{
		    System.out.println("The enter password do not match\nkindly enter correct password:");
		    pass5=scan.next();
		}
		
		System.out.println("Your order is confirmed\n Kindly wait till we process your order.");
		        }
		        else
		        {
		          System.out.println("Your order is placed.\n To confirm the order kindly enter your password: ");
		         String pass6=scan.next();
		         
		         	while(!pass6.equals(pass1))
		{
		    System.out.println("The enter password do not match\nkindly enter correct password:");
		    pass6=scan.next();
		}
		
		System.out.println("Your order is confirmed\n Kindly wait till we process your order.");  
		        }
		        
		    }
		}
		else{
		    System.out.println("Alright have a great day!");
		}
		
	}
}

