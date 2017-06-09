import java.io.*;
import java.util.*;
class Number
{
    public static void main(String[] args) {
        Scanner scan=new Scanner(System.in);
        int sum=0;
        int a=scan.nextInt();
        for(int i=1;i<=a;i++)
        {
         
            sum=sum+i;
            
        }
        System.out.println(sum);
        
    }
    
}
