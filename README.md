# linecompare.java
import java.util.Scanner;
public class Linecomaprisonuc1{
	public static void main(String[] args){
	double x1, x2, y1, y2;
	Scanner sc=new Scanner(System.in);
	System.out.println("enter the x1 coordinates");
	x1=sc.nextDouble();
	System.out.println("enter the x2 coordinates");
        x2=sc.nextDouble();
	System.out.println("enter the y1 coordinates");
        y1=sc.nextDouble();
	System.out.println("enter the y2 coordinates");
        y2=sc.nextDouble();

	double distance=Math.sqrt(Math.pow(x1-x2,2)+Math.pow(y1-y2,2));
	System.out.println(distance);
}
}
