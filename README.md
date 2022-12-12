# VucutKitleIndeksi
```
import java.util.Scanner;

public class VucutKitle {
    public static void main(String[] args) {
        double b,k,bmi;
        Scanner i = new Scanner(System.in);
        System.out.print("Boyunuzu m cinsinden giriniz: ");
        b = i.nextDouble();

        System.out.print("Kilonuzu kg cinsinden giriniz: ");
        k = i.nextDouble();

        bmi = k / (b * b);
        System.out.println("Vücut Kitle İndeksiniz: " + bmi);


    }
}
```
[Patika.dev](https://app.patika.dev/iremr)
