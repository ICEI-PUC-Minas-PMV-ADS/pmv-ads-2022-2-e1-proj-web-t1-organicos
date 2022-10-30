# Programação de Funcionalidades

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>, <a href="4-Metodologia.md"> Metodologia</a>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>, <a href="5-Arquitetura da Solução.md"> Arquitetura da Solução</a>

Nesta seção vamos descrever a implementação do sistema por meio dos requisitos funcionais e/ou não funcionais. Vamos relacionar os requisitos atendidos os artefatos criados (código fonte) além das estruturas de dados utilizadas e as instruções para acesso e verificação da implementação que deve estar funcional no ambiente de hospedagem.

Para cada requisito funcional, pode ser entregue um artefato e esses artefatos serão detalhados nesta seção

> **Links Úteis que foram consultados**:
>
> - [Trabalhando com HTML5 Local Storage e JSON](https://www.devmedia.com.br/trabalhando-com-html5-local-storage-e-json/29045)
> - [JSON Tutorial](https://www.w3resource.com/JSON)
> - [JSON Data Set Sample](https://opensource.adobe.com/Spry/samples/data_region/JSONDataSetSample.html)
> - [JSON - Introduction (W3Schools)](https://www.w3schools.com/js/js_json_intro.asp)
> - [JSON Tutorial (TutorialsPoint)](https://www.tutorialspoint.com/json/index.htm)


## Estrutura geral do site e seções de navegação (Autor Caio César )

A estrutura do site está sendo desenvolvida em HTML5, CSS e JavaScript. Para o desenvolvimento do site estamos utilizando uma ferramenta de apoio chamada Bootstrap. O Bootstrap é um framework front-end que fornece estruturas de CSS para a criação de sites e aplicações responsivas de forma rápida e simples. Até o momento, o framework tem nos auxiliado no desenvolvimento das principais características do site, incluindo a criação de excelentes estruturas de visualização e responsividade. Nas subseções abaixo vamos detalhar cada página com suas funcionalidades e estrutura de dados. Entretanto, vamos primeiramente apresentar uma lista geral dos principais requisitos e artefatos referente a estrutura geral do site que até o momento conseguimos desenvolver.

Requisitos Funcionais atendidos:

- RF-01: O site deve oferecer links externos que permitam ao usuário visualizar as notícias, artigos e outras bibliografias de fontes externas (sources e backlinks).
- RF-03: O site deve permitir visualizar as informações de contatos do mantenedor do site.
- RF-04: O site deve permitir o compartilhamento das informações visualizadas em plataformas de redes sociais (links ou botões). 
- RF-07: O site deve permitir que usuários comentem na página de informação sobre um determinado produto orgânico.
- RF-08: O site deve exibir os comentários registrados juntamente com a informação sobre o produto orgânico 
- RF-09: O site deve permitir o cadastro do usuário por meio de formulário para receber notificações de atualização de conteúdo.
- RF-12: O site deve apresentar, para cada produto orgânico, uma imagem correspondente (thumbnail).
- RF-13: O site deve permitir manutenções constantes, as quais envolverão principalmente atualizações de informações sobre os produtos orgânicos.
- RF-14: O site deve permitir ao usuário visualizar o texto completo onde todos os detalhes da publicação sobre o produto orgânico são exibidos. 

Requisitos Não Funcionais atendidos:

- RNF-02: O site deverá ser responsivo permitindo a visualização em um celular ou tablet de forma adequada.
- RNF-03: O site deve permitir uma boa visualização dos elementos da página. 
- RNF-04: O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Opera, Microsoft Edge e outros)
- RNF-05: O site deve apresentar páginas dinâmicas com interatividade entre o usuário o sistema (empregar Javascript juntamente com HTML5 e CSS3).
- RNF-06: O site deverá ter uma interface simples e intuitiva para motivar e facilitar a sua utilização.
- RNF-09: O site deve apresentar um layout moderno e padronizado seguindo as recomendações da W3C.

Artefatos gerais da funcionalidade:

-	index.html;
-	about.html;
-	fruit.html;
-	informações.html;
-	infosobresite;
-	contact.html;
-	testimonial.html;
-	noticiash.html;
-	Bootstrap.css;
-	Responsivo.css;
-	Style.css;
-	Style.css.map;
-	Style.scss;
- slider-img.jpg;
-	about-img.jpg;
-	f-1.jpg;
-	f-2.jpg;
-	f-3.jpg;
-	f-4.jpg;
-	f-5.jpg;
-	f-6.jpg;
-	horta-organica-1.jpg;
-	foto1.jpg;
-	foto2.jpg;
-	foto3.jpg;
-	organico.jpg;
-	pessoa1.png;
-	pessoa2.png;
-	pessoa3.png
-	caiocesar.jpg;
-	left-quote.png;
-	right-quote.png;
-	leticiaperfil.jpg;
-	helioperfil.jpg;
-	herbet.png;
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

Estrutura de dados do Boostrap que foi utilizado no desenvolvimento do site.

![Bootstrap 1](/src/img/bootstrap/Bootstrap1.png)  
##### *Figura 19 - Estrutura do Bootstrap empregado. Em virtude do arquivo conter várias linhas de código são exibidas apenas as primeiras linhas. 

Estrutura de dados do CSS: 

![Arquivo CSS](/src/img/código/csshtml.png)  
##### *Figura 20 - Estrutura do CSS (arquivo style.css) desenvolvida. Em virtude do arquivo conter várias linhas de código são exibidas apenas as primeiras linhas do documento.


**1 - HomePage** 

Tela do homepage:

![Cabeçalho padrão do site - Tela de Informações](/src/img/telas/homepage.png)  
##### *Figura 21 - Cabeçalho do site com os itens de navegação*

Requisitos Funcionais atendidos:

- RF-03: O site deve permitir visualizar as informações de contatos do mantenedor do site
- RF-04: O site deve permitir o compartilhamento das informações visualizadas em plataformas de redes sociais (links ou botões). 
- RF-09: O site deve permitir o cadastro do usuário por meio de formulário para receber notificações de atualização de conteúdo.
- RF-12: O site deve apresentar, para cada produto orgânico, uma imagem correspondente (thumbnail).
- RF-13: O site deve permitir manutenções constantes, as quais envolverão principalmente atualizações de informações sobre os produtos orgânicos.
- RF-14: O site deve permitir ao usuário visualizar o texto completo onde todos os detalhes da publicação sobre o produto orgânico são exibidos. 

Requisitos Não Funcionais atendidos:

- RNF-02: O site deverá ser responsivo permitindo a visualização em um celular ou tablet de forma adequada.
- RNF-03: O site deve permitir uma boa visualização dos elementos da página. 
- RNF-04: O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Opera, Microsoft Edge e outros)
- RNF-05: O site deve apresentar páginas dinâmicas com interatividade entre o usuário o sistema (empregar Javascript juntamente com HTML5 e CSS3).
- RNF-06: O site deverá ter uma interface simples e intuitiva para motivar e facilitar a sua utilização.
- RNF-09: O site deve apresentar um layout moderno e padronizado seguindo as recomendações da W3C.

Artefatos da funcionalidade:

-	index.html;
-	Bootstrap.css;
-	Responsivo.css;
-	Style.css;
-	Style.css.map;
-	Style.scss;
-	slider-img.jpg;
-	about-img.jpg;
-	f-1.jpg;
-	f-2.jpg;
-	f-3.jpg;
-	f-4.jpg;
-	f-5.jpg;
-	f-6.jpg;
-	caiocesar.jpg;
-	left-quote.png;
-	right-quote.png;
-	leticiaperfil.jpg;
-	helioperfil.jpg;
-	herbet.png;
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

Estrutura do HTML:

![Cabeçalho padrão do site - homepage](/src/img/código/cabeçalhohtml.png)  
##### *Figura 21 - Cabeçalho do site com os itens de navegação*

![slider - homepage](/src/img/código/cabeçalhohtml.png)  
##### *Figura 22 - HTML do cabeçalho do site*

![slider - homepage](/src/img/código/sliderhtml.png)  
##### *Figura 23 - HTML do Slider do site*

![navegação - homepage](/src/img/código/navegaçãohtml.png)  
##### *Figura 24 - HTML dos itens de navegação do site*

![Destaues - homepage](/src/img/código/destaqueshtml.png)  
##### *Figura 25 - HTML dos destaques*



**2 - Sobre o site** 

Tela sobre o site:

![Cabeçalho padrão do site - Tela de Informações](/src/img/telas/sobreosite.png)  
##### *Figura 25 - Página sobre o site*

Requisitos Funcionais atendidos:

- RF-04: O site deve permitir o compartilhamento das informações visualizadas em plataformas de redes sociais (links ou botões). 
- RF-12: O site deve apresentar, para cada produto orgânico, uma imagem correspondente (thumbnail).
- RF-13: O site deve permitir manutenções constantes, as quais envolverão principalmente atualizações de informações sobre os produtos orgânicos.
- RF-14: O site deve permitir ao usuário visualizar o texto completo onde todos os detalhes da publicação sobre o produto orgânico são exibidos. 

Requisitos Não Funcionais atendidos:

- RNF-02: O site deverá ser responsivo permitindo a visualização em um celular ou tablet de forma adequada.
- RNF-03: O site deve permitir uma boa visualização dos elementos da página. 
- RNF-04: O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Opera, Microsoft Edge e outros)
- RNF-05: O site deve apresentar páginas dinâmicas com interatividade entre o usuário o sistema (empregar Javascript juntamente com HTML5 e CSS3).
- RNF-06: O site deverá ter uma interface simples e intuitiva para motivar e facilitar a sua utilização.
- RNF-09: O site deve apresentar um layout moderno e padronizado seguindo as recomendações da W3C.

Artefatos da funcionalidade:

-	about.html;
-	Bootstrap.css;
-	Responsivo.css;
-	Style.css;
-	Style.css.map;
-	Style.scss;
-	about-img.jpg;
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

Estrutura do HTML:

![Informação - sobre o site](/src/img/código/sobreositehtml.png)  
##### *Figura 26 - HTML da página de informação sobre o site*

**3 - Produtos** 

Tela sobre os produtos:

![artigos sobre produtos - Tela de produtos](/src/img/telas/artigos.png)  
##### *Figura 27 - Página com imagens e artigos sobre produtos orgânicos *

Requisitos Funcionais atendidos:

- RF-04: O site deve permitir o compartilhamento das informações visualizadas em plataformas de redes sociais (links ou botões). 
- RF-12: O site deve apresentar, para cada produto orgânico, uma imagem correspondente (thumbnail).
- RF-13: O site deve permitir manutenções constantes, as quais envolverão principalmente atualizações de informações sobre os produtos orgânicos.
- RF-14: O site deve permitir ao usuário visualizar o texto completo onde todos os detalhes da publicação sobre o produto orgânico são exibidos. 

Requisitos Não Funcionais atendidos:

- RNF-02: O site deverá ser responsivo permitindo a visualização em um celular ou tablet de forma adequada.
- RNF-03: O site deve permitir uma boa visualização dos elementos da página. 
- RNF-04: O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Opera, Microsoft Edge e outros)
- RNF-05: O site deve apresentar páginas dinâmicas com interatividade entre o usuário o sistema (empregar Javascript juntamente com HTML5 e CSS3).
- RNF-06: O site deverá ter uma interface simples e intuitiva para motivar e facilitar a sua utilização.
- RNF-09: O site deve apresentar um layout moderno e padronizado seguindo as recomendações da W3C.

Artefatos da funcionalidade:

-	fruit.html;
-	Bootstrap.css;
-	Responsivo.css;
-	Style.css;
-	Style.css.map;
-	Style.scss;
-	f-1.jpg;
-	f-2.jpg;
-	f-3.jpg;
-	f-4.jpg;
-	f-5.jpg;
-	f-6.jpg;
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

Estrutura do HTML:

![Artigos sobre produtos - produtos](/src/img/código/artigoshtml.png)  
##### *Figura 28 - HTML da página de artigos sobre produtos orgânicos.


**4 - Desenvolvedores** 

Tela sobre os desenvolvedores:

![perfil - Tela sobre os desenvolvedores](/src/img/telas/desenvolvedores.png)  
##### *Figura 29 - Página dos desenvolvedores*

Requisitos Funcionais atendidos:
- RF-03: O site deve permitir visualizar as informações de contatos do mantenedor do site.
- RF-04: O site deve permitir o compartilhamento das informações visualizadas em plataformas de redes sociais (links ou botões). 

Requisitos Não Funcionais atendidos:

- RNF-02: O site deverá ser responsivo permitindo a visualização em um celular ou tablet de forma adequada.
- RNF-03: O site deve permitir uma boa visualização dos elementos da página. 
- RNF-04: O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Opera, Microsoft Edge e outros)
- RNF-05: O site deve apresentar páginas dinâmicas com interatividade entre o usuário o sistema (empregar Javascript juntamente com HTML5 e CSS3).
- RNF-06: O site deverá ter uma interface simples e intuitiva para motivar e facilitar a sua utilização.
- RNF-09: O site deve apresentar um layout moderno e padronizado seguindo as recomendações da W3C.

