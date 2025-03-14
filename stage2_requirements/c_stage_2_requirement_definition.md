[Back to main Logbook Page](../hci_logbook.md)

---
# C. Requirement Definition
>	Based on all the gathered context, including an understanding of current practices, competitors, and user feedback and expectations: 
>	- summarize the user characteristics, context, and motivations using Personas
>	- explain your vision for a novel solution that will target user motivations using Scenarios
>	- identify requirements

# Personas

## Persona: [Matteo Rossi] 
### Summary 
| Attribute        | Details                                       |
| ---------------- | --------------------------------------------- |
| **Photo**        | ![Matteo Rossi\|100](personas/estudante.png)  |
| **Name**         | [Matteo Rossi]                                |
| **Age**          | [18]                                 |
| **Occupation**   | [Estudante]                           |
| **Location**     | [Roma, Itália -> Aveiro,Portugal]                               |
| **Goals**        | [Encontrar um quarto que seja confortável, seguro e próximo do seu departamento.]           |
| **Pain Points**  | [Não encontra nenhuma informação sobre os senhorios; Não está satisfeito com a quantidade de detalhes que encontra nos anúncios]              |
| **Motivation**   | ["Quero encontrar um quarto sem surpresas desagradáveis. Se pudesse ver avaliações de outros estudantes sobre os senhorios e saber mais detalhes sobre a casa, tomaria uma decisão com mais confiança."]                |
| **Full Profile** | [📄 Read More](personas/persona2_estudante.md) |

---
## Persona: [Sr. Danilo Oliveira e Silva] 
### Summary 
| Attribute        | Details                                                                                                                                                                                  |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Photo**        | ![Sr. Danilo Oliveira e Silva\|100](personas/senhorio.png)                                                                                                                               |
| **Name**         | [Sr. Danilo Oliveira e Silva]                                                                                                                                                            |
| **Age**          | [68]                                                                                                                                                                                     |
| **Occupation**   | [CEO de uma multinacional portuguesa e senhorio do seu alojamento]                                                                                                                       |
| **Location**     | [Aveiro, Portugal]                                                                                                                                                                       |
| **Goals**        | [Sucesso da empresa na qual é CEO e arranjar uma forma eficaz de anunciar o alojamento que procura pôr a alugar]                                                                         |
| **Pain Points**  | [Não encontra uma forma fácil para comunicar com possíveis inquilinos; Websites atuais não fornecem informações suficientes sobre as pessoas interessadas em alugar quarto]              |
| **Motivation**   | ["Quero uma forma fácil de publicitar o meu novo alojamento e de comunicar com os inquilinos. Gostava de ter acesso às informações dos mesmos de modo a tomar a decisão mais acertada."] |
| **Full Profile** | [📄 Read More](personas/persona1_senhorio.md)                                                                                                                                            |

---


# Hierarchical Task Analysis

### Breaking down user actions
Em conjuntura com análises como o Cognitive Walkthrough, foi também efetuada uma análise por diagramas às diversas tarefas presentes na nossa plataforma de procura de quartos idealizada. Posteriormente serão analisados requisitos relacionados com isto, mas de seguida apresentam-se as diversas opções de navegação do site:

### Publicar um anúncio

