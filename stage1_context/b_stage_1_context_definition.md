[Back to main Logbook Page](../hci_logbook.md)

---
# B. Stage 1 - Context Definition


# B.1. Competitor Identification
>	The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative. It ends with a summary of the main findings including an HCI SWOT analysis



## B.1a. Competitors


| **Competitor**    | **Description**                            			| Information repository              |
| ----------------- | ----------------------------------------------------------------- | ----------------------------------- |
| [BQuarto]	    | [Plataforma online de procura e publicidade de alojamento]        | [[Competitor Analysis BQuarto](competitors/Competitor%20Analysis%20BQuarto.md)]	|




## B.1b. Detailed Competitor Analysis
>	Choose the most notable competitor and do a more thorough analysis of their interactive solution


### - Heuristic Evaluation

#### Method
*[ Describe the method used for the heuristic evaluation: procedure, number of experts, heuristics, severity scale considered, how was consensus done.]*

> Para a avaliação heurística em questão, **3 experts** foram usados,  nomeadamente cada elemento do grupo. Cada expert fez uma análise individual  pormenorizada do website do competidor escolhido (**BQuarto**), registando  qualquer problema que fosse encontrado, desde pequenos detalhes estéticos a  falhas funcionais do sistema. 
> Com os problemas registados, decidimos juntar as descobertas feitas por cada um dos experts e discuti-las, de modo a estarmos todos de acordo. 
> Por fim avançámos com a avaliação, baseando-nos nas **10 heurísticas  de usabilidade de Jakob Nielsen**, nomeadamente: 
> * **H1** - Visibility of system status 
> * **H2** - Match between system and the real world  
> * **H3** - User control and freedom 
> * **H4** - Consistency and standards 
> * **H5** - Error prevention 
> * **H6** - Recognition rather than recall 
> * **H7** - Flexibility and efficiency of use 
> * **H8** - Aesthetic and minimalist design 
> * **H9** - Help users recognize, diagnose, and recover from errors 
> * **H10** - Help and documentation 
> 
> Depois de atribuirmos as heurísticas que considerávamos mais adequadas a cada um dos problemas, categorizámos a gravidade dos mesmos, seguindo uma escala de 0 a 4, que se baseiam na combinação de 3 fatores: a frequência da ocorrência do problema, o impacto que esse problema tem e a persistência do mesmo.
> Como tal, esta foi a [escala seguida](heuristic_evaluations/severity_scale_heuristic_evaluation.md):
> * **0** - I don't agree that this is a usability problem at all;
> * **1** - Cosmetic problem;
> * **2** - Minor usability problem;
> * **3** - Major usability problem;
> * **4** - Usability catastrophe.

#### Individual Evaluations
<!-- For the individual heuristic evaluations by each member of the group, you can use the templates below, grouping problems by heuristic OR each evaluator can have a table listing all the detected problems with the number of the violated heuristics on the second column. Whichever your choice, you should have a list of problems, the severity, and a recommendation to mitigate it -->



- [expert1_heuristic_evaluation_workbook](heuristic_evaluations/expert1_heuristic_evaluation_workbook.md)

- [expert2_heuristic_evaluation_workbook](heuristic_evaluations/expert2_heuristic_evaluation_workbook.md)

- [expert3_heuristic_evaluation_workbook](heuristic_evaluations/expert3_heuristic_evaluation_workbook.md)


#### Consensus

>	After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

