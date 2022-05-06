# Materiais
IDE: https://portugol-webstudio.cubos.io/ide
Materiais: http://rafaelmuniz.com.br/ifsp/alpt2020/

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
