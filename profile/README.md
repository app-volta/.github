# VOLTA

Uma solução para ajudar empresas a descartar seus resíduos industriais de forma mais simples, rastreável e inteligente.

---

## A ideia

Muitas empresas ainda têm dificuldade para descartar corretamente os resíduos gerados em suas operações. Esse processo hoje costuma ser manual, demorado e desorganizado: WhatsApp, planilhas, e-mails e ligações para tentar encontrar alguém que aceite o material.

O **VOLTA** nasce para resolver esse problema de um jeito simples:

1. O colaborador da empresa **tira uma foto** do resíduo direto pelo celular.
2. Essa foto gera automaticamente uma **ocorrência** dentro do sistema.
3. Uma **Inteligência Artificial analisa a imagem** e entende que tipo de resíduo é aquele.
4. Com base nessa análise, o VOLTA **indica as melhores cooperativas** de reciclagem para fazer o descarte — considerando o tipo de material, a localização e outros critérios.

Ou seja: menos burocracia para a empresa, mais destino correto para o resíduo, e mais oportunidade de trabalho para as cooperativas de reciclagem.

## Objetivo

O objetivo do VOLTA é conectar empresas que geram resíduos industriais a cooperativas de reciclagem de forma prática e inteligente, substituindo processos manuais por um fluxo digital simples: **foto → ocorrência → análise por IA → recomendação de cooperativas**.

## Como o sistema é organizado

De forma bem resumida, o sistema é dividido em três partes que conversam entre si:

- **Aplicativo mobile** — onde o usuário tira a foto e acompanha suas ocorrências.
- **API** — o "cérebro" do sistema, que recebe as informações do aplicativo, conversa com a Inteligência Artificial e organiza as recomendações de cooperativas.
- **Banco de dados** — onde tudo fica armazenado com segurança e histórico.

Todo o projeto é versionado no GitHub e containerizado, o que facilita o trabalho em equipe e a colocação do sistema no ar.

---

## Equipe

O projeto é desenvolvido por dois grupos: os alunos do **1º ano**, criadores e donos originais da ideia, e os alunos do **2º ano**, responsáveis por desenvolver a solução.

### 1º Ano — Idealizadores

| Integrante | Frente | Ferramentas |
|---|---|---|
| Miguel Lapa | Banco de Dados | SQL |
| Lucca | Desenvolvimento I | HTML e CSS |
| Gustavo Sousa | Lógica de Programação | Java |
| Gustavo Sousa | Programação Orientada a Objetos | Java, JDBC, Spring |
| Gustavo Sousa | Sistemas Operacionais | Excel, REGEX, Git |
| Gustavo Sousa | Introdução à Inteligência Artificial | — |
| Gustavo Azenha | Experiência do Usuário (UX) | Figma |

### 2º Ano — Desenvolvedores

| Integrante | Frente | Ferramentas |
|---|---|---|
| Lucas Fabiano | Modelagem de Dados | SQL |
| Lucas Fabiano | Banco de Dados II | MongoDB, Redis, Neo4j |
| Gabriel Peotta | Business Intelligence | Python, Databricks |
| Gabriel Peotta | Inteligência Artificial | Python, LangChain/LangGraph, MongoDB, FastAPI |
| Enzo Herrera | Desenvolvimento II | Spring Boot, Maven, Swagger, JWT |
| Enzo Herrera | DevOps Ágeis | Docker, Docker Compose, Cloud, Kubernetes |
| Breno / Carlos | Aplicações Dinâmicas | JavaScript, TypeScript, React |
| Carlos Amaral | Aplicativo Móvel | Android nativo, Java, XML, Gradle *(inicialmente previsto em Kotlin/Firebase)* |
| Davi Liu | Engenharia de Software | Diagramas e metodologia |
| Breno | UX | Figma |

---

## Repositórios

Todo o código do projeto está organizado na organização **[app-volta](https://github.com/app-volta)** no GitHub, dividido em 11 repositórios:

| Repositório | O que contém |
|---|---|
| [volta-mobile](https://github.com/app-volta/volta-mobile) | Aplicativo mobile (Android nativo). |
| [volta-api](https://github.com/app-volta/volta-api) | API principal do sistema (Spring Boot). |
| [volta-api-nosql](https://github.com/app-volta/volta-api-nosql) | Camada de dados NoSQL (MongoDB, Redis, Neo4j). |
| [volta-database](https://github.com/app-volta/volta-database) | Modelagem e banco de dados relacional (SQL). |
| [volta-chatbot](https://github.com/app-volta/volta-chatbot) | Módulo de Inteligência Artificial (Python). |
| [volta-business-inteligence](https://github.com/app-volta/volta-business-inteligence) | Análises e dashboards de Business Intelligence. |
| [volta-landing-page](https://github.com/app-volta/volta-landing-page) | Página/aplicação web do projeto. |
| [volta-devops](https://github.com/app-volta/volta-devops) | Infraestrutura, containers e automações de deploy. |
| [volta-docs](https://github.com/app-volta/volta-docs) | Documentação, diagramas e metodologia do projeto. |
| [volta-website-dad](https://github.com/app-volta/volta-website-dad) | Website institucional do projeto. |
| [.github](https://github.com/app-volta/.github) | Configurações e arquivos padrão da organização. |

> Cada repositório é mantido pela frente correspondente da equipe, seguindo a divisão apresentada acima.

---

### Sobre este documento

Este README foi escrito para apresentar o VOLTA de forma simples e acessível — a ideia por trás do projeto, o objetivo, quem faz parte da equipe e onde encontrar cada parte do código. Para detalhes técnicos de arquitetura, funcionalidades e regras de negócio, consulte a documentação em [volta-docs](https://github.com/app-volta/volta-docs).