Artefatos da funcionalidade:

-	testimonial.html;
-	Bootstrap.css;
-	Responsivo.css;
-	Style.css;
-	Style.css.map;
-	Style.scss;
-	caiocesar.jpg;
-	left-quote.png;
-	right-quote.png;
-	leticiaperfil.jpg;
-	helioperfil.jpg;
-	herbet.png;
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

Estrutura do HTML:

![Artigos sobre produtos - produtos](/src/img/código/desenvolvedoreshtml.png)  
##### *Figura 30 - HTML da página dos desenvolvedores do site


**5 - Contato** 

Tela de contato:

![perfil - Tela com formulário de contato](/src/img/telas/contato.png)  
##### *Figura 31 - Página com formulário de contato e mapa de localização*

Requisitos Funcionais atendidos:
- RF-03: O site deve permitir visualizar as informações de contatos do mantenedor do site.
- RF-04: O site deve permitir o compartilhamento das informações visualizadas em plataformas de redes sociais (links ou botões). 
- RF-09: O site deve permitir o cadastro do usuário por meio de formulário para receber notificações de atualização de conteúdo.

Requisitos Não Funcionais atendidos:

- RNF-02: O site deverá ser responsivo permitindo a visualização em um celular ou tablet de forma adequada.
- RNF-03: O site deve permitir uma boa visualização dos elementos da página. 
- RNF-04: O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Opera, Microsoft Edge e outros)
- RNF-05: O site deve apresentar páginas dinâmicas com interatividade entre o usuário o sistema (empregar Javascript juntamente com HTML5 e CSS3).
- RNF-06: O site deverá ter uma interface simples e intuitiva para motivar e facilitar a sua utilização.
- RNF-09: O site deve apresentar um layout moderno e padronizado seguindo as recomendações da W3C.

