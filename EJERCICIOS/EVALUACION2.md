## Práctica 2. 6 puntos
2 Práctica 2. Números enteros y reales.

Realiza los ejercicios de acuerdo a las indicaciones

2.1 Ejercicio 1 (1.5 puntos)

Escribir un programa que convierta un valor dado en grados Fahrenheit a grados
Celsius.

    temp_far=input('ingresa una temperatura en grados farengeit')
    cel=(int(temp_far)-32)*(5/9)
    print(cel)


2.2 Ejercicio 2 (1.5 puntos)

Dados dos números, mostrar la suma, resta, división y multiplicación de
ambos.

    num1=input('ingresa el primer numero')
    num2=input('ingresa el segundo numero')
    suma=int(num1)+int(num2)
    resta=int(num1)-int(num2)
    mul=int(num1)*int(num2)
    div=int(num1)/int(num2)
    print('suma',suma, " resta ", resta, " multiplicacion ", mul, " division      ", div )

2.3 Ejercicio 3 (1.5 puntos)

Calcular el perímetro y área de un rectángulo dada su base y su altura.
Respuesta:

    base=input('ingresa la base')
altura=input('ingresa la altura')
res=int(base)*int(altura)
print(res)


