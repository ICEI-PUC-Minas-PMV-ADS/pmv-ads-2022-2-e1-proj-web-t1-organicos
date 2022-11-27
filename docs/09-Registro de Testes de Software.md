# Registro de Testes de Software

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>, <a href="8-Plano de Testes de Software.md"> Plano de Testes de Software</a>

Relatório com as evidências dos testes de software realizados no sistema pela equipe, baseado em um plano de testes pré-definido.

## Avaliação 

### Testes realizados (Caio)

|ID do caso de teste    | CT 01 - Visualizar informações dos desenvolvedores do site| 
|-------|-------------------------|
| Requisitos Associados |RF-03 |  
| Objetivo do Teste | Verificar se é exibido corretamente as informações sobre os desenvolvedores do site|
| Passos | 1) Ir na barra de navegação e clicar em desenvolvedores 2) Verificar se as informações dos desenvolvedores estão sendo exibidas corretamente 3) Testar se a classe carrousel está funcionando em exibir corretamente o perfil dos desenvolvedores |
| Resultados|As informações sobre os desenvolvedores estão sendo exibidas corretamente. Ao clicar no botão próximo é exibido a foto e as informações do próximo desenvolvedor e ao clicar no botão anterior é exibido a foto e as informações do desenvolvedor anterior. Esta página não apresentou nenhum bug.| 

![Resultado](/src/img/dev1.png) 
![Resultado](/src/img/dev2.png) 

ID do caso de teste    | CT 02 - Funcionalidade de filtro e caixa de pesquisa| 
|-------|-------------------------|
| Requisitos Associados |RF-02 |  
| Objetivo do Teste | Verificar se o botão de pesquisar está funcionando na página|
| Passos | 1) clicar em pesquisar e digitar algum item para busca|
| Resultados|O botão e o campo pesquisar não estão funcionando corretamente. Ao clicar no ícone não aparece nenhum campo de pesquisa. É necessário implementar essa funcionalidade no HTML e Js. De acordo com nossa classificação de bug esse é um bug grave, porém fácil de implementar. |

![Resultado](/src/img/navpesquisa.png) 



|ID do caso de teste    | CT 03 - Realização de manutenção constante no site| 
|-------|-------------------------|
| Requisitos Associados |RF-13 |  
| Objetivo do Teste | Verificar o site permite manutenções constantes|
| Passos | Verificar se os arquivos HTML, CSS e Js podem ser atualizados sem nenhum impedimento|
| Resultados|O site presenta facilidade de atualização de informações e imagens por meio dos arquivos HTML e CSS| 

![Resultado](/src/img/manutenção.png) 


|ID do caso de teste    | CT 04 - Responsividade do site| 
|-------|-------------------------|
| Requisitos Associados |RNF-02|  
| Objetivo do Teste | Verificar a responsividade do site|
| Passos | Alterar as dimensões da tela e observar se o site se adapta as variações das dimensões da tela|
| Resultados|O site é responsivo e não perde a formatação de layout em diferentes tamanho de telas.| 

![Resultado](/src/img/resp1.png) 

![Resultado](/src/img/resp2.png) 


|ID do caso de teste    | CT 05 - Visualização dos elementos da página| 
|-------|-------------------------|
| Requisitos Associados |RNF-02|  
| Objetivo do Teste | Verificar os elementos da página são vísiveis|
| Passos | Visualizar se os elementos das páginas são nitídos, mesmo em diferentes tamanho de telas|
| Resultados|Todos os elementos da página são visíveis e nítidos.|

![Resultado](/src/img/elem1.png) 

![Resultado](/src/img/elem2.png) 
 


### Testes realizados (Letícia)
|Caso de Teste    | CT-06 - Visualizar links externos  | |
|-------|-------------------------|----|
| Requisitos Associados | RF-01 - O site deve oferecer links externos que permitam ao usuário visualizar as notícias, artigos e outras bibliografias de fontes externas (sources e backlinks). |  |
| Objetivo do Teste | Verificar se as fontes de notícias externos estão funcionando | |
| Passos | 1) Acessar o Navegador, 2) Informar o endereço do Site, 3) Visualizar as fontes da página |  |
| Critérios de Êxito | As informações sobre a fonte das informações externas trazidas à página estão funcionando corretamente. | |

