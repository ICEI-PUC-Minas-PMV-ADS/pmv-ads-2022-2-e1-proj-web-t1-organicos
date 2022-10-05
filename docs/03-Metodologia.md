
# Metodologia

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Documentação de Especificação</a></span>

Nesta seção vamos detalhar as ferramentas que a equipe de desenvolvimento vem utilizando para a manutenção dos códigos e demais artefatos que estão sendo usados para a organização do time na execução das tarefas do projeto. 

## Relação de ambientes de trabalho
Os artefatos do projeto serão desenvenvolvidos a partir das plataformas GitHub e Invision, e a relação dos ambientes está apresentada na tabela abaixo.

|Ambiente     | Plataforma  |Link de acesso |
|-------|-------------------------|----|
| Repositório de código fonte | GitHub | <https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e1-proj-web-t1-organicossim> |
| Design de Interfaces | InVision | https://hliobernardes751344.invisionapp.com/freehand/orgnicos-5FirhG6Zw|
| Gerenciamento do Projeto | GitHub | <https://github.com/orgs/ICEI-PUC-Minas-PMV-ADS/projects/176> |
| Comunicação e Reuniões | Microsoft Teams | <https://teams.microsoft.com>|

## Controle de Versão

A ferramenta de controle de versão adotada no projeto foi o
[Git](https://git-scm.com/), sendo que o [Github](https://github.com)
foi utilizado para hospedagem do repositório e gerenciamento de tarefas no Project.

O projeto segue a seguinte convenção para o nome de branches:

- `main`: versão estável já testada do software
- `unstable`: versão já testada do software, porém instável
- `testing`: versão em testes do software
- `dev`: versão de desenvolvimento do software
- 
Algumas branches específicas serão criadas pelos desenvolvedores e poderão ser mescladas a main principal deste que os pull requests sejam análisados e válidados por todo o time desenvolvimento.

Quanto à gerência de issues, o projeto está adotando a seguinte convenção padrão para
etiquetas:

- `documentation`: melhorias ou acréscimos à documentação
- `bug`: uma funcionalidade encontra-se com problemas
- `enhancement`: uma funcionalidade precisa ser melhorada
- `feature`: uma nova funcionalidade precisa ser introduzida
- `duplicate`: Quando a issue ou pull request já existe
- `help wanted`: atenção extra é requerida
- `invalid`: não parece válido
- `question`: mais informação é requerida
- `wontfix`: isto não irá funcionar

Discuta como a configuração do projeto foi feita na ferramenta de versionamento escolhida. Exponha como a gerência de tags, merges, commits e branchs é realizada. Discuta como a gerência de issues foi realizada.

> **Links Úteis que foram utilizados como material de consulta para a elaboração desta seção**:
> - [Tutorial GitHub](https://guides.github.com/activities/hello-world/)
> - [Git e Github](https://www.youtube.com/playlist?list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA)
>  - [Comparando fluxos de trabalho](https://www.atlassian.com/br/git/tutorials/comparing-workflows)
> - [Understanding the GitHub flow](https://guides.github.com/introduction/flow/)
> - [The gitflow workflow - in less than 5 mins](https://www.youtube.com/watch?v=1SXpE08hvGs)

## Gerenciamento de Projeto
A equipe está utilizando as metodologias ágeis, tendo escolhido o Scrum como base para a definição do processo de desenvolvimento. O Scrum é um das formas de utilizar métodos ágeis em seus projetos e tem como principal objetivo auxiliar na gestão e no desenvolvimento de projetos que tenham um prazo curto de entrega. Em virtude disso, estamos empregando essa ferramenta de gestão a fim de agregar praticidade na gestão de desenvolvimento do site, aumentando a eficiência e agilidade na entrega do produto. Conforme o Scrum demanda, o projeto de desenvolvimento do site está sendo divida em etapas, onde o ciclos de atividades (Sprints) estão sendo feitos a cada 7 dias, com reuniões diárias e semanais de acompanhamento das atividades desenvolvidas.

### Divisão de Papéis

A equipe está organizada da seguinte maneira:
* ***Scrum Master:*** Caio César Ferreira Florindo
* ***Product Owner:*** Hélio Vieira Bernardes
* ***Equipe de Desenvolvimento:***
     - Hebert Paixão do Nascimento
     - Denian Cesar Soares Faria
* ***Equipe de Design:***
     - Leticia Layane Pauli

Para organização e distribuição das tarefas do projeto, a equipe está utilizando o GitHub Project estruturado com as seguintes listas: 

●	*Backlog:* recebe as tarefas a serem trabalhadas e representa o Product Backlog. Todas as atividades identificadas no decorrer do projeto também devem ser incorporadas a esta lista.

●	*To Do:* Esta lista representa o Sprint Backlog. Este é o Sprint atual que estamos trabalhando.

●	*Doing:* Quando uma tarefa tiver sido iniciada, ela é movida para cá.

●	*Done:* nesta lista são colocadas as tarefas que passaram pelos testes e controle de qualidade e estão prontos para ser entregues ao usuário. Não há mais edições ou revisões necessárias, ele está agendado e pronto para a ação.

O quadro kanban do grupo desenvolvido na ferramenta de gerenciamento de projetos GitHub Projects está disponível através da URL <https://github.com/orgs/ICEI-PUC-Minas-PMV-ADS/projects/176> e é apresentado, no estado atual conforme mostra a Figura 1 abaixo. 

![Logo do site](/docs/img/printkanban.png)  


### Processo

Todo o processo poderá ser acompanhado pelo repositório do projeto no GitHub.

### Ferramentas

As ferramentas empregadas neste projeto são:

- Editores de códigos (HTML5, CSS3 e Java Script).
- Ferramentas de comunicação (Teams)
- Ferramentas de gerenciamento e armazenamento do repositório (https://github.com/)
- Ferramentas de desenho de tela (Invision)

O editor de código foi escolhido porque ele possui uma integração com o
sistema de versão. As ferramentas de comunicação utilizadas possuem
integração semelhante e por isso foram selecionadas. Por fim, para criar
diagramas utilizamos as ferramentas acima listadas por melhor captar as
necessidades da nossa solução.

