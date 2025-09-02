# Comentarios línea por línea — Programa.java

1  import java.util.Scanner;  → Importa la clase Scanner desde java.util para leer desde consola.
3  public class Programa {    → Declara la clase pública; debe llamarse igual que el archivo.
4  public static void main(String[] args) { → Punto de entrada del programa.

5  Scanner scanner = new Scanner(System.in); → Crea lector de la entrada estándar.

7  String marca;              → Variable de texto para la marca.
8  String modelo;             → Variable de texto para el modelo.
9  int cilindrada;            → Variable entera para cilindrada (cc).
10 String tipoCombustible;    → Variable de texto para el combustible.
11 int capacidadPasajeros;    → Variable entera para capacidad.

13 System.out.println("Ingrese la marca:"); → Mensaje en pantalla.
14 marca = scanner.nextLine();              → Lee línea completa para marca.

16 System.out.println("Ingrese el modelo:");→ Mensaje en pantalla.
17 modelo = scanner.nextLine();             → Lee modelo.

19 System.out.println("Ingrese la cilindrada (en cc):"); → Mensaje.
20 cilindrada = scanner.nextInt();          → Lee entero para cilindrada.
21 scanner.nextLine();                      → Consume salto pendiente tras nextInt.

23 System.out.println("Ingrese el tipo de combustible:"); → Mensaje.
24 tipoCombustible = scanner.nextLine();    → Lee combustible.

26 System.out.println("Ingrese la capacidad en pasajeros:"); → Mensaje.
27 capacidadPasajeros = scanner.nextInt(); → Lee entero capacidad.

29 System.out.println("La marca que ha ingresado es: " + marca);            → Imprime marca.
30 System.out.println("El modelo que ha ingresado es: " + modelo);          → Imprime modelo.
31 System.out.println("La cilindrada que ha ingresado es: " + cilindrada);  → Imprime cilindrada.
32 System.out.println("El tipo de combustible es: " + tipoCombustible);     → Imprime combustible.
33 System.out.println("Tiene una capacidad de " + capacidadPasajeros + " pasajeros."); → Imprime capacidad.

35 scanner.close(); → Cierra el lector.
36 }                → Cierra main.
37 }                → Cierra clase.
