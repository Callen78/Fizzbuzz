# Fizzbuzz
/* This program is a for a game called Fizz Buzz. 
  It allows a user to count for 1 to 100 and if the number is divisible by 3 then it print out Fizz.
  If it is divisible by 5 then it prints out Buzz. If the number isn't divisible by either then it just prints 
  out the number.
*/ 

public class FizzBuzz 
  {
	public static void main(String[] args)	
	{
	String buzz =  "buzz", fizz = "fizz"; //initializes the string variables
	for (int i = 1; i <= 100; i++)
	{
	if (i % 15 == 0) //check if number in position i is divisable by 15, if so don't check other 2 conditions - we don't want a double print
	{
	  System.out.println(buzz + fizz + " " + i);
	}
	else if (i % 3  == 0 )
	{
	  System.out.println(buzz + " " + i);
	}
	else if (i % 5== 0)
	{
	  System.out.println(fizz + " "+ i);
	}
	}
	}
  }
