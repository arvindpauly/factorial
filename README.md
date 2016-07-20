# factorial
import java.util.Scanner;
public class factorial {
	 
	private static Scanner fact;

	public static void main(String []arg){
		fact = new Scanner(System.in);
		int i,n;
		int a=1;
		System.out.println("enter the numberto get factorial");
		n = fact.nextInt();
		
		for(i=1;i<=n;i++)
				{
					a=a*i;
				}
		System.out.println("The Factorial of "+n+" is "+a);
				
	}

}
