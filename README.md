# Mi programa favorito en Java :coffee:

Uno de mis programas favoritos de Java es el que salen caracteres aleatorios al estilo Matrix. Es un programa fácil. 

:large_blue_circle: A continuación os muestro el código :red_circle:

```java

public class Matrix {
  public static void main(String[] args) {
  
  int numero;
  
  for (int i = 0; i < 1000000; i++) {
  
    numero = (int)(Math.random() * 95 + 32);
    
    char caracter = (char)(numero);
    System.out.print("\033[32m" + caracter + " ");
    }
  }
}
  ```
  
  Solo hay que hacer un bucle "infinito" el cual pinte caracteres ASCII aleatorio entre el 32 y el 126. 
  
