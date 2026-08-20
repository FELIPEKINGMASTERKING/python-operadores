# python-operadores

# 🚀 Guia Completo de Operadores em Python

Este repositório contém um resumo prático e focado sobre os principais tipos de operadores da linguagem Python. O objetivo é servir como uma colmeia de consulta rápida para o dia a dia e revisões de sintaxe.

---

## 📌 Resumo Prático dos Operadores

### 1. Operadores Aritméticos
Utilizados para a execução de cálculos matemáticos tradicionais.
* `+` (Soma)
* `-` (Subtração)
* `*` (Multiplicação)
* `/` (Divisão)
* `//` (Divisão Inteira) — *Descarta as casas decimais*
* `%` (Módulo) — *Retorna o resto de uma divisão*
* `**` (Exponenciação) — *Potenciação*

### 2. Operadores de Comparação
Servem para avaliar condições. O resultado retornado é sempre um valor Booleano (`True` ou `False`).
* `==` (Igual a)
* `!=` (Diferente de)
* `>` (Maior que)
* `<` (Menor que)
* `>=` (Maior ou igual a)
* `<=` (Menor ou igual a)

### 3. Operadores de Atribuição
Servem para definir ou modificar o valor armazenado em uma variável de forma direta ou compacta.
* `=` (Atribuição simples)
* `+=` (Adição e atribuição) — *Ex: `x += 5` é o mesmo que `x = x + 5`*
* `-=` (Subtração e atribuição)
* `*=` (Multiplicação e atribuição)
* `/=` (Divisão e atribuição)

### 4. Operadores Lógicos
Utilizados para construir lógica condicional composta, combinando expressões booleanas.
* `and` (Retorna `True` apenas se **todas** as condições forem verdadeiras)
* `or` (Retorna `True` se **pelo menos uma** das condições for verdadeira)
* `not` (Inverte o estado lógico: transforma `True` em `False` e vice-versa)

### 5. Operadores de Identidade
Servem para verificar se duas variáveis apontam exatamente para o **mesmo objeto na memória** do computador (não apenas se possuem valores iguais).
* `is` (É o mesmo objeto)
* `is not` (Não é o mesmo objeto)

### 6. Operadores de Associação
Utilizados para verificar a presença ou ausência de um elemento dentro de uma sequência (como listas, strings, tuplas ou dicionários).
* `in` (Está contido em)
* `not in` (Não está contido em)

---

## 💻 Como Executar o Script de Testes

1. Clone este repositório:
   ```bash
   git clone https://github.com
   ```
2. Navegue até a pasta:
   ```bash
   cd NOME_DO_REPOSITORIO
   ```
3. Execute o arquivo do script:
   ```bash
   python operadores.py
   ```

# ==============================================================================
# GUIA COMPLETO DE OPERADORES EM PYTHON
# ==============================================================================
# Este repositório serve como um guia prático e rápido sobre os principais
# tipos de operadores da linguagem Python, cobrindo a sintaxe e exemplos de uso.
# ==============================================================================

print("--- 1. OPERADORES ARITMÉTICOS ---")
a, b = 10, 3
print(f"Soma (10 + 3): {a + b}")
print(f"Subtração (10 - 3): {a - b}")
print(f"Multiplicação (10 * 3): {a * b}")
print(f"Divisão (10 / 3): {a / b}")
print(f"Divisão Inteira (10 // 3): {a // b}")  # Descarta as casas decimais
print(f"Módulo / Resto (10 % 3): {a % b}")    # Resto da divisão estruturada
print(f"Exponenciação (10 ** 3): {a ** b}")  # Potência
print("-" * 40)


print("\n--- 2. OPERADORES DE COMPARAÇÃO ---")
# Sempre retornam um valor Booleano: True ou False
x, y = 5, 8
print(f"Igual a (5 == 8): {x == y}")
print(f"Diferente de (5 != 8): {x != y}")
print(f"Maior que (5 > 8): {x > y}")
print(f"Menor que (5 < 8): {x < y}")
print(f"Maior ou igual (5 >= 5): {5 >= 5}")
print(f"Menor ou igual (5 <= 8): {x <= y}")
print("-" * 40)


print("\n--- 3. OPERADORES DE ATRIBUIÇÃO ---")
saldo = 500  # Atribuição simples (=)
print(f"Saldo inicial: {saldo}")

saldo += 300  # Mesmo que: saldo = saldo + 300
print(f"Após saldo += 300: {saldo}")

saldo -= 100  # Mesmo que: saldo = saldo - 100
print(f"Após saldo -= 100: {saldo}")

saldo *= 2    # Mesmo que: saldo = saldo * 2
print(f"Após saldo *= 2: {saldo}")

saldo /= 4    # Mesmo que: saldo = saldo / 4
print(f"Após saldo /= 4: {saldo}")
print("-" * 40)


print("\n--- 4. OPERADORES LÓGICOS ---")
tem_dinheiro = True
dia_sol = False

# AND: Só é True se AMBOS forem True
print(f"Vou à praia? (tem_dinheiro AND dia_sol): {tem_dinheiro and dia_sol}")

# OR: É True se pelo menos UM for True
print(f"Vou sair de casa? (tem_dinheiro OR dia_sol): {tem_dinheiro or dia_sol}")

# NOT: Inverte o estado lógico
print(f"Inversão do clima (NOT dia_sol): {not dia_sol}")
print("-" * 40)


print("\n--- 5. OPERADORES DE IDENTIDADE ---")
# Verificam se os objetos apontam para o mesmo endereço de memória
lista_original = [1, 2, 3]
lista_copia = lista_original
lista_identica = [1, 2, 3]

print(f"lista_original is lista_copia: {lista_original is lista_copia}")       # True (mesmo objeto)
print(f"lista_original is lista_identica: {lista_original is lista_identica}") # False (valores iguais, mas objetos distintos)
print(f"lista_original == lista_identica: {lista_original == lista_identica}") # True (o conteúdo é idêntico)
print(f"lista_original is not lista_identica: {lista_original is not lista_identica}")
print("-" * 40)


print("\n--- 6. OPERADORES DE ASSOCIAÇÃO ---")
# Verificam se um elemento está presente dentro de uma sequência (string, lista, etc.)
tecnologias = ["Python", "Git", "GitHub", "Docker"]
texto = "Estudando programação na trilha de sintaxe"

print(f"'Python' está na lista? {'Python' in tecnologias}")
print(f"'Java' não está na lista? {'Java' not in tecnologias}")
print(f"'trilha' está no texto descritivo? {'trilha' in texto}")
print("-" * 40)
