# Trabajo Practico 8
## Trabajo grupal Diagramas de flujo

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
**Grafo y Diagrama de flujo:**## Ejercicio 1:
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
Ejercicio 1:
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
**Grafo y Diagrama de flujo:**## Ejercicio 1:
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
**Grafo y Diagrama de flujo:**## Ejercicio 1:
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
**Grafo y Diagrama de flujo:**## Ejercicio 1:
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

