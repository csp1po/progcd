# **Exercícios Práticos: operadores aritméticos, lógicos e entrada de dados (Nível Básico)**

> * **Dicas para resolver os exercícios:**
> 
> * Leia atentamente o enunciado do exercício e entenda o que é preciso fazer.
> 
> * Pense nos tipos de dados que você precisa usar para resolver o exercício.
> 
> * Escreva o código passo a passo, verificando se está correto a cada passo.
> 
> * Por último, execute o código


### **1. Escreva um programa que imprime a soma de dois números inteiros.**


```python
a = int(input("Digite o primeiro número: "))
b = int(input("Digite o segundo número: "))

soma = a + b

print(f"A soma de {a} e {b} é {soma}")
```

### **2. Escreva um programa que imprime o produto de dois números inteiros.**


```python
a = int(input("Digite o primeiro número: "))
b = int(input("Digite o segundo número: "))

produto = a * b

print(f"O produto de {} e {} é {}")
```

### **3. Escreva um programa que imprime o resto da divisão de dois números inteiros.**


```python
a = int(input("Digite o primeiro número: "))
b = int(input("Digite o segundo número: "))

resto = a % b

print(f"O resto da divisão de {a} e {b} é {resto}")
```


### **4. Escreva um programa que imprime o resultado do cálculo de 2 elevado a n, onde n é um número inteiro fornecido pelo usuário.**


```python
n = int(input("Digite um número inteiro: "))

potencia = 2 ** n

print(f"2^{n} = {potencia}")
```

### **5. Escreva um programa que imprime o resultado do cálculo de 1/n, onde n é um número inteiro fornecido pelo usuário.**


```python
n = int(input("Digite um número inteiro: "))

racional = 1 / n

print(f"1/{n} = {racional}")
```

### **6. Escreva um programa que imprime o resultado do cálculo de √n (raiz quadrada de um número n), onde n é um número inteiro fornecido pelo usuário.**


```python
n = int(input("Digite um número inteiro: "))

raiz = n ** (1/2)

print(f"A raiz quadrada de √{n} = {raiz}")
```

### **7. Escreva um programa que leia uma temperatura em graus Fahrenheit (fornecido via teclado pelo usuário) e converta-a para graus Celsius. Fórmula para converter: c = (f - 32) * 5/9.**

```python
f = float(input('Entre com a temperatura em Fahrenheit: '))
c = (f - 32) * 5/9

# print("A Temperatura",f,"Fahrenheit =",c,"Celsius")
print(f"A Temperatura em {f} Fahrenheit = {c} Celsius")
```

### **8. Faça um programa que solicite o preço de uma mercadoria e seu percentual de desconto. Depois imprima o valor do desconto e o valor a pagar**

```python
m = float(input('Digite o Preço: '))
p = float(input('Digite o Percentual do Desconto (%): '))

desconto = m * p / 100
novo = m - desconto

print(f'Desconto: R$ {desconto:.2f}')
print(f'Preço a pagar: {novo:.2f}')
```

### **9. Escreva um programa que leia via teclado um valor em metros e o exiba convertido para milímetros**

```python
m = int(input('Digite o valor em metros: '))

print (f'Milímetros = {m*1000}')
```




