RETO 3 

Plantear el algoritmo para obtener los números primos hasta n, usando pseudocódigo y diagramas de flujo.

lo que haremos es plantear variables 
n: entero( numero mayor o igual a 2)
i :entero (es el numero que se esta evaluando )
x : entero (se va a usar para ir por la lista y encontrar los valores que sean divisibles por i)

lo que vamos a hacer es primero crear un numero limite que se va a evaluar esto lo vamos a hacer con (n)
y se creara una lista de todos los numeros naturales desde el 2 hasta (n).
despues tomaremos el primer numero de la lista que en este caso es el 2 y se buscara todos los numeros multiplos de ese numero (es decir, todos los que se pueden dividir por él, excluyendo al mismo número) y pues estos numeros se deben tachar es decir que no son primos. 
esto se hace con todos los numeros que no son tachados hasta llegar al numero limite 
en pseudocodigo se veria algo asi 



inicio
  escribir("Ingrese un número entero mayor o igual a 2:")
  leer n

  Crear una lista llamada 'numeros' con los valores desde 2 hasta n

  Para cada i en numeros hacer
    Si i * i > n entonces
      salir del ciclo
    Fin si
      Para cada x en numeros hacer
      Si x > i y x mod i == 0 entonces
        tachar j de la lista (es decir, eliminarlo o marcarlo como no primo)
      Fin si
  Fin 

  escribir("Los números primos hasta", x, "son:")
  Para cada elemento en numeros hacer
    Si el número no está tachado entonces
      escribir el número
    Fin si
  Fin para
fin


el diagrama se veria algo asi
https://www.mermaidchart.com/app/projects/75cd038a-bed1-4729-904b-c3d1039bb930/diagrams/b756afd6-2b6f-440b-9737-a4eaa57fb972/version/v0.1/edit

![image](https://github.com/user-attachments/assets/f4bffdb8-1566-4a7f-a9db-0b9d28e66246)

![image](https://github.com/user-attachments/assets/9ec7e22b-7684-4511-b07f-41b648cc4db7)

![image](https://github.com/user-attachments/assets/b7d662c0-ea04-4617-a689-fdf397b2c923)

