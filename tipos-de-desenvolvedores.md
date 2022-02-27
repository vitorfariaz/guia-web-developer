Se você pesquisou as vagas como sugeri no material anterior, deve ter lido os termos frontend/backend/web... 

Bom, além de diferenciar um sistema pela plataforma, celular(android/IOS), TV, computador, sim tinha esquecido de comentar, além dessa divisão toda, 
não é UM desenvolvedor Android que irá fazer TODO o desenvolvimento daquele aplicativo sozinho. <br />
Além de ser papéis diferentes que tem a ideia do aplicativo, o que cria o protótipo das interfaces, ainda no próprio desenvolvimento são pessoas diferentes 
que desenvolvem a parte visual do aplicativo, da pessoa que faz as funcionalidades "internas", como salvar algo no banco de dados ou consultar
informações no banco de dados. E essa divisão, é feita por cargos/papéis diferentes. <br />

Mas aqui vai um resumo das resposnabilidade de alguns tipos de desenvolvedores: <br />
 - **Desenvolvedor Backend**: responsável pelos processos que rodam "por baixo dos panos"
 - **Desenvolvedor FrontEnd Web**(Sites): responsável pela construção da parte visual de sites
 - **Desenvolvedor FrontEnd IOS**(Aplicativos para IOS): responsável pela construção da parte visual de Aplicativo IOS
 - **Desenvolvedor FrontEnd Android**(Aplicativos para Android): responsável pela construção da parte visual de Aplicativos Android
 - **Desenvolvedor FullStack Web**(FrontEnd site + backend): responsável pela construção tanto da parte visual de sites quanto pelos processos do back 
 - **Desenvolvedor FullStack Android**(FrontEnd Android + backend): responsável pela construção tanto da parte visual de android quanto pelos processos do back
 - **Desenvolvedor FullStack IOS**(FrontEnd IOS + backend): responsável pela construção tanto da parte visual de IOS quanto pelos processos do back

Obs.: existem vários termos para desenvolvedores, alguns deles:
 - Software Engineer
 - Developer
 - Programador

Dependendo da vaga, vai possuir algum desses títulos, ou até mesmo a linguagem de programação ou a senioridade no nome da vaga, exemplo:
 - Java Developer
 - Senior Java Developer
 - Junior Software Engineer


Abaixo, vou contar a versão mais longa e completa dos Tipos de desenvolvedores que existem em uma equipe de desenvolvimento de software através 
de um exemplo pois acredito que vá ficar 
mais claro de entender: <br />

Imaginem que nós trabalhamos para a empresa fictícia ENTERPRISE-X, que desenvolve programas e dessa vez um hospital nos contratou para criar um
programa  que faça toda a gestão dos pacientes internados, informe quantos pacientes estão internados, quais os motivos, sintomas, quais remédios
foram prescritos, quais remédios, em qual horário foram dados os remédios, qual o médico responsável por cada paciente, etc.. E por praticidade, 
o hospital decidiu que seria melhor criar uma versão para aplicativo Android e um Site na internet. <br />
 
O projeto foi iniciado há algumas semanas, nessas primeiras semanas detalharam melhor as funcionalidades que terá o programa e criaram protótipos 
de como será o aplicativo android e a versão do site também. <br />

E a nossa empresa decidiu que, para agilizar o desenvolvimento, e conseguirmos concluir o projeto mais rápido, nós iremos nos dividir 
em equipes/times de desenvolvimento. Cada equipe irá pegar uma parte do sistema para desenvolver, dessa forma conseguiremos paralelizar o trabalho. <br />
Nosso time ficou responsável somente pela parte do cadastro dos pacientes, o restante será construído pelos outros times de desenvolvimento. <br />

Nosso time é composto por: 
 - 1 analista de negócio: responsável pelo negócio e explicar para o time as necessidades que devem ser atendidas, além de aprovar ou não
se o sistema que iremos desenvolver atende os requisitos do hospital. 
 - 1 UX/UI:  responsável por entender e criar os protótipos do sistemas com o intuito de antes de construir o código, já termos feedback 
do analista de negócio para garantir que atende os requisitos do hospital 
 - 1 Desenvolvedor Frontend Web: responsável por desenvolver a parte visual do site, baseado nos protótipos criados pelo UX/UI. 
 - 1 Desenvolvedor Frontend Android: responsável por desenvolver a parte visual do site, baseado nos protótipos criados pelo UX/UI. 
 - 1 Desenvolvedor Backend: responsável por desenvolver os processos que rodam por "trás" do sistema. 
 - 1 Analista de qualidade: responsável por garantir a qualidade do processo de desenvolvimento. 

A ordem de execução para criar esse projeto deveria ser algo assim:  

1. Análise: dado que analista de negócio e o UX/UI já entenderam o projeto e o UX/UI já criou o protótipo de como será o sistema, 
os desenvolvedores precisam entender o projeto e o que deve ser feito e elaborar os requisitos do sistema para aquela solução proposta. 

2. Implementação: agora que já temos o entendimento do projeto e os requisitos de negócios e de sistemas levantados, os Desenvolvedores FrontEnd
Android e Frontend Web vão se basear no protótipo e requisitos para criar o aplicativo Android e o site, fazendo a funcionalidade de cadastro dos pacientes. <br /> 
Essa funcionalidade precisará salvar as informações do cadastro dos pacientes de forma persistente em algum lugar, para que a  funcionalidade de 
pesquisa de pacientes funcione depois. "Salvar de forma persistente" significa que as informações do cadastro dos pacientes devam ser salvas em 
"algum lugar" para que possam ser consultadas depois de forma programática(através do sistema). Nós chamamos esse "algum lugar" de banco de dados. <br />

