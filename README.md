# Mi programa favorito en Java :coffee:

Uno de mis programas favoritos de Java es el que salen caracteres aleatorios al estilo Matrix. Es un programa fácil. 

:large_blue_circle: A continuación os muestro el código :red_circle:

```java

public class Matrix {
  public static void main(String[] args) throws InterruptedException {
    for (int i = 1; i > 0; i++){
      System.out.print((char)((Math.random()*127)+32));
      Thread.sleep();
    }
  }
  
  ```
  
  