Artefatos da funcionalidade:

-	contato.html;
-	Bootstrap.css;
-	Responsivo.css;
-	Style.css;
-	Style.css.map;
-	Style.scss;
-	Link do mapa do google;
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

Estrutura do HTML:

![Artigos sobre produtos - produtos](/src/img/código/contatohtml.png)  
##### *Figura 32 - HTML da página com formulário de contato e mapa de localização.

**5 - Rodapé do site e redes sociais** 

Tela de rodapé:

![perfil - Tela com formulário de contato](/src/img/telas/rodape.png)  
##### *Figura 33 - Página com rodapé e compartilhamente em rede sociais*

Requisitos Funcionais atendidos:
- RF-04: O site deve permitir o compartilhamento das informações visualizadas em plataformas de redes sociais (links ou botões). 


Requisitos Não Funcionais atendidos:

- RNF-02: O site deverá ser responsivo permitindo a visualização em um celular ou tablet de forma adequada.
- RNF-03: O site deve permitir uma boa visualização dos elementos da página. 
- RNF-04: O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Opera, Microsoft Edge e outros)
- RNF-05: O site deve apresentar páginas dinâmicas com interatividade entre o usuário o sistema (empregar Javascript juntamente com HTML5 e CSS3).
- RNF-06: O site deverá ter uma interface simples e intuitiva para motivar e facilitar a sua utilização.
- RNF-09: O site deve apresentar um layout moderno e padronizado seguindo as recomendações da W3C.

