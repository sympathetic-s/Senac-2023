# Desenvolvimento de uma modelagem de projeto voltado a gestão de dados de um centro universitário 

A modelagem do projeto foi pensada para uma melhor estruturação de uma gestão de dados de um centro universitário. Através dos conceitos de elaboração de projetos da [UML](https://www.uml.org/) foi desenvolvimento um protótipo capaz de representar o cadastro de diferentes tipos de pessoas em um sistema de universidade. O software é configurado com base no diagrama de casos de uso onde o administrador controla os dados inseridos e define as permissões que cada usuário possui. 

O **diagrama de casos de uso** tem como função exemplificar em como os usuários interagem com os sistemas e como usuários secundários se relacionam com outros usuários. Ele destaca diferentes casos de uso, ou cenários, nos quais os atores interagem com o sistema para atingir objetivos específicos. O **diagrama de classes** serve de estrutura e para se observar a relação das classes que irão servir de modelo para objetos, além de desempenhar um papel fundamental em todas as fases do ciclo de vida do desenvolvimento do software, desde a análise e projeto até a implementação e manutenção do sistema. 


&nbsp;


## Diagrama de casos de uso

![Página inicial](Imagens/Diagrama-de-casos-de-uso.png)


&nbsp;


## Diagrama de classes

![Página inicial](Imagens/Diagrama-de-classes.png)


&nbsp;


# Interface do trabalho

Através dos diagramas foi elaborado uma interface do trabalho utilizando Html e CSS.

&nbsp;


## Sobre o projeto

As páginas foram desenvolvidas para ter uma funcionalidade próxima ao BlackBoard usado no Senac.


&nbsp;


![Projeto](Imagens/Sobre-o-projeto.png)


&nbsp;


## Página inicial

Logo de início mostra os nomes dos criadores do projeto. 


&nbsp;


![Página inicial](Imagens/Página-inicial.png)

&nbsp;


## Página inicial

O software se inicia mostrando a tela inicial tendo o Senac como pano de fundo.


&nbsp;


![Página inicial](Imagens/Página-inicial-2.png)


&nbsp;


## Login e senha

Para os que já possui cadastro, existe a opção de fazer o login.


&nbsp;


![Login e senha](Imagens/Login-e-senha.png)


&nbsp;


## Cadastro alunos

Nesta página inicial existe a possibilidade de um aluno se cadastrar, inserindo dados pessoais.


&nbsp;


![Página inicial](Imagens/Cadastro-alunos.png)


&nbsp;


## Cadastro professor

A mesma opção de cadastro existe para os professores. 


&nbsp;


![Página inicial](Imagens/Cadastro-professor.png)


&nbsp;


## Cadastro parceiros

O cadastro para parceiros se diferencia com a obrigação de inserir CNPJ e nome fantasia.


&nbsp;


![Página inicial](Imagens/Cadastro-parceiros.png)


&nbsp;


# Classes do trabalho (backend)

Nessa parte do trabalho foi utilizado a linguagem de programação Java para criar as classes da gestão de dados do centro universitário.


&nbsp;


## Domain turma

Nesta tela de códigos podemos perceber as informações referentes às turmas dos alunos. Estas são descritas por uma identificação, nome e ano. É possível visualizar, adicionar ou remover disciplinas.


&nbsp;


![Página inicial](Imagens/Domain-turma.jpeg)


&nbsp;


## Domain professor

A tela de códigos representa a classe dos professores. Estes serão definidos pelo seu código de identificação, matrícula, nome e data de nascimento.


&nbsp;


![Página inicial](Imagens/Domain-professor.jpeg)


&nbsp;


## Domain disciplina

Nesta etapa, os códigos utilizados descrevem as informações que podem ser cadastradas e/ou alteradas dentro das disciplinas, sendo elas: matricular/desmatricular alunos, cadastrar o professor da disciplina, definir código para disciplina, carga horária e listar alunos inscritos.

&nbsp;


![Página inicial](Imagens/Domain-disciplina.jpeg)


&nbsp;


## Domain aluno

Os códigos utilizados definem a classe dos alunos. Os alunos serão caracterizados por um código de identificação, matrícula, nome e data do nascimento.

![Página inicial](Imagens/Domain-aluno.jpeg)



