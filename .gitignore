# Nome do Programa

print ("Calculo de sálario")

# Função com Parametro

def calc1 (salarioLiquido):
    return salarioLiquido * 0.925

def calc2 (salarioLiquido):
    return salarioLiquido * 0.85

def calc3 (salarioLiquido):
    return salarioLiquido * 0.775

def calc4 (salarioLiquido):
    return salarioLiquido * 0.725  

def descontoINSS(salarioLiquido):
    return salarioLiquido * 0.0725

def descontoVT(salarioLiquido):
    return salarioLiquido * 0.06

def descontoVR(salarioLiquido):
    return salarioLiquido * 0.10




# Concatenando as funções

descIR1 = calc1
descIR2 = calc2
descIR3 = calc3
descIR4 = calc4
descINSS = descontoINSS
descVR = descontoVR
descVT = descontoVT


# Começo do código

salario = float(input("Digite o valor do seu sálario: "))

if salario <= 2112.00: # Condições para o calculo do sálario
    print(f"O valor do desconto do INSS é de: R$ {descINSS(salario)}")
    print(f"O valor do desconto do VR é de: R$ {descVR(salario)}")
    print(f"O valor do desconto do VT é de: R$ {descVT(salario)}")
    print("Isento de Imposto de Renda") 
    salario = salario - (descINSS(salario) + descVR(salario) + descVT(salario))
    print(f"Seu salário é R$: {salario}")

elif salario <= 2826.66:
    salario = round(descIR1(salario) , 2)
    valorDesconto1 = round(salario * 0.075 , 2)
    print(f"Foi descontado 7,5% de imposto de renda: R$ {valorDesconto1}")
    print(f"O valor do desconto do VR é de: R$ {descVR(salario)}")
    print(f"O valor do desconto do VT é de: R$ {descVT(salario)}")
    salario = salario - (descVR(salario) + descVT(salario))
    print(f"Seu salário será de R$: {salario}")

elif salario <= 3751.06:
    valorDesconto2 = round(salario * 0.15 , 2)
    print(f"Foi descontado 15% de imposto de renda: R$ {valorDesconto2}")
    print(f"O valor do desconto do VR é de: R$ {descVR(salario)}")
    print(f"O valor do desconto do VT é de: R$ {descVT(salario)}")
    salario = salario - (descVR(salario) + descVT(salario))
    print(f"Seu sálario sera de R$: {salario}")

elif salario <= 4664.68:
    valorDesconto3 = round(salario * 0.225 , 2)
    print(f"Foi descontado 22,5% de imposto de renda: R$ round({valorDesconto3, 2})")
    print(f"O valor do desconto do VR é de: R$ {descVR(salario)}")
    print(f"O valor do desconto do VT é de: R$ {descVT(salario)}")
    salario = salario - (descVR(salario) + descVT(salario))
    print (f"Seu salário será de R$: {salario}")

else:
    valorDesconto4 = round(salario * 0.275 , 2)
    print(f"Foi descontado 27,5% de imposto de renda: R$ {valorDesconto4}")
    print(f"O valor do desconto do VR é de: R$ {descVR(salario)}")
    print(f"O valor do desconto do VT é de: R$ {descVT(salario)}")
    salario = salario - (descVR(salario) + descVT(salario))
    print(f"Seu salario será de R$: {salario}")

# Codígo Finalizado
