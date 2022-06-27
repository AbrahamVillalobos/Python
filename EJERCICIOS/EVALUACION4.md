# Práctica 4. 6 puntos
## Tipos de colección de datos.
### 4.1 Ejercicio 1(1.2 puntos)
Realizar un programa que inicialice una lista con 10 valores aleatorios (del 1 al 10)
y posteriormente muestre en pantalla cada elemento de la lista junto con su
cuadrado y su cubo.
Respuesta:

      from random import randint


      num1=randint(1,10)
      num2=randint(1,10)
      num3=randint(1,10)
      num4=randint(1,10)
      num5=randint(1,10)
      num6=randint(1,10)
      num7=randint(1,10)
      num8=randint(1,10)
      num9=randint(1,10)
      num10=randint(1,10)

      cua1=int(num1)**2
      cua2=int(num2)**2
      cua3=int(num3)**2
      cua4=int(num4)**2
      cua5=int(num5)**2
      cua6=int(num6)**2
      cua7=int(num7)**2
      cua8=int(num8)**2
      cua9=int(num9)**2
      cua10=int(num10)**2

      cub1=int(num1)**3
      cub2=int(num2)**3
      cub3=int(num3)**3
      cub4=int(num4)**3
      cub5=int(num5)**3
      cub6=int(num6)**3
      cub7=int(num7)**3
      cub8=int(num8)**3
      cub9=int(num9)**3
      cub10=int(num10)**3

      print('a continuacion se muestran: \n cuadrados \n cubos')

      print(num1, cua1, cub1)
      print(num2, cua2, cub2)
      print(num3, cua3, cub3)
      print(num4, cua4, cub4)
      print(num5, cua5, cub5)
      print(num6, cua6, cub6)
      print(num7, cua7, cub7)
      print(num8, cua8, cub8)
      print(num9, cua9, cub9)
      print(num10, cua10, cub10)
      
      
      
      

### 4.2 Ejercicio 2 (1.2 puntos)
Crea una lista e inicializarla con 5 cadenas de caracteres leídas por teclado. Copia
los elementos de la lista en otra lista pero en orden inverso, y muestra sus
elementos por la pantalla.


### 4.3 Ejercicio 3 (1.2 puntos)
Se quiere realizar un programa que lea por teclado las 5 notas obtenidas por un
alumno (comprendidas entre 0 y 10). A continuación debe mostrar todas las notas,
la nota media, la nota más alta que ha sacado y la menor.

### 4.4 Ejercicio 4 (1.2 puntos)
Codifica un programa en python que nos permita guardar los nombres de los
alumnos de una clase y las notas que han obtenido. Cada alumno puede tener
distinta cantidad de notas. Guarda la información en un diccionario cuya claves
serán los nombres de los alumnos y los valores serán listados con las notas de
cada alumno.

El programa pedirá el número de alumnos que vamos a introducir, pedirá su
nombre e irá pidiendo sus notas hasta que introduzcamos un número negativo. Al
final el programa nos mostrará la lista de alumnos y la nota media obtenida por
cada uno de ellos. Nota: si se introduce el nombre de un alumno que ya existe el
programa nos dará un error.


### 4.5 Ejercicio 5 (1.2 puntos)
Crea una tupla con los meses del año, pide números al usuario, si el número está
entre 1 y la longitud máxima de la tupla, muestra el contenido de esa posición sino
muestra un mensaje de error. El programa termina cuando el usuario introduce un
cero.


# TRATA DE RESOLVER Y AVANZAR LO MÁS POSIBLE EN LOS EJERICICIOS, EL MARTES HABILITO "AYUDAS" EN CADA EJERCICIO
