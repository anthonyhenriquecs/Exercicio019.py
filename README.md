# Exercicio019.py
# Faça um programa que ajude ele, lendo o nome dos alunos e escrevendo na tela o nome do escolhido.

import random
a = str(input('Digite um nome: '))
b = str(input('Digite um nome: '))
c = str(input('Digite um nome: '))
d = str(input('Digite um nome: '))
lista = [a,b,c,d]
escolhido = random.choice(lista)
print('O escolhido foi: {}'.format(escolhido))
