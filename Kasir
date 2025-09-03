/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package latihanpemogramansekuensiel;

import java.util.Scanner;

/**
 *
 * @author revin
 */
public class LatihanPemogramanSekuensiel {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        // Input jumlah beras dan harga per kg
        System.out.print("Masukkan jumlah beras (kg): ");
        double jumlahBeras = input.nextDouble();

        System.out.print("Masukkan harga per kg: ");
        double hargaPerKg = input.nextDouble();

        // Hitung total sebelum diskon
        double total = jumlahBeras * hargaPerKg;

        // Hitung diskon 5%
        double diskon = total * 0.05;
        double totalAkhir = total - diskon;

        System.out.println("\n=== Rincian Belanja ===");
        System.out.println("Jumlah Beras: " + jumlahBeras + " kg");
        System.out.println("Harga per kg: Rp " + hargaPerKg);
        System.out.println("Total sebelum diskon: Rp " + total);
        System.out.println("Diskon 5%: Rp " + diskon);
        System.out.println("Total setelah diskon: Rp " + totalAkhir);

        // Input uang dari pembeli
        System.out.print("\nMasukkan jumlah uang dari pembeli: Rp ");
        double uangPembeli = input.nextDouble();

        // Hitung kembalian
        double kembalian = uangPembeli - totalAkhir;

        if (kembalian < 0) {
            System.out.println("Uang pembeli kurang Rp " + Math.abs(kembalian));
        } else {
            System.out.println("Uang kembalian: Rp " + kembalian);
        }

        input.close();
    }
    
}
