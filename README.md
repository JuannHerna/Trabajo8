# Trabajo Practico 8
## Trabajo grupal Diagramas de flujo
Alumnos: Juan Cruz Hernandez y Luz María Tranzillo 

## Ejercicio 1:
### Enunciado: 
Ingresar un número natural en la variable N. Determinar e imprimir un mensaje informando: si ‘N
es PAR’ o si ‘N es IMPAR’. 

**Código**
```  python 
print("Ingrese un numero para derterminar si es par:")
N= int(input(""))

if numero%2==0:
    print(f"El numero  ingresado {N} es par")
else:
    print("El numero ingresado {N} es impar")
```
**Grafo y Diagrama de flujo:**

![Image text](https://github.com/JuannHerna/Trabajo8/blob/main/diagramasygrafos/ejercicio1.jpg)

**Calculo de complejidad**
```
R=2
V(G)= 7- 7 + 2 = 2
V(G)= 1 + 1=2
```
**Caminos posibles**
```
1) 1,2,3,4,5,7
2) 1,2,3,4,6,7
```

## Ejercicio 2:
### Enunciado: 
Escriba un diagrama de flujo que permita ingresar un valor numérico real en una variable llamada
X, y que determine si X pertenece o no, a alguno de los intervalos [-1; 0) o (0; 1] (o a ninguno de
ellos), imprimiendo un mensaje que diga a cuál intervalo pertenece.

**Código**
``` python
print("Ingrese un valor real:  ")
x=float(input(""))
if x>=-1 and x<0:
    print(f"{x} pertenece al intervalo [-1;0)")
elif x>0 and x<=1:
    print(f"{x} pertecene al intervalo (0;1]")
else:
    print(f"{x} no pertenece a ningúno de los dos  intervalos")
```
**Grafo y Diagrama de flujo:**

![Image text](https://github.com/JuannHerna/Trabajo8/blob/main/diagramasygrafos/ejercicio2.jpg)

**Calculo de complejidad**
```
R=3
V(G)=10-9+2=3
V(G)=2+1=3
```
**Caminos posibles**
```
1) 1,2,3,4,5,6
2) 1,2,3,4,7,8,6
3) 1,2,3,4,7,9,6
```
## Ejercicio 3:
### Enunciado: 
Escriba un diagrama de flujo que permita generar e imprimir los primeros 5 números naturales (a
partir de 1).

**Código**
```  python 
print("Imprime los 5 primeros numero naturales ")
num=5
n=1
while n<=num:
    print(f"{n}")
    n+=1
```
**Grafo y Diagrama de flujo:**

![Image text](https://github.com/JuannHerna/Trabajo8/blob/main/diagramasygrafos/ejercicio3.jpg)

**Calculo de complejidad**
```
R=2
V(G)= 8 - 8 + 2 = 2
V(G)= 1+1
```

**Caminos posibles**
```
1)1,2,3,4,5,6,7,5,6,7,5,6,7,5,6,7,5,6,7
2) 1,2,3,4,5,8
```

## Ejercicio 4:
### Enunciado: 
Escriba un diagrama de flujo que permita generar e imprimir los primeros 5 números enteros
negativos.

**Código**
```  python 
print("Imprime los 5 primeros numeros enteros negativos ")
num=-5
n=-1
while n>=num:
    print(f"{n}")
    n-=1
```

**Grafo y Diagrama de flujo:**
![Image text](https://github.com/JuannHerna/Trabajo8/blob/main/diagramasygrafos/ejercicio4.jpg)

**Calculo de complejidad**
```
R=2
V(G)= 8 - 8 + 2 = 2
V(G)= 1+1
```
**Caminos posibles**
```
1) 1,2,3,4,5,6,7,5,6,7,5,8
2) 1,2,3,4,5,8
```
## Ejercicio 5:
### Enunciado: 
Escriba un diagrama de flujo que permita generar e imprimir los primeros 5 números naturales en
orden descendente (a partir de 5).

**Código**
```  python 
print("Imprime los 5 primeros numero naturales en orden descendente ")
num=1
n=5
while n>=num:
    print(f"{n}")
    n-=1
```
**Grafo y Diagrama de flujo:**
![Image text](https://github.com/JuannHerna/Trabajo8/blob/main/diagramasygrafos/ejercicio_5.jpg)
```
calculo complejidad:
R=2
V(G)= 8 - 8 + 2 = 2
V(G)= 1+1=2
```
**Caminos posibles**
```
1) 1,2,3,4,5,8
2) 1,2,3,4,5,6,7,5,6,7,5,8
```
## Ejercicio 6:
### Enunciado: 
Escriba un diagrama de flujo que permita generar e imprimir los primeros 5 números naturales
pares (a partir de 2).

**Código**
```  python 
print("Imprime los 5 primeros numeros naturales pares")
pares=2
cont=0
while cont<5:
    if pares%2==0:
        print(f"{pares}")
        cont+=1
    pares+=1
```
**Grafo y Diagrama de flujo:**
![Image text](https://github.com/JuannHerna/Trabajo8/blob/main/diagramasygrafos/ejercicio_6.jpg)

**Complejidad ciclomatica**
```
R=3
V(G)= 11 - 10 + 2 = 3
V(G)= 2+1=3
```
**Caminos posibles**
```
1) 1,2,3,4,5,6,7,8,5,6,9,5,6,7,8,5,10
2) 1,2,3,4,5,6,9,5,6,7,8,5,6,9,5,10
3) 1,2,3,4,5,10
```
## Ejercicio 7:
### Enunciado: 
Escriba un diagrama de flujo que permita generar e imprimir los primeros 5 números naturales
impares (a partir de 1).

**Código**
```  python 
print("Imprime los 5 primeros numeros naturales impares")
impar=1
cont=0
while cont<5:
    if impar%2==1:
        print(f"{impar}")
        cont+=1
    impar+=1
```

**Grafo y Diagrama de flujo:**
![Image text](https://github.com/JuannHerna/Trabajo8/blob/main/diagramasygrafos/ejercicio_7.jpg)

**Calculo de complejidad**
```
R=3
V(G)= 11 - 10 + 2 = 3
V(G)= 2 + 1= 3
```

**Caminos posibles**
```
1) 1,2,3,4,5,6,7,8,5,9
2) 1,2,3,4,5,6,10,5,9
3) 1,2,3,4,5,6,7,8,5,6,10,5,6,7,8,5,9
```
## Ejercicio 8
### Enunciado:
Escriba un diagrama de flujo que permita ingresar 6 pares de números naturales que representan
notas de parciales, en las variables N1 y N2, y que calcule e imprima el promedio de cada par de
notas.

**Codigo**

```python
promedios=[]
cont=0
while cont<3:
    print("Ingrese un par de notas de parciales para determinar el promedio:")
    n1= int(input("Nota 1:"))
    n2= int(input("Nota 2:"))
    prom=n1+n2
    prom= prom/2
    print(f"El promedion de las notas es: {prom}")
    promedios.append(prom)
    cont+=1
print(f"El promedio de las pares de notas son: {promedios}")
```
**Grafo y Diagrama de flujo:**
![Image text](https://github.com/JuannHerna/Trabajo8/blob/main/diagramasygrafos/ejercicio_8.jpg)

**Complejidad ciclomatica**
```
R=2
V(G)= 14 - 14 + 2 = 2
V(G)= 1+1
```
**Caminos posibles**
```
1) 1,2,3,4,5,6,7,8,9,10,11,12,4,13,14
2) 1,2,3,4,13,14
```
## Ejercicio 9
### Enunciado:
Ingresar un número natural en la variable A. Determinar e imprimir un mensaje informando: si A
es múltiplo de 3 o no.

**Codigo**
```python
print('Multiplos de 3')
A=int(input('Ingrese un número natural '))
if A%3==0:
    print(f'{A} es múltiplo de 3')
else:
    print(f'{A} no es múltiplo de 3')
```
**Grafo y Diagrama de flujo:**
![Image text](https://github.com/JuannHerna/Trabajo8/blob/main/diagramasygrafos/ejercicio9.jpg)

**Complejidad ciclomatica**
```
R=2
V(G)= 7 - 7 + 2 = 2
V(G)= 1+1=2
```
**Caminos posibles**
```
1) 1,2,3,4,5,6
2) 1,2,3,4,7,6
```
## Ejercicio 10:
### Enunciado:
Ingresar números enteros en la variable B y, MIENTRAS el valor ingresado en B sea
POSITIVO, calcular la cantidad de números ingresados e imprimirla en un mensaje.

**Codigo**
``` Python
cont=0
print("Ingrese valores positivos, el programa le mostrar cuantos valores ingreso:")
print("Un valor negativo cortara el programa")
b=int(input(""))
while b>=0:
    cont+=1
    b=int(input("Ingrese un valor positivo: "))
print(f"Ustes ingreso {cont} numero positivos")
```

**Grafo y Diagrama de flujo:**

![Image text](https://github.com/JuannHerna/Trabajo8/blob/main/diagramasygrafos/ejercicio_10.jpg)

**Calculo de complejidad**
```
R=2
V(G)= 10- 10 + 2 = 2
V(G)= 1+1
```

**Caminos posibles**
```
1) 1,2,3,4,5,6,7,8,6,9,10
2) 1,2,3,4,5,6,9,10
```

## Ejercicio 11:
### Enunciado:
Ingresar números enteros en la variable Z, HASTA que la suma de los valores ingresados en Z
sea mayor a 500. Determinar e imprimir la cantidad de números ingresados.

**Codigo**
``` Python
print('Contador de números hasta que la suma de ellos sea mayor a 500')
suma=0
contador=0
while suma<=500:
    z=int(input('Ingrese un número '))
    suma+=z
    contador+=1
print(f'La cantidad de números ingresados fue de {contador}')
```

**Grafo y Diagrama de flujo:**

![Image text](https://github.com/JuannHerna/Trabajo8/blob/main/diagramasygrafos/ejercicio11.jpg)

**Calculo de complejidad**
```
R=2
V(G)= 9 - 9 + 2 = 2
V(G)= 1+1=2
```

**Caminos posibles**
```
1) 1,2,3,4,5,6,7,8,5,9
2) 1,2,3,4,5,6,7,8,5,6,7,8,5,9
```

## Ejercicio 12
### Enunciado:
Ingresar 10 números enteros usando la variable X. Determinar e imprimir un mensaje
informando: la cantidad de números POSITIVOS, la cantidad de números NEGATIVOS y, la
cantidad de CEROS ingresados.
**Codigo**
```python
cont_nega=0
cont_cero=0
cont_posi=0
suma_cont=0
print("Ingrese 10 valores")
print("El programa le mostrara cuantos valores ingreso, postivos, negativos y cero")

while suma_cont<10:
    x=int(input("Ingrese un numero: "))
    if x>0:
        cont_posi+=1
    elif x<0:
        cont_nega+=1
    else:
        cont_cero+=1
    suma_cont=cont_nega+cont_cero+cont_posi

print("Ustes ingreso:")
print(f"Positivos: {cont_posi}")
print(f"Negativos: {cont_nega}")
print(f"Ceros: {cont_cero}")
```
**Grafo y Diagrama de flujo**
![Image text](https://github.com/JuannHerna/Trabajo8/blob/main/diagramasygrafos/ejercicio_12.jpg)
**Comlejidad ciclomatica**
```
R=4
V(G)= 22 - 20+ 2 = 4
V(G)= 3+1=4
```
**Caminos posibles**
```
1) 1,2,3,4,5,6,7,8,9,10,11,12,8,9,10,13,14,12,8,16,17,18,19,20
2) 1,2,3,4,5,6,7,8,9,10,13,15,12,8,9,10,11,12,8,9,10,13,14,12,8,9,10,13,15,12,8,16,17,18,19,20
```
## Ejercicio 13
### Enunciado:
Ingresar 2 números naturales P y Q, donde P representa el multiplicando y Q el multiplicador.
Se pide que, utilizando solamente la operación de suma, calcule el resultado de la operación P * Q
e imprima el valor de P, de Q y de P * Q.

**Codigo**
```python
print('Multiplicación sumando')
p=int(input('Ingrese un número de multiplicando '))
q=int(input('Ingrese un número de multiplicador '))
producto=0
contador=q
while contador!=0:
      producto+=p
      contador-=1
print(f'El producto de multiplicar {p} por {q} es {producto}')
```

**Grafo y Diagrama de flujo:**

![Image text](https://github.com/JuannHerna/Trabajo8/blob/main/diagramasygrafos/ejercicio_13.jpg)

**Calculo de complejidad**
```
R=2
V(G)= 11- 11 + 2 = 2
V(G)= 1+1= 2
```

**Caminos posibles**
```
1) 1,2,3,4,5,6,7,8,9,7,10
2) 1,2,3,4,5,6,7,10
```
# Trabajo 8 Bis

## Ejercicio 2
### Enunciado:

2) Dibujar un diagrama de flujo de datos que permita cargar y determinar e imprimir la posición del
último elemento negativo dentro de un vector X con datos numéricos enteros ingresados por el
usuario, con entre 8 y 40 elementos.

**Codigo**
```python
numero=[]
i=0
pos=0
j=0
maxx=int(input('Ingrese la cantidad de elementos que desea cargar, de 8 a 40: '))
while maxx<8 or maxx>40:
    print('Ingrese un numero dentro del rango, 8 a 40')
    maxx= int(input(''))

while i<maxx:
    print('ingrese un numero')
    num=int(input())
    numero.append(num)
    print(numero)
    i+=1
limite= len(numero)

while j<limite:
    if numero[j]<0:
        pos=j
    j+=1
if pos>0:
    print(f'La posicion del ultimo elemento negativo ingresado es : {pos}')
else:
    print("no existen numeros negativvos ingresados")

```
**Grafo y Diagrama de flujo:**
![Image text](https://github.com/JuannHerna/Trabajo8/blob/main/tp8_bis/ejercicio2.jpg)
**Calculo de complejidad**
```
v(g)= R=6
v(g)= A-N+2=26-22+2=6
v(g)= P +1= 6
```
**Caminos posibles**
```
1) 1,2,3,4,5,6,7,10,11,12,13,14,10,15,16,17,18,15,19,20,22
2) 1,2,3,4,5,6,7,8,9,7,10,11,12,13,14,10,11,12,13,14,10,15,16,17,18,15,19,21,22
```
