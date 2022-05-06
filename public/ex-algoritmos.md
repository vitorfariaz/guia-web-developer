 # XANDA:
 Fundamentos da computação
  - Aprendi como funciona as linguagens de programação
  - Aprendi para que serve os algoritmos

Aprendi a resolver problemas com algoritmos
  1. Aprendi a criar variáveis
  2. Aprendi como fazer Loops (PARA, ENQUANTO, FAÇA-ENQUANTO)
  3. Aprendi o que são condicionais(SE/SENAO, ESCOLHA-CASO)
  4. Expressões booleanas (true e false)
  5. Operadores lógicos: E, OU, NÃO, NÃO-E, NÃO-OU, OU-EXCLUSIVO E NÃO-OU-EXCLUSIVO
  6. Operadores relacionais: igual, diferente, maior, menor
  7. Operadores aritméticos: adição, subtração, divisão, multiplicação, resto
  8. Aprendi sobre estrutura dados: listas, mapas e objetos
  9. Aprendi o que são métodos/funções e parâmetros

# Materiais
IDE
https://portugol-webstudio.cubos.io/ide

Materiais
http://rafaelmuniz.com.br/ifsp/alpt2020/

## Tipos de variáveis

Tipo variáveis| O que é               | Exemplos
------------- | -------------         |  -------------
inteiro       | número inteiro        | 123, 333, 1 , 2 , 4 
real          | número fracionado     | 12,21 , 13,32 , 12 , 99
caracter      | um caractere          | 'A', '#', 'k', '2'
cadeia        | lista de caracteres   | "palavra", "palavra com espaço"
logico        | verdadeiro ou falso   |  verdadeiro, falso

## Atribuição
```
inteiro idade     = 32
real preco        = 22,22
caracter letra    = 'a'
cadeia pergunta   = "Qual seu nome"
logico resposta   = verdadeiro
OU
inteiro idade
idade = 12
```

## Entrada e saída

```
     cadeia nome 
     escreva("Digite seu nome: ")
     leia(nome)
     escreva("ola, ", nome)
  
     //comentario
     escreva("\n QUEBRA DE \n linha, ", nome)
```

## Operadores
Operador Lógico | Na liguagem
-------------   | -------------       
e               | e
nao             | nao
ou              | ou

Exemplo
```
   se((letra == 'c' ou nao(letra == 'd')) e (letra2 == 'c' ou letra2 == 'd') ){
```
<br />

Operador Relacional | Na liguagem
-------------       | -------------       
maior               | >
menor               | <
igual               | ==
diferente           | !

Exemplo
```
 se(nro == nro2){ 
 	escreva("numeros diferentes")
 }
```
<br />


Operador Aritmético  | Na liguagem
-------------        | -------------       
soma                 | +
subtração            | -
divisão              | /
multiplicação        | *
incremento           | ++
decremento           | --

Exemplo
```
inteiro nro,nro2, resultado
leia(nro)
leia(nro2)
resultado = nro + nro2
```
<br />

## Condicional

SE/SENÃO 
```
	    inteiro idade 
	    escreva("Digite sua idade: ")
	    leia(idade)
	    se(idade < 16){
               escreva("NÃO pode votar!")
            }senao
               escreva("Pode votar!")
```

ESCOLHA-CASO
```
	    inteiro idade 
	    escreva("Digite sua idade: ")
	    leia(idade)
            escolha(idade){
               caso 16:
                  escreva("tá no hype")
                  pare
               caso 18:
                  escreva("se ferro")
                  pare
               caso 70:
                  escreva("tá vei hein")
                  pare
        }
```

## Loops

PARA
```	 
            para(inteiro i = 0 ; i < 10 ; i++){
               escreva("\n contador: ", i)
           }
```

ENQUANTO
```
	inteiro idade 
	inteiro contador = 5
        enquanto(contador > 0){
            escreva("\ncontador: ", contador)
            contador--
        }
```

FAÇA-ENQUANTO
```
        faca{
            escreva("\ncontador: ", contador)
            contador--
        }enquanto(contador > 0)
```

## Funções 

FUNCOES sem retorno
```
programa {
    	funcao inicio() {
	 
	    apresentaLinhas()
	    escreva("Ola mundo")
            apresentaLinhas()
	}

	funcao apresentaLinhas(){
	    escreva("\n-------------------------------------\n")
	}
}
```

FUNCOES com retorno 
```
programa {
	funcao inicio() {
	    inteiro numero1, numero2
	    escreva("digite primeiro numero")
	    leia(numero1)
	    escreva("digite segundo numero")
	    leia(numero2)
	    inteiro resultado = soma(numero1, numero2)
	    escreva("resultado da soma: ", resultado)
	}
	
	funcao inteiro soma(inteiro nro1, inteiro nro2){
	    retorne nro1 + nro2
	}
}
```

<br />


## Material de apoio para exercício
 - [Especificação portugol studio](#portugol-spec.md)

# Exercícios

1. Apresente "hello, world" na tela

2. Peça para o usuário informar um nome e apresente a mensagem "Olá" e mais o nome que o usuário informou

3. O usuário informará 2 números e o sistema retornará a soma dos 2
soma

4. O usuário informará 3 valores e o sistema calculará a média dos 3 valores
soma e divisão

##



## Condicionais
5. O sistema apresentará a pergunta "Qual o nome do sistema que os desenvolvedores usam para salvar o código fonte dos sites e poder edita-los em paralelo sem conflitos?" se o usuário responder "git" 
o sistema apresentará a mensagem "Acertou!" se não, o sistema apresentará "Errou!"
condicional


6. O sistema apresentará a mensagem "Você quer treinar quais conhecimentos?
Digite 1 para TI. 
Digite 2 para Algoritmos?"
Caso o usuário digite 1 apresentará 3 perguntas abaixo
"Digite algum operador lógico?" resposta: "e", "ou", "nao", "nao-e", "nao-ou"
"Digite algum operador aritmético" resposta: 
"Digite algum operador relacional" resposta: 

Caso o usuário digite 1 apresentará 3 perguntas abaixo
"Qual o mês que contém menos dias no ano?" resposta: fevereiro
"Qual o mês que contém menos dias no ano?" respota: 
"Qual o mês que contém menos dias no ano?"




Condicional aninhada

loop, lista
7. O usuário informará quantos valores quiser e o sistema calculará a média dos valores informados

















