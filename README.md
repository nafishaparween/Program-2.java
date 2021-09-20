# Program-2.java
Generate series of numbers.

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner scanner=new Scanner(System.in);
        System.out.println("enter value of ");
        int a=scanner.nextInt();
        int n=1;
        int max=Integer.MAX_VALUE;
        for(int i=1;i< max;i++)
        {
                if (i % 2 != 0) {
                    if(n>a)
                    {
                        break;
                    }
                    System.out.print(i + " ");
                    n++;
                }

        }


        scanner.close();
    }
}