| **Issue**                                                                                                                                        | **Expert 1** | Expert 2 | Expert 3 | Recommendations                                                                                     |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------ | -------- | -------- | --------------------------------------------------------------------------------------------------- |
| Botões de mudar de linguagem não funcionam/mostram feedback                                                                                      | 3            | 3        | 3        | Implementar a funcionalidade e dar feedback ao user                                                 |
| Clicar em anuncios da homepage ou nos detalhes dos alojamentos leva a uma página vazia e não indica que ouve um erro                             | 4            | 3        | 4        | Corrigir funcionalidade mal implementada                                                            |
| Mensagens recebidas num periodo de assinante não podem ser vistas depois do periodo acabar                                                       | 4            | 4        | 2        | Retirar opção de assinatura ou deixá-las visíveis mas impedir escrita                               |
| O mapa é uma imagem estática                                                                                                                     | 2            | 3        | 1        | Implementar um mapa dinâmico, dando liberdade ao user                                               |
| O design dos botões nos anúncios não indicam o que fazem                                                                                         | 2            | 4        | 3        | Trocar o nome das labels                                                                            |
| Estando nas páginas de anúncios, à medida que explora-se mais o site, torna a navegação confusa para eventos como retroceder nas páginas         | 3            | 3        | 2        | Resumir mais a navegação o site em menos secções, com indicações mais claras do que cada uma possui |
| Existem vários tipos de botão de mudar de língua                                                                                                 | 2            | 2        | 2        | Unificar no cabeçalho esses mesmos botões, por exemplo                                              |
| Nos filtros, inserir datas (ou range de preços) é lento por ter de se avançar os valores 1 a 1, não permite meter diretamente o valor pretendido | 2            | 4        | 2        | Utilizar uma seleção mais dinâmica e/ou até aceitar a escrita de números                            |
| Homepage com excessivo texto e links, alguns até não funcionais/repetidos, tornando a navegação overwhelming                                     | 2            | 2        | 2        | Simplificar o design evitando redundâncias                                                          |
| A página "myads" possui muita informação incluindo coisas que já estão na página de criar ads                                                    | 2            | 2        | 2        | Manter só o essencial em cada página                                                                |
| Filtros sem uma label explicativa ( "outro" )                                                                                                    | 3            | 2        | 3        | Adicionar labels explicativas                                                                       |
| Botões nos anúncios não indicam oq fazem                                                                                                         | 3            | 3        | 3        | Adicionar icones que façam mais sentido                                                             |
| Existe uma indexação de perfis de procura e anúncios de alojamento cujas labels são pouco explicativas daquilo para que remetem                  | 2            | 2        | 2        | Simplificar e adicionar labels                                                                      |




---
### - Cognitive Walkthrough

#### Method
[Briefly described  the method you used for the Cognitive Walkthrough analysis. ]
Simulou-se todo o processo da aquisição de conhecimento por parte do utilizador para cada tarefa, a partir do seu início comum - a página inicial. Navegámos até ao objetivo final, e concluímos se era, ou não, de fácil acesso. O Cognitive Walkthrough foi executado pelo grupo e não só uma pessoa para promover a diversidade de processos conceptuais na exploração do site.
#### Task Selection and Task Analysis

[Which tasks did you select and why. What are the subtasks entailed for each ]
Posto isto, foram selecionadas 3 tarefas que consideram-se pertinentes para a tipologia de site/plataforma enveredada:

| Task | Subtasks             |
| ---- | -------------------- |
| *    | Procurar numa região |

| Task                        | Subtasks             |
| --------------------------- | -------------------- |
| **1. Filtrar uma pesquisa** | *                    |
|                             | Selecionar um filtro |

| Task                                    | Subtasks                                       |
| --------------------------------------- | ---------------------------------------------- |
| **2. Trocar mensagens com um senhorio** | *                                              |
|                                         | Selecionar o balão de conversa de um resultado |
|                                         | Efetuar o registo para contactar               |
|                                         | Submeter e aguardar pelo contacto              |

| Task                    | Subtasks                                   |
| ----------------------- | ------------------------------------------ |
| **3. Alterar o idioma** | Efetuar login                              |
|                         | Navegar para as preferências               |
|                         | Trocar a linguagem                         |
|                         | Carregar num botão para guardar alterações |


#### Results

