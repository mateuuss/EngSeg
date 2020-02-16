# Projetos para a cadeira de Engenharia de Segurança

Tal como referido na primeira aula, o "Projeto de desenvolvimento de software" / "Investigação sobre um
tópico" é uma componente de avaliação da cadeira de Engenharia de Segurança (componente C) que vale
75% da nota final, e que é constituída por 3 projetos, a entregar nas seguintes datas:

+ Projeto 1 - 23/03/2020
+ Projeto 2 - 04/05/2020
+ Projeto 3 - 08/06/2020


Estes projetos são feitos por um grupo de trabalho com o máximo de 3 elementos.

As **reuniões de projeto** ocorrerão sempre que os alunos as pedirem (por favor enviem um mail prévio a marcar um slot de reunião), às segundas-feiras a seguir à UC de Engenharia de Segurança.

Existe também um *workspace* da UC no slack para ser utilizado no âmbito da UC de  Engenharia de Segurança.
Para se juntar, utilize o convite em
https://join.slack.com/t/engenhariadeseguranca/shared_invite/enQtNTU1Mzk4MTc2NjE1LTc2NTExY2U5Y2RiNmZkY2I4MGFlOTZkZGMyMTEzZTc0Y2UzM2VhMTczZjU4ZWI5YzY4N2JiNWVhZjVmMTk1MDM



## 1. Projeto 1

Cada grupo vai efetuar investigação sobre o tópico de desenvolvimento seguro de software, sendo esperado que no final entreguem um relatório escrito, assim como façam uma apresentação oral (30 minutos) em formato de aula.

Consoante o número do seu grupo, para a realização deste projeto deverá centrar a sua atenção nos seguintes documentos de apoio:

+ Grupo 1 - [Principles for Software Assurance Assessment](https://safecode.org/wp-content/uploads/2015/11/SAFECode_Principles_for_Software_Assurance_Assessment.pdf)
+ Grupo 2 - [Fundamental Practices for Secure Software Development, Third Edition](https://safecode.org/wp-content/uploads/2018/03/SAFECode_Fundamental_Practices_for_Secure_Software_Development_March_2018.pdf)
+ Grupo 3 - [Software Security Takes a Champion](https://safecode.org/wp-content/uploads/2019/02/Security-Champions-2019-.pdf)
+ Grupo 4 - [Tactical Threat Modeling](https://safecode.org/wp-content/uploads/2017/05/SAFECode_TM_Whitepaper.pdf)
+ Grupo 5 - [Managing Security Risks Inherent in the Use of Third-party Components](https://safecode.org/wp-content/uploads/2017/05/SAFECode_TPC_Whitepaper.pdf)
+ Grupo 6 - [Practices for Secure Development of Cloud Applications](https://safecode.org/wp-content/uploads/2018/01/SAFECode_CSA_Cloud_Final1213.pdf)
+ Grupo 7 - [OWASP Proactive Controls](https://github.com/OWASP/CheatSheetSeries/blob/master/IndexProactiveControls.md)
+ Grupo 8 - [OWASP Mobile Application Security Verification Standard (MASVS)](https://mobile-security.gitbook.io/masvs/)
+ Grupo 9 - [OWASP Mobile Security Testing Guide (MSTG)](https://owasp.org/www-project-mobile-security-testing-guide/)


## 2. Projeto 2

Cada grupo vai efetuar investigação sobre ferramentas de qualidade de software e/ou testes de segurança, sendo esperado que no final entreguem um relatório escrito, assim como façam uma apresentação oral (30 minutos) em formato de aula.

O trabalho dos 8 primeiros grupos é efetuado no âmbito de _indicadores de qualidade_ do código/software, podendo tomar como base o trabalho de [The TIOBE Quality Indicator a pragmatic way of measuring code quality](https://www.tiobe.com/files/TIOBEQualityIndicator_v4_3.pdf):

> To obtain a systematic way of measuring and qualifying these measurements, the 8 most commonly used
> software code quality metrics in industry today have been selected that can be measured in an automated
> way. These are:
> 1. Code coverage
> 2. Abstract interpretation
> 3. Cyclomatic complexity
> 4. Compiler warnings
> 5. Coding standards
> 6. Code duplication
> 7. Fan out
> 8. Security 

O objetivo destes 8 primeiros grupos é explicarem o que é o indicador de qualidade  de software analisado, para que serve, quais as ferramentas (pode encontrar [aqui](https://www.tiobe.com/tics/fact-sheet/) alguma informação, mas espera-se que no relatório utilize também outras fontes para apresentar mais e melhores ferramentas) utilizadas consoante a linguagem de programação, detalhando ferramentas open-source e apresentando exemplos básicos e avançados da sua utilização.

+ Grupo 1 - Ferramentas e técnicas de *Code coverage*
+ Grupo 2 - Ferramentas e técnicas de *Abstract Interpretation* / * Deep Flow Analysis*
+ Grupo 3 - Ferramentas e técnicas de *Cyclomatic complexity*
+ Grupo 4 - Ferramentas e técnicas de *Compiler warnings*
+ Grupo 5 - Ferramentas e técnicas de *Coding standards*
+ Grupo 6 - Ferramentas e técnicas de *Code duplication*
+ Grupo 7 - Ferramentas e técnicas de *Fan out*
+ Grupo 8 - Ferramentas e técnicas de *Security*

O Grupo 9 irá analisar e explorar as ferramentas [OWASP Code Pulse](https://owasp.org/www-project-code-pulse/) e [OWASP ZAP](https://www.zaproxy.org/), apresentando exemplos básicos e avançados da sua utilização.


## 3. Projeto 3

Baseado no que foi aprendido no Projeto 1 e Projeto 2, cada grupo irá desenvolver numa linguagem de programação distinta, uma aplicação comando linha (CLI) que permita testar as operações do serviço SCMD (Signature CMD), fazendo *reverse engineer* da aplicação [CMD-SOAP](https://github.com/devisefutures/CMD-SOAP).

+ Grupo 1 - C
+ Grupo 2 - Rust
+ Grupo 3 - Ruby
+ Grupo 4 - PHP
+ Grupo 5 - Java
+ Grupo 6 - Node
+ Grupo 7 - Go (Golang)
+ Grupo 8 - Swift
+ Grupo 9 - Perl

No final deverá disponibilizar o código e relatório no github (ou gitlab ou similar), devendo explicitar no relatório:

+ Técnicas de desenvolvimento seguro de software utilizou, e como as aplicou;
+ Ferramentas e indicadores de qualidade  de software utilizados, e com que resultados.
