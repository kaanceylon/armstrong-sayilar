# armstrong-sayilar

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);
        System.out.print( "bir sayı giriniz : " );
        int number   = input.nextInt();
        int basamakNumber=0;
        int tempNumber = number;
        int basValue;
        int result = 0;

        while (tempNumber !=0){
            tempNumber/= 10;
            basamakNumber++;

        }
        tempNumber = number;
        while(tempNumber !=0){
            basValue =  tempNumber % 10;
            tempNumber/= 10;
            result += basValue;
        }
        System.out.println( result);

















    }
}

































