import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
		Scanner sc = new Scanner (System.in);
		int num = sc.nextInt();
		System.out.println("Enter thr number");
	 	System.out.println(+num);
   
		if(num % 2 == 0)
		{
		    System.out.println("It is Even number");
		}
		else{
		    System.out.println("It is odd");
		}
		
		
}
}
