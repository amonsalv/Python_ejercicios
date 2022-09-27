# Python_ejercicios

#Crea una función  que reciba una lista con valores numéricos y devuelva el valor máximo y el mínimo ingresados


#*args son argumentos indeterminados, por eso procedere a hacer una lista de numeros infinita

from array import array



listadenumeros()

#  Crea una función  que reciba una lista con valores numéricos y devuelva el valor máximo y el mínimo ingresados

def listadenumeros ():
    numeros = []
    for i in range (20):
        numero = int(input('Digite un numero: '))
        numeros.append(numero)  
    print(numeros.sort())   
    
def mayor(numero):
    max = numero[0];
    for x in numero:
        if x > max:
            max = x
    return max    
 
def menor(numero):
    min = numero[0];
    for x in numero:
        if x < min:
            min = x
    return min
 
def main(numeros):
    print ("La lista es ", numeros)
    print ("El número mayor es ", mayor(numero))
    print ("El número menor es ", menor(numero))
    
