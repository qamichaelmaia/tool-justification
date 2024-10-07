# Justificativa de Ferramentas para Testes Automatizados e Integração Contínua

Neste projeto de uma Plataforma Web, composto por duas equipes de desenvolvimento, utilizaremos as seguintes ferramentas: **Cypress**, **TestNG**, **MSTest**, **Mocha** e **Jenkins**. Abaixo estão as justificativas para a escolha de cada uma delas:

## Cypress
O **Cypress** é uma ferramenta de teste automatizado ideal para validar tanto a interface do usuário quanto as integrações com serviços de API. Ele permite:
- Simular interações do usuário com o sistema.
- Verificar se as chamadas de API estão retornando as respostas corretas.
- Facilitar a execução de testes de ponta a ponta (frontend e backend).

## TestNG
O **TestNG** será utilizado para criar testes unitários automatizados no ambiente **Java**. Ele oferece:
- Flexibilidade para agrupar, organizar e executar testes.
- Suporte à execução de testes em paralelo, o que melhora a eficiência e agilidade no desenvolvimento.

## MSTest
No ambiente **.NET**, será utilizado o **MSTest**. Ele possibilita:
- Criação e execução de testes unitários integrados com o Visual Studio.
- Automação de testes e manutenção da qualidade do código backend de maneira eficiente.

## Mocha
O **Mocha** será empregado para testes da aplicação frontend em **React**. Ele oferece:
- Suporte a testes unitários e de integração em **JavaScript/Node.js**.
- Uma estrutura modular para criar e organizar testes.
- Ferramentas de relatórios detalhados e cobertura de código, garantindo a robustez dos testes frontend.

## Jenkins
O **Jenkins** será a ferramenta de integração contínua utilizada para automatizar a execução dos testes. Ele garante que:
- A cada mudança no código-fonte, os testes sejam executados automaticamente.
- A validação contínua do código seja realizada, acelerando o ciclo de desenvolvimento.

---

Esse conjunto de ferramentas proporciona uma abordagem abrangente de testes, cobrindo desde o frontend até o backend, com automação do ciclo de entrega. A integração de todas elas garante a qualidade do software em todas as etapas do processo de desenvolvimento.
