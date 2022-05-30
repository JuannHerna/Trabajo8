# Trabajo Practico 8
## Trabajo grupal Diagramas de flujo

## Ejercicio 1:
### Enunciado: 
Ingresar un número natural en la variable N. Determinar e imprimir un mensaje informando: si ‘N
es PAR’ o si ‘N es IMPAR’. 
**Codigo**
```  python 
print("Ingrese un numero para derterminar si es par:")
N= int(input(""))

if numero%2==0:
    print(f"El numero  ingresado {N} es par")
else:
    print("El numero ingresado {N} es impar")
```
**Grafo y Diagrama de flujo:**

![Image text](https://github.com/JuannHerna/Trabajo8/blob/main/ejercicio1.jpg)

**Calculo de complijedad**
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
