# HarmonikSeri

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);
        System.out.print("Sayı Giriniz: ");
        int number = input.nextInt();
        double toplam=0;

        for (int i=1;i<=number;i++){
            toplam=toplam + (1.0/i);
        }
        System.out.println(toplam);
    }
}
