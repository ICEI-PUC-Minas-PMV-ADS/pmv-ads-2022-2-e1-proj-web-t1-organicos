# Plano de Testes de Software

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>

Nesta seção vamos apresentar os diferentes cenários de testes utilizados na realização dos testes de nosso site sobre produtos orgânicos. O site ainda não foi hospedado em um servidor, então alguns requisitos funcionais e não funcionais não foram testados. Porém, para a próxima entrega esses RF e RNF serão devidadamente analisados e testados.

## Funcionalidades que serão testadas

|Funcionalidades     | Comportamento esperado |Verificações|
|--------------------|------------------------------------|----------------------------------------|
|RF-01           | O site deve oferecer links externos que permitam ao usuário visualizar as notícias, artigos e outras fontes externas (sources e backlinks)| Acesso dos links externos|
|RF-02           | O site deve oferecer uma funcionalidade de filtro/pesquisa para permitir ao usuário localizar um produto específico que será informado na caixa de pesquisa| O ícone pesquisar visível
|RF-03       | O site deve permitir visualizar as informações de contatos do mantenedor do site| Visualizar o perfil dos desenvolvedores do site | 
|RF-07       | O site deve permitir que usuários comentem na página de informação sobre um determinado produto orgânico| Ao realizar login o usuário pode realizar comentário. 
|RF-08       | O site deve exibir os comentários registrados juntamente com a informação sobre o produto orgânico| Os comentários devem ser exibidos adequadamente na página comentada.
|RF-09       | O site deve permitir o cadastro do usuário por meio de formulário para receber notificações de atualização de conteúdo| Cadastramento do usuário
|RF-12       | O site deve apresentar, para cada produto orgânico, uma imagem correspondente (thumbnail)| As imagens são visíveis e corresponde ao produto orgânico específicado.
|RF-13       | O site deve permitir manutenções constantes, as quais envolverão principalmente atualizações de informações sobre os produtos orgânicos| Facilidade de atualização de informações e imagens por meio dos arquivos HTML e css.

## Requisitos não funcionais que serão testados

|Funcionalidades     | Comportamento esperado |Verificações|
|--------------------|------------------------------------|----------------------------------------|
|RNF-02          | O site deverá ser responsivo permitindo a visualização em computadores, celulares ou tablets de diferentes tamanho| Adaptam o tamanho página ao tamanho das telas que estão sendo exibidos|
|RNF-03          | O site deve permitir uma boa visualização dos elementos da página| Todos os elementos da página são visíveis e nítidos
|RNF-05       | O site deve apresentar páginas dinâmicas com interatividade entre o usuário o sistema (empregar Javascript juntamente com HTML5 e CSS3)| As páginas do site são dinâmicas e adotam um visual moderno| 
|RNF-09       | O site deve apresentar um layout moderno e padronizado seguindo as recomendações da W3C| O design e estilo do site são modernos 

 
## Estratégia de Testes 

Serão executados os seguintes testes: 


 - Teste de Caixa Preta: Este é um teste onde não é necessário conhecer sobre a implementação e/ou arquitetura do software, são desconsideradas as análises de códigos fontes, focando nas funcionalidades do ponto de vista do usuário. Este teste foi escolhido porque permite visualizar a manifestação de bugs em tempo de execução da aplicação. Além disso, ele fornece uma visão de métricas de eficiência e eficácia com base na perspectiva da experiência trazida pelo uso, ou seja, o contato do usuário/tester com a aplicação já fornece uma visão geral sobre o comportamento do jogo. As funcionalidades serão testadas sob uma visão de alto nível para identificar se cada uma delas cumpre sua função dentro do site. 
 - Testes Manuais: Estes testes permitem a exploração de situações em diferentes ambientes. Visa a avaliação do design, a funcionalidade e o desempenho da aplicação. Todas as funcionalidades serão testadas manualmente. Este teste será executado junto aos testes de caixa preta. Ele foi escolhido por permitir os testes em condições semelhantes quando o sistema estiver em produção e por requerer baixo investimento por não precisar de ferramentas caras ou habilidades de alto nível para ser executado. Além disso, ele permite uma análise criteriosa e a possibilidade de avaliação com base em raciocínio e interpretação de caso a caso, aproveitando a capacidade humana de identificar, analisar e diagnosticar problemas. Nesta etapa, todos os testes que puderem ser automatizados serão testados manualmente. 


Vale ressaltar que neste momento não vamos utilizar testes automatizados e nem ferramentas de testes, porém estes serão usados durantes a finalização da próxima etapa do projeto.

##	Classificação de Bugs

Os Bugs serão classificados com as seguintes severidades:

|ID     | Nível de severidade |Descrição|
|--------------------|------------------------------------|----------------------------------------|
|1          | Gravíssimo| ●	Bug que bloqueia o teste da função ou gere crash na aplicação (site travar, mensagens sequências erros, perda do acesso); Botão não exerce a função determinada na modelagem, impossibilitando a aplicação dos testes da sua funcionalidade.
|2          | Grave| A funcionalidade não cumpre a sua função como esperado; Os Inputs não correspondem com as entradas. 
|3       | Moderado| Mensagens de erro ou de sair ou voltar no site; nem todas as funcionalidades do site são observadas; As funções não atingem todos os critérios de aceitação e não comprometerem a experiência final do usuário.
|4       | Pequena| Erros na interface do site; Erros ortográficos na parte visual do site; Presença de pequenos bugs que não atrapalham os objetivos das ferramentas.





