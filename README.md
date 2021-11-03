 ![git](https://statics.rubenortiz.es/wp-content/uploads/2020/10/04105143/GitHub_Logo.png)
# MUY BUENAS TARDES A TODOS.😄
  Mi nombre es **Héctor Xavier** y esta es mi página de GitHub, hecha con MarkDown. 
  

 Estoy junto con mis compañeros (obviamente) estudiando **1ºDAM** en el **IES Luis Vives.**
 Nuestro tutor @joseluisgs, nos da Programación y Entornos de Desarrollo. Una persona demasiado lista al cual se le nota que le gusta su vocación.
 ***Lo cual da mucho miedo*** No blame please.
 
```java
public class main{
public static void main(String[] args) {
        int[][] matriz = {{1, 3, 5}, {7, 9, 11}, {3, 1, 13}};
        printMatriz(matriz);
        System.out.println("");
        maxMatriz(matriz);
        System.out.println("");
        minMatriz(matriz);
    }

    //Printar la Matriz
    private static void printMatriz(int[][] matriz) {
        for (int i = 0; i < matriz.length; i++) {
            for (int j = 0; j < matriz[i].length; j++) {
                System.out.print(matriz[i][j] + " ");
            }
            System.out.println();
        }
    }

    //Máximo en las filas
    private static void maxMatriz(int[][] matriz) {
        int maxNumber = matriz[0][0];
        for (int i = 0; i < matriz.length; i++) {
            maxNumber = matriz[i][0];
            for (int j = 0; j < matriz[i].length; j++) {
                if (maxNumber < matriz[i][j]) {
                    maxNumber = matriz[i][j];
                }
            }
            System.out.println("El valor Máximo de la fila " + i + " es " + maxNumber);

        }
    }
```


En **Programación** estamos viendo los **Las Arrays Unidimensionales y multidimensionales**. Lo cual me parece muy loco ahora mismo.
Estamos trabajando en Java

  
<!--
**XavierSinPiernas/XavierSinPiernas** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