Task: [Filtrar uma pesquisa]

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes                                                         | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement         |
| ------ | ---------------------- | ------------------------------------------------ | ------------------------------------------------------------- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | ----------------------------------- |
| 1      | Procurar numa região   | Yes                                              |                                                               | Yes                                                                                       |       | Yes                            |                                     |
| 2      | Selecionar um filtro   | Yes                                              | Depende do botão utilizado, devido à falta de clareza nalguns | No                                                                                        |       | Yes                            | Maior clareza nas opções de filtros |


Task: [Trocar mensagens com um senhorio]

| Step # | Task/Action to Perform                         | Will User Know What to do at this step? (Yes/No) | Notes                                           | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement                                                                                                 |
| ------ | ---------------------------------------------- | ------------------------------------------------ | ----------------------------------------------- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| 1      | Procurar numa região                           | Yes                                              |                                                 | Yes                                                                                       |       | Yes                            |                                                                                                                             |
| 2      | Selecionar o balão de conversa de um resultado | No                                               | Botões pouco visíveis                           | Yes                                                                                       |       | Yes                            |                                                                                                                             |
| 3      | Efetuar o registo para contactar               | Yes                                              |                                                 | Yes                                                                                       |       | Yes                            |                                                                                                                             |
| 4      | Submeter e aguardar pelo contacto              | No                                               | Não há garantias nem de resposta nem de leitura | Yes                                                                                       |       | Yes                            | Utilizar um recibo de leitura ou de acesso do senhorio ao site para saber se está a par do anúncio e consequentes mensagens |

Task: [Alterar o idioma]

| Step # | Task/Action to Perform                     | Will User Know What to do at this step? (Yes/No) | Notes                                                                    | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement                                                      |
| ------ | ------------------------------------------ | ------------------------------------------------ | ------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | -------------------------------------------------------------------------------- |
| 1      | Efetuar login                              | No                                               | Metade dos botões de linguagem não funciona senão após o registo e login | No                                                                                        |       | Yes                            | Resolver questões de tradução inconsistentes sobre quais botões funcionam ou não |
| 2      | Navegar para as preferências               | Yes                                              |                                                                          | Yes                                                                                       |       | Yes                            |                                                                                  |
| 3      | Trocar a linguagem                         | Yes                                              |                                                                          | Yes                                                                                       |       | Yes                            |                                                                                  |
| 4      | Carregar num botão para guardar alterações | Yes                                              |                                                                          | Yes                                                                                       |       | Yes                            | Não necessitar de login para alterar a linguagem corretamente                    |


## B.1c. Overall Analysis

*[Here, you should summarize the main findings for the competitor panorama, listing key points that are valuable to inform the design of your solution, and also make an HCI SWOT analysis for the main competitor, taking into consideration what you learned from the heuristic evaluatio, cognitive walkthrough, online reviews, user feedback, etc.]*

#### List of key points/findings

- O website cobre uma ampla gama de alojamentos e permite contactar diretamente os senhorios.
- Algumas seções do site são pouco intuitivas, dificultando a navegação do usuário.
- O layout apresenta redundâncias, elementos pouco chamativos e inconsistências no design.
- A ferramenta de busca oferece uma boa variedade de filtros para personalização da experiência do usuário.
- Algumas funcionalidades não são bem indicadas e podem dificultar o uso por novos usuários.
- Há potencial para tornar o ambiente mais atraente e incluir funcionalidades interativas como reviews de alojamentos e senhorios.

#### HCI SWOT Analysis Table

