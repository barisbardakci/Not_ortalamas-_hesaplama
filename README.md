# Not_ortalamas-_hesaplama
Patika java101_1
import java.util.Scanner;

public class Main
{
	public static void main(String[] args) {
		int mat, fizik, kimya, turkce, tarih, muzik;
		
		Scanner ders=new Scanner(System.in);
		
		System.out.println("Matematik notunuz :");
		mat=ders.nextInt();
		System.out.println("Fizik notunuz :");
		fizik=ders.nextInt();
		System.out.println("Kimya notunuz :");
		kimya=ders.nextInt();
		System.out.println("Türkçe notunuz :");
		turkce=ders.nextInt();
		System.out.println("Tarih notunuz :");
		tarih=ders.nextInt();
		System.out.println("Müzik notunuz :");
		muzik=ders.nextInt();
		
		int toplam=(mat+fizik+kimya+turkce+tarih+muzik);
		double ortalama=toplam/6 ;
		System.out.println("Geçti : " + (ortalama >= 60));
		System.out.println("Kaldı :" + (ortalama < 60));
