# PRIVATE-SYSTEM-
Um sistema de hospedagem construído com privacidade como princípio — não como recurso adicional.

# Motivação
A ideia surgiu de uma pergunta simples: o quanto um hóspede realmente precisa expor para fazer uma reserva?
A resposta desse projeto é: apenas um e-mail. Nada de nome, telefone ou documento. O hóspede recebe um código único, e é com ele que tudo funciona — do check-in ao pagamento.


#FUNCIONAMENTO 

E-mail do hóspede
      │
      ▼
Geração de código único (UUID4)
      │
      ▼
Envio do código por e-mail (Nodemailer)
      │
      ▼
Login e acesso com o código
      │
      ▼
Pagamento via Bitcoin

#Funcionalidades presentes
- Envio do código ao email utilizando Nodemailer(Node.js)
- Gerador de código unico usando UUID4(PYTHON), onde se mostrou mais efetivo ao conceito do projeto
- Registro dos hóspedes atráves de uma simples tela de login/registro em HTML,CSS.
- Armazenamento dos dados de e-mail e de seu respectivo código,utilizando o Banco de Dados PostgreSQL ,onde comprovei que se tornou a melhor opção ao projeto por justamento entregar uma quantidade maior de funcionalidades e recursos quando comparado ao MYSQL E SQLSERVER(já utilizei em produção).

# STACK : 
-Python (GERAÇÃO DE UUID4)
- Node.js(ENVIO DE E-MAIL COM NODEMAILER)
- HTML + CSS3 (INTERFACE DE REGISTRO E LOGIN)
- POSTGRESQL(BANCO DE DADOS)
- JAVASCRIPT(LOGICA NO FRONT-END)

#ESTRUTURA DO PROJETO 
(60%)

#DECISÕES:
A escolha de usar o POSTGRE gira em torno do banco ter funcioanlidades com menos restrições e uma facilidade de integração com o PYTHON,onde fica armazenado o UUID, para neste caso ter uma ligação direta e atender a proposta do projeto, uma decisão tecnica!

A escolha pelo Nodemailer ,também é uma decisão de conceito, ou seja, não fugiu muito da proposta do projeto e decisão pessoal de ser instalado e executado mais facilmente.

Sobre o UDID4 ,após diveros testes com outras versões ,essa versão 4 obteve um resultado melhor na questão de tamanho e aleatoriedade, pois eu precisava de junção de números e letras.


#ENGLISH TRANSLATE

# PRIVATE-SYSTEM

A hosting system built with privacy as a principle — not as an added feature.

# Motivation
The idea arose from a simple question: how much does a guest really need to reveal to make a reservation?

The answer for this project is: just an email. No name, phone number, or ID. The guest receives a unique code, and everything works with that code — from check-in to payment.

#FUNCTIONALITY

Guest Email

│

▼
Unique Code Generation (UUID4)

│

▼
Sending the code via email (Nodemailer)

│

▼ Login and access with the code

│

▼
Payment via Bitcoin

#Features Present
- Sending the code to the email using Nodemailer (Node.js)
- Unique code generator using UUID4 (PYTHON), which proved to be more effective for the project concept
- Guest registration through a simple login/registration screen in HTML, CSS.

- Storage of email data and its respective code, using the PostgreSQL Database, which I found to be the best option for the project precisely because it delivers a greater number of functionalities and resources when compared to MySQL and SQL Server (which I have already used in production).

# STACK:

- Python (UUID4 GENERATION)
- Node.js (EMAIL SENDING WITH NODEMAILER)
- HTML + CSS3 (REGISTRATION AND LOGIN INTERFACE)
- POSTGRESQL (DATABASE)
- JAVASCRIPT (FRONT-END LOGIC)

# PROJECT STRUCTURE

(60%)

# DECISIONS:

The choice to use POSTGRE revolves around the database having functionalities with fewer restrictions and ease of integration with PYTHON, where the UUID is stored, in this case to have a direct link and meet the project's proposal, a technical decision!

The choice of Nodemailer is also a conceptual decision, that is, it did not deviate much from the project's proposal and a personal decision for it to be easier to install and run.

Regarding UDID4, after several tests with other versions, this version 4 achieved a better result in terms of size and randomness, as I needed a combination of numbers and letters.