Artefatos da funcionalidade:

-	index.html;
-	about.html;
-	fruit.html;
-	informações.html;
-	contact.html;
-	testimonial.html;
-	noticiash.html;
-	infosobresite;
-	Bootstrap.css;
-	Responsivo.css;
-	Style.css;
-	Style.css.map;
-	Style.scss;
-	Link do mapa do google;
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

Estrutura do HTML:

![icones - rodapé](/src/img/código/rodapehtml.png)  
##### *Figura 34 - HTML do rodapé padrão do site.

![img - rede social](/src/img/código/redesocialhtml.png)  
##### *Figura 35 - HTML das redes sociais (sem links por enquanto).






## Página sobre o site e tela de informações (autora Leticia L. Pauli)

- Tela de Informações: é apresentado em destaque as informações gerais sobre produtos orgânicos, como seu cultivo, certificação, regulamentação, história, entre outras, também é acrescentado o link das fontes.

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
##### *Figura 36 - Cabeçalho padrão so site, onde temos a parte do menu, contato, buscar*

![Conteúdo da tela de Informações](/src/img/telas/artigoleparte2.png) 
##### *Figura 37 - Contexto da tela, onde temos imagens para melhor visualização e diversas informações dos produtos, assim como sua regulamentação, certificação, cultivo, histórias e entre outros*