| SWOT Element  | Description/HCI Focus                                                                                                                                                                                        | Example                                                                                                                                                                                                                       |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Strengths     | Um website na sua grande maioria funcional, com cobertura de alojamentos a nível nacional, oferecendo uma variedade de acomodações com base em preferências<br>                                              | Usando o site é mesmo possivel contactar senhorios numa região especificada. Na secção de procura de alojamento, existe uma boa variedade de filtros para personalizar a experiência<br>                                      |
| Weaknesses    | O site é pouco intuitivo em certas partes, podendo não ser user-friendly. O design do mesmo também é algo que deixa a desejar, com várias redundâncias. Existem falhas funcionais em alguns componentes.<br> | Não há indicação da função de certos botões. Design do website pouco atrativo, com features que por vezes não chamam a atenção. Mudança de língua através dos botões existentes é inconsistente ou não funcional<br>          |
| Opportunities | Um ambiente mais atraente e user-friendly. Implementação de features que permitissem ao user receber informação adicional e dar mais feedback sobre experiências passadas<br>                                | Usar um melhor esquema de cores e escolher icones que têm significado, para o usuário saber o que fazem. Implementação de uma secção de forum público e criar a possibilidade de fazer reviews de alojamentos e senhorios<br> |
| Threats       | Têm cobertura nacional e uma elevada userbase. Métodos de comunicação entre pessoas implementados<br>                                                                                                        | O bquartos já abrange uma boa parte do país, com centenas de usuários a usarem diariamente o website. Já possuem um sistema de chat entre membros do website<br>                                                              |
---

# B.2. Users
>	For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...


## B.2a. Method

*[What approach was followed to talk with users; what kind of users were considered. What was the goal of the interviews? What were the questions considered?]*

De modo a obter a maior quantidade de informação útil para o nosso caso de estudo, focámo-nos em adquirir o feedback de estudantes universitários, uma vez que acabam por ser o nosso principal público-alvo.
Recorremos a 2 métodos para abordar os users em questão: um formulário feito com recurso ao google forms e entrevistas em aula aos colegas da nossa turma prática, como iniciativa do nosso professor.

Apesar de cair um pouco "fora do âmbito" do que era pedido nesta secção de entrevistas, optámos pela criação de um tal formulário, porque achámos que era algo que seria de fácil criação, facilmente partilhável e simples de responder. Sendo este forms online, também nos permitiu alcançar usuários de diversas localidades e universidades, para além de não haver a necessidade de estar presentes fisicamente para estas entrevistas poderem decorrer, sendo apenas pedido 5 minutos do tempo dos intervenientes.

Com estes recursos, o nosso objetivo era por um lado ouvir as várias experiências que cada pessoa pudesse ter tido relativamente à procura de alojamento por questões universitárias, bem como abordar de forma geral problemas que as soluções atuais para este problema possam ter e receber ligeiro feedback sobre o competidor por nós escolhido, BQuartos.

Como tal, no formulário online tocámos em assuntos como os métodos a que os usuários recorreram para obter informação sobre os alojamentos na cidade da universidade onde estudam, que "features" procurariam numa plataforma online que procurasse facilitar este processo, pontos fortes e fracos das soluções atuais, entre outros. Criámos igualmente uma breve secção dedicada ao nosso concorrente, BQuartos, como referido anteriormente, para podermos possivelmente expandir ou confirmar os problemas levantados na avaliação heurística por nós realizada. 

Nas entrevistas presenciais realizadas em aula, focámo-nos principalmente nas experiências e feedback dos users com o processo de procura de alojamento, pois sentimos que para o âmbito da atividade realizada em aula, não se adequava tanto questionar sobre o nosso concorrente.
## B.2b. Results

>	This section tracks all informal user interviews, summarizing key insights and linking to detailed notes for each session. 

