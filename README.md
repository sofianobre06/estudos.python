# estudos.python
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
