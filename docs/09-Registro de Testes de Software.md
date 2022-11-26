# Registro de Testes de Software

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>, <a href="8-Plano de Testes de Software.md"> Plano de Testes de Software</a>

Relatório com as evidências dos testes de software realizados no sistema pela equipe, baseado em um plano de testes pré-definido.

## Avaliação

Discorra sobre os resultados do teste. Ressaltando pontos fortes e fracos identificados na solução. Comente como o grupo pretende atacar esses pontos nas próximas iterações. Apresente as falhas detectadas e as melhorias geradas a partir dos resultados obtidos nos testes.

> **Links Úteis**:
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)



|Caso de Teste    | CT-01 - Visualizar links externos  | |
|-------|-------------------------|----|
| Requisitos Associados | RF-01 - O site deve oferecer links externos que permitam ao usuário visualizar as notícias, artigos e outras bibliografias de fontes externas (sources e backlinks). |  |
| Objetivo do Teste | Verificar se as fontes de notícias externos estão funcionando | |
| Passos | 1) Acessar o Navegador, 2) Informar o endereço do Site, 3) Visualizar as fontes da página |  |
| Critérios de Êxito | As informações sobre a fonte das informações externas trazidas à página estão funcionando corretamente. | |

![Teste 01](src/img/telas/teste01.png)  

|Caso de Teste    | CT-02 - Visualizar comentários   | |
|-------|-------------------------|----|
| Requisitos Associados | RF-07: O site deve permitir que usuários comentem na página de informação sobre um determinado produto orgânico;
RF-08: O site deve exibir os comentários registrados juntamente com a informação sobre o produto orgânico
 |  |
| Objetivo do Teste | Verificar se os comentários estão aparecendo | |
| Passos | 1) Acessar o Navegador, 2) Informar o endereço do Site, 3) Visualizar no final da página os comentários |  |
| Critérios de Êxito | Os comentários devem ser exibidos de forma correta no final da página; | |

![Teste 02](src/img/telas/teste02.png)  


|Caso de Teste    | CT-03 – Botão de buscar/pesquisar  | |
|-------|-------------------------|----|
| Requisitos Associados | RF-02: O site deve oferecer uma funcionalidade de filtro/pesquisa para permitir ao usuário localizar um produto específico que será informado na caixa de pesquisa. |  |
| Objetivo do Teste | Verificar se o botão de pesquisar está aparecendo na página | |
| Passos | 1) Acessar o Navegador, 2) Informar o endereço do Site, 3) Verificar se o botão de pesquisar está aparecendo |  |
| Critérios de Êxito | O botão de pesquisar está aparecendo corretamente no topo da página, com fácil acesso e visualização, não sendo escondido | |

![Teste 03](src/img/telas/teste03.png)  

|Caso de Teste    | CT-04 – Visualizar informações principais  | |
|-------|-------------------------|----|
| Requisitos Associados | RF-12 - O site deve apresentar, para cada produto orgânico, uma imagem correspondente (thumbnail). |  |
| Objetivo do Teste | Verificar se a carga de notícias está acontecendo corretamente | |
| Passos | 1) Acessar o Navegador, 2) Informar o endereço do Site, 3) Visualizar a página principal |  |
| Critérios de Êxito | As informações devem ser exibidas corretamente no site, sendo necessárias pelo menos 2 ou mais informações sendo apresentadas, as informações devem trazer imagens visíveis associadas ao assunto. | |

![Teste 04](src/img/telas/teste04.png)  
