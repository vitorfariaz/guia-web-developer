**EXERCÍCIOS: fundamentos computação**
 1. Qual a linguagem que o  computador entende? 
 2. Como o computador representa informações? O que ele "guarda"? 
 3. Se usarmos 3 lampâdas para guardar informação, até quanto poderemos contar? 
 4. Por que isso é importante?
 5. Se o computador só entende binário(1 e 0), como ele guarda letras do alfabeto ou qualquer caractere como exclamação, números, etc? 
 6. O que é bit? 
 7. Quantos símbolos 1 bits podem representar? 
 8. Quantos símbolos 8 bits podem representar? 
 9. Por que o ASCII é limitado para representar a linguagem humana?
 10. Qual foi a solução para o ASCII?
 11. Como os computadores representam cores só com binários?
 12. Como os computadores representam vídeos só com binários? 
 13. O computador entende a linguagem de programação que nós programadores usamos?
 14. O que temos que fazer para ele entender? 
 15. Qual o nome do processo para transformar o código fonte que os desenvolvedores codificam em código que a máquina entende(Binário)? 

**Responda você mesmo primeiro, caso não saiba a resposta, assista novamente os vídeos e depois confira as Respostas no final da página.**

**EXERCÍCIOS: fundamentos da internet**

 1. Qual a linguagem que um computador se comunica com outro? 
 2. Como os computadores padronizaram o endereço de cada um dos computadores? 
 3. Quando vamos enviar uma informação para o facebook por exemplo, não sabemos qual o IP dele, nós digitamos uma URL(endereço do site). Quem "redireciona" essa chamada para o endereço IP dos servidores do facebook?
 4. Quem fornece o serviço de DNS?
 5. Quando você acessa um site como facebook.com, qual página você está "buscando" do servidor?
 6. Como é formada uma típica requisição HTTP?
 7. Como é uma típica **resposta** de uma requisição HTTP que retornou com sucesso?
 8. Quando você visita uma página na internet geralmente é feito somente 1 requisição e retornado somente 1 arquivo?
 9. Por quais componentes fisícos uma requisição HTTP passa do seu Computador até chegar no servidor destino?
 10. Faça um desenho da arquitetura da internet da sua casa até um servidor que você acessa.

**Responda você mesmo primeiro, caso não saiba a resposta, assista novamente os vídeos e depois confira as Respostas no final da página.**

**EXERCÍCIOS: fundamentos da internet**
 1. O que é HTTP? 
 2. O que é HTTPS?
 3. Quando você envia sua senha para para algum site, é exatamente o valor que você inseriu que é trafegado pela rede?
 5. O que é DNS?
 7. O navegador é um interpretador de qual tipo de arquivo?
 8. Quais a linguagens o navegador entende?

**Responda você mesmo primeiro, caso não saiba a resposta, assista novamente os vídeos e depois confira as Respostas no final da página.** <br />

Algumas definições <br />
<br /> IP: como os computadores se endereçam exclusivamente com números de algum tipo
<br /> TCP: Governa algumas coisas, elas entre elas a numeração de serviços como 80 para trafego inseguro na web(http), 443 para trafego seguro(https)
<br /> DNS: identifica e relaciona os dominios com os endereços dos PCs
<br /> URL: uniform resource locator. 
<br /> Um endereço na web é formado pelo seguinte:
<br /> Endereço exemplo: https://github.com/vitorfariaz/guia-web-developer
<br /> github = nome do dominio
<br /> .com = categoria do dominio: com = comercial, edu = educacional, gov = governamental, etc..
<br /> vitorfariaz = caminho de um recurso específico

<br /> Esse bando de siglas é como se fosse o encanamento de como uma informação vai de um ponto para o outro. Como a água. Sabendo disso, somos capazes de construir sistemas que funcionam através desses "canos"


**EXERCÍCIOS**
 - O que é um algoritmo? 
 - "Lógica" é usada somente na tecnologia e desenvolvimento de sistemas?  
 - Em quais outros lugares a lógica pode ser usada? 


# RESPOSTAS para os exercícios

### Fundamentos Computação
 1. Binário, zeros e uns
 2. Bits = binary digits = Binários
 3. 8 possibilidades

