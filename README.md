# Hoja_de_trabajo_progra3
hoja de trabajo numero 3
#Ejercicio_numero1
# print('hola a \'" todos \'" y \'" todas! \'" ')

#Ejercicio_numero2
#nombre = input('porfavor ingrese el usuario: ')
#print("hola mucho gusto <",nombre,">")
#Ejercicio_numero3
"""
print("A", "\tB", "\tW")
print("-----------------")
print("0", "\t0","\n0" "\t1", "\n1", "\t0", "\n1", "\t1")
i = 0
while i<4:
    i = i+1
    a = int(input("ingrese el valor de A: "))
    b = int(input("ingrese el valor de B: "))
    if(a == 0 and b == 0):
        print('W = 0')
    elif(a == 0 and b == 1):
        print('W = 1')
    elif(a == 1 and b == 0):
        print('W = 1')
    elif(a == 1 and b == 1):
        print('W = 1')
    else:
        print('ERROR')
        break
    
"""
#ejercicio_numero4

"""a = int(input("ingrese el numero total de de horas que ha estudiado: "))
b = int(input("ingrese el promedio de uso por dia: "))
c = a + b
print("la suma total de las horas estudiadas y promediadas es de: ", c)
"""
#Ejercicio_numero5
"""
def sumar(n):
    return(n * (n+1))/2
m= int (input("introduzca el numero M que desea: "))
sumar=sumar(m)
print("el resultado es: ", sumar)
"""
#Ejercicio_numero6
"""
p = float(input("ingrese su peso con especificación en libras: "))
e = float(input("ingrese su altura con especificación en metros: "))
media = p/2.2046
indice = float(media/(e**2))
result = round(indice, 2)
print("tu indice de masa corporal segun tu altura es: ", result)
"""
#Ejercicio_numero7
"""
a = float(input("introduzca el numero decimal deseado: "))
b = float(input("introduzca otro numero decimal que desee: "))
c = a/b
d = a%b
e = round(c, 2)
f = round(d, 2)
print("el resultado de la operación es: ", e)
print("el resultado del residuo de la operación es: ", f)

"""
#Ejercicio_numero8
"""
a=float(input("introduzca el monto que desea invertir: "))
b=float(input("introduzca el interes anual: "))
c=float(input("introduzca el total de años "))
d= float(b/100)
i = a*b*c
cf = a + i
f = round(cf, 2)
print(i)
print("el capital obtenido fue de: ",f)
"""
#Ejercicio_numero9
"""
b_barrenos=int(input("cuantos barrenos fueron vendidos en la ultima orden? "))
s_sierras=int(input("cuantas sierras se vendieron en la ultima orden? "))
b=112
s=75
totalb=b*b_barrenos
totals=s*s_sierras
total=totalb+totals
print("el total del peso del pedido es de:",total,"kilogramos")
"""
#Ejercicio_numero10
ram=20
ramuni=ram*0.60
a=int(input("ingrese la cantidad de RAM´s que va a comprar"))
b=a*ram
c=a*ramuni
d=b-c
print("el precio original de la venta es: ", b)
print("el descuento de la venta es de: ", d)
print("el precio final de la venta incluyendo descuento es de: ", c)
