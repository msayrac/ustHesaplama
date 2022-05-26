# ustHesaplama
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int num, k;
        int total = 1;
        Scanner input = new Scanner(System.in);
        System.out.println("Bir sayi giriniz");
        num = input.nextInt();
        System.out.println(" ussu giriniz ");
        k = input.nextInt();
        for (int i = 1; i <= k; i++) {
            total = total * num;
        }
        System.out.println(total);
        
    }
}