Valor em binário | Valor em Decimal  
------------- | -------------
|    000       |   0      |       
|    001       |   1      |      
|    010       |   2      |      
|    011       |   3      |      
|    100       |   4      |       
|    101       |   5      |      
|    110       |   6      |      
|    111       |   7      |         


 4. Por que o computador com pouco recurso ou seja, só guardando energia elétrica(ligado ou desligado) ele consegue guardar e montar informações mais complexas. Dentro do computador existem bilhões de transistores(interruptores) que guardam a energia elétrica ligada ou desligada e com isso, eles conseguem interpretar/processar e manter informações mais complexas, como letras, números, cores, fotos, vídeos, sons, etc...
 5. Os humanos chegaram em um acordo que cada número representa uma letra, caractere, números, etc... Essa tabela de representação se chama ASCII.
 6. É um termo utilizado para dígito binário ou binary digit em inglês.
 7. 2. Pode guardar 0 e 1, Ligado ou desligado, verdadeiro ou falso, isso depende do contexto.
 8. 256, pois é 2x2x2x2 x 2x2x2x2 = 256
 9. Por que as 256 possibilidades do ASCII não são suficientes? Letras de outras linguas como japonês, mandarim, etc... Demandam muito mais que 256 possibilidades.
 10. Inventaram o Unicode, que representa todas as linguagens dos humanos. Unicode usa até 16/24/32 bits para representar todas outras linguas, caracteres.
 11. RGB, é a quantidade de Red, Green and blue em cada pixel.
 12. Eles guardam primeiro a informação de que aquele arquivo binário é um vídeo, depois guardam diversas imagens, com vários pixels em cada imagem, dizendo onde está cada pixel, cada ponto RGB da foto, tudo através dos bits. Por isso um vídeo as vezes tem Gigabits de informações, por que são muitos pixels. E existem vários formatos de leitura de vídeos e imagens, como mp4, mov, JPG, PNG, etc... São várias convenções que pessoas chegaram de como armezenar os bits de forma que um computador conseguisse interpretar e apresentar isso.
 13. Não, só entende 0 e 1
 14. Transformar o código da linguagem em código binário
 15.  Compilar
<br />


### Fundamentos da Internet
 1. TCP/IP Transmission Control Protocol / Internet Protocol. Essa é a forma como todos os humanos concordaram que os computadores iriam se comunicar. Podemos relacionar isso com enviar cartas no correio, a carta é um pacote de informação e na carta, você precisa identificar o endereço de origem e destino, no computador esse endereço é o endereço da sua máquina e o endereço destino, conhecidos como IP
 2. Através do endereço IP
 3. DNS = Domain Name system = Sistema de nomes de domínio. É um sistema que fica "interceptando" as suas chamadas para redirecionar para o endereço IP correto dos computadores/servidores a partir da URL que você digitou ou qualquer chamada de rede que você fez para outro computador passando um nome de dominio.
 4. É o provedor de internet, se você usa Oi, é ela, se usa Vivo é ela, se você está no shopping, é o provedor de internet do shopping.
 5. index.html
 6. Típica requisição HTTP?
```
GET / HTTP/1.2 
host: facebook.com
```
<br /> O GET significa que você está "buscando" uma informação
<br /> O http/1.2 significa a versão da requisição http
<br /> host é o endereço do servidor que você está buscando a informação
 
 7. Típica resposta com sucesso abaixo
```
HTTP/1.1 200 OK
Content-Type: text/html
Body: ~ arquivo html

```
<br /> O 200 significa status da requisição, 200 é uma convenção para informar que a requisição retornou com sucesso.
<br /> O content-Type significa o tipo do arquivo. Pode ser uma página html, uma foto, um vídeo, etc...

 8. Geralmente quando acessamos uma página, é retornado diversos arquivos e é feito diversas requisições http "por baixo dos panos" para retornar todas os conteúdos de uma página html como música, imagens, vídeos, etc...
 9. PC, Modem/roteador de casa, roteador/modem da sua internet provedora, roteadores/cabos da internet, provedora de internet do server, roteador/modem do server, Server.
 10. [Verifique a imagem](public/arquitetura-internet.png)

### Reforçando conceitos da internet
 1. HTTP(Protocolo de Transferência de Hipertexto) é o padrão que espeficica o formato das mensagens que são enviadas entre os computadores e servidores. Através desse padrão é possível compartilhar todo tipo de arquivo; texto, imagens, vídeos, sons, páginas HTML, etc..
 2. É a forma segura de enviar e receber mensagens: em vez de ir as informações "originais" na mensagem, é encriptografado as informações enviadas para que caso alguém intercepte a informação não consiga identificar o que significa.
 3. Caso você esteja usando HTTPS para fazer a comunicaçãom não pois é encriptografado a informação trafegada. Mas caso não seja, é exatamente a sua senha é que passada pela requisição.
 5. Domain Name System. É o sistema que identifica o endereço IP dos computadores a partir do nome de domínio
 7. Arquivos HTML, CSS
 8. Javascript
