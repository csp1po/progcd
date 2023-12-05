# **Exercícios Práticos: Tipos de Dados e Variáveis em Python (Nível Básico)**

> * **Dicas para resolver os exercícios:**
> 
> * Leia atentamente o enunciado do exercício e entenda o que é preciso fazer.
> 
> * Pense nos tipos de dados que você precisa usar para resolver o exercício.
> 
> * Escreva o código passo a passo, verificando se está correto a cada passo.
> 
> * Por último, execute o código


### **Exercício 1: Tipos de Dados Básicos**
```python
# Declare uma variável para cada tipo de dado básico em Python (int, float, str, bool)
numero_inteiro = 10
numero_decimal = 5.5
texto = "Olá, mundo!"
verdadeiro_ou_falso = True
```
---

### **Exercício 2: Definindo Variáveis**
```python
# Declare uma variável chamada 'idade' e atribua um valor numérico a ela
idade = 25
```
---

### **Exercício 3: Nomeando Variáveis**
```python
# Declare uma variável com um nome que siga as regras de nomenclatura em Python
nome_do_usuario = "João"
```
---

### **Exercício 4: Manipulação de Variáveis - Concatenação**

```python
# Crie duas variáveis de texto e concatene-as
fruta1 = "maçã"
fruta2 = "banana"
frutas_concatenadas = fruta1 + fruta2
print(frutas_concatenadas)
```
---

### **Exercício 5: Manipulação de Variáveis - Booleanas (Lógicas)**
```python
# Crie duas variáveis booleanas e imprima o resultado de operações básicas (and, or, not)
verdadeiro = True
falso = False
resultado_and = verdadeiro and falso
resultado_or = verdadeiro or falso
resultado_not = not verdadeiro
print(resultado_and, resultado_or, resultado_not)
```
---

### **Exercício 6: Conversão de Tipos**
```python
# Declare uma variável numérica e uma de texto. Converta a numérica para texto e concatene com a variável de texto.
numero_convertido = str(42)
texto = "O número é: " + numero_convertido
print(texto)
```
---

### **Exercício 7: Formatação de Strings**
```python
# Utilize formatação de strings para imprimir uma mensagem que inclua variáveis.
idade = 30
mensagem = f"Eu tenho {idade} anos de idade."
print(mensagem)
```
---

### **Exercício 8: Concatenação e Repetição**
```python
# Crie duas variáveis de texto e concatene-as usando o operador de repetição (*).
palavra = "Olá"
repeticao = 3
mensagem_final = palavra * repeticao
print(mensagem_final)
```
---

### **Exercício 9: Concatenação e Repetição**
```python
# Crie uma variável chamada nome e atribua a ela o valor “João”. 
# Crie uma variável chamada altura e atribua a ela o valor 1.75 
# Crie uma variável saudacao que seja a concatenação das variáveis nome e altura
saudacao = "Olá, meu nome é " + nome + " e eu tenho " + str(altura) + "m de altura."
print(saudacao)

```


### **Exercício 10: Desafio - Descobrindo o Tipo de Dado**
```python
# Declare uma variável e use a função type() para imprimir o tipo de dado.
variavel_desconhecida = 3.14
tipo_de_dado = type(variavel_desconhecida)
print("O tipo de dado é:", tipo_de_dado)
```
