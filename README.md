import java.util.*;
import java.io.*;
class simpleinterest
{
   public static void main(String args[])
   {
     Scanner sc = new Scanner(System.in);
     System.out.println("enter the principle amount:");
     int p = sc.nextInt();
     System.out.println("enter the rate of interest amount:");
     int r = sc.nextInt();
     System.out.println("enter the Time peroid:");
     int t = sc.nextInt();
     int S_I = p*t*r/100;
     System.out.println("the simpleinterest of principle amount:"+S_I);
  }
}