A funcionalidade do Site e do aplicativo Android são iguais, as 2 devem salvar o cadastro do usuário, o que muda é a parte visual, do site e 
do aplicativo android. <br />

Notem que são 2 cargos diferentes para fazer o desenvolvimento Android e do Site, pois são linguagens de programação diferentes. <br />

Imaginem a quantidade de código que teve que ser escrito e que fazem a mesma coisa, no Site e no Aplicativo... 
Imaginem se quiserem lançar uma versão para IOS? <br />

Será que teria uma forma de ter menos trabalho "dobrado"? Teria sim! Mas não tudo. <br />

Imaginem que as informações dos pacientes, que devem ser salvas, são as mesmas tanto no Android quanto no Site, porém, a parte visual,
é diferente, mas os 2 sistemas precisam salvar em um único lugar aquelas informações. Será que no Site e no Aplicativo precisaria ter 
toda a lógica pra se comunicar com um banco de dados e aplicar as regras do banco de dados? A resposta é não. O Android e o Site, podem 
chamar uma mesma "função" que simplesmente salva as informações num banco de dados, e a responsabilidade de tratar os dados, se conectar 
com o banco de dados fica somente nessa "função", mas tanto o Android quanto o site terão que chamar essa "função" da sua forma... <br />

E é aí que entra o Backend que vou explicar melhor abaixo, mas aqui no "frontEnd", você só irá chamar uma "função" que salva o cadastro 
dos pacientes, por exemplo, em cada plataforma diferente usando linguagem de programação diferentes. <br />

## Backend 
Geralmente no desenvolvimento terão funcionalidades que precisarão ser usadas diversas vezes em lugares diferentes,
no exemplo do aplicativo hospitalar, precisamos salvar o cadastro dos pacientes pelo site, que será criado pelo Desenvolvedor 
FrontEnd Web e pelo aplicativo Android. Como são códigos/linguagens diferentes, não faz sentido repetir isso em todas as plataforma,
pois se tivesse uma mudança no cadastro, teríamos que codificar em todos os lugares, com o tempo, daria muito trabalho pra conseguir
evoluir o sistema em todas as plataformas... Então aí que entra o Desenvolvedor Backend. Ele trabalha nas funcionalidades em comum que
serão usadas por diversas plataformas. Exemplo: tanto o aplicativo Android, IOS, ou Site, precisarão somente chamar uma função do BackEnd 
para salvar, alterar ou excluir pacientes. Dessa forma, é mais fácil evoluir todos aplicativos. Mais pra frente na mentoria você vai entender
o que é essa "Função" que o frontEnd chama. Não quis usar um termo mais técnico para não confundir. Mas é algo que em qualquer linguagem, 
de qualquer dispositivo, com poucas linhas de código conseguiria chamar a mesma "funcionalidade". <br />

Mas é só isso que o backend faz, salva coisas no banco de dados? Não! <br />
Imaginem que o SUS ou a OMS solicita que enviemos relatórios dos pacientes cadastrados no hospital diariamente. Nós teríamos que criar um processo que 
deveria ficar executando diariamente, consultando o banco de 
dados, pegando diversas informações de lugares diferentes para montar o relatório e enviar para OMS. Esse processo geralmente seria feito pelo desenvolvedor
backend. <br />
Ou imaginem que temos que consultar alguma informação do paciente através do sistema do SUS? Teríamos que passar a informação do CPF do paciente e consultar
o sistema do SUS para verificar alguma informação daquele paciente, isso poderia ser feito pelo Dev backend Também. Só alguns exemplos... <br />


## Por que Desenvolvimento Frontend Web?
Aqui na mentoria vamos focar no Desenvolvimento FrontEnd Web. Por que? Hoje, existe mais demanda para desenvolvimento Web que aplicativo,
pois um site pode ser aberto no celular Android, IOs, na TV, etc... Pois todos essas plataformas possuem o navegador. Então é natural que
tenha mais demanda.  <br />
Terão diversos conhecimentos que vocês irão aprender que serão muito úteis caso vocês queiram "mudar" de trilha no futuro.
Então não se desesperem achando que escolheram a trilha errada. <br />
Por que não o Backend? O backend por você não visualizar as coisas acontecendo, trabalhar somente vendo código e não vendo de fato o que seu 
código está criando, muitas vezes não é tão animador quanto o frontend.<br />

<strong> O que vamos aprender na trilha de desenvolvimento FrontEnd Web? </strong> <br />
  Criação de sites, componentes convencionais de um site, tudo aquilo que vemos em sites: cabeçalhos, menus, 
  rodapés, botões, caixa de diálogo, campos de texto, colocar imagens no site, etc... Algumas interações simples nesses 
  componentes como: cores, estilização dos componentes, etc.. <br />
  
Basicamente você vai aprender a construir aquilo que você vê quando acessa sites tipo: blog, e-commerce, rede social(sem a parte de
  mensagem em tempo real), site com gestão interna de empresas, etc.. <br />

<strong> O que não vamos aprender dentro do mundo desenvolvimento FrontEnd Web? </strong> <br />
  Reconhecimento e identificação de imagem ou som, jogos 3D, mensagens entre dispositivos em tempo real(chat online),
  Inteligência artificial, machine learning, big data...  
<br />

[Voltar para página inicial](https://github.com/vitorfariaz/guia-web-developer)
