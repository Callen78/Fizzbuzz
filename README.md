# Fizzbuzz
/* This program is a for a game called Fizz Buzz. 
  It allows a user to count from 1 to 100 and if the number is divisible by 3 then it print out Fizz.
  If it is divisible by 5 then it prints out Buzz. If the number isn't divisible by either then it just prints 
  out the number.
*/ 

public class Fizz_Buzz {

    
    public static void main(String[] args) {
      
        String x = "Fizz"; 
        String y = "Buzz"; 
        String z = "FizzBuzz"; 
        
        for (int i = 1; i <= 100; i++){
    
          
           if (i % 15 == 0){
               System.out.println(z + " " + i);
               
           }  
              else if (i % 5 == 0){
                  System.out.println(y + " " + i);
               }
              
                 else if (i % 3 == 0){
                        System.out.println(x + " " + i);
                    }

           }    
           
              
       
   }       
        
 }
