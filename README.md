# lista_dirigido
Exercise list in programing IFC Araquari, Teatcher Jefferson
# Bíbliotecas

import math

# Variaveis

nota1= int(input("Nota que foi tirada no exame 1:"))
nota2= int(input("Nota que foi tirada no exame 2:"))
nota3= int(input("Nota que foi tirada no exame 3:"))
nota4= int(input("Nota que foi tirada no exame 4:"))

#Calculo de média

media = float (( nota1 + nota2 + nota3 + nota4)) / (4)
print("á média é",media)

# Condicoes

if nota1 >= 8:
     print ("Aluno aprovado")

if nota2 >= 8:
     print ("Aluno aprovado")

if nota3 <= 8:
     print ("Aluno reprovado")

if nota4 <= 8:
     print ("Aluno reprovado")

if media >= 5 and media < 7:
    print("Aluno está de exame")