![Resultado](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e1-proj-web-t1-organicos/blob/main/src/img/telas/teste01.png)  
![Resultado](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e1-proj-web-t1-organicos/blob/main/src/img/telas/teste02.png) 

|Caso de Teste    | CT-07 - Visualizar comentários   | |
|-------|-------------------------|----|
| Requisitos Associados | RF-07: O site deve permitir que usuários comentem na página de informação sobre um determinado produto orgânico;
RF-08: O site deve exibir os comentários registrados juntamente com a informação sobre o produto orgânico
 |  |
| Objetivo do Teste | Verificar se os comentários estão aparecendo | |
| Passos | 1) Acessar o Navegador, 2) Informar o endereço do Site, 3) Visualizar no final da página os comentários |  |
| Critérios de Êxito | Os comentários devem ser exibidos de forma correta no final da página; | |

 ![Resultado](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e1-proj-web-t1-organicos/blob/main/src/img/telas/teste03.png)  

|Caso de Teste    | CT-08 – Botão de buscar/pesquisar  | |
|-------|-------------------------|----|
| Requisitos Associados | RF-02: O site deve oferecer uma funcionalidade de filtro/pesquisa para permitir ao usuário localizar um produto específico que será informado na caixa de pesquisa. |  |
| Objetivo do Teste | Verificar se o botão de pesquisar está aparecendo na página | |
| Passos | 1) Acessar o Navegador, 2) Informar o endereço do Site, 3) Verificar se o botão de pesquisar está aparecendo |  |
| Critérios de Êxito | O botão de pesquisar está aparecendo corretamente no topo da página, com fácil acesso e visualização, não sendo escondido | |

![Resultado](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e1-proj-web-t1-organicos/blob/main/src/img/telas/teste04.png) 

|Caso de Teste    | CT-09 – Visualizar informações principais  | |
|-------|-------------------------|----|
| Requisitos Associados | RF-12 - O site deve apresentar, para cada produto orgânico, uma imagem correspondente (thumbnail). |  |
| Objetivo do Teste | Verificar se a carga de notícias está acontecendo corretamente | |
| Passos | 1) Acessar o Navegador, 2) Informar o endereço do Site, 3) Visualizar a página principal |  |
| Critérios de Êxito | As informações devem ser exibidas corretamente no site, sendo necessárias pelo menos 2 ou mais informações sendo apresentadas, as informações devem trazer imagens visíveis associadas ao assunto. | |

 
![Resultado](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e1-proj-web-t1-organicos/blob/main/src/img/telas/teste05.png)
![Resultado](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e1-proj-web-t1-organicos/blob/main/src/img/telas/teste06.png)
![Resultado](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e1-proj-web-t1-organicos/blob/main/src/img/telas/teste12.png)

|Caso de Teste    | CT-10 – Permitir cadastro de usuário  | |
|-------|-------------------------|----|
| Requisitos Associados | RF-09 - O site deve permitir o cadastro do usuário para receber notificações de atualização de conteúdo. |  |
| Objetivo do Teste |Verificar se o cadastro de usuário está funcionando corretamente | |
| Passos | 1) Acessar o Navegador, 2) Informar o endereço do Site, 3) Acessar o cadastro, 4) Tentar cadastrar |  |
| Critérios de Êxito | 	O cadastro está funcionando corretamente;
Não permite deixar campos necessários em branco
	Quando coloca um CEP válido, o mesmo puxa o endereço automaticamente, sendo assim o usuário não precisa ficar preenchendo tudo. | |
 

 ![Resultado](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e1-proj-web-t1-organicos/blob/main/src/img/telas/teste07.png)
 
 ![Resultado](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e1-proj-web-t1-organicos/blob/main/src/img/telas/teste08.png)
 
 ![Resultado](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e1-proj-web-t1-organicos/blob/main/src/img/telas/teste09.png)
 
 ![Resultado](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e1-proj-web-t1-organicos/blob/main/src/img/telas/teste10.png)
 
 ![Resultado](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e1-proj-web-t1-organicos/blob/main/src/img/telas/teste11.png)
 