![image](https://github.com/user-attachments/assets/f3de17b9-1b1c-41d6-95ae-4270897dc3ab)



### Contactar pessoas (Mensagem Direta)

![image](https://github.com/user-attachments/assets/85a64502-ddc9-454a-9bff-50ce2892f7c6)



### Procurar alojamento

![image](https://github.com/user-attachments/assets/19b48a97-a04f-4176-bf69-514a54001817)



### Utilizar fórum

![image](https://github.com/user-attachments/assets/409951e3-312c-4c72-a36a-07448858050f)



### Avaliar

![image](https://github.com/user-attachments/assets/c2c12cf3-113f-44af-bd65-c90c34b2ba7b)




# Scenarios

## Scenario 1: Matteo searches for accommodation
O Matteo acabou de fazer 18 anos e está pronto para se mudar para portugal e começar o curso de "Língua, literatura e cultura".
Ele percorre incansavelmente página por página para encontrar o alojamento perfeito no centro de aveiro, perto do seu apartamento, mas ele acha que os websites não são muito informativos. Além disso, alguns deles nem permitem mudar a linguagem para inglês, nem permitem personalizar a procura., então ele acaba pro sair sempre de mãos vazias.
É quando ele se depara com a *EasyRoom*, a plataforma que oferece tudo que ele procurava.
Ele entra no website e muda a lingugem para Inglês. Ele depois abre a aba de procura por acomodações e encontra uma variedade de filtros que o ajudam a ajustar a sua procura com as suas necessidades. Ele acaba por ler reviews e descrições dos anúncios que ele mais gostou, o que o ajudou a escolher uma acomodação. 

---
## Scenario 2: Mister Danilo publishes an advertisement for his appartment's rooms

Tendo comprado recentemente um apartamento com três quartos no centro de Aveiro, o Sr. Danilo está à procura de uma forma de anunciar o seu arrendamento.
Ele navega por vários websites mas considera que ou são demasiado problemáticos/confusos de preencher e publicar, ou que o alojamento não está bem publicitado neles. O Sr. Danilo também não teve sorte nenhuma ao publicar os detalhes do alojamento fisicamente.
Ao fim de algum tempo, ele descobre a *EasyRoom*, que oferece uma interface muito intuitiva e fácil de preencher. Ele adiciona a informação necessária acerca do apartamento e dos respetivos quartos, e aguarda por qualquer oferta feita por estudantes interessados.
O Sr. Danilo considera que o seu apartamento está bem anunciado neste website, o que o deixa satisfeito com a sua escolha.

---
## Scenario 3: Matteo tries to contact landlords
Tendo escolhido um conjunto de alojamentos que condizem com as suas necessidades,o Matteo procura entrar em contacto com os respetivos senhorios, para que ele se possa finalmente mudar para Aveiro.
Contudo, as experiẽncias passadas dele não têm sido as melhores, já que muitos dos senhorios que ele contactou no passado através das informações retiradas de outros websites não retornavam as suas chamadas, nem respondiam aos emails dele. Ele pondera se eles apenas o estarão a ignorar, demasiado ocupados para dar resposta, ou se os contactos que ele obteve estão simplesmente desatualizados.
É nesse momento que ele tenta utilizar a feature de chat da *EasyRoom*, que lhe permite comunicar diretamente com cada senhorio. Felizmente, ele recebe mensagens de volta por parte de vários daqueles que tentou contactar. Depois de negociar bem, acaba por definir um acordo com o senhor Danilo, que está mais do que contente por o ter lá. E igualmente está o Matteo, que se sente excitado por finalmente ter encontrado o lugar onde vai ficar.


# Requirements

## C.1. Functional requirements
- O senhorio tem de ser capaz de adicionar novo anúncios personalizados.
- O senhorio tem de ser capaz de editar os seus anúncios.
- O senhorio tem de ser capaz de remover os anúncios que publicou. 
- O sistema deve prover ao aluno uma lista de anúncios publicados.
- O sistema deve permitir aos estudantes refinar a procura por quartor disponíveis com base em critérios especificos.
- Os estudantes devem ser capazes de contactar os senhorios.
- O sistema deve fornecer um forum para que os usuários se comunicarem e partilharem informações 
- O sistema deve monitorar o relacionamento senhorio-inquilino
- O sistema deve permitir que os inquilinos e senhorios deem feedback sobre suas experiências uns com os outros.


## C.2. Non-functional requirements
Non-Functional requirements:
- Apenas proprietários e alunos autenticados devem conseguir acessar seus respectivos painéis
- Uma pesquisa deve retornar resultados rapidamente
- O sistema deve ter uma interface intuitiva e amigável
- O sistema deve funcionar em vários sistemas operacionais (Windows, macOS, Linux)
- A plataforma deve ser compatível com dispositivos móveis
- A plataforma deve oferecer suporte a pelo menos dois idiomas

---
[Back to main Logbook Page](../hci_logbook.md)
