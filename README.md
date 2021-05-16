import java.util.Scanner;
public class EvenOdd
{
public static void main(String args [])
{
Scanner scan=new Scanner(System.in);
System.out.print("Entert the number :");
int num=scan.nextInt();
checkOddEven(num);
}
public static void checkOddEven(int num)
{
if(num % 2 == 0)
System.out.println(num+"is Even ");
else
System.out.println(num+"is Odd ");
}
}

