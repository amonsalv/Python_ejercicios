# Python_ejercicios

#Crea una función  que reciba una lista con valores numéricos y devuelva el valor máximo y el mínimo ingresados


#*args son argumentos indeterminados, por eso procedere a hacer una lista de numeros infinita

from array import array


def listadenumeros ():
    numeros = []
    for i in range (20):
        numero = int(input('Digite un numero: '))
        numeros.append(numero)  
    print(numeros.sort())   
    
listadenumeros()
