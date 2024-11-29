package Exercise;

import java.util.Scanner;

public class sayıSıralama {
    public static void main(String[] args) {
        int a, b, c;
        Scanner input = new Scanner(System.in);

        System.out.print("1.sayı: ");
        a = input.nextInt();
        System.out.print("2.sayı: ");
        b = input.nextInt();
        System.out.print("3.sayı: ");
        c = input.nextInt();

        if ((a > b) && (a > c)) {
            if (b > c) {
                System.out.println("1.sayı>2.sayı>3.sayı");
            } else {
                System.out.println("1.sayı>3.sayı>2.sayı");
            }
        } else if ((b > a) && (b > c)) {
            if (a > c) {
                System.out.println("2.sayı>1.sayı>3.sayı");
            } else {
                System.out.println("2.sayı>3.sayı>1.sayı");
            }
        } else if ((c > b) && (c > a)) {
            if (b > a) {
                System.out.println("3.sayı>2.sayı>1.sayı");
            } else {
                System.out.println("3.sayı>1.sayı>2.sayı");
            }
        }


    }
}
