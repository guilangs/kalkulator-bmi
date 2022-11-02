/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */
package projekperdana;

import java.util.Scanner;

/**
 *
 * @author MOKLET GAMING
 */
public class empat {

    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);

        //DEKLARASI
        double bmi, tinggibadan, beratbadan;
        String jeniskelamin, jawaban;
        
        //PENGULANGAN
        boolean ulang = true;
        while (ulang == true) {
            
            
            //PEMANIS
            System.out.println("===KALKULATOR BMI===");

            //PROSES
            System.out.print("Masukkan Berat Badan (Kg)= ");
            beratbadan = in.nextInt();
            System.out.print("Masukkan Tinggi badan (Cm)= ");
            tinggibadan = in.nextInt();
            System.out.print("Jenis Kelamin (L/P) = ");
            jeniskelamin = in.next();
            tinggibadan /= 100; //KONVERSI CENTIMETER KE METER
            bmi = beratbadan / (tinggibadan * tinggibadan);
            System.out.println("===================");
            System.out.println("BMI = " + bmi);

            //LAKI-LAKI
            if (jeniskelamin.equalsIgnoreCase("l")) {
                if (bmi < 17) {
                    System.out.println("-KURUS-");
                } else if (bmi >= 17 && bmi < 23) {
                    System.out.println("-NORMAL-");
                } else if (bmi >= 23 && bmi < 27) {
                    System.out.println("-KEGEMUKAN-");
                } else {
                    System.out.println("OBESITAS");
                }
            }

            //PEREMPUAN
            if (jeniskelamin.equalsIgnoreCase("p")) {
                if (bmi < 18) {
                    System.out.println("-KURUS-");
                } else if (bmi >= 18 && bmi < 25) {
                    System.out.println("-NORMAL-");
                } else if (bmi >= 25 && bmi < 27) {
                    System.out.println("-KEGEMUKAN-");
                } else {
                    System.out.println("OBESITAS");
                }
            }

            System.out.println("===================");
            System.out.println("Pengen ngulangi? (y/n)");
            jawaban = in.next();
            if (jawaban.equalsIgnoreCase("y")) {
                ulang = true;
            } else {
                ulang = false;
                System.out.println("== TERIMA KASIH ==");
            }
        }

    }
}
