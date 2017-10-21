# Problem-3-triangle---left-


import java.util.Scanner;

public class Star3 {

    public static void main(String[] args) {
         
        int i,j,star;
        Scanner input=new Scanner(System.in);
        System.out.println("enter the number");
        star=input.nextInt();
        for(i=1;i<=4;i++)
        {
             for(j=1;j<=i;j++)
            {
                System.out.print("* ");
            }
             
              System.out.println(" ");
        }
        
    }
    
}
