# RETO 5


#### Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula

```pseudocode
 n : int = 103
if n == 97 or n == 101 or n== 106 or n== 111 or n== 117:
  print("el número "+str(n)+" corresponde al código ASCII de una vocal minúscula")
else:
  print("el número "+str(n)+" no corresponde al código ASCII de una vocal minúscula")
```


#### Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.
```pseudocode
 cadena = "x"
primer_caracter = cadena[0]
codigo_ascii = ord(primer_caracter)

if codigo_ascii % 2 == 0:
    print("El código ASCII de la primera letra de la cadena es par.")
else:
    print("El código ASCII de la primera letra de la cadena es impar.")
```
#### Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.
```pseudocode
caracter = input("Ingrese un carácter: ")
if caracter.isdigit():
    print("El carácter es un dígito.")
else:
    print("El carácter no es un dígito.")
```
#### Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero.
```pseudocode
n:float
n=float(input("Digite un número"))
if n == 0:
    print("El número x es el neutro para la suma")
elif n < 0:
    print("El número x es negativo")
elif n > 0:
    print ("El número x es positivo")

```

#### Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.
```pseudocode
x:float
y:float
x_c:float
y_c:float
x = float(input("Ingrese la coordenada x "))
y = float(input("Ingrese la coordenada y "))
x_c = float(input("Ingrese la coordenada x del centro del círculo "))
y_c = float(input("Ingrese la coordenada y del centro del círculo "))
radio = float(input("Ingrese el radio del círculo: "))

distancia = float((x - x_c)**2 + (y - y_c)**2)

if distancia < radio:
    print("El punto está dentro del círculo.")
else:
    print("El punto está fuera del círculo.")
```
#### Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo
```pseudocode
a:float
b:float
c:float
a = float(input("Ingrese la longitud del lado a"))
b = float(input("Ingrese la longitud del lado b"))
c = float(input("Ingrese la longitud del lado c"))

if a > 0 and b > 0 and c > 0:
    if a + b > c and a + c > b and b + c > a:
        print("Se puede construir un triángulo")
    else:
        print("No se puede construir un triángulo")
else:
    print("Las longitudes deben ser positivas.")
```