![Rodapé padrão do site - Tela de Informações](/src/img/telas/artigoleparte3.png) 
##### *Figura 38 - Parte onde contém as fontes, comentários das pessoas, contato, redes sociais, localizalção*


Estrutura de dados: As páginas seguem o padrão de formatação do template do site

HTML:

![Estrutura de dados do conteúdo do site](/src/img/código/contextoinfo.png) 
##### *Figura 39 - Contexto da tela de informações*

![Estrutura de dados do conteúdo do site](/src/img/código/fontesinfo.png) 
##### *Figura 40 - Código da parte de fontes*

![Estrutura de dados do conteúdo do site](/src/img/código/comentariosinfo.png) 
##### *Figura 41 - Código da parte de comentários*


Telas da página Sobre o Site (Feita por Leticia L. Pauli):

![Conteúdo e rodapé da Tela Sobre o Site](/src/img/telas/infosobresite2.png) 
##### *Figura 42 - Contexto da tela de Sobre o Site e rodapé padrão do site*

Estrutura de dados: As páginas seguem o padrão de formatação do template do site

HTML:

![Estrutura de dados da parte ](/src/img/código/contextosobre.png) 
##### *Figura 43 - Contexto da tela Sobre o Site*

![Estrutura de dados inicial](/src/img/código/contato2.png) 
##### *Figura 44 - Contexto da tela Sobre o Site*


CSS: É tanto da página de Informações quanto da Sobre o Site:

![CSS da parte inicial](/src/img/código/CSS-FormataçãoSI.png) 
##### *Figura 45 - Estrutura de dados da parte de imagens e linhas*

![CSS da parte de imagens e linhas](/src/img/código/CSS-FormataçãoSI2.png) 
##### *Figura 46 - Estrutura de dados da formatação dos comentários*

![CSS da parte inicial](/src/img/código/CSS-FormataçãoSI3.png) 
##### *Figura 47 - Estrutura de dados da formatação dos comentários continuação do código*

## Página sobre as notícias (autor Hélio)

![Conteúdo e rodapé da Tela Sobre o Site](/src/img/telas/noticias.png) 
##### *Figura 48 - Contexto da tela de Sobre nas Notícias*

HTML

![Estrutura de dados da parte ](/src/img/código/codigonoticias.png) 
##### *Figura 43 - Contexto da tela Sobre o Site nas Notícias*

## Página sobre as receitas (autor Herbet)