### Interview List (Presencial Interviews)
| Date       | Participant / Role | Key Insights                                                    | Link to Notes                |
| ---------- | ------------------ | --------------------------------------------------------------- | ---------------------------- |
| 27-02-2025 | (Eduardo Romano + Tiago Mendes) / students      | Obtiveram online informações sobre o alojamento onde residem, criticam o tempo de resposta dos senhorios e procuram sobretudo acesso fácil a detalhes e reviews de alojamentos e filtragem personalizada de resultados | [📄 Notes](interviews/presencial-interview-Eduardo-Tiago.md) |
| 27-02-2025        | Simão Santos / student                   | Obteve localmente informações sobre o alojamento onde reside, critica a natureza confusa e falta de informação sobre os mesmos e procura sobretudo acesso fácil a detalhes e reviews de alojamentos e filtragem personalizada de resultados                                                                | Ver nota abaixo                             |
| 27-02-2025        | Pedro Fonseca / student                   |  Obteve localmente informações sobre o alojamento onde reside, critica falta de contacto com os senhorios e falta de esclarecimento de detalhes dos alojamentos e procura sobretudo acesso fácil a detalhes e reviews de alojamentos, filtragem personalizada de resultados e forum de divulgação publico                                                              | Ver nota abaixo                             |
| 27-02-2025        | Tiago Oliveira / student                   |  Obteve online informações sobre o alojamento onde reside, critica falta de contacto com os senhorios e procura sobretudo acesso fácil a detalhes e reviews de alojamentos, filtragem personalizada de resultados e feature de chat com senhorios                                                             |Ver nota abaixo                              |
| 27-02-2025        | Catarina / student                  | Obteve online informações sobre o alojamento onde reside, critica falta de esclarecimento de detalhes dos alojamentos e procura sobretudo acesso fácil a detalhes e reviews de alojamentos e filtragem personalizada de resultados                                                                 |       Ver nota abaixo                       |
| 27-02-2025        | Matilde / student                  |  Obteve localmente informações sobre o alojamento onde reside, critica falta de atualização de informação sobre os alojamentos e procura sobretudo acesso fácil a detalhes e reviews de alojamentos, filtragem personalizada de resultados e feature de chat com senhorios                                                                |        Ver nota abaixo                      |
| 27-02-2025        | Gabriel Gonçalves / student                   |   Obteve localmente informações sobre o alojamento onde reside, critica falta de reviews dos senhorios e procura sobretudo acesso fácil a detalhes e reviews de alojamentos, filtragem personalizada de resultados e feature de chat com senhorios                                                            | Ver nota abaixo                             |
| 27-02-2025        | (Henrique + Rodrigo + Eduardo Rosário) / students                   | Obtiveram localmente informações sobre o alojamento onde residem, criticam falta de atualização dos anúncios e procuram sobretudo acesso fácil a detalhes e reviews de alojamentos, filtragem personalizada de resultados e reviews de senhorios                                                                | Ver nota abaixo                             |

**Nota:** O link para as notas presente na tabela representa apenas uma representação "formal" das perguntas feitas presencialmente, tendo sido escolhido arbitrariamente um dos grupos entrevistado para o seu preenchimento. 
Para ver o conjunto de resultados na sua extensão, consultar o seguinte link: [Presencial_Google_Spreadsheet](https://docs.google.com/spreadsheets/d/1PkgK2dTlNVyNClTKK8XUEyoak6CA1qvrvgNpAFJJ-Ww/edit?usp=sharing) 
#### Results of the google forms interview
* Google sheets com os resultados das entrevistas online: [Google_Spreadsheet](https://docs.google.com/spreadsheets/d/1eWOvblwGFSEar0d18toHJbEqv9-zWmBSrRjTBFYxbM0/edit?usp=sharing)

* Template das perguntas realizadas: [Online_Interview_Template](interviews/online-interview-template.md)

### Common Themes & Patterns 

- **Recurring Problems:** 
	- Falta de contacto com os senhorios
	- Falta de informação/informação desatualizada
	- Preços elevados (apesar de não ser um problema causado pelo nosso competidor)
- **Frequently Used Tools:** 
	- Páginas Web
	- Contactos locais/anúncios locais
	- Contacto através de amigos
- **Desired Features / Solutions:** 
	- Reviews dos alojamentos e dos senhorios
	- Fórum de divulgação de anúncios/informações entre pessoas
	- Informações sobre contratos, distâncias a locais importantes, métodos de pagamento (Filtros personalizados)
	- Detalhes e fotos dos alojamentos
- --- 



---
[Back to main Logbook Page](../hci_logbook.md)

---
