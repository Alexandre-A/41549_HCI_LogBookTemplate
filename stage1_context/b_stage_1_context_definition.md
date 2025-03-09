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
> Como tal, esta foi a escala seguida:
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

| **Issue**       | **Expert 1** | Expert 2 | Expert 3 | Recommendations                             |
| --------------- | ------------ | -------- | -------- | ------------------------------------------- |
| Botões de mudar de linguagem não funcionam/mostram feedback | 3            | 1        | 0        | Something could be done to the button to... |
| Clicar em anuncios da homepage ou nos detalhes dos alojamentos leva a uma página vazia e não indica que ouve um erro   | 4            | 3        | 4        | Other thing to recommend                    |
| Mensagens recebidas num periodo de assinante não podem ser vistas depois do periodo acabar             |  4            |          |          |                                             |
| O mapa é uma imagem estática             |  2            |          |          |                                             |
| O design dos botões nos anúncios não indicam o que fazem             |  2            |          |          |                                             |
| Estando nas páginas de anúncios, à medida que explora-se mais o site, torna a navegação confusa para eventos como retroceder nas páginas             |  3            |          |          |                                             |
| Existem vários tipos de botão de mudar de língua             | 2             |          |          |                                             |
| Nos filtros, inserir datas (ou range de preços) é lento por ter de se avançar os valores 1 a 1, não permite meter diretamente o valor pretendido             |  2            |          |          |                                             |
| Homepage com excessivo texto e links, alguns até não funcionais/repetidos, tornando a navegação overwhelming             | 2             |          |          |                                             |
| A página "myads" possui muita informação incluindo coisas que já estão na página de criar ads             |  2            |          |          |                                             |
| Filtros sem uma label explicativa ( "outro" )             |  3            |          |          |                                             |
| Botões nos anúncios não indicam oq fazem             | 3             |          |          |                                             |
| Existe uma indexação de perfis de procura e anúncios de alojamento cujas labels são pouco explicativas daquilo para que remetem             | 2             |          |          |                                             |




---
### - Cognitive Walkthrough

#### Method
[Briefly described  the method you used for the Cognitive Walkthrough analysis. ]

#### Task Selection and Task Analysis

[Which tasks did you select and why. What are the subtasks entailed for each ]


| Task                        | Subtasks                               |
| --------------------------- | -------------------------------------- |
| **1. Buyng a grammar book** | Search for available grammar books     |
|                             | Identify a specific book from the list |
|                             | Add the selected book to the cart      |
|                             | Proceeed to checkout                   |


| Task                          | Subtasks                                |
| ----------------------------- | --------------------------------------- |
| **1. Booking a train ticket** | Select departure and destination cities |
|                               | Choose travel date and time             |
|                               | Pick a seat (if applicable)             |
|                               | Confirm booking and make payment        |


#### Results

Task: [This is the task]

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- |
| 1      | [Step 1 description]   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 1]              |
| 2      | [Step 2 description]   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 2]              |
| 3      | [Step 3 description]   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |
| ...    | [Further steps]        | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestions]               |

## B.1c. Overall Analysis

[Here, you should summarize the main findings for the competitor panorama, listing key points that are valuable to inform the design of your solution, and also make an HCI SWOT analysis for the main competitor, taking into consideration what you learned from the heuristic evaluatio, cognitive walkthrough, online reviews, user feedback, etc.]

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
