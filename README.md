# Reto-10-Brayuxx
Punto 1: Promedio de un arreglo de reales
```python
#Cree una lista donde los números sean representados por variables que el usuario digitara
def promedio(a:float, b:float, c:float) -> float:
    #Funcion para hacer el cálculo del promedio
    prome = (a+b+c)/len(lista)
    return prome


if __name__=="__main__":
    #le pedimos al usuario 3 números reales
    a=float(input("Ingrese un número real: "))
    b=float(input("Ingrese un 2do número real: "))
    c=float(input("Ingrese un 3er número real: "))
    #llamamos la función
    dio=promedio(a,b,c)
    print(f"El promedio de su arreglo de valores reales es de: {dio:.3f}")
```
Punto 2: Producto punto de dos arreglos
````python
#Calcular  Punto punto de dos arreglos de reales de igual tamaño.
#Creamos 2 listas
listaA = [10,20,30,40,50]
listaB = [2,3,4,5,6]
#Le damos valor 0 a nuestra variable
Punto : int = 0
#Se utiliza For para hacer el procedimiento del producto
for i in range(len(listaA)):
    Punto = Punto + (listaA[i]*listaB[i])
print(Punto)
````
Punto 3
````python
# Hacer un algoritmo que deje al final de un arreglo de números todos los ceros que aparezcan en dicho arreglo.
# Inicializa un arreglo vacío para almacenar los números
arreglo_numeros = []

cantidad_arreglo = int(input("¿De cuantos numeros quiere el arreglo?:"))

primer_numero = int(input("Ingrese su primer numero para el arreglo:"))
arreglo_numeros.append(primer_numero)

# Utiliza un bucle for para pedir al usuario los números intermedios
for i in range(cantidad_arreglo - 2):
    numeros = int(input("Ingrese el siguiente numero: "))
    arreglo_numeros.append(numeros)

ultimo_numero = int(input("Ingrese el ultimo numero para el arreglo:"))
arreglo_numeros.append(ultimo_numero)


# Imprime el arreglo de números original
print("Su arreglo de numeros es:" + str(arreglo_numeros))

# Recorre el arreglo de números
for numero in arreglo_numeros:
    # Si el número es 0, lo agrega al final del arreglo y lo elimina de su posición actual
    if numero == 0:
        arreglo_numeros.append(numero)
        arreglo_numeros.remove(numero)
    # Si el número no es 0, continúa con la siguiente iteración del bucle
    else:
        if numero != 0:
            continue
print("Su arreglo de numeros con los ceros al final del arreglo es:" + str(arreglo_numeros))

````
Punto 4: Bubble-Sort?
Bubble-sort es un algoritmo de clasificación  el cual va  reemplazando iterativamente elementos  si están desordenados con el fin de ordenarlos de menor a mayor sin embargo existe un problema y es que este algoritmo no es adecuado para grandes conjuntos de datos porque su complejidad temporal se vuelve alta a medida que la lista incremente sus elementos ya que utilizaria mas condicionales
:)



