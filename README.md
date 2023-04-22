# body
import java.util.Scanner;

public class vucutkitle {

    public static void main(String[] args) {
      double boy , kilo , index;

        Scanner kitle = new Scanner(System.in);
        System.out.print("Boyunuzu Metre Cinsinden Giriniz : ");
        boy = kitle.nextDouble();

        System.out.print("Kilonuzu Giriniz : ");
        kilo = kitle.nextDouble();

        index = kilo / (boy * boy);

        System.out.print("Kitle indeksiniz : "+ index);
        
    }
    
}
