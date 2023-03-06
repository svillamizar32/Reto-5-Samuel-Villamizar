# Reto-5-Samuel-Villamizar
Solving problems related with conditionals, using if-else and elif.
## Resolver los siguientes problemas usando un notebook de python y subirlos a un repo.
1. Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.
```python
x= int((input ("Ingrese un numero")))
print (x) 
if x == 97 or x == 101 or x == 105 or x == 111 or x == 117:
    print ( chr(x),"es una vocal minuscula")
else :
    print ( chr(x), "no es una vocal")
```
2. Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.
```python
x = ord(input ("introduzca un caracter"))
if x % 2 == 0 :
    print ("el código ASCII del caracter es par")
else :
    print ("el código ASCII del caracter es impar")
```
3. Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.
```python
x = input ("introduzca un caracter")
if 65 < ord(x) < 122 :
    print (x,"no es un digito")
else :
    print (x,"es un digito")
```
4. Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación: 
	- Positivo: "El número x es positivo"
	- Negativo: "El número x es negativo"
	- Cero (0): "El número x es el neutro para la suma"
```python
x = int(input ("introduzca un numero"))
if x == 0 :
    print (x,"El número es el neutro para la suma")
elif x < 0 :
    print (x,"El número es negativo")
else : 
    print (x,"El número es positivo")
```
5. Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.
6. Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.
```python
a = float (input("Longitud 1"))
b = float (input("Longitud 2"))
c = float (input("Longitud 3"))
if (a + b) > c and (a + c)> b and (c + b) > a:
    print("es posible hacen un triangulo")
else:
    print("no es posible hacen un triangulo")
```
