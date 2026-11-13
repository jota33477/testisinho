
import random

# 1. Caracteres que podem fazer parte da senha
caracteres = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"

# 2. Pedir o comprimento da senha
comprimento = int(input("Digite o comprimento da senha: "))

# 3. Criar a variável que armazenará a senha
senha = ""

# 4. Selecionar caracteres aleatórios
for i in range(comprimento):
    senha += random.choice(caracteres)

# 5. Exibir a senha
print("Sua senha gerada é:", senha)
