# Calculadora

Este é um script em Python que implementa uma calculadora simples, permitindo operações de adição, subtração, multiplicação e divisão entre dois números. O usuário pode escolher a operação desejada e o programa executará a operação correspondente.

## Descrição

O script permite que o usuário escolha uma operação matemática entre dois números. Ele continua em execução até que o usuário decida encerrar o programa.

## Funcionalidades

- Somar dois números.
- Subtrair dois números.
- Multiplicar dois números.
- Dividir dois números.
- Encerrar o programa.

## Como usar

1. Certifique-se de ter o Python instalado em seu sistema.
2. Salve o script em um arquivo com a extensão `.py` (por exemplo, `calculadora.py`).
3. Abra um terminal ou prompt de comando.
4. Navegue até o diretório onde o script foi salvo.
5. Execute o script com o comando `python calculadora.py`.
6. Siga as instruções na tela para selecionar a operação desejada e insira os números.

## Exemplo de uso

```python
from multi import multiplicação, divisao, soma, subtracao

while True:
    opcao = int(input("Digite 1 para somar 2 números\nDigite 2 para multiplicar\nDigite 3 para dividir\nDigite 4 para subtrair\nDigite 5 para encerrar o programa: "))

    if opcao == 1:
        num1 = int(input("Digite o 1° número: "))
        num2 = int(input("Digite o 2° número: "))
        soma1 = soma(num1, num2)
        print(f"O resultado da soma é: {soma1}")
    elif opcao == 2:
        num1 = int(input("Digite o 1° número: "))
        num2 = int(input("Digite o 2° número: "))
        multiplicação1 = multiplicação(num1, num2)
        print(f"O resultado da multiplicação: {multiplicação1}")
    elif opcao == 3:
        num1 = int(input("Digite o 1° número: "))
        num2 = int(input("Digite o 2° número: "))
        divisao1 = divisao(num1, num2)
        print(f"O resultado da divisão: {divisao1}")
    elif opcao == 4:
        num1 = int(input("Digite o 1° número: "))
        num2 = int(input("Digite o 2° número: "))
        subtracao1 = subtracao(num1, num2)
        print(f"O resultado da subtracao: {subtracao1}")
    elif opcao == 5:
        break
