import random

numero_misterioso = random.randint(1, 10)
tentativas = 0
max_tentativas = 3

print(' seja bem vindo ao jogo meu caro, voçe tem que adivinhar o número de 1 a 10.')
print(f'Você tem {max_tentativas} tentativas para acertar o número.')

while tentativas < max_tentativas:
    palpite = int(input(f" escreva um número de 1 e 10: "))
    
    if palpite == numero_misterioso:
        print("Cara voçe e muito bom!")
        break
    else:
        tentativas += 1
        if tentativas < max_tentativas:
            print(f"Vamos mais uma, voçe tem {max_tentativas - tentativas} tentativas.")
        else:
            print(f"Suas tentativas acabaram. O número correto era {numero_misterioso}.")
            print("Valeu meu bom voçe e muito bom, obrigado por jogar! ")


            FIM <333
