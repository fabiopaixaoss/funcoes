# funcoes
# Funções

#Função com Retorno
def somar_quadrados(x1, x2):
    quad1=x1*x1
    quad2=x2*x2
    vFinal=quad1+quad2
    return vFinal
#Início do Programa
v1=float(input("Digite o 1° número: "))
v2=float(input("Digite o 2° número: "))
#Pode-se simplesmente imprimir o resultado...:
print(somar_quadrados(v1, v2))
#...como também guardá-lo para futuro processamento:
result=somar_quadrados(v1, v2)
#e com esse valor (result) continuar o processamento.
