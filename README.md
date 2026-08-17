# Python Graduação Superior ADS - Linguagem de Programação
Atividades realizadas em sala de aula da matéria de Linguagem de Programação  (Python).

<img width="269" height="180" alt="image" src="https://github.com/user-attachments/assets/71db860c-ead9-4687-a1b6-8e4750f4b83b" />
<img width="387" height="130" alt="image" src="https://github.com/user-attachments/assets/9759ffab-b4ed-4a67-a695-b45ab081877b" />
<img width="286" height="176" alt="image" src="https://github.com/user-attachments/assets/4fc39319-ba96-4fc0-ae00-f766d48cbfea" />


### 05/03/2026 - Atividades Proposta

**Q1.** Descreva, em pseudocódigo, um algoritmo para calcular a média de três números.
```
Algoritmo CalcularMediaTresNumeros
Var
    // Declaração das variáveis
    num1, num2, num3 : Real
    media : Real

Inicio
    // Entrada de dados
    Escreva("Digite o primeiro número: ")
    Leia(num1)
    Escreva("Digite o segundo número: ")
    Leia(num2)
    Escreva("Digite o terceiro número: ")
    Leia(num3)

    // Processamento
    // A soma deve ser realizada antes da divisão, por isso os parênteses
    media <- (num1 + num2 + num3) / 3

    // Saída de dados
    Escreva("A média aritmética é: ", media)
FimAlgoritmo

```
**Q2.** Descreva um algoritmo que calcule o total a ser pago por um produto, considerando valor unitário e
quantidade.
```
Algoritmo: CalculaTotalProduto
Início
Declarar Variáveis:
valorUnitario (Real) - Para armazenar o preço por item.
quantidade (Inteiro/Real) - Para armazenar quantos itens.
total (Real) - Para armazenar o resultado final.
Entrada de Dados:
Escreva "Digite o valor unitário do produto: "
Leia valorUnitario
Escreva "Digite a quantidade comprada: "
Leia quantidade
Processamento:
total 
 valorUnitario * quantidade
Saída de Dados:
Escreva "O total a pagar é: R$ ", total
Fim 
```
**Q3.** Elabore um algoritmo que identifique o menor entre três valores informados.
```
Algoritmo: Encontrar o Menor de Três Valores 
Início
Declare as variáveis n1, n2, n3, menor como números reais.
Escreva "Digite o primeiro número: "
Leia n1
Escreva "Digite o segundo número: "
Leia n2
Escreva "Digite o terceiro número: "
Leia n3
Assuma inicialmente que o menor é o primeiro: menor = n1
Se n2 < menor então:
menor = n2 (atualiza o menor para n2)
Fim Se
Se n3 < menor então:
menor = n3 (atualiza o menor para n3, se n3 for ainda menor)
Fim Se
Escreva "O menor número é: ", menor
Fim 

```
**Q4.** Explique, com suas próprias palavras, a diferença entre algoritmo, pseudocódigo e código-fonte,
destacando o papel de cada um no processo de desenvolvimento de software.
```

```
<hr>

### 09/03/2026 - Estruturas de Decisão (if / else / elif)

### ***Maior ou Menor de Idade***
**Q5.** .Crie um programa que solicite a idade do usuário e informe se ele é maior ou menor de idade.

```
idade = int(input("Digite dua idade,usuário:"))
    if idade >= 18
        print("Maior de Idade!")
    else 
        print("Menor de idade!")
```
### ***Situação Do Aluno*** `
**Q6.** Crie um programa que solicite a nota de um aluno e informe sua situação: <br>
 <br>
* **Aprovado** → nota ≥ 7 <br>
* **Recuperação** → nota ≥ 5 e < 7 <br>
* **Reprovado** → nota < 5 <br>


```
 if nota >= 7.0:
        print("Aprovado!")
    elif nota >= 5.0:
        print("Recuperação!")
    else:
        print("Reprovado!")
```

### ***Desconto em Compra***
**Q7.** Crie um programa que solicite o valor de uma compra e informe: <br>
<br>
* **“Desconto disponível”** se o valor for maior ou igual a 100 <br>
* **“Sem desconto”** caso contrário <br>
```
compra = int(input("Digite o valor da sua Compra"))

    if compra >= 100
        print("Desconto Disponível")
    else
        print("Desconto Indisponível")
```
<hr>

### 16/03/2026 - Laços de Repetição
**Q8.** Crie um programa que mostre os números de 1 a 10 utilizando o laço while.

```
contador = 1 

    while contador <=10:
        print (contador)
        contador + = 1
```
**Q9.** Crie um programa que mostre os números de 1 a 10 utilizando o laço for.

```
for i in range(1,10):
    print(i)
```
**Q10.** Crie um programa que solicite 5 números ao usuário, calcule e mostre a soma total dos valores informados.
.

```
soma = 0

for i in range(5):
    numero = float(input("Digite um número"))
    soma += numero
        print("A soma dos números é:",soma)
```
<hr>

### 23/03/2026 - Estruturas de Dados
**Objetivo** - Praticar o uso de listas, tuplas e dicionários, compreendendo como armazenar e acessar conjuntos de dados em Python.

### ***Lista de Números*** 
**Q11.** Crie uma lista com 5 números informados pelo usuário e exiba todos os valores armazenados.
.

```
numeros = []

for i in range(5):

    valor = float(input("Digite um número: "))
    numeros.append(valor)
    
print("Os números armazenados são:")
print(numeros)

```
### **Tupla de Nomes*** 
**Q12.** Crie uma tupla com 3 nomes e mostre apenas o segundo nome.
.

```
nomes = ["Julia","Marcos", "Mariana"]
print(nomes[1])
```
### **Dicionário de Aluno*** 
**Q13.** Crie um dicionário com os seguintes dados de um aluno: <br><br>
* **nome** <br>
* **idade** <br>
* **curso** <br>

```
aluno = {
    "nome":"Marcos",
    "idade": 18,
    "curso": "ADS"
}

print (aluno)
```
<hr>


