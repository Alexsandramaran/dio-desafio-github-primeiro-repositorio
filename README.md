# Desafio de Projeto sobre Git/GitHub da DIO
Repositório criado para o Desafio de Projeto sobre Git/GitHub
## Links Úteis
[Sintaxe Basica Markdown](https://www.markdownguide.org/basic-syntax/)


# Programação em PYTHON - Soma dos dígitos

### Código em PYTHON
import math

num = int(input("Digite um número a ter seus algarismos somados:"))


x = num
y = num
soma = 0

while y != 0:
    x = y % 10
    y = y // 10
    soma = soma + x

print("A soma dos algarismo de",num,"é:",(soma))
