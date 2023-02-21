# Manav-Kasa-Program-
www.patika.dev

----------------------


import java.util.Scanner;

public class Meyve {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

      
        double armutFiyati = 2.14;
        double elmaFiyati = 3.67;
        double domatesFiyati = 1.11;
        double muzFiyati = 0.95;
        double patlicanFiyati = 5.00;

        
        System.out.println("Meyve miktarlarını girin:");
        System.out.print("Armut: ");
        double armutMiktari = scanner.nextDouble();

        System.out.print("Elma: ");
        double elmaMiktari = scanner.nextDouble();

        System.out.print("Domates: ");
        double domatesMiktari = scanner.nextDouble();

        System.out.print("Muz: ");
        double muzMiktari = scanner.nextDouble();

        System.out.print("Patlıcan: ");
        double patlicanMiktari = scanner.nextDouble();

        
        double toplamTutar = armutFiyati * armutMiktari +
                             elmaFiyati * elmaMiktari +
                             domatesFiyati * domatesMiktari +
                             muzFiyati * muzMiktari +
                             patlicanFiyati * patlicanMiktari;

        System.out.printf("Toplam Tutar: %.2f TL", toplamTutar);
    }
}

