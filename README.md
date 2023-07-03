# Control-Statements
//Print Prime Numbers in a range
//SOURCE CODE
import java.io.*;
import java.util.*;
public class Solution {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();         
        for (int i=2;i<=n;i++){
            int sum=0;
            for (int j=2;j<=i/2;j++)
            {
                if (i%j==0){
                    sum++;
                    break;
                }                
            }
        if (sum==0)
        {
            System.out.print(i+" ");
        }        
        }
    }
}

//Amoeba Multiplication
//SOURCE CODE
import java.io.*;
import java.util.*;
public class Solution {
    public static void main(String[] args) {
        Scanner sc=new Scanner (System.in);
        int month=sc.nextInt();
        int n1=0,n2=1,n3=0;
        for(int i=1;i<=(month-2);i++)
             {    
                n3=n1+n2;    
                n1=n2;    
                n2=n3;  
             } 
         System.out.print(n3);
    }
}

//Hollow square pattern
//SOURCE CODE
import java.io.*;
import java.util.*;
public class Solution {
    public static void main(String[] args) {
        Scanner sc=new Scanner (System.in);
        int num=sc.nextInt();
        for(int i=1;i<=num;i++){
                for(int j=1;j<=num;j++){
                    if(i==1||i==num||j==1||j==num){
                        System.out.print("*");
                    }
                    else
                    {
                        System.out.print(" ");
                    }
                }
         System.out.println();   
        }
      }
}
