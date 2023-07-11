import java.util.Scanner;
public class Main { public static void main(String[] args){
        System.out.print("Matematik notunuzu giriniz :");
        int not, not1, not2, not3, not4, not5;
        Scanner inp = new Scanner(System.in);
        not = inp.nextInt();
        System.out.print(not);
        System.out.print("Fizik notunuzu giriniz :");
        not1 = inp.nextInt();
        System.out.print(not1);
        System.out.print("Kimya notunuzu giriniz :");
        not2 = inp.nextInt();
        System.out.print(not2);
        System.out.print("Türkçe notunuzu giriniz :");
        not3 = inp.nextInt();
        System.out.print(not3);
        System.out.print("Müzik notunuzu giriniz :");
        not4 = inp.nextInt();
        System.out.print(not4);
        System.out.print("Tarih notunuzu giriniz");
        not5 = inp.nextInt();
        System.out.print(not5);

        int toplam = (not + not1 + not2 +not3 + not4 + not5);
        double ortalama = toplam / 6;
        System.out.println("Ortalamanız :" + ortalama);

        String sonuc = (ortalama<60) ? ("Kaldı") : ("Geçti");
        System.out.print(sonuc);
    }
}
