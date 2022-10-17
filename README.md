# EBOB-EKOK
---
Bu bir [patika.dev](www.patika.dev) projesidir.
```
import java.util.Scanner;
public class ebobEkok {
    public static void main(String[] args) {
        int a,b;
        int i=1,k=1;
        int ebob=1,ekok;
        Scanner input = new Scanner(System.in);
        System.out.print("Birinci sayıyı giriniz: ");
        a = input.nextInt();
        System.out.print("İkinci sayıyı giriniz: ");
        b = input.nextInt();

        while(i<=a) {
            if (a % i == 0 && b % i == 0) {
                ebob = i;
            }
            i++;
        }
        System.out.println("EBOB: "+ebob);

        while (k<=(a*b)){
            if (k % a == 0 && k % b == 0) {
                ekok = k;
                break;
            }
            k++;
        }
        System.out.print("EKOK: "+k);
    }
}
```
