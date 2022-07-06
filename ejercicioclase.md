num1=int(input('ingresa el primer numero'))
num2=int(input('ingresa el segundo numero'))

while True:
    opcion = int(input("""selecciona la opcion
    1-mostrar numeros
    2-sumar numeros
    3-restar numeros
    4-dividir numeros
    5-multiplicar
    6-cerrar"""))

    if opcion == 1: 
        print(num1,num2)
    elif opcion==2: 
        suma=num1 + num2
        print(suma)
    elif opcion==3: 
        resta=num1-num2
        print (resta)
    elif opcion==4: 
        if num1 == 0 or num2 == 0:
        print('valor invalido')
        else: 
        div=num1/num2
        print(div)
    elif opcion==5: 
        mult=num1*num2
        print (mult)
    elif opcion==6: 
        break

    else: 
        opcion > 6: print('solo puedes ingresar del 1 al 6')
        
        
        _________________________________________________
        
        
        
        class Calculadora():
 def __init__(self,num1,num2):
    self.suma = num1 + num2
    self.resta = num1 - num2
    self.mult = num1*num2
    self.div = num1/num2

while True:
    opcion = int(input("""selecciona la opcion
    1-iniciar
    2-sumar numeros
    3-restar numeros
    4-dividir numeros
    5-multiplicar
    6-cerrar"""))

    if opcion == 1:
