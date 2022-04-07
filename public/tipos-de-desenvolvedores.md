## Tipos de desenvolvedores
Aqui vou explicar quais são os tipos de desenvolvedores, alguns cargos na área de TI e por que Desenvolvimento de Sites (Desenvolvimento FrontEnd Web) é minha indicação e falarei também um pouco mais sobre o que são esses termos todos.<br />

Se você pesquisou as vagas como sugeri no material anterior, deve ter lido os termos frontend/backend/web... 

Bom, além de diferenciar um sistema pela plataforma, celular(android/IOS), TV, computador,  
não é somente UM desenvolvedor Android por exemplo, que irá fazer TODO o desenvolvimento daquele aplicativo sozinho. <br />
Além de ser papéis diferentes que tem a **ideia** do aplicativo, o que cria o **protótipo das interfaces**, ainda no próprio desenvolvimento são pessoas diferentes 
que desenvolvem a parte **visual** do aplicativo, da pessoa que faz as funcionalidades **internas**, como salvar/consultar/editar algo no **banco de dados**, ou algum processamento mais longo. E essa divisão, é feita por cargos diferentes dentro de um *time de desenvolvimento*. <br />

Mas aqui vai um resumo das responsabilidade de alguns tipos de desenvolvedores: <br />
 - **Desenvolvedor Backend**: responsável pelos processos que rodam "por baixo dos panos"
 - **Desenvolvedor FrontEnd Web**(Sites): responsável pela construção da parte visual de sites
 - **Desenvolvedor FrontEnd IOS**(Aplicativos para IOS): responsável pela construção da parte visual de Aplicativo IOS
 - **Desenvolvedor FrontEnd Android**(Aplicativos para Android): responsável pela construção da parte visual de Aplicativos Android
 - **Desenvolvedor FullStack Web**(FrontEnd site + backend): responsável pela construção tanto da parte visual de sites quanto pelos processos do back 

Obs.: existem vários termos para desenvolvedores, alguns deles:
 - Software Engineer
 - Developer
 - Programador

Dependendo da vaga, vai possuir algum desses títulos, ou até mesmo a linguagem de programação ou a senioridade no nome da vaga, exemplo:
 - Java Developer
 - Senior Java Developer
 - Junior Software Engineer


Além somente dos desenvolvedores existem diversos outros cargos/pessoas que fazem diferentes partes do processo de desenvolvimento como:
 - **Product Owner**: responsável pelo escopo do produto de negócio. Ele que diz O QUE o time deve fazer
 - **UX/UI designer**: responsável por fazer pesquisa e descoberta do produto, além de criar protótipos para os desenvolvedores
 - **Analista de qualidade**: responsável por todo o processo de desenvolvimento e validação se O QUE foi pedido foi entregue.
 - **DevOps**: responsável por facilitar a vida dos devs automatizando etapas que são comuns para todos os devs de uma empresa.
 - **Scrum master / Agile Coach**: responsável por incentivar uma metodologia de trabalho organizada que meça produtividade
 - Entre outros...

Porém a maior parte das vagas para o mercado são para desenvolvedores. Mas ainda, os outros papéis possuem muitas vagas também.

## Backend 
Geralmente no desenvolvimento terão funcionalidades que precisarão ser usadas diversas vezes em lugares diferentes,
no exemplo do aplicativo hospitalar, precisamos salvar o cadastro dos pacientes pelo site, que será criado pelo Desenvolvedor 
FrontEnd Web e pelo aplicativo Android. Como são códigos/linguagens diferentes, não faz sentido repetir isso em todas as plataforma,
pois se tivesse uma mudança no cadastro, teríamos que codificar em todos os lugares, com o tempo, daria muito trabalho pra conseguir
evoluir o sistema em todas as plataformas... Então aí que entra o Desenvolvedor Backend. Ele trabalha nas funcionalidades em comum que
serão usadas por diversas plataformas. Exemplo: tanto o aplicativo Android, IOS, ou Site, precisarão somente chamar uma função do BackEnd 
para salvar, alterar ou excluir pacientes do banco de dados. Dessa forma, é mais fácil evoluir todos aplicativos. Mais pra frente no guia você vai entender o que é essa "Função" que o frontEnd chama. Não quis usar um termo mais técnico para não confundir. Mas é algo que em qualquer linguagem, 
de qualquer dispositivo, com poucas linhas de código conseguiria chamar a mesma "funcionalidade". <br />

Mas é só isso que o backend faz, salva coisas no banco de dados? Não! <br />
Imaginem que o SUS ou a OMS solicita que enviemos relatórios dos pacientes cadastrados no hospital diariamente. Nós teríamos que criar um processo que 
deveria ficar executando diariamente, consultando o banco de 
dados, pegando diversas informações de lugares diferentes para montar o relatório e enviar para OMS. Esse processo geralmente seria feito pelo desenvolvedor backend. <br />
Ou imaginem que temos que consultar alguma informação do paciente através do sistema do SUS? Teríamos que passar a informação do CPF do paciente e consultar
o sistema do SUS para verificar alguma informação daquele paciente, isso poderia ser feito pelo Dev backend Também. Só alguns exemplos... <br />


## Por que Desenvolvimento Frontend Web?
Aqui nesse guia vamos focar no Desenvolvimento FrontEnd Web. Por que? Hoje, existe mais demanda para desenvolvimento Web que aplicativo,
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
