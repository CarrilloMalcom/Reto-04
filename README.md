# Reto-04
## 1.
```python
print("Ingrese un número")
a=input()
try:
    a=int(a)
    a=abs(a)
    b=chr(a)    
    match b:
        case "a":
            print("El número que ingresaste corresponde a una vocal minuscula: "+b)
        case "e":
            print("El número que ingresaste corresponde a una vocal minuscula: "+b)
        case "i":
            print("El número que ingresaste corresponde a una vocal minuscula: "+b)
        case "o":
            print("El número que ingresaste corresponde a una vocal minuscula: "+b)
        case "u":
            print("El número que ingresaste corresponde a una vocal minuscula: "+b)
        case _:
            print("El número que ingresaste NO corresponde a una vocal minuscula: "+b)
except ValueError:
    print("No es un numero: ", a)
    

```

## 2.

```python
print("Ingrese una cadena de carácteres")
a=input()
a=str(a)
b= a[0]
b=ord(b)

if b%2==0:
    print("El primer carácter de los ingresados sí es par")
else:
    print("El primer carácter de los ingresados no es par")
```
## 3.

```python
print("Ingrese solo un caracter")
a=input()
a=a[0]
match a:
    case "0":
        print("El caracter que ingresaste es un digito: "+a)
    case "1":
        print("El caracter que ingresaste es un digito: "+a)
    case "2":
        print("El caracter que ingresaste es un digito: "+a)
    case "3":
        print("El caracter que ingresaste es un digito: "+a)
    case "4":
        print("El caracter que ingresaste es un digito: "+a)
    case "5":
        print("El caracter que ingresaste es un digito: "+a)
    case "6":
        print("El caracter que ingresaste es un digito: "+a)
    case "7":
        print("El caracter que ingresaste es un digito: "+a)
    case "8":
        print("El caracter que ingresaste es un digito: "+a)
    case "9":
        print("El caracter que ingresaste es un digito: "+a)
    case _:
        print("El caracter que ingresaste no es un digito: "+a)
```
## 4.
```python
print("Ingrese un número")
try:
    a = int(input())
    if a > 0:
        print ("El numero ", a, " ingresado es positivo")
    elif a < 0:
        print ("El numero ", a, " ingresado es negativo")
    else:
        print("El numero ingresado es ", a)
except ValueError:
    print("No es un número")
    
```
## 5.
```python
r=int(input("ingrese un Radio: "))
xc=int(input("Ingrese la coordenada x del centro del circulo: "))
yc=int(input("Ingrese la coordenada y del centro del circulo: "))
x=int(input("Ingrese la coordenada x de su punto"))
y=int(input("Ingrese la coordenada y de su punto"))

d=((((x-xc)**2)+((y-yc)**2))**0.5)
if d<r:
    print("El punto está dentro del circulo")
else:
    print("El punto no pertenece al circulo")
```
## 6.
```python
print("Ingrese 3 longitudes positivas: ")
a = int(input("a: "))
b = int(input("b: "))
c = int(input("c: "))
if a>b:
    if a>c:
        if a<(b+c):
            print("Es posble crear un triangulo con estos lados")
        else:
            print("No es posible crear un triangulo con estos lados")
    elif c>a:
        if c<(a+b):
            print("Es posble crear un triangulo con estos lados")
        else:
            print("No es posible crear un triangulo con estos lados")
elif b>c:
    if b<(a+c):
        print("Es posble crear un triangulo con estos lados")
    else:
        print("No es posible crear un triangulo con estos lados")
elif c<a+b:
    print("Es posble crear un triangulo con estos lados")
else:
    print("No es posible crear un triangulo con estos lados")
```
