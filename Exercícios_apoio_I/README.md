# 📝 Exercícios de apoio semanais.

Os Seguintes exercícios são de Algoritmos Programacao de Computadores I do primeiro semestre de 2024. 

- [Semana 1](#semana-1-)
- [Semana 2](#semana-2-)
- [Semana 3](#semana-3-)
- [Semana 4](#semana-4-)
- [Semana 5](#semana-5-)
- [Semana 6](#semana-6-)
- [Semana 7](#semana-7-)

# Semana 1 ✅


- **Exerc_01**: Ler uma temperatura em graus Celsius e apresentá-la convertida em graus Fahrenheit.

```python
    """
    Ler uma temperatura em graus Celsius e apresentá-la convertida
    em graus Fahrenheit. A fórmula de conversão é F ← C * 9 / 5 + 32,
    sendo F a temperatura em Fahrenheit e C a temperatura em Celsius.
    """

    def exerc_01(temperaturaC):
        " Ler uma temperatura em graus Celsius e apresentá-la convertida em graus Fahrenheit."
        print("Em Farenheight é",(temperaturaC * 9 / 5) + 32, "°F.")
        return temperaturaC

    exerc_01(0) # Saída => Em Farenheight é 32 °F.
    exerc_01(1) # Saída => Em Farenheight é 33,8 °F.
    exerc_01(10) # Saída => Em Farenheight é 50 °F.
    exerc_01(100) # Saída => Em Farenheight é 212 °F.
```


---
- **Exerc_02**: Organizador de listas.
```python
"""
Primeiro, execute a atribuição palavras =
['taco', 'bola', 'celeiro', 'cesta', 'peteca']
Agora, escreva duas expressões Python que são avaliadas, respectivamente, como a
primeira e a última palavras em palavras, na ordem do dicionário.
"""

def exerc_2(*args):
    "Organizador de listas."
    print(sorted(*args))
    return sorted(*args)

exerc_2(['taco', 'bola', 'celeiro', 'cesta', 'peteca']) # Output => ['bola', 'celeiro', 'cesta', 'peteca', 'taco']
```

---
- **Exerc_03**: Calculadora de média escolar.
```python
"""
Realizar a leitura dos valores de quatro notas escolares bimestrais de um aluno
representadas pelas variáveis N1, N2, N3 e N4. Calcular a média aritmética
(variável MD) desse aluno e apresentar a mensagem “Aluno Aprovado com média” se a
média obtida for maior ou igual a 5; caso contrário, apresentar a mensagem “Aluno
Reprovado com média”. Informar também, após a apresentação das mensagens, o valor
da média obtida pelo aluno.
"""
def exerc_03(nota_minima, *args):
    "Calculadora de média escolar."
    MD = (sum(args)) / len(args)
    if (MD >= nota_minima):
        print("Aluno Aprovado com média", MD)
    else:
        print("Aluno Reprovado com média", MD)

exerc_03(6, 1, 1, 1, 1) # Output => Aluno Reprovado com média 1.0
exerc_03(6, 5, 5, 5, 5) # Output => Aluno Reprovado com média 5.0
exerc_03(6, 10, 10, 10, 10) # Output => Aluno Reprovado com média 10.0
exerc_03(6, 2, 7, 6, 4) # Output => Aluno Reprovado com média 4.75
exerc_03(6, 6, 6, 6, 6) # Output => Aluno Aprovado com média 6.0
```
---
- **Exerc_04**: Soma dos 100 primeiros números naturais.
```python
# Desenvolver os diagramas de blocos e as codificações em português estruturado usando
# laço incondicional (para) do seguinte problema: Construir um programa que apresente a
# soma dos cem primeiros números naturais (1 + 2 + 3 +...+ 98 + 99 + 100).

def exerc_04():
    "Soma dos 100 primeiros números naturais."
    conta = 0
    for i in range(101):
        conta = conta + i
    print("Exercício 4 é", conta)

exerc_04() # Output => Exercício 4 é 5050
```
---

## Semana 2 ✅

- **Exerc_05**: Diferentes expressões matemáticas.
```python
"""
Escreva expressões algébricas Python correspondentes aos seguintes comandos:  
a) A soma dos 5 primeiros inteiros positivos.
b) A idade média de Sara (idade 23), Mark (idade 19) e Fátima (idade 31).
c) O número de vezes que 73 cabe em 403.
d) O resto de quando 403 é dividido por 73.
e) 2 à 10ª potência.
f) O valor absoluto da distância entre a altura de Sara (54 polegadas) e a altura de Mark (57 polegadas).
g) O menor preço entre os seguintes preços: R$ 34,99, R$ 29,95 e R$ 31,50.
"""

# a)
print("A soma dos 5 primeiros inteiros positivos é",sum([1,2,3,4,5])) 
    # Output => 15

# b)
def exerc_05_b(*args):
    print('(float) A idade média deles é', sum(args) / len(args))
    print('(int) A idade média deles é', sum(args) // len(args)) 
exerc_05_b(23,19,31)
    # Output => 24.333333333333332
    # Output => 24

# c)
print("(float) O número de vezes que 73 cabe em 403", 403 / 73)
print("(int) O número de vezes que 73 cabe em 403", 403 // 73) 
    # Output => 5.52054794520548
    # Output => 5

# d)
print("O resto de quando 403 é dividido por 73.", 403 % 73) 
    # Output => 38


# e)
print("2 à 10ª potência.", 2**10) 
    # Output => 1024

# f)
print("O valor absoluto da distância entre as alturas",abs(54 - 57)) 
    # Output => 3

# g)
print("O menor preço entre os preços é", min([34.99, 29.95, 31.50]))
    # Output => 29.95
```
---
- **Exerc_06**: Função comparativa.
```python
"""
Traduza os comandos a seguir para expressões Booleanas em Python e avalie-as:
A soma de 2 e 2 é menor que 4.
O valor de 7 // 3 é igual a 1 + 1.
A soma de 3 ao quadrado e 4 ao quadrado é igual a 25.
A soma de 2, 4 e 6 é maior que 12.
1387 é divisível por 19.
31 é par. (Dica: o que o resto lhe diz quando você divide por 2?)
O preço mais baixo dentre R$ 34,99, R$ 29,95 e R$ 31,50 é menor que R$ 30,00.*
"""

def exerc_06(a, b, c):
    "Função comparativa"
    match c:
        case ">=":
            print(a >= b)
            return a >= b
        case "<=":
            print(a <= b)
            return a <= b
        case ">":
            print(a > b)
            return a > b
        case "<":
            print(a < b)
            return a < b
        case "==":
            print(a == b)
            return a == b
        case "!=":
            print(a != b)
            return a != b


# A soma de 2 e 2 é menor que 4. 
exerc_06(2+2, 4, "<")  
# Output => False

# O valor de 7 // 3 é igual a 1 + 1. 
exerc_06(7//3, 1+1, "==") 
# Output => True

# A soma de 3 ao quadrado e 4 ao quadrado é igual a 25. 
exerc_06((3**2)+(4**2), 25, "==") 
# Output => True

# A soma de 2, 4 e 6 é maior que 12.
exerc_06(2+4+6, 12, ">") 
# Output => False

# 1387 é divisível por 19.
exerc_06(1387%19, 0, "==") 
# Output => True

# 31 é par.
exerc_06(31%2, 0, "==") 
# Output => False

# O preço mais baixo dentre R$ 34,99, R$ 29,95 e R$ 31,50 é menor que R$ 30,00.
exerc_06(min([34.99, 29.95, 31.50]), 30, "<") 
# Output => True

```
---
- **Exerc_07**: Manipulação de strings.
```python
"Manipulação de strings."
# Comece executando as instruções de atribuição:

s1 = 'ant'
s2 = 'bat'
s3 = 'cod'
            
#Escreva expressões Python usando s1, s2 e s3 e os operadores + e * a fim de avaliar para:   
print(s1, s2, s3) 
# Output => 'ant bat cod'

print((s1 + " ") *10) 
# Output =>  ant ant ant ant ant ant ant ant ant ant'

print(s1, (s2 + " ")*2 + (s3+" ")*3)
# Output => 'ant bat bat cod cod cod'

print((s1 + " " + s2 + " ")*8) 
# Output => 'ant bat ant bat ant bat ant bat ant bat ant bat ant bat'

print((s2*2+s3 + " ")*5) 
# Output => 'batbatcod batbatcod batbatcod batbatcod batbatcod'
```
---
- **Exerc_08**: Localizado caracteres em uma string pelo seu índice.
```python
"Localizado caracteres em uma string pelo seu índice."
# Comece executando a atribuição:

s = '0123456789'

#Agora, escreva expressões usando a string s e o operador de indexação que é avaliado como:  

print(s[0]) 
    #Output => 0
print(s[1]) 
    #Output => 1
print(s[6]) 
    #Output => 6
print(s[8]) 
    #Output => 8
print(s[9]) 
    #Output => 9
```
---

## semana 3 ✅

- **Exerc_09**: Utilização de índices em listas.
```python
"Pegando de índices em listas."
# Primeiro, execute a atribuição
palavras = ['taco', 'bola', 'celeiro', 'cesta', 'peteca']

# Agora, escreva duas expressões Python que são avaliadas, respectivamente,
# como a primeiro e a última palavras em palavras, na ordem do dicionário.

palavras.sort() 
    # Output => ['bola', 'celeiro', 'cesta', 'peteca', 'taco']
print(f"{palavras[0]}, {palavras[-1]}") 
    # Output => bola,taco

```
---
- **Exerc_10**: Utilização de métodos de listas.
```python
# Dada a lista de notas de trabalho de casa dos alunos

notas = [9, 7, 7, 10, 3, 9, 6, 6, 2]

# Escreva: 
print("Uma expressão que avalia para o número de 7 notas.")
print(notas.count(7)) 
    # Output => 2

print("Uma instrução que muda a última nota para 4.")
notas[-1] = 4
print(notas) 
    # Output => [9, 7, 7, 10, 3, 9, 6, 6, 4]

print("Uma expressão que avalia para a nota mais alta.")
print(max(notas)) 
    # Output => [9, 7, 7, 10, 3, 9, 6, 6, 4]

print("Uma instrução que classifica as notas da lista.")
notas.sort()
print(notas) 
    # Output => [9, 7, 7, 10, 3, 9, 6, 6, 4]

print("Uma expressão que avalia para a média das notas.")
print(sum(notas) / len(notas)) 
print(sum(notas) // len(notas))
    # Output => [9, 7, 7, 10, 3, 9, 6, 6, 4]
    # Output => [9, 7, 7, 10, 3, 9, 6, 6, 4]

```
---
- **Exerc_11**: Ordem de importância de execução de expressões matemáticas.
```python```
---
- **Exerc_12**: Retornando tipo do dado.
```python```
---
- **Exerc_13**: Cálculos geométricos com visualização gráfica.
```python```
---

## Semana 4 ✅

- **Exerc_14**: Média entre dois números.
```python```
---
- **Exerc_15**: Perímetro de um determinado número.
```python```
---
- **Exerc_16**: Filtra Números negativos em uma lista.
```python```
---
- **Exerc_17**: Usa função Help em exercícios da semana 4.
```python```
---
- **Exerc_18**: Manipulação de items em uma lista.
```python```
---

## Semana 5 ✅

- **Exerc_19**: Uso de condicionais para verificação se há ou não direito a pensão.
```python```
---
- **Exerc_20**: Verificação de Items em uma lista com if.
```python```
---
- **Exerc_21**: Verificação usando operadores lógicos.
```python```
---
- **Exerc_22**: Verificação de Items em um dict com if.
```python```
---
- **Exerc_23**: Verificação de ano Bissexto.
```python```
---
- **Exerc_24**: Sistema básico de verificação de bilhetes de loteria.
```python```
---
- **Exerc_25**: Sistema básico de Login.
```python```
---
- **Exerc_26**: Sistema básico de verificação taxa no IMC.
```python```
---

## Semana 6 ✅

- **Exerc_27**: Uso de Seleção de elementos em uma lista.
```python```
---
- **Exerc_28**: Exibição de sequências usando range 1.
```python```
---
- **Exerc_29**: Exibição de sequências usando range 2.
```python```
---

## Semana 7 ✅

- **Exerc_27**: Mostrando com indices de strings.
```python```
---
- **Exerc_28**: Métodos em String.
```python```
---
- **Exerc_29**: Soma entre duas listas Bidimensionais.
```python```
---
