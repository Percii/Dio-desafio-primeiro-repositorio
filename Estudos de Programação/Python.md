# Python :desktop_computer:

### Primeiro contato com uma linguagem de programação.

O python foi meu primeiro contato "mais avançado" com uma linguagem de programação, o principal motivo foi por causa da faculdade, pois foi a linguagem escolhida para fosse iniciado o aprendizado em programação.



#### Primero código feito:

sobrenome = input("Qual seu ultimo sobrenome? ")

print("Você faz parte da familia", sobrenome)



#### Último código feito:



\#Interação

n1 = int(input ("Digite um número: "))

n2 = int(input ("Digite outro número: "))



print("Digite 1 - - para Média\n")

print("Digite 2 - - para Diferença maior-menor\n")

print("Digite 3 - - para Produto\n")

print("Digite 4 - - para Divisão\n")



operacao = int (input ("Digite a operação desejada: "))



\#Operações



if operacao == 1:

  media = (n1 + n2) / 2

  print(f"Média = {media}\n")



elif operacao == 2:

  dif = n1 - n2

  print(f"Diferença = {dif}\n")



elif operacao == 3:

  prod = n1 * n2

  print(f"Produto = {prod}\n")



elif operacao == 4:

  div = n1 / n2

  print(f"Divisão = {div}\n")

  

else:

  print("Opção inválida.")