# calculator
package pac1;

import java.util.Scanner;

public class switchCal {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int a=5;
		int b=3;
		Scanner sc=new Scanner(System.in);
		int cal= sc.nextInt();
		switch(cal)
		{
		case 1:
		   int c=a+b;
			System.out.println(c);
			   break;
		case 2:
	    	int d=a-b;
		    System.out.println(d);
		     break;
		case 3:
	    	int e=a/b;
		    System.out.println(e);
		     break;
		case 4:
	    	int f=a%b;
		    System.out.println(f);
		     break;
		case 5:
	    	int g=a^b;
		    System.out.println(g);
		     break;
		default:
			System.out.println("false");
		
		
		
		

	}

	}
}
