# 📝 Exercícios d.e apoio semanais.

Os Seguintes exercícios s.ão de Algoritmos Programacao de Computadores I do primeiro semestre de 2024. 

## Indíce

- [Semana 1 ✅.](#semana-1-)
    - [Exercício 1.](#exerc_01)
    - [Exercício 2.](#exerc_02)
    - [Exercício 3.](#exerc_03)
    - [Exercício 4.](#exerc_04)
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
### **Exerc_16**:
Filtra Números negativos em uma lista.


```python
# Escreva a função negativos(), que aceita uma lista como entrada e exibe, um por
# linha, os valores negativos na lista. A função não deverá retornar nada.
# >>> negatives([4, 0, −1, −3, 6, −9])

def negativos(args):
    "Retorna os elementos negativos em uma lista passada como paramêtro"
    filtered = list(filter(lambda x: x < 0,args))
    print(filtered)
    return filtered

negativos([4, 0, -1, -3, 6, -9])
    # Output => [-1, -3, -9]
```
---
### **Exerc_17**:
Usa função Help em exercícios d.a semana 4.


```python
"""
Help on function média in module __main__:

média(a=<class 'int'>, b=<class 'int'>)
    Função que retorna média entre dois valores a e b

Help on function negativos in module __main__:

negativos(args)
    Retorna os elementos negativos em uma lista passada como paramêtro
"""
import exerc_14
import exerc_16

help(exerc_14.average)
help(exerc_16.negativos)
```
---
### **Exerc_18**:
Manipulação de items em uma lista.


```python
# Suponha que uma lista não vazia time foi atribuída. Escreva uma instrução Python ou
# instruções que mapeiam o primeiro e último valor da lista. Assim, se a lista
# original for:

# >>> time = ["Ava", "Eleanor", "Clare", "Sarah"]
  
# então a lista resultante deverá ser:
  
# >>> time
# ["Sarah", "Eleanor", "Clare", "Ava"]

def exerc_18(args):
    if len(args) > 1:
        firstItem = args[0]
        lastItem = args[-1]
        args[0] = lastItem
        args[-1] = firstItem
        return args
    else:
        raise IndexError("Lista menor que 1.")

print(exerc_18([0,2,3,4,5,6,7]))
    # Output => [7, 2, 3, 4, 5, 6, 0]

print(exerc_18(["Sarah", "Eleanor", "Clare", "Ava"]))
    # Output => ['Ava', 'Eleanor', 'Clare', 'Sarah']

print(exerc_18([True,False,True,False]))
    # Output => [False, False, True, True]

print(exerc_18([True,False]))
    # Output => [False, True]

print(exerc_18([True]))
    # Output => IndexError: Lista menor que 1.
```
---

## Semana 5 ✅

### **Exerc_19**:
Uso de condicionais para verificação se há ou não direito a pensão.


```python
# Traduza estas instruções condicionais em instruções if do Python:  
# Se idade é maior que 62, exiba 'Você pode obter benefícios de pensão'.

def exerc_19(idade=int):
    if (idade > 62):
        print("Você pode obter benefícios de pensão")
        
exerc_19(10)
exerc_19(20)
exerc_19(30)
exerc_19(40)
exerc_19(50)
exerc_19(60)
exerc_19(63)
    # Output => Você pode obter benefícios de pensão
```
---
### **Exerc_20**:
Verificação de Items em uma lista com if.


```python
# Se o nome está na lista ['Musial', 'Aaraon', 'Williams', 'Gehrig', 'Ruth'],
# exiba 'Um dos 5 maiores jogadores de beisebol de todos os tempos!'.

def exerc_20(nome=str):
    if (nome in ['Musial', 'Aaraon', 'Williams', 'Gehrig', 'Ruth']):
        print('Um dos 5 maiores jogadores de beisebol de todos os tempos!')

exerc_20("Gabriel")
exerc_20("Rafael")
exerc_20("Simone")
exerc_20("Felipe")
exerc_20("Williams")
    # Output => Um dos 5 maiores jogadores de beisebol de todos os tempos!
```
---
### **Exerc_21**:
Verificação usando operadores lógicos.


```python
# Se golpes é maior que 10 e defesas é 0, exiba 'Você está morto…'.

def Exercicio32c(golpes=int, defesas=int):
    if (golpes > 10 and defesas == 0):
        print("Você está morto")

Exercicio32c(9,1)
Exercicio32c(9,0)
Exercicio32c(10,1)
Exercicio32c(11,0)
```
---
### **Exerc_22**:
Verificação de Items em um dict com if.


```python
# Se pelo menos uma das variáveis booleanas norte, sul, leste e oeste for True,
# exiba 'Posso escapar.'.

def Exercicio32d(**pontos_cardeais):
    if True in pontos_cardeais.values():
        print("Posso escapar.")
        
Exercicio32d(norte=True,sul=True,leste=True,oeste=True)

```
---
### **Exerc_23**:
Verificação de ano Bissexto.


```python
"""
Traduza estas declarações em instruções if/else do Python:

Se ano é divisível por 4, exiba 'Pode ser um ano bissexto.'; caso contrário,
exiba 'Definitivamente não é um ano bissexto.'
"""
def exerc_23(ano=int):
    if (ano % 4 == 0):
        print("Pode ser um ano bissexto.")
    else:
        print("Definitivamente não é um ano bissexto.")

exerc_23(2013)
    # Output => Definitivamente não é um ano bissexto.
exerc_23(1990)
    # Output => Definitivamente não é um ano bissexto.
exerc_23(1994)
    # Output => Definitivamente não é um ano bissexto.
exerc_23(2024)
    # Output => Pode ser um ano bissexto.
exerc_23(2004)
    # Output => Pode ser um ano bissexto.
exerc_23(2010)
    # Output => Definitivamente não é um ano bissexto.
exerc_23(2008)
    # Output => Pode ser um ano bissexto.
exerc_23(2003)
    # Output => Definitivamente não é um ano bissexto.

```
---
### **Exerc_24**:
Sistema básico de verificação de bilhetes de loteria.


```python
import random
"""
Se a lista bilhete é igual à lista loteria, exiba 'Você ganhou!'; se não, exiba
'Melhor sorte da próxima vez…'.
"""

def Exercicio33b(lista=set):
    lista_loteria = random.sample(range(1, 60), 6)
    if (sorted(lista) == sorted(lista_loteria)):
        print('Você ganhou!')
        return True
    else:
        print('Melhor Sorte da Próxima vez')
        return False

Exercicio33b([2,10,7,8,9,14])
```
---
### **Exerc_25**:
Sistema básico de Login.


```python
"""
Implemente um programa que comece pedindo ao usuário para digitar uma identificação
de login (ou seja, uma string). O programa, então, verifica se a identificação
informada pelo usuário está na lista ['joe', 'sue', ' hani', 'sophie' ] de usuários
válidos. Dependendo do resultado, uma mensagem apropriada deverá ser impressa. Não
importando o resultado, sua função deverá exibir 'Fim.' antes de terminar.
Aqui está um exemplo de um login bem-sucedido:
  
>>>
Login: joe
Você entrou!
Fim.

E aqui está um que não tem sucesso:

>>>
Login: john
Usuário desconhecido.
Fim.
"""

def exerc_25(user=str):
    if (user in ['joe', 'sue', 'hani', 'sophie' ]):
        print("Logado com Sucesso")
    else:
        print("Usuário desconhecido")

exerc_25(input("Login:"))
```
---
### **Exerc_26**:
Sistema básico de verificação taxa no IMC.


```python
"""
Implemente a função meuIMC(), que aceita como entrada a altura de uma pessoa
(em metros) e o peso (em quilos) e calcula o Índice de Massa Corporal (IMC)
dessa pessoa. A fórmula do IMC é:.
Sua função deverá exibir a string 'Abaixo do peso' se o imc < 18.5,
'Normal' se 18,5 <= imc < 25, e
'Sobrepeso' se imc >= 25.
  
>>> meuIMC(86, 1.90)
Normal
>>> meuIMC(63, 1.90)
Abaixo do peso
"""

def exerc_26(weight=int,height=float):
    imc = weight/(height**2)
    if (imc < 18.5):
        print('Abaixo do peso')
    elif (imc >= 18.5 and imc <= 25):
        print('Normal')
    else:
        print('Sobrepeso')

exerc_26(68, 1.69)
    # Output => Normal
```
---

## Semana 6 ✅

### **Exerc_27**:
Uso de Seleção de elementos em uma lista.


```python
"""
Implemente um programa que solicite do usuário uma lista de palavras
(ou seja, strings) e depois exiba na tela, uma por linha, todas as strings de
quatro letras nessa lista.
Digite a lista de palavras: ['pare', 'desktop', 'tio', 'pote']
pare pote
"""

def exerc_27(lista):
    return list(filter(lambda x: len(x) == 4, lista))

print(exerc_27(['pare', 'desktop', 'tio', 'pote']))
```
---
### **Exerc_28**:
Exibição de sequências usando range 1.


```python
"""
Implemente um programa que comece pedindo ao usuário para digitar uma identificação
de login (ou seja, uma string). O programa, então, verifica se a identificação
informada pelo usuário está na lista ['joe', 'sue', ' hani', 'sophie' ] de usuários
válidos. Dependendo do resultado, uma mensagem apropriada deverá ser impressa. Não
importando o resultado, sua função deverá exibir 'Fim.' antes de terminar.
Aqui está um exemplo de um login bem-sucedido:
  
Login: joe
Você entrou!
Fim.

E aqui está um que não tem sucesso:
Login: john
Usuário desconhecido.
Fim.
"""

def exerc_25(user=str):
    if (user in ['joe', 'sue', 'hani', 'sophie' ]):
        print("Logado com Sucesso")
    else:
        print("Usuário desconhecido")

exerc_25(input("Login:"))
```
---
### **Exerc_29**:
Exibição de sequências usando range 2.


```python
"""
Implemente a função meuIMC(), que aceita como entrada a altura de uma pessoa
(em metros) e o peso (em quilos) e calcula o Índice de Massa Corporal (IMC)
dessa pessoa. A fórmula do IMC é:.
Sua função deverá exibir a string 'Abaixo do peso' se o imc < 18.5,
'Normal' se 18,5 <= imc < 25, e
'Sobrepeso' se imc >= 25.
  
>>> meuIMC(86, 1.90)
Normal
>>> meuIMC(63, 1.90)
Abaixo do peso
"""

def exerc_26(weight=int,height=float):
    imc = weight/(height**2)
    if (imc < 18.5):
        print('Abaixo do peso')
    elif (imc >= 18.5 and imc <= 25):
        print('Normal')
    else:
        print('Sobrepeso')

exerc_26(68, 1.69)
    # Output => Normal
```
---

## Semana 7 ✅

Soma entre duas listas Bidimensionais.


```python
"""
Escreva um laço for que exiba a seguinte sequência de números, um por linha.

  
Inteiros de 3 até 12, inclusive este.
Inteiros de 0 até (mas não incluindo) 9, com um passo de 2 em vez do padrão 1
(isto é, 0, 2, 4, 6, 8).
Inteiros de 0 até (mas não incluindo) 24, com um passo de 3.
Inteiros de 3 até (mas não incluindo) 12, com um passo de 5.
"""
print("Inteiros de 3 até 12, inclusive este.")
for i in range(3,13):
    print(i)
    """  Output =>
    Inteiros de 3 até 12, inclusive este.
    3
    4
    5
    6
    7
    8
    9
    10
    11
    12
    """
print("Inteiros de 0 até (mas não incluindo) 9, com um passo de 2 em vez do padrão 1")
for i in range(0,9,2):
    print(i)
    """ Output =>
    Inteiros de 0 até (mas não incluindo) 9, com um passo de 2 em vez do padrão 1
    0
    2
    4
    6
    8
    """

print("Inteiros de 0 até (mas não incluindo) 24, com um passo de 3.")
for i in range(0,24,3):
    print(i)
    """ Output =>
    Inteiros de 0 até (mas não incluindo) 24, com um passo de 3.
    0
    3
    6
    9
    12
    15
    18
    21
    """
print("Inteiros de 3 até (mas não incluindo) 12, com um passo de 5.")
for i in range(3,12,5):
    print(i)
    """
    Inteiros de 3 até (mas não incluindo) 12, com um passo de 5.
    3
    8
    """
```
---
### **Exerc_30**:
Soma entre duas listas Bidimensionais.


```python
"""
Comece executando a atribuição:
s = '0123456789'
Agora, escreva expressões (usando s e o operador de indexação) que
sejam avaliadas como:  
'234'
'78'
'1234567'
'0123'
'789'
"""

s = '0123456789'

print(s[2:5])
    # Output => 234
print(s[7:8])
    # Output => 78
print(s[1:8])
    # Output => 1234567
print(s[0:4])
    # Output => 0123
print(s[7:10])
    # Output => 789

```
---
### **Exerc_31**:
Soma entre duas listas Bidimensionais.


```python
"""
Supondo que a variável previsão tenha recebido a string
'It will be a sunny day today'
escreva instruções Python correspondentes a estas atribuições:

  
A variável cont, a quantidade de ocorrências da string 'day' na string previsão.
A variável clima, o índice em que a substring 'sunny' começa.
A variável troca, uma cópia de previsão na qual cada ocorrência da substring
'sunny' é substituída por 'cloudy'.
"""

prevision = 'It will be a sunny day today'
count = prevision.count("day")
weather = prevision.index("sunny")
change = prevision.replace("sunny", "cloudy")

print(prevision)
    # Output => It will be a sunny day today
print(count)
    # Output => 2
print(weather)
    # Output => 13
print(change)
    # Output => It will be a cloudy day today

```
---
### **Exerc_32**:
Soma entre duas listas Bidimensionais.


```python
"""
Escreva uma função exerc_32() que aceita duas listas bidimensionais do mesmo
tamanho (ou seja, o mesmo número de linhas e colunas) como argumentos de entrada e
incrementa cada entrada na primeira lista com o valor da entrada correspondente
na segunda lista.

            
>>> t = [[4, 7, 2, 5], [5, 1, 9, 2], [8, 3, 6, 6]]
>>> s = [[0, 1, 2, 0], [0, 1, 1, 1], [0, 1, 0, 0]]
>>> exerc_32(t,s)
>>> for linha in t:
print(linha)

[4, 8, 4, 5]
[5, 2, 10, 3]
[8, 4, 6, 6]
"""

def exerc_32(lista1=list, lista2=list):
    try:
        if (len(lista1) == len(lista2)):
            print(f"Lista 1: {lista1}")
            print(f"Lista 2: {lista2}")
            for i, rows in enumerate(lista1):
                for j, cols in enumerate(rows):
                    lista1[i][j] += lista2[i][j]
            print(f"Resultado: {lista1}")
    except:
        raise IndexError("Argumentos Inválidos")
    
# List 1
obj_1 = [[16, 64, 11, 38],[54, 41, 77, 2],[84, 55, 4, 88],[11, 80, 16, 48]]
obj_2 = [[36, 5, 43, 9],[48, 48, 96, 64],[85, 2, 16, 75],[91, 95, 22, 84]]

exerc_32(obj_1, obj_2)
"""
Lista 1: [[16, 64, 11, 38], [54, 41, 77, 2], [84, 55, 4, 88], [11, 80, 16, 48]]
Lista 2: [[36, 5, 43, 9], [48, 48, 96, 64], [85, 2, 16, 75], [91, 95, 22, 84]]
Resultado: [[52, 69, 54, 47], [102, 89, 173, 66], [169, 57, 20, 163], [102, 175, 38, 132]]
"""
```
---
