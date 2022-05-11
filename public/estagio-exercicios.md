# Algoritmos
1. Apresente "hello, world" na tela

2. Peça para o usuário informar um nome e apresente a mensagem "Olá" e mais o nome que o usuário informou

Exemplo: 
```
O usuário digita "Eduardo"
O sistema apresenta "Olá, Eduardo"
```

3. O usuário informará 2 números e o sistema retornará a soma dos 2

Exemplo:
```
O usuário digita "3 e 3"
O sistema apresenta "6"
```
<br />

4. O usuário informará 3 valores e o sistema calculará a média dos 3 valores

Exemplo: 
```
O usuário digita "10, 10 e 1"
O sistema apresenta "7"
```
<br />

5. Crie um sistema que apresentará perguntas para o usuário e o sistema deve informar se o usuário acertou ou não as questões
Perguntas:
- Qual o nome do sistema que os devs usam para salvar o código fonte dos programas e edita-los em paralelo sem conflitos? Resposta certa: "git" 
- Digite algum operador lógico? Possíveis respostas certas: "e", "ou", "nao", "nao-e", "nao-ou", "ou-exclusivo", "nao-ou-exclusivo"
- Digite algum operador aritmético? Possíveis respostas certas: "+","-","/","*","++", "--"
- Digite algum operador relacional? Possíveis respostas certas: ">", "<", "=", "!="

<br />

6. Faça um sistema em que o usuário digite o salário dele e o sistema calcule se o usuário precisará pagar o imposto de renda
 ou não e qual será o valor mensal do imposto.

Base de cálculo <br />
- Até R$ 1.903,99, isento
- De R$ 1.903,99 até R$ 2.826,65,	paga 7,5% do salário	menos R$ 142,80
- De R$ 2.826,66 até R$ 3.751,05	paga 15% menos R$ 354,80
- De R$ 3.751,06 até R$ 4.664,68	paga 22,5% menos  R$ 636,13
- Acima de R$ 4.664,68 paga 27,5% menos  R$ 869,36

Obs.: Pode se verificar o resultado olhando no site https://www27.receita.fazenda.gov.br/simulador-irpf/

```
Exemplo 1
Salário de R$2.000
Cai no 7,5% de 2.000 = 150
150 - 142,80 = R$7,20 reais 
O usuário cai na tabela de 7,5% e precisa pagar R$7,20 reais de imposto de renda por mês.

Exemplo 2
Salário de 1.800
Cai no isento 
Usuário não precisa pagar imposto de renda
```

7. Subtraia o desconto do INSS antes de calcular o percentual de imposto de renda sobre o salário do exercício anterior. 

Base de cálculo INSS:
- até R$1.212,00,	7,5% sobre o salário
- de R$1.212,01 e R$2.427,35,	9% sobre o exceder do desconto anterior 
- de R$2.427,36 e R$3.641,03,	12% sobre o exceder dos descontos anteriores
- de R$3.641,04 e R$7.087,22, 	14% sobre o exceder dos descontos anteriores 

Exemplos:
```
Salário de R$1.212,00
Cai nos 7,5% de R$1.212 = R$90,90 
---------------------------------
Salário de R$2.000
Cai nos 9% do que exceder o desconto anterior.
desconto anterior é: 7,5% de 1.212 = R$90,90
O que excede a faixa anterior R$1.212: 2.000 - 1.212 = R$788 
9% sobre o que excedeu: 788 - 9% = R$70,92
Soma os descontos: 70,92 + 90,90 = R$161,82 de desconto de INSS
--------------------------------------------
Salário de R$7.087,22
Cai nos 14% do que exceder as faixas anteriores.
1. desconto: 7,5% de 1.212 = R$90,90

2. O que excede: 2.427,35 - 1.212,01 = 1.215,34
desconto: 9% de 1.215,34 = R$109,38 desconto

3. O que excede: 3.641,03 - 2.427,36 = 1.213,67
12% sobre o que excedeu: 1.213,67 - 12% = R$145,64 de desconto

4. O que excede: 7087,22 - 3.641,03 = 3.446,19
14% sobre o que excedeu: 3.446,19 = 482,46 de desconto
-----------------------------------------------------
Salário de R$8.000
contribuição fixa de R$828,38

```

<br /> 

Lista con mais algoritmos: <br />
https://docente.ifsc.edu.br/rafael.grebogi/MaterialDidatico/Mecatronica/Linguagem%20de%20Programacao%20I%20(Old)/Introducao%20a%20Informatica/Lista%20de%20Exerc%C3%ADcios%20-%20Algoritmos%20sequenciais.pdf

## Vetores
https://educapes.capes.gov.br/bitstream/capes/597925/2/Lista%20de%20Exerc%C3%ADcios%20sobre%20Vetores%20Num%C3%A9ricos.pdf



