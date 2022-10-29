# Template padrão do site

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>, <a href="4-Metodologia.md"> Metodologia</a>

Um template, também chamado de tema, atribui ao site o aspecto visual e também funcionalidades que otimizem a sua performance.  O template do site desenvolvido por nossa equipe foi atualizado e seguirá um padrão um pouco diferente dos wireframes (serão atualizados) apresentados na seção de projeto de interface.   O padrão de layout segue conforme a figura 9 abaixo.

![Logo do site](/src/img/telas/homepage.png)  
##### *Figura 09 - homepage*

A tela acima é o homepage inicial de nosso site. Nele está condito um slider com uma <a href="(/src/img/telas/homepage.png)">foto</a> sobre produtos 
 composto pelos seguintes botões de navegação na aba de homepage:

- Home

- sobre o site;  

- produtos

- noticias;  

- desenvolvedores;  

- contato;  

- login;

- Rodapé  

A responsividade segue o padrão do Bootstrap. 

**1 - Home:**

Home é idenficado pelo arquivo *index.html*. Essa página contém basicamente todos os outros itens da barra de navegação. Ao clicar em home ocorre o carregamento de todas as informações do site em uma única página. O primeiro item no homepage é o destaque da semana, onde ao clicar na imagem o usuário será direcionado para uma página que destaca as principais noticíais, artigos e produtos favoritados na semana.

**2 - sobre o site:**
Ao cliar no item "sobre o site" na barra de navegação, o usuário será direcionado para a seguinte página (arquivo *about.html*) mostrada na figura 10.

![Logo do site](/src/img/telas/sobreosite.png)  
##### *Figura 10 - Informações sobre o site*

E o clicar em leia mais, outra página (arquivo *infosobresite.html*) irá carregar com as informações sobre o site, conforme mostra a figura 11
![Logo do site](/src/img/telas/infosobresite.png)  
##### *Figura 11 - Página descrevendo detalhadamente o site*

**3 - Produtos:**

Ao clicar em produtos, o usuário será direcionado a página de artigos (arquivo *fruit.html*) que armazena fotos e informações sobre os produtos orgânicos, conforme mostra a figura 12.

![produtos](/src/img/telas/artigos.png)  
##### *Figura 12 - Página contendo imagens associadas a links de leitura sobre os produtos orgânicos*

Clicando no botão mais informações de um certo produto orgânico, o usuário será direcionado para uma página (arquivo *informações.html*) onde são detalhadas informações específicas sobre o produto orgânico de interesse. As figuras 13, 14 e 15 mostram o inicio, meio e fim dessa página que inclusive exibe os comentários das personas que visitam a página. 

![artigoparte1](/src/img/telas/artigoleparte1.png)  
##### *Figura 13 - Parte inicial da página de informações sobre produtos orgânicos*

![artigoparte2](/src/img/telas/artigoleparte2.png)  
##### *Figura 14 - Parte do meio da página de informações sobre produtos orgânicos*

![artigoparte3](/src/img/telas/artigoleparte3.png)  
##### *Figura 15 - Parte final e decomentários das personas*

**4 - Noticias:**
Ao clicar em notícias, o usuário é levada a uma página (arquivo *noticiash.html*) que contem links de diversas fontes sobre determinados produtos orgânicos. O print desta tela é mostrado na figura 16.
![noticias](/src/img/telas/noticiash.png)  
##### *Figura 16 - Página de notícias e links externos*

**5 - Desenvolvedores:**
Nesta página (arquivo *testimonial.html*) são exibidas informações de perfil profissional sobre os desenvolvedores do site. O print desta tela é mostrado na figura 17.
![desenvolvedores](/src/img/telas/desenvolvedores.png)  
##### *Figura 17 - Página onde são exibidas informações sobre os desenvolvedores do site*

**6 - Contato:**
Nesta página (arquivo *contact.html*) uma formulario de contato é aberto. Nele o usuário pode inserir suas informações para contato. O print desta tela é mostrado na figura 18.
![contato](/src/img/telas/contato.png)  
##### *Figura 18 - Formulário de contato*

**7 - Login:**
Essa página ainda está em desenvolvimento.

**8 - Rodapé:**
Página de rodapé padrão do site (presente em todas as páginas), onde estão exibidas as principais formas de contato e os links externos para as redes sociais do site.O print desta tela é mostrado na figura 19.

![rodape](/src/img/telas/rodape.png)  
##### *Figura 19 - Rodapé padrão do site*


Layout padrão do site (HTML e CSS) que será utilizado em todas as páginas com a definição de identidade visual, aspectos de responsividade e iconografia.



> **Links que foram consultados**:
>
> - [CSS Website Layout (W3Schools)](https://www.w3schools.com/css/css_website_layout.asp)
> - [Website Page Layouts](http://www.cellbiol.com/bioinformatics_web_development/chapter-3-your-first-web-page-learning-html-and-css/website-page-layouts/)
> - [Perfect Liquid Layout](https://matthewjamestaylor.com/perfect-liquid-layouts)
> - [How and Why Icons Improve Your Web Design](https://usabilla.com/blog/how-and-why-icons-improve-you-web-design/)
