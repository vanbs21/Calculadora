# 🧮 Calculadora Genius  

Este projeto é uma calculadora simples em Python que realiza operações matemáticas básicas com dois números.  

## 🔹 Como funciona?  
1. O usuário insere dois números.  
2. Escolhe uma operação: **+**, **-**, **\*** ou **/**.  
3. A calculadora retorna o resultado da operação.  

## 🔹 Código:
```python
print("Bem-vindo à Calculadora Genius")
num1 = float(input("Insira aqui o primeiro número: "))
num2 = float(input("Insira aqui o segundo número: "))
operacao = input("Selecione uma operação: (+, -, *, /): ")

if operacao == "+":
    resultado = num1 + num2
    print("O resultado desta operação é:", resultado)
elif operacao == "-":
    resultado = num1 - num2
    print("O resultado desta operação é:", resultado)
elif operacao == "*":
    resultado = num1 * num2
    print("O resultado desta operação é:", resultado)
elif operacao == "/":
    resultado = num1 / num2
    print("O resultado desta operação é:", resultado)
else:
    print("Operação inválida!")
```

## 🎯 Funcionalidades:
- Soma (`+`)  
- Subtração (`-`)  
- Multiplicação (`*`)  
- Divisão (`/`)  

---

Sinta-se à vontade para aprimorar e adicionar mais funcionalidades! 🚀  
