# Deniz_Solana_Estrellaturtle
https://github.com/aledeniiz/Deniz_Solana_Estrellaturtle
import turtle
from turtle import *
turtle.speed(5)
texto = "¡Hola, esta es una estrella de 9 puntas!"
turtle.write(texto, align="left", font=("Arial", 16, "normal"))
"""while True:
    try:
        numero_de_puntos = int(input("Introduce un número entero positivo: "))

        if numero_de_puntos > 0 :
            break  
        else:
            print("Error: Ingresa un número entero positivo.")
    except ValueError:
        print("Error: Ingresa un número entero válido.")
"""
numero_de_puntos=9

angulo= 180/numero_de_puntos
for _ in range(numero_de_puntos):
    turtle.forward(150)  
    turtle.right(180-angulo)

turtle.exitonclick()
