# nota com media ponderada
nome = input ("Digite o nome do aluno:")
nota1 = float (input("Digite a nota da primeira prova do aluno:"))
peso1= int (input("Digite o peso da primeira prova:"))
nota2 = float (input("Digite a nota da segunda prova do aluno:"))
peso2 = int (input("Digite o peso da segunda prova:"))
nota3= float (input("Digite a nota da terceira prova:"))
peso3 = int (input("Digite o peso da terceira prova:"))
primeira_nota = (peso1*nota1)
print(f"A nota da primeira prova é {primeira_nota} e o seu peso é {peso1}")
segunda_nota = (peso2 * nota2)
print(f"A nota da segunda prova é {segunda_nota} e o seu peso é {peso2}")
terceira_nota = (peso3*nota3)
print(f"A nota da terceira prova é {terceira_nota} e o seu peso é {peso3}")
media = (primeira_nota + segunda_nota + terceira_nota)/(peso1 + peso2 + peso3)
if media >= 5:
    print (f"A nota do aluno {nome} é {media:.2f} e ele foi aprovado!")
else: 
    print(f"A nota do aluno {nome} é {media:.2f}, e ele foi reprovado")


# valor q o vendedor receb de porcentagem
nome = input("Digite o nome do vendedor(a):")
vendas = float(input("Digite o valor total das vendas desse vendedor:"))
porcentagem = int (input("Digite a porcentagem que o vendedor ganha de comissao em \nem cima das vendas:"))
comissao = (vendas * (porcentagem/100))
print(f"O vendedor(a) {nome} vai receber {comissao:.2f} de comissao")

# senha usando while 
senha = input ("Digite a senha:")

while senha != "band0628":
    print("senha incorreta tente novamente")
    senha = input ("Digite a senha:")
print ("Acesso permitido")

# while
contador = int (10) 
while contador >= 1:
    print (f"{contador}")
    contador -= 1
    
print ("Feliz ano novo")
