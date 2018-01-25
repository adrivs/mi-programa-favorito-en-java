# Mi programa favorito en Java :coffee:

Uno de mis programas favoritos de Java es el que salen caracteres aleatorios al estilo Matrix. Es un programa fácil. 

:large_blue_circle: A continuación os muestro el código :red_circle:

```java

public class Matrix {
  public static void main(String[] args){
    int num;
    final String GREEN = "\033[32m";
    for(int i = 0; i < 8000; i++) {
      num = (int)(Math.random() * (126 - 32 + 1) + 32);
      System.out.print(GREEN + (char)(num));
      if (i % 100 == 0){
        System.out.println();
      }
    } 
  }
}
  
  ```
  
  
