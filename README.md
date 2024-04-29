# Reto-10-Brayuxx
Punto 1: Promedio de un arreglo de reales
'''python
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
    '''
