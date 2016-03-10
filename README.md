# Are-you-thirsty-Buy-a-coke-program.JAVA

import java.util.Scanner;
public class Lab1 { 

    public static void main(String[] args){

        Scanner input = new Scanner(System.in);
     string breakfast;
     double num;
        System.out.println("I'm Hungry");
        System.out.println("Get in line");
        System.out.println("Buy Lunch");
        System.out.println("Are you thirsty? (1=Yes, 0=No): ");
        num = input.nextDouble();
     if(num == 1)
         {
            System.out.println("Did you eat breakfast?(Y/N) ");
            breakfast = input.nextLine();
            
            if(breakfast.equals("Y")
                System.out.println("Buy a diet coke");
            else
                System.out.println("Buy a coke");
            
            }
    else
        System.out.println("Get water");
        
    System.out.println("Eat lunch");
    System.out.println("Return tray");
    System.out.println("Leave");
}
}
