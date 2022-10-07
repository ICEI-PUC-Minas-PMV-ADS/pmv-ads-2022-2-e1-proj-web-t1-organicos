# Arquitetura da Solução

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>

Nesta seção são apresentados os detalhes técnicos da solução criada pela equipe, tratando dos componentes que fazem parte da solução e do ambiente de hospedagem da solução.

## Diagrama de componentes

Diagrama que permite a modelagem física de um sistema, através da visão dos seus componentes e relacionamentos entre os mesmos. Na figura 2 apresentamos os componetes que fazem parte da solução. 

Exemplo: 

![Diagrama de Componentes](/docs/img/organicocomponentes.jpg)
<center>Figura 2 - Arquitetura da Solução</center>

A solução implementada conta com os seguintes módulos:
- **Navegador** - Interface básica do sistema  
  - **Páginas Web** - Conjunto de arquivos HTML, CSS, JavaScript e imagens que implementam as funcionalidades do sistema.
   - **Armazenamento local** - armazenamento mantido no Navegador, onde são implementados bancos de dados baseados em JSON. São eles: 
     - **Informações** - seções de notícias apresentadas 
     - **Comentários** - registro de opiniões dos usuários sobre as notícias
     - **salvas** - lista de notícias mantidas para leitura e acesso posterior
     - **Perfil do produtor** - perfil dos produtores rurais da região
 - **Bootstrap** - Auxilia na responsividade e em algumas funcionalidades do site;
 - **Produtos API** - plataforma que o cadastro dos produtos
 - **Notícias API**- permite o acesso às notícias exibidas no site.
 - **Hospedagem** - local na Internet onde as páginas são mantidas e acessadas pelo navegador. 


## Tecnologias Utilizadas

As tecnologias utilizadas para desenvolvimento da Aplicação Web Front-End são:

- Visual Studio Code
- Bootstrap e similares
- GitHub
- Invision, Figma e Mirror

Para elaboração e desenvolvimento da Aplicação Web Front-End utilizamos as seguintes linguagens de programação e marcarção:

- HTML;
- CSS;
- JavaScript;


## Hospedagem

O site irá utilizar a plataforma Heroku como ambiente de hospedagem do site do projeto. 

> **Links que serão consultados **:
>
> - [Website com GitHub Pages](https://pages.github.com/)
> - [Programação colaborativa com Repl.it](https://repl.it/)
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Publicando Seu Site No Heroku](http://pythonclub.com.br/publicando-seu-hello-world-no-heroku.html)
