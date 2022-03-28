## Introdução - Fundamentos da Computação
Agora que você entendeu o que é TI, ainda que de maneira bem ampla e conceitual, você vai entender como funciona um computador e as linguagens de programação. O que acho fantástico nesse mini curso é que o professor consegue explicar algo complexo como o computador, de forma simples e lúdica. <br />

A ideia de passar esse vídeo é que ele reforça um pouco o conceito do que é tecnologia, pra que serve e o que podemos fazer com ela. <br />

No menu lateral onde tem "Week 0-10", tem 11 aulas, asista as aulas **Week 0** e **Week 1**. Que são a introdução sobre ciência da computação e explica de modo genérico como funciona o computador e as linguagens de programação.

Fala também sobre outros termos que no futuro vai ser interessante você já saber do que se trata. <br />
Obs.: No player do vídeo, marque a opção de legendas, vá em configurações(ícone de engrenagem) e seleciona o idioma Português. <br />

Assista somente as aulas **Week 0** e **Week 1** <br />

[Clique aqui para acessar](https://cs50.harvard.edu/x/2021/weeks/0)

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


## Introdução - Fundamentos da Internet

Nesse material, você vai entender como a internet funciona. Como é trafegado as informações pela rede, o que acontece quando você acessa um site, qual o papel do navegador, entre outras coisas. <br />
A internet é como se fosse os canos que trazem água para nossa casa, nesses mini cursos, você vai entender um pouco mais sobre como esse "encanamento da internet" funciona. <br />

São bastante conteúdos, mas são só o básico para você se contextualizar e entender por cima os fundamentos básicos. Isso vai ser a base de todo o teu conhecimento. Tudo que você irá construir, sites e aplicativos, irão ser feitos em cima dessa base de conhecimento. <br />

Assista somente a aula **Week 8**, acione as legendas no vídeo clicando nas legendas > depois engrenagem > traduzir legendas automaticamente em Português  <br />

[Clique aqui para acessar](https://cs50.harvard.edu/x/2021/weeks/0)


**EXERCÍCIOS:**

 1. Qual a linguagem que um computador se comunica com outro? a linguagem da internet? TCP/IP Transmission Control Protocol / Internet Protocol. Essa é a forma como todos os humanos concordaram que os computadores iriam se comunicar. Como enviar cartas no correio, a carta é um pacote de informação e na carta, você precisa identificar o endereço de origem e destino, no computador esse endereço é o endereço da sua máquina e o endereço destino, conhecido como IP
 2. Como os computadores padronizaram o endereço de cada um dos computadores? Através do endereço IP
 3. Quando vamos enviar uma informação para o facebook por exemplo, não sabemos qual o IP dele, nós digitamos uma URL(endereço do site). Quem "redireciona" essa chamada para o endereço IP dos servidores do facebook? DNS = Domain Name system = Sistema de nomes de domínio. É um sistema que fica "interceptando" as suas chamadas para redirecionar para o endereço IP correto dos computadores/servidores a partir da URL que você digitou ou qualquer chamada de rede que você fez para outro computador passando um nome de dominio.
 4. Quem fornece o serviço de DNS? é o provedor de internet, se você usa Oi, é ela, se usa Vivo é ela, se você está no shopping, é o provedor de internet do shopping.
 5. Quando você acessa um site como facebook.com, qual página você está "buscando" do servidor? index.html
 6. Como é formada uma típica requisição HTTP?
```
GET / HTTP/1.2 
host: facebook.com
```
<br /> O GET significa que você está "buscando" uma informação
<br /> O http/1.2 significa a versão da requisição http
<br /> host é o endereço do servidor que você está buscando a informação
 
 7. Como é uma típica **resposta** de uma requisição HTTP que retornou com sucesso?
```
HTTP/1.1 200 OK
Content-Type: text/html
Body: ~ arquivo html

```
<br /> O 200 significa status da requisição, 200 é uma convenção para informar que a requisição retornou com sucesso.
<br /> O content-Type significa o tipo do arquivo. Pode ser uma página html, uma foto, um vídeo, etc...

 8. Quando você visita uma página na internet geralmente é feito somente 1 requisição e retornado somente 1 arquivo? Geralmente quando acessamos uma página, é retornado diversos arquivos e é feito diversas requisições http "por baixo dos panos" para retornar todas os conteúdos de uma página html como música, imagens, vídeos, etc...
 9. Por quais componentes fisícos uma requisição HTTP passa do seu Computador até chegar no servidor destino? PC, Modem/roteador de casa, roteador/modem da sua internet provedora, roteadores/cabos da internet, provedora de internet do server, roteador/modem do server, Server.
 10. Faça um desenho da arquitetura da internet da sua casa até um servidor que você acessa.

**Responda você mesmo primeiro, caso não saiba a resposta, assista novamente os vídeos e depois confira as Respostas no final da página.**


### Reforçando conteúdo sobre fundamentos da internet

Nesse material, você vai reforçar os mesmos conceitos de outras formas para pegar bem. O site é em inglês, traduza a página e acione as legendas no vídeo clicando nas legendas > depois engrenagem > traduzir legendas automaticamente em Português portugal(portugal mesmo, a legenda do Brasil ficou atrasada)

[Clique aqui para acessar](https://roadmap.sh/guides/what-is-internet)

**EXERCÍCIOS:**
 - O que é HTTP? 
 - O que é HTTPS?
 - Quando você envia sua senha para para algum site, é exatamente o valor que você inseriu que é trafegado pela rede?
  Se não, qual é o valor?
 - O que é TLS?
 - O que é DNS?
 - O que é SSL?
 - O navegador é um interpretador de qual arquivo?
 - Qual a linguagem que o navegador entende?
 - O que é a internet?

**Responda você mesmo primeiro, caso não saiba a resposta, assista novamente os vídeos e depois confira as Respostas no final da página.**


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


### HTML, CSS (9Hrs)
Nesse curso você irá aprender quase tudo sobre como criar páginas HTML estáticas. Com isso, é possível você criar um site inteiro, 
então é bastante conteúdo. Porém, é limitado, pois com esse conhecimento, você só conseguirá criar páginas que não se modificam, por exemplo: 
imagine que você quer que quando seja apertado um botão na sua página HTML, algum elemento ou componente mude de cor ou de lugar(que algo modifique 
na sua página) você não conseguirá pois isso é feito através do Javascript, que você só irá aprender no próximo curso. O curso de Javascript complementa 
o de HTML, então vá com calma e aprenda um de cada vez. Pratique, faça os exercícios junto com o professor do curso.  HTML e CSS são partes 
fundamentais/cruciais do desenvolvimento de sites, então caso queira repetir uma aula pois não entendeu um conteúdo, faça isso sem duvidar. 
Com a prática você vai dominando e se lembrando das coisas. Por isso é extremamente importante você praticar mais do que somente estudar.
Se você só estuda e não faz exercício, você não vai evoluir. <br />

[Clique aqui para acessar](https://www.youtube.com/watch?v=Ejkb_YpuHWs&list=PLHz_AreHm4dkZ9-atkcmcBaMZdmLHft8n&ab_channel=CursoemV%C3%ADdeo)

**EXERCÍCIOS**
 - O que é a "linguagem" html? 
 - Qual programa tem a inteligência para interpretar código HTML e transformar isso no que vemos quando acessamos um site? 
 - O que acontece se abrirmos um arquivo com extensão .html com o programa bloco de notas? 
 - O que acontece se abrirmos esse mesmo arquivo .html com o programa google Chrome? Por que acontece essa diferença? 
 - O que é a "linguagem de marcação" CSS? 

PRIMEIRO EXERCÍCIO PRÁTICO, GUARDE ESSE CÓDIGO POIS SERÁ USADO PARA SEU PORTFÓLIO E CURRÍCULO FUTURAMENTE: 
 - Faça um site de cadastro e consulta de pacientes. É preciso poder criar, alterar e consultar pacientes. (Essa será nosso site inicial que servirá como base prática para os próximos conhecimentos) 
 - Cadastro: Deve ser possível cadastrar o paciente com as seguintes informações: nome, data de nascimento, sintomas, doenças, cpf. (não precisa salvar em banco de dados real) 
 - Alteração: deve ser possível alterar qualquer uma das informações(Pode ser somente uma página, sem a funcionalidade de alterar os dados de fato pois ainda não terão sido salvos) 
 - Pesquisa: deve ser possível consultar por CPF, nome parcial ou completo e doenças. (Pode ser somente a página com os filtros, sem a funcionalidade de trazer de fato os registros pois ainda não terão sido construído) 


### Lógica e algoritmos (7Hrs)
Nesse curso você irá aprender sobre lógica e algoritmos. Isso é fundamental e é "alheio" a tecnologias e a linguagem de programação.
É basicamente sobre como pensar de forma racional para resolver um problema específico. Entender isso e ter esse racional antes mesmo de aprender 
coisas mais complexas e técnicas é fundamental e vai ti ajudar muito nos próximos conteúdos mais complexos. <br />

[Clique aqui para acessar](https://www.youtube.com/watch?v=8mei6uVttho&list=PLHz_AreHm4dmSj0MHol_aoNYCSGFqvfXV&ab_channel=CursoemV%C3%ADdeo)

**EXERCÍCIOS**
 - O que é um algoritmo? 
 - "Lógica" é usada somente na tecnologia e desenvolvimento de sistemas?  
 - Em quais outros lugares a lógica pode ser usada? 


### JavaScript (9Hrs)
Com esse curso, você irá aprender a deixar sua página HTML mais dinâmica, poderá fazer com que quando um botão seja apertado na página, a mesma seja 
modificada e/ou seja chamada uma função do "backend" ou diversas outras possibilidades. Esse é somente um curso inicial, o potencial do Javascript é
enorme. Existe diversos Games que são criados somente com JavaScript, HTML e CSS. Isso é a base fundamental do desenvolvimento Web, é extremamente 
importante você conhecer esses conceitos. Pratique, faça os exercícios junto com o professor do curso. <br />

[Clique aqui para acessar](https://www.youtube.com/watch?v=BXqUH86F-kA&list=PLntvgXM11X6pi7mW0O4ZmfUI1xDSIbmTm&index=1)

**EXERCÍCIOS**
 - Crie a parte do "backend" do cadastro de pacientes, faça com que salve em memória os dados dos pacientes  
 - Crie a parte do "backend" da funcionalidade de alteração das informações do paciente. 
 - Crie a parte do "backend" da funcionalidade de pesquisa dos pacientes, possibilitando a pesquisa por CPF, nome parcial ou completo e doenças.  

Até agora, você já absorveu no mínimo 25 Horas de conteúdo/cursos em vídeo. Isso já é bastante coisa. Agora você precisa colocar em prática aquilo 
que aprendeu. Faça no mínimo mais 2 projetos com o conhecimento que você aprendeu. Além de fortalecer o seu conhecimento você estará melhorando seu 
currículo/portifólio para as futuras vagas que você irá se candidatar. 


### REACT (7Hrs)
ReactJS é uma biblioteca de desenvolvimento em javaScript, que ajuda e muito no desenvolvimento web, com ela, você consegue criar componentes HTML
reutilizáveis, e mescla o javaScript com o html em um mesmo arquivo. Pra que isso? Hoje quando vamos desenvolver um site grande, nós precisamos reutilizar 
diversos componentes, além de importar coisas prontas de outras bibliotecas, o React facilita muito tudo isso. <br />

Hoje, essa biblioteca é uma das mais utilizadas no mundo para o desenvolvimento de sites. Do facebook até sites pequenos usam essa biblioteca de 
desenvolvimento. <br />

Introdução React <br />
[Clique aqui para acessar](https://www.youtube.com/watch?v=aJR7f45dBNs&ab_channel=FilipeDeschamps)

Curso React <br />
[Clique aqui para acessar](https://www.youtube.com/watch?v=FXqX7oof0I4&list=PLnDvRpP8BneyVA0SZ2okm-QBojomniQVO&ab_channel=MatheusBattisti-HoradeCodar)


### GITHUB

Já parou para pensar como as empresas atualizam o código fonte dos seus sistemas? Imagina vários desenvolvedores mexendo no mesmo código fonte de um site? 😧 <br />
GitHub é o site de armazenamento e gestão de código fonte. É através dessa ferramenta que as empresas fazem a gestão dos códigos fontes de seus sistemas. <br /> 
Ela fornece diversas ferramentas de versionamento de código para que vários desenvolvedores consigam editar diversos arquivos fontes. <br />
Você irá disponibilizar seus projetos que fez até aqui nessa ferramenta e irá colocar o link do seu Github no currículo e Linkedin para que os avaliadores vejam seus projetos, servirá como seu portifólio. <br />

[Clique aqui para acessar](https://www.youtube.com/watch?v=xEKo29OWILE&list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA&ab_channel=CursoemV%C3%ADdeo)


### PROCESSO DE DESENVOLVIMENTO ÁGIL
Talvez em algum momento você se pergunte: tá, mas como é feito o processo todo? Como assim outra pessoa vai fazer o desenho da tela e eu vou criar o 
código depois? O processo de idealização até a construção e colocar o produto "no ar" como é? Quantas pessoas participam do processo como um todo? <BR />

ADICIONAR CURSO

<br />

[Voltar para página inicial](https://github.com/vitorfariaz/guia-web-developer)


## Respostas para os exercícios

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


 5. Por que o computador com pouco recurso ou seja, só guardando energia elétrica(ligado ou desligado) ele consegue guardar e montar informações mais complexas. Dentro do computador existem bilhões de transistores(interruptores) que guardam a energia elétrica ligada ou desligada e com isso, eles conseguem interpretar/processar e manter informações mais complexas, como letras, números, cores, fotos, vídeos, sons, etc...
 6. Os humanos chegaram em um acordo que cada número representa uma letra, caractere, números, etc... Essa tabela de representação se chama ASCII.
 7. É um termo utilizado para dígito binário ou binary digit em inglês.
 8. 2. Pode guardar 0 e 1, Ligado ou desligado, verdadeiro ou falso, isso depende do contexto.
 9. 256, pois é 2x2x2x2 x 2x2x2x2 = 256
 10. Por que as 256 possibilidades do ASCII não são suficientes? Letras de outras linguas como japonês, mandarim, etc... Demandam muito mais que 256 possibilidades.
 11. Inventaram o Unicode, que representa todas as linguagens dos humanos. Unicode usa até 16/24/32 bits para representar todas outras linguas, caracteres.
 12. RGB, é a quantidade de Red, Green and blue em cada pixel.
 13. Eles guardam primeiro a informação de que aquele arquivo binário é um vídeo, depois guardam diversas imagens, com vários pixels em cada imagem, dizendo onde está cada pixel, cada ponto RGB da foto, tudo através dos bits. Por isso um vídeo as vezes tem Gigabits de informações, por que são muitos pixels. E existem vários formatos de leitura de vídeos e imagens, como mp4, mov, JPG, PNG, etc... São várias convenções que pessoas chegaram de como armezenar os bits de forma que um computador conseguisse interpretar e apresentar isso.
 14. Não, só entende 0 e 1
 15. Transformar o código da linguagem em código binário
 16.  Compilar
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
 10. [Verifique a imagem](arquitetura-internet.png)

