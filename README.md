import java.util.Scanner;

public class taksii {
    public static void main(String[] args) {

        double mesafe , kmbasinatutar , toplamtutar, acilis , minimumtutar ;

        Scanner girdi = new Scanner(System.in);
        System.out.print("Mesafeyi Giriniz :");
        mesafe = girdi.nextDouble();




        kmbasinatutar = 2.20 ;
        acilis = 10 ;
        toplamtutar = acilis + (mesafe * kmbasinatutar) ;
        minimumtutar = 20;



        if(toplamtutar < minimumtutar) {
            System.out.print("Ödenecek Tutar :" + minimumtutar);
        } else {
            System.out.print("Ödenecek Tutar :" + toplamtutar);
        }






    }
}
