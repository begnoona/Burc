import java.util.Scanner;

public class Main {

        public static void main(String[] args) {

         /* Koç Burcu : 21 Mart - 20 Nisan

            Boğa Burcu : 21 Nisan - 21 Mayıs

            İkizler Burcu : 22 Mayıs - 22 Haziran

            Yengeç Burcu : 23 Haziran - 22 Temmuz

            Aslan Burcu : 23 Temmuz - 22 Ağustos

            Başak Burcu : 23 Ağustos - 22 Eylül

            Terazi Burcu : 23 Eylül - 22 Ekim

            Akrep Burcu : 23 Ekim - 21 Kasım

            Yay Burcu : 22 Kasım - 21 Aralık

            Oğlak Burcu : 22 Aralık - 21 Ocak

            Kova Burcu : 22 Ocak - 19 Şubat

            Balık Burcu : 20 Şubat - 20 Mart*/



            int ay,gun;
            Scanner input= new Scanner(System.in);
            System.out.print("Doğduğunuz ayı giriniz: ");
            ay=input.nextInt();

            System.out.print("Doğduğunuz günü giriniz: ");
            gun=input.nextInt();

            switch (ay){
                case 1:
                    if(gun<=21 && gun>=1)
                    {
                        System.out.print("Oğlak burcusunuz.");
                    }
                    else if(gun>21 && gun<=31){
                        System.out.print("Kova burcusunuz. ");
                    }
                    break;
                case 2:
                  if(gun<=19 && gun>=1)
                  {
                      System.out.print("Kova Burcusunuz.");
                  } else if (gun>=20 && gun<=30) {
                      System.out.print("Balık burcusunuz.");

                  }
                  break;
                case 3:
                    if(gun<=20 && gun>=1)
                    {
                        System.out.print("Balık Burcusunuz.");
                    } else if (gun>=21 && gun<=31) {
                        System.out.print("koç burcusunuz.");

                    }
                    break;
                case 4:
                    if(gun<=20 && gun>=1)
                    {
                        System.out.print("koç Burcusunuz.");
                    } else if (gun>=21 && gun<=30) {
                        System.out.print("Boğa burcusunuz.");

                    }
                    break;
                case 5:
                    if(gun<=21 && gun>=1)
                    {
                        System.out.print("Boğa Burcusunuz.");
                    } else if (gun>=22 && gun<=31) {
                        System.out.print("İkizler burcusunuz.");

                    }
                    break;
                    case 6:
                    if(gun<=22 && gun>=1)
                    {
                        System.out.print("İkizler Burcusunuz.");
                    } else if (gun>=23 && gun<=30) {
                        System.out.print("Yengeç burcusunuz.");

                    }break;
                    case 7:
                    if(gun<=22 && gun>=1)
                    {
                        System.out.print("Yengeç Burcusunuz.");
                    } else if (gun>=23 && gun<=31) {
                        System.out.print("Aslan burcusunuz.");

                    }
                    break;
                    case 8:
                    if(gun<=22 && gun>=1)
                    {
                        System.out.print("Aslan Burcusunuz.");
                    } else if (gun>=23 && gun<=30) {
                        System.out.print("Başak burcusunuz.");

                    }
                    break;
                case 9:
                    if(gun<=23 && gun>=1)
                    {
                        System.out.print("Başak Burcusunuz.");
                    } else if (gun>=24 && gun<=31) {
                        System.out.print("Terazi burcusunuz.");

                    }
                    break;
                case 10:
                    if(gun<=23 && gun>=1)
                    {
                        System.out.print("Terazi Burcusunuz.");
                    } else if (gun>=23 && gun<=30) {
                        System.out.print("Akrep burcusunuz.");

                    }
                    break;
                case 11:
                    if(gun<=22 && gun>=1)
                    {
                        System.out.print("Akrep Burcusunuz.");
                    } else if (gun>=23 && gun<=31) {
                        System.out.print("Yay burcusunuz.");

                    }
                    break;
                case 12:
                    if(gun<=22 && gun>=1)
                    {
                        System.out.print("yay Burcusunuz.");
                    } else if (gun>=23 && gun<=30) {
                        System.out.print("oğlak burcusunuz.");

                    }
                    break;
                default:
                    System.out.print("yanlış tercih yaptınız");


            }




    }
}
