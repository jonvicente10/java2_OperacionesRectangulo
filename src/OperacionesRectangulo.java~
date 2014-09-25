import java.util.Scanner;
/* Programa para calcular el area y el perimetro de un rectangulo. */

public class OperacionesRectangulo {

	public static void main (String args[]) {

		/* Se declaran la variable alto y base */
		double altointroducido, baseintroducida;

		Rectangulo rectangulo1 = new Rectangulo();
	
		Scanner sc = new Scanner(System.in);

		/* Mediante el escaner se solicita el alto del rectangulo */
		System.out.print("\nIntroduce el alto del rectangulo (en metros): ");
		altointroducido = sc.nextDouble();

		/* Mediante el escaner se solicita la base del rectangulo */
		System.out.print("\nIntroduce la medida de la base del rectangulo (en metros): ");
		baseintroducida = sc.nextDouble();

		/* A los metodos setRadio, setArea y setCircunferencia se les llama con el valor del dato introducido */
		rectangulo1.setAlto(altointroducido);
		rectangulo1.setBase(baseintroducida);

		/* El sistema nos muestra el resultado que obtiene mediante un getter */
		System.out.println("\nEl area del rectangulo es: " + rectangulo1.getArea() + "m²");
		System.out.println("\nEl perimetro del rectangulo es: " + rectangulo1.getPerimetro() + "m");

	}
}
