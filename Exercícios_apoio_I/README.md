# 📝 Exercícios d.e apoio semanais.

Os Seguintes exercícios s.ão de Algoritmos Programacao de Computadores I do primeiro semestre de 2024. 

## Indíce

- [Semana 1 ✅.](#semana-1-)
    - [Exercício 1..](#exerc_01)
    - [Exercício 2..](#exerc_02)
    - [Exercício 3..](#exerc_03)
    - [Exercício 4..](#exerc_04)
- [Semana 2 ✅.](#semana-2-)
    - [Exercício 05.](#exerc_05)
    - [Exercício 06.](#exerc_06)
    - [Exercício 07.](#exerc_07)
    - [Exercício 08.](#exerc_08)
- [Semana 3 ✅.](#semana-3-)
    - [Exercício 09.](#exerc_09)
    - [Exercício 10.](#exerc_10)
    - [Exercício 11.](#exerc_11)
    - [Exercício 12.](#exerc_12)
    - [Exercício 13.](#exerc_13)
- [Semana 4 ✅.](#semana-4-)
    - [Exercício 14.](#exerc_14)
    - [Exercício 15.](#exerc_15)
    - [Exercício 16.](#exerc_16)
    - [Exercício 17.](#exerc_17)
    - [Exercício 18.](#exerc_18)
- [Semana 5 ✅.](#semana-5-)
    - [Exercício 19.](#exerc_19)
    - [Exercício 20.](#exerc_20)
    - [Exercício 21.](#exerc_21)
    - [Exercício 22.](#exerc_22)
    - [Exercício 23.](#exerc_23)
    - [Exercício 24.](#exerc_24)
    - [Exercício 25.](#exerc_25)
    - [Exercício 26.](#exerc_26)
- [Semana 6 ✅.](#semana-6-)
    - [Exercício 27.](#exerc_27)
    - [Exercício 28.](#exerc_28)
    - [Exercício 29.](#exerc_29)
- [Semana 7 ✅.](#semana-7-)
    - [Exercício 30.](#exerc_30)
    - [Exercício 31.](#exerc_31)
    - [Exercício 32.](#exerc_32)

## Semana 1 ✅


### **Exerc_01**:
Ler uma temperatura em graus Celsius e apresentá-la convertida em graus Fahrenheit.


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

exerc_01(0) # Saída => Em Farenheight é 32 °F
exerc_01(1) # Saída => Em Farenheight é 33,8 °F
exerc_01(10) # Saída => Em Farenheight é 50 °F
exerc_01(100) # Saída => Em Farenheight é 212 °F.
```


---
### **Exerc_02**:
Organizador de listas.


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
    return sorted(*args

exerc_2(['taco', 'bola', 'celeiro', 'cesta', 'peteca']) # Output => ['bola', 'celeiro', 'cesta', 'peteca', 'taco']
```

---
### **Exerc_03**:
Calculadora de média escolar.


```python
"""
Realizar a leitura dos valores de quatro notas escolares bimestrais de um aluno
representadas pelas variáveis N1, N2, N3 e N4. Calcular a média aritmética
(variável MD) desse aluno e apresentar a mensagem 'Aluno Aprovado com média' se a
média obtida for maior ou igual a 5; caso contrário, apresentar a mensagem 'Aluno
Reprovado com média'. Informar também, após a apresentação das mensagens, o valor
da média obtida pelo aluno.
"""
def exerc_03(nota_minima, *args):
    "Calculadora de média escolar."
    MD = (sum(args)) / len(args)
    if (MD >= nota_minima):
        print("Aluno Aprovado com média", MD)
    else:
        print("Aluno Reprovado com média", MD

exerc_03(6, 1, 1, 1, 1) # Output => Aluno Reprovado com média .0
exerc_03(6, 5, 5, 5, 5) # Output => Aluno Reprovado com média .0
exerc_03(6, 10, 10, 10, 10) # Output => Aluno Reprovado com média 1.0
exerc_03(6, 2, 7, 6, 4) # Output => Aluno Reprovado com média .75
exerc_03(6, 6, 6, 6, 6) # Output => Aluno Aprovado com média 6.0
```
---
### **Exerc_04**:
Soma dos 100 primeiros números naturais.


```python
# Desenvolver os diagramas de blocos e as codificações em português estruturado usando
# laço incondicional (para) do seguinte problema: Construir um programa que apresente a
# soma dos cem primeiros números naturais (1 + 2 + 3 +...+ 98 + 99 + 100).
def exerc_04():
    "Soma dos 100 primeiros números naturais."
    conta = 0
    for i in range(101):
        conta = conta + i
    print("Exercício 4 .é", conta

exerc_04() # Output => Exercício 4 .é 5050
```
---

## Semana 2 ✅

### **Exerc_05**:
Diferentes expressões matemáticas.


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

# b
def exerc_05_b(*args):
    print('(float) A idade média deles é', sum(args) / len(args))
    print('(int) A idade média deles é', sum(args) // len(ars)) 
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
### **Exerc_06**:
Função comparativa.


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


# A soma de 2 e 2 é menor qu 4. 
exerc_06(2+2, 4, "<")  
# Output => False

# O valor de 7 // 3 é igual a 1  1. 
exerc_06(7//3, 1+1, "==") 
# Output => True

# A soma de 3 ao quadrado e 4 ao quadrado é igual  25. 
exerc_06((3**2)+(4**2), 25, "==") 
# Output => True

# A soma de 2, 4 e 6 é maior qu 12.
exerc_06(2+4+6, 12, ">") 
# Output => False

# 1387 é divisível po 19.
exerc_06(1387%19, 0, "==") 
# Output => True

# 31  par.
exerc_06(31%2, 0, "==") 
# Output => False

# O preço mais baixo dentre R$ 34,99, R$ 29,95 e R$ 31,50 é menor que R$ 3,00.
exerc_06(min([34.99, 29.95, 31.50]), 30, "<") 
# Output => True

```
---
### **Exerc_07**:
Manipulação de strings.


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
### **Exerc_08**:
Localizado caracteres em uma string pelo seu índice.


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

## Semana 3 ✅

### **Exerc_09**:
Utilização de índices em listas.


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
### **Exerc_10**:
Utilização de métodos de listas.


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
### **Exerc_11**:
Ordem de importância de execução de expressões matemáticas.


```python
#Em que ordem os operadores nas expressões a seguir são avaliados?

# 2 + 3 == 4 or 5 >= 5
print("Ordem: +, ==, >=, or") 

# list[1] * -3 < -10 == 0
print("Ordem: *, <, ==")

# (list[1] * -3 < -10) in [0, True]
print("Ordem: *, <, in")

# 2 * 3**2
print("Ordem: **, *")

# 4 / 2 in [1, 2, 3]
print("Ordem: /, in")
```
---
### **Exerc_12**:
Retornando tipo do dado.


```python
# Qual é o tipo do objeto ao qual essas expressões são avaliadas?

print(type(False + False)) 
    # Output => int
print(type(2 * 3**2.0)) 
    # Output => float
print(type(4 // 2 + 4 % 20)) 
    # Output => int
print(type(2 + 3 == 4 or 5 >= 5)) 
    # Output => Boolean
```
---
### **Exerc_13**:
Cálculos geométricos com visualização gráfica.


```python
import math
import turtle

# Escreva expressões Python correspondentes ao seguinte:
# O comprimento da hipotenusa em um triângulo retângulo cujos dois outros lados
# têm comprimentos a e b

a = 4
b = 3
hip = math.sqrt(a**2 + b**2)
print(hip) 
    # Output => 5.0

# O valor da expressão que avalia se o comprimento da hipotenusa acima é 5
Resultado = hip > 5
print(Resultado) 
    # Output => False

# A área de um disco com raio a
area = (math.pi * a**2)
print(area) 
    # Output => 50.26548245743669
print(round(area,2)) 
    # Output => 50.27

# O valor da expressão Booleana que verifica se um ponto com coordenadas x e y está
# dentro de um círculo com centro ( a, b ) e raio r
x = 50
y = 49
print(f"x, y = {x, y}") 
    # Output => x, y = (50, 49)
a = 0
b = 0
print(f"a, b = {a, b}") 
    # Output => a, b = (0, 0)
r = 50

resultado = ((a - x)**2 + (b - y)**2 > r**2) 
print("(x,y) está fora círculo? Resposta:", resultado) 
    # Output => (x,y) está fora círculo? Resposta: True

# Visualmente
screen = turtle.Screen()
screen.setup(r*4, r*4)
circle_pen = turtle.Turtle(visible=False)
circle_pen.up()
circle_pen.setpos(0, -r)
circle_pen.down()
circle_pen.circle(radius=r)
xy_pos = turtle.Turtle(shape="circle")
xy_pos.color("#000", "#f00")
xy_pos.shapesize(0.2,0.2,0.2)
xy_pos.up()
xy_pos.setpos(x, y)
screen.mainloop()
```
---

## Semana 4 ✅

### **Exerc_14**:
Média entre dois números.


```python
# Defina, a função média(), que aceita dois
# números como entrada e retorna a média dos números. Um exemplo de uso é:
# >>> average(2, 3.5)

def average(a=int, b=int):
    "Função que retorna média entre dois valores a e b"
    try:
        return (a + b) / 2
    except:
        raise ValueError("Valor não inteiro")
    finally:
        print((a + b) / 2)

average(10,10) 
    # Output => 10.0
average(10, 4) 
    # Output => 7.0
average(4, 5) 
    # Output => 4.5
average(8, 10) 
    # Output => 9.0
```

---
### **Exerc_15**:
Perímetro de um determinado número.


```python
import math
# Implemente a função perímetro(), que aceita, como entrada, o raio de um círculo
# (um número não negativo) e retorna o perímetro do círculo. Você deverá escrever sua
# implementação em um módulo chamado perímetro.py. Um exemplo de uso é:

def perimetro(raio=int):
    if raio >= 0:
        return 2 * math.pi * raio
    else:
        raise ValueError("Valor menor que zero, por favor insira um valor diferente")

print(perimetro(0)) 
    # Output => 0.0
print(perimetro(1)) 
    # Output => 6.283185307179586
print(perimetro(2)) 
    # Output => 12.566370614359172
```
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
