import java.util.Scanner;
 
public class PositiveOrNegativeUsingIf 
{
	private static Scanner sc;
	
	public static void main(String[] args) 
	     {
	     
	                	int Number;
	                      	sc = new Scanner(System.in);		
	                        	System.out.println("\n Please Enter the any integer Value: ");
	                          	Number = sc.nextInt();
		
		       if (Number >= 0)
		       
		              {
			                    System.out.println("\n You have entered POSITIVE Number");
	               	}
		          else             
		                 {
		                      	System.out.println("\n You have entered NEGATIVE Number
			               }
	          	else
			               {
			                          	System.out.println("\n Number is zero");
		                 }
	
	}
	
}
