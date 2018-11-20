# while-loop

import java.util.Scanner;

public class sum1 {
    public static void main(String[] args) {

        /*int sum = 0;
        int number = 1;
        while (number != 0) {
            Scanner input = new Scanner(System.in);
            System.out.println("Enter a number or 0 to get the sum: ");
            number = input.nextInt();
            sum = sum + number;
        }
        System.out.println("The sum is " + sum);*/

        /*int x = 0;
        while(x < 100) {
            System.out.println(x + "");
            x= x+10;
        }*/

        /*int max = 8;
        while(max < 10) {
            System.out.println("Count down : " + max);
            max++;
        }*/

        /* int x = 250;
        while(x % 3 != 0) {
            System.out.println(x);
        }*/
        int x = 100;
        while(x > 0) {
            System.out.println(x/10);
            x=x/2;
        }
    }
}
