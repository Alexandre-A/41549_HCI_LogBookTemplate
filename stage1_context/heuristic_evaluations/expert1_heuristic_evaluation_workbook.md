<!-- This Heuristic Evaluation Workbook replicates the one proposed by the 
Nielsen Norman Group available at: https://media.nngroup.com/media/articles/attachments/Heuristic_Evaluation_Workbook_-_Nielsen_Norman_Group.pdf
-->

**Evaluator**: [Alexandre Andrade]
**Date**: [08-03-2025]
**Product**: [BQuarto]

Severity Scale adopted: [[severity_scale_heuristic_evaluation]]
Summary of each usability heuristic: [here](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1-compressed.pdf)

# 1 Visibility of System Status
>	The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time. 
>	- Does the design clearly communicate its state?
>	- Is feedback presented quickly after user actions?

| **Issue**                                                                                                | **Severity** | Recommendation                                      |
| ---------------------------------------------------------------------------------------------------------| ------------ | ----------------------------------------------------|
| Botões de mudar de linguagem não funcionam/mostram feedback                                              | 3            | Implementar a funcionalidade e dar feedback ao user |
| Clicar em anuncios da homepage ou nos detalhes dos alojamentos leva a uma página vazia e não indica que ouve um erro                                                 | 4            | Corrigir funcionalidade mal implementada            |
| Mensagens recebidas num periodo de assinante não podem ser vistas depois do periodo acabar               | 4            | Retirar opção de assinatura ou deixá-las visíveis mas impedir escrita |
| O mapa é uma imagem estática                                                                             | 2            | Implementar um mapa dinâmico, dando liberdade ao user |



# 2 Match Between System and The Real World
>	The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order. 
>	- Will user be familiar with the terminology used in the design? 
>	- Do the design’s controls follow real-world conventions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| O design dos botões nos anúncios não indica o que fazem | 2 | Tornar os botões mais explícitos |

# 3 User Control and Freedom
>	Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action without having to go through an extended process. 
>	- Does the design allow users to go back a step in the process? 
>	- Are exit links easily discoverable? 
>	- Can users easily cancel an action? 
>	- Is Undo and Redo supported?

| **Issue**                                                                                   | **Severity** | Recommendation                         |
| ------------------------------------------------------------------------------------------- | ------------ | -------------------------------------- |
| Estando nas páginas de anúncios, à medida que explora-se mais o site, torna a navegação confusa para eventos como retroceder nas páginas | 3            | Facilitar navegação no website |

# 4 Consistency and Standards
>	Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform and industry conventions. 
>	- Does the design follow industry conventions? 
>	- Are visual treatments used consistently throughout the design?

| **Issue**                                        | **Severity** | Recommendation                                          |
| ------------------------------------------------ | ------------ | ------------------------------------------------------- |
| Existem vários tipos de botão de mudar de língua | 2            | Uniformizar o estilo dos botões pelo site               |

# 5 Error Prevention
>	Good error messages are important, but the best designs carefully prevent problems from occurring in the first place. Either eliminate error-prone conditions, or check for them and present users with a confirmation option before they commit to the action. 
>	- Does the design prevent slips by using helpful constraints? 
>	- Does the design warn users before they perform risky actions?

| **Issue**                                                                                                        | **Severity** | Recommendation                                         |
| ---------------------------------------------------------------------------------------------------------------- | ------------ | ------------------------------------------------------ |
| Clicar em anúncios da homepage ou nos detalhes dos alojamentos leva a uma página vazia e não indica que houve um erro | 4            | Corrigir funcionalidade e dar feedback em caso de erro |

# 6 Recognition Rather than Recall
>	Minimize the user's memory load by making elements, actions, and options visible. The user should not have to remember information from one part of the interface to another. Information required to use the design (e.g. field labels or menu items) should be visible or easily retrievable when needed. 
>	- Does the design keep important information visible, so that users do not have to memorize it? 
>	- Does the design offer help in-context?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| _______________ | ____________ | _______________________ |

# 7 Flexibility and Efficiency of Use
>	Shortcuts — hidden from novice users — may speed up the interaction for the expert user such that the design can cater to both inexperienced and experienced users. Allow users to tailor frequent actions. 
>	- Does the design provide accelerators like keyboard shortcuts and touch gestures? 
>	- Is content and funtionality personalized or customized for individual users?

| **Issue**                                                                                                                                        | **Severity** | Recommendation |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------ | -------------- |
| Nos filtros, inserir datas (ou range de preços) é lento por ter de se avançar os valores 1 a 1, não permite meter diretamente o valor pretendido | 2            | Permitir inserção direta dos valores pretendidos               |
| O mapa é uma imagem estática | 2            | Implementar um mapa dinâmico, dando liberdade ao user |
| Mensagens recebidas num periodo de assinante não podem ser vistas depois do periodo acabar | 4            | Retirar opção de assinatura ou deixá-las visíveis mas impedir escrita |


# 8 Aesthetic and Minimalist Design
>	Interfaces should not contain information that is irrelevant or rarely needed. Every extra unit of information in an interface competes with the relevant units of information and diminishes their relative visibility. 
>	- Is the visual design and content focused on the essentials? 
>	- Have all distracting, unnescessary elements been removed?

| **Issue**                                                                                                    | **Severity** | Recommendation                                         |
| -------------------------------------------------------------------------------------------------------------| ------------ | ------------------------------------------------------ |
| Homepage com excessivo texto e links, alguns até não funcionais/repetidos, tornando a navegação overwhelming | 2            | Simplificar o design, eliminando coisas desnecessárias |
| A página "myads" possui muita informação incluindo coisas que já estão na página de criar ads | 2       | Evitar redundâncias desnecessárias |

# 9 Help Users Recognize, Diagnose, and Recover from Errors
>	Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution. 
>	- Does the design use traditional error message visuals, like bold, red text? 
>	- Does the design offer a solution that solves the error immediately?

| **Issue**                                                                                                       | **Severity** | Recommendation               |
| --------------------------------------------------------------------------------------------------------------- | ------------ | ---------------------------- |
| Botões de ver os anúncios de alojamento ou de procura de quarto existentes na homepage levam a uma página vazia | 4            | Dar feedback em caso de erro |

# 10 Help and Documentation
>	It’s best if the system doesn’t need any additional explanation. However, it may be necessary to provide documentation to help users understand how to complete their tasks. 
>	- Is help documentation easy to search? 
>	- Is help provided in context right at the moment when the user requires it?

| **Issue**                                          | **Severity** | Recommendation                                 |
| -------------------------------------------------- | ------------ | ---------------------------------------------- |
| Filtros sem uma label explicativa ( "outro" ) | 3       | Tornar os filtros mais explícitos              |
| Botões nos anúncios não indicam o que fazem    | 3     | Tornar os botões mais explícitos |
| Existe uma indexação de perfis de procura e anúncios de alojamento cujas labels são pouco explicativas daquilo para que remetem |  2   |  Tornar mais clara a intenção de cada label  |
