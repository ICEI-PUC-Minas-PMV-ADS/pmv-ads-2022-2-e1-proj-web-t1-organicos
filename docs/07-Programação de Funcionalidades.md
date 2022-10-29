# Programação de Funcionalidades

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>, <a href="4-Metodologia.md"> Metodologia</a>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>, <a href="5-Arquitetura da Solução.md"> Arquitetura da Solução</a>

Nesta seção vamos descrever a implementação do sistema descritas por meio dos requisitos funcionais e/ou não funcionais. Vamos relacionar os requisitos atendidos os artefatos criados (código fonte) além das estruturas de dados utilizadas e as instruções para acesso e verificação da implementação que deve estar funcional no ambiente de hospedagem.

Para cada requisito funcional, pode ser entregue um artefato e esses artefatos serão detalhados nesta seção

> **Links Úteis que foram consultados**:
>
> - [Trabalhando com HTML5 Local Storage e JSON](https://www.devmedia.com.br/trabalhando-com-html5-local-storage-e-json/29045)
> - [JSON Tutorial](https://www.w3resource.com/JSON)
> - [JSON Data Set Sample](https://opensource.adobe.com/Spry/samples/data_region/JSONDataSetSample.html)
> - [JSON - Introduction (W3Schools)](https://www.w3schools.com/js/js_json_intro.asp)
> - [JSON Tutorial (TutorialsPoint)](https://www.tutorialspoint.com/json/index.htm)


## Estrutura geral do site e seções de navegação

A estrutura do site está sendo desenvolvida em HTML5, CSS e JavaScript. Para o desenvolvimento do site estamos utilizando uma ferramenta de apoio chamada Bootstrap. O Bootstrap é um framework front-end que fornece estruturas de CSS para a criação de sites e aplicações responsivas de forma rápida e simples. Até o momento, o framework tem nos auxiliado no desenvolvimento das principais características do site, incluindo a criação de excelentes estruturas de visualização e responsividade. Nas subseções abaixo vamos detalhar cada página com suas funcionalidades e estrutura de dados.

**1 - HomePage**






Página do site - Tela de Informações (Feita por Leticia L. Pauli): é apresentado em destaque as informações gerais sobre produtos orgânicos, como seu cultivo, certificação, regulamentação, história, entre outras, também é acrescentado o link das fontes.

Requisitos atendidos:

Funcionais:

- RF-01: O site deve oferecer links externos que permitam ao usuário visualizar as notícias, artigos e outras bibliografias de fontes externas (sources e backlinks).
- RF-03: O site deve permitir visualizar as informações de contatos do mantenedor do site
- RF-04: O site deve permitir o compartilhamento das informações visualizadas em plataformas de redes sociais (links ou botões). 
- RF-07: O site deve permitir que usuários comentem na página de informação sobre um determinado produto orgânico.
- RF-08: O site deve exibir os comentários registrados juntamente com a informação sobre o produto orgânico 
- RF-09: O site deve permitir o cadastro do usuário para receber notificações de atualização de conteúdo.
- RF-14: O site deve permitir ao usuário visualizar o texto completo onde todos os detalhes da publicação sobre o produto orgânico são exibidos. 

Não Funcionais:

- RNF-02: O site deverá ser responsivo permitindo a visualização em um celular ou tablet de forma adequada
- RNF-03: O site deve permitir uma boa visualização dos elementos da página. 
- RNF-04: O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Opera, Microsoft Edge e outros)
- RNF-05: O site deve apresentar páginas dinâmicas com interatividade entre o usuário o sistema (empregar Javascript juntamente com HTML5 e CSS3).
- RNF-06: O site deverá ter uma interface simples e intuitiva para motivar e facilitar a sua utilização.

Artefatos da funcionalidade:

-	Informações.html;
-	Bootstrap.css;
-	Responsivo.css;
-	Style.css;
-	Style.css.map;
-	Style.scss;
-	Foto1.jgp;
-	Foto2.jgp;
-	Foto3.jpg;
-	Organico.jgp;
-	Pessoa1.png;
-	Pessoa2.png;
-	Pessoa3.png;
-	Facebook-logo-button.png;
-	Twitter-logo-button.png;
-	Linkedin.png
-	Intagram.png;
-	Mail.png;
-	Location.png;
-	Call.png;
-	Jquery-3.4.1.min.js;
-	Bootstrap.js;
-	Custom.js.


Telas da página de Informações:

![Cabeçalho padrão do site - Tela de Informações](/src/img/telas/artigoleparte1.png)  
##### *Figura 19 - Cabeçalho padrão so site, onde temos a parte do menu, contato, buscar*

![Conteúdo da tela de Informações](/src/img/telas/artigoleparte2.png) 
##### *Figura 20 - Contexto da tela, onde temos imagens para melhor visualização e diversas informações dos produtos, assim como sua regulamentação, certificação, cultivo, histórias e entre outros*

![Rodapé padrão do site - Tela de Informações](/src/img/telas/artigoleparte3.png) 
##### *Figura 21 - Parte onde contém as fontes, comentários das pessoas, contato, redes sociais, localizalção*


Estrutura de dados: As páginas seguem o padrão de formatação do template do site

HTML:

![Estrutura de dados inicial](/src/img/código/cabeçalho.png) 
##### *Figura 22 - Cabeçalho padrão do Site*

![Estrutura de dados do conteúdo do site](/src/img/código/cabeçalho2.png) 
##### *Figura 23 - Continuação do cabeçalho padrão do Site*

![Estrutura de dados do conteúdo do site](/src/img/código/contextoinfo.png) 
##### *Figura 24 - Contexto da tela de informações*

![Estrutura de dados do conteúdo do site](/src/img/código/fontesinfo.png) 
##### *Figura 25 - Código da parte de fontes*

![Estrutura de dados do conteúdo do site](/src/img/código/comentariosinfo.png) 
##### *Figura 26 - Código da parte de comentários*

![Estrutura de dados da parte ](/src/img/código/contato.png) 
##### *Figura 27 - Código da parte de contato, redes sociais e localização*

![Estrutura de dados inicial](/src/img/código/contato2.png) 
##### *Figura 28 - Código da parte de contato, redes sociais e localização*

Telas da página Sobre o Site (Feita por Leticia L. Pauli):

![Cabeçalho da Tela Sobre o Site](/src/img/telas/infosobresite.png) 
##### *Figura 29 - Cabeçalho padrão do site*

![Conteúdo e rodapé da Tela Sobre o Site](/src/img/telas/infosobresite2.png) 
##### *Figura 30 - Contexto da tela de Sobre o Site e rodapé padrão do site*

Estrutura de dados: As páginas seguem o padrão de formatação do template do site

HTML:

![Estrutura de dados do Cabeçalho](/src/img/código/cabeçalho.png) 
##### *Figura 31 - Cabeçalho padrão do Site*

![Estrutura de dados do Cabeçalho](/src/img/código/cabeçalho2.png) 
##### *Figura 32 - Continuação do cabeçalho padrão do Site*

![Estrutura de dados da parte ](/src/img/código/contextosobre.png) 
##### *Figura 33 - Contexto da tela Sobre o Site*

![Estrutura de dados inicial](/src/img/código/contato2.png) 
##### *Figura 34 - Contexto da tela Sobre o Site*

Telas da página de notícias e receitas no Site (Feito por Hélio Vieira Bernardes):

![Cabeçalho da Tela sobre Notícias](/src/img/telas/noticas.png)
#### *Figura 35 - Tela sobre Notícias

HTML:

![Estrutura de dados da parte ](/src/img/código/codigonoticias.png) 
##### *Figura 36 - Contexto da tela Nóticas*

![Cabeçalho da Tela sobre Receitas](/src/img/telas/receitas.png)
#### *Figura 37 - Tela sobre Receitas

HTML:

![Estrutura de dados da parte ](/src/img/código/codigoreceitas.png) 
##### *Figura 38 - Contexto da tela Receitas*

CSS: É tanto da página de Informações quanto da Sobre o Site:

![CSS da parte inicial](/src/img/código/CSS-FormataçãoSI.png.png) 
##### *Figura 39 - Estrutura de dados da parte de imagens e linhas*

![CSS da parte de imagens e linhas](/src/img/código/CSS-FormataçãoSI2.png.png) 
##### *Figura 40 - Estrutura de dados da formatação dos comentários*

![CSS da parte inicial](/src/img/código/CSS-FormataçãoSI3.png.png) 
##### *Figura 41 - Estrutura de dados da formatação dos comentários continuação do código*

