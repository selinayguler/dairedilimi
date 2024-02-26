# dairedilimi
package patika;
import java.util.Scanner;


public class dairediliminibulma {

	public static void main(String[] args) {
		double r ,a , pi =3.14 , circleA;
		Scanner input = new Scanner(System.in);
		System.out.println("Yarıçapını giriniz:");
		r = input.nextDouble();
		System.out.println("Merkez açı ölçüsünü giriniz:");
		a = input.nextDouble();
		circleA = (pi*(r*r)*a)/360;
		System.out.println("Daire diliminin alanı :" + circleA);
				
		
	

	}

}
