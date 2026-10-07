<div align="center">

<!-- <img src="./assets/banner.png" alt="VOLTA — Resíduo industrial com destino certo" width="100%"/>

<br/>

<img src="./assets/mascote.png" alt="Mascote do VOLTA" width="180"/> -->

<img src="./assets/volta.svg">

### *"Tudo que vai, VOLTA"*

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-2ED3A0?style=for-the-badge)
![Repos](https://img.shields.io/badge/repositórios-12-0B3D2E?style=for-the-badge&logo=github&logoColor=white)
![Sustentabilidade](https://img.shields.io/badge/♻️-economia%20circular-14805E?style=for-the-badge)

[A ideia](#-a-ideia) •
[ODS 12](#-ods-12--consumo-e-produção-responsáveis) •
[Como funciona](#-como-funciona) •
[Tecnologias](#-tecnologias) •
[Equipe](#-equipe) •
[Repositórios](#-repositórios)

</div>

---

## 💡 A ideia

Muitas empresas ainda têm dificuldade para descartar corretamente os resíduos gerados em suas operações. Hoje esse processo costuma ser **manual, demorado e desorganizado**: WhatsApp, planilhas, e-mails e ligações para tentar encontrar alguém que aceite o material.

O **VOLTA** conecta empresas que geram resíduos industriais a **cooperativas de reciclagem**, trocando a burocracia por um fluxo digital simples:

<div align="center">

| 📸 | ➜ | 📋 | ➜ | 🤖 | ➜ | ♻️ |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Foto** do resíduo | | **Ocorrência** criada | | **IA** identifica o material | | **Cooperativas** recomendadas |

</div>

> Menos burocracia para a empresa, mais destino correto para o resíduo e mais oportunidade de trabalho para as cooperativas.

### Por que o VOLTA existe

No dia a dia de uma indústria, o resíduo é um problema que ninguém quer carregar: sobra de material, peça descartada, embalagem, sucata. Quem tem pouco tempo acaba deixando o material parado, descartando de forma inadequada ou aceitando a primeira solução que aparece. Do outro lado, existem cooperativas de reciclagem que precisam de matéria-prima e não sabem onde ela está.

O VOLTA nasce para ser a **ponte entre esses dois lados**. O aplicativo foi pensado para ser tão simples que qualquer colaborador consiga usá-lo no meio da operação, sem treinamento: basta abrir o app e fotografar o resíduo.

### O que o aplicativo faz por você

- **Registra a ocorrência na hora:** a foto, o local e os dados da empresa viram um registro rastreável, no lugar de uma mensagem perdida em um grupo de WhatsApp.
- **Identifica o material com IA:** a imagem é analisada para entender que tipo de resíduo é aquele, sem a empresa precisar classificar na mão.
- **Indica para onde o resíduo deve ir:** as cooperativas são recomendadas conforme o tipo de material, a localização e outros critérios, e um ranking dinâmico ajuda a escolher a melhor opção.
- **Mantém o histórico:** a empresa acompanha cada ocorrência e prova que deu um destino correto ao que gerou.
- **Tira dúvidas pelo chat:** um assistente conversacional orienta o usuário durante o processo.

O intuito final é duplo: **simplificar a vida de quem gera o resíduo** e **gerar trabalho e renda para quem recicla**, fechando o ciclo em que o que seria descartado volta para a cadeia produtiva.

## 🌍 ODS 12 — Consumo e Produção Responsáveis

<div align="center">

![ODS 12](https://img.shields.io/badge/ODS%2012-Consumo%20e%20Produ%C3%A7%C3%A3o%20Respons%C3%A1veis-BF8B2E?style=for-the-badge)

</div>

O **Objetivo de Desenvolvimento Sustentável 12**, da Agenda 2030 da ONU, propõe assegurar padrões de produção e de consumo sustentáveis. Ele olha para o ciclo inteiro: usar melhor os recursos, gerar menos resíduos e dar um destino adequado ao que sobra.

O VOLTA se conecta diretamente a esse objetivo, principalmente a três metas:

| Meta | O que diz | Como o VOLTA contribui |
|---|---|---|
| **12.4** | Gestão ambientalmente adequada de resíduos, reduzindo sua liberação no ambiente | A IA identifica o tipo de resíduo e direciona para quem sabe tratá-lo corretamente |
| **12.5** | Reduzir substancialmente a geração de resíduos por prevenção, redução, reciclagem e reuso | O resíduo industrial volta para a cadeia produtiva por meio das cooperativas de reciclagem |
| **12.6** | Incentivar empresas a adotar práticas sustentáveis | O histórico rastreável de ocorrências ajuda a empresa a comprovar seu descarte correto |

Na prática, o VOLTA reduz o descarte inadequado, aumenta o volume de material reciclado e fortalece as cooperativas, o que também reforça a economia circular e a inclusão produtiva.

## 🧩 Como funciona


```mermaid
flowchart LR
    subgraph Ano1["1º Ano"]

        L[Landing Page] --> AD[Área Admin]
        AD -->|CRUD| S[Servlet + JDBC + JSP]
        S --> DB1[(Banco 1º ano)]
    end

    subgraph Ano2["2º Ano"]

        A[Mobile]
        B[API Principal<br/>Spring Boot]
        C[API Chatbot<br/>FastAPI]
        R[API Redis<br/>Ranking Dinâmico]
        W[Website do Gerente]

        D[(PostgreSQL<br/>Neon)]
        M[(MongoDB<br/>Atlas)]

        A -->|CRUD| B
        B --> D

        A -->|Foto + dados| C
        C --> M

        B -->|Ocorrência + distância| R
        R -->|Score| W
    end

    DB1 <-->|RPA| D
```
## 🛠️ Tecnologias

<div align="center">

**Back-end**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-007ACC?style=for-the-badge&logo=apachemaven&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

**Inteligência Artificial**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white)


**Ánalise de Dados** 

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)

**Bancos de dados**

![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=for-the-badge&logo=neo4j&logoColor=white)

**Front-end**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Mobile**

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Glide](https://img.shields.io/badge/Glide-18B6F2?style=for-the-badge&logo=glide&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)

**Infraestrutura**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

**Design**

![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Maze](https://img.shields.io/badge/Maze-000000?style=for-the-badge&logo=maze&logoColor=white)

</div>

## 👥 Equipe

### 🌱 1º Ano — Idealizadores

<table align="center">
  <tr>
    <td align="center"><a href="https://github.com/miguellapa25"><img src="./assets/team/miguel-lapa.png" width="110" alt="Miguel Lapa"/><br/><b>Miguel Lapa</b></a><br/><sub>Banco de Dados</sub><br/><img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white"/></td>
    <td align="center"><a href="https://github.com/ldb2010"><img src="./assets/team/lucca.png" width="110" alt="Lucca"/><br/><b>Lucca</b></a><br/><sub>Desenvolvimento I</sub><br/><img src="https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white"/></td>
    <td align="center"><a href="https://github.com/Gustavo031210"><img src="./assets/team/gustavo-souza.png" width="110" alt="Gustavo Souza"/><br/><b>Gustavo Souza</b></a><br/><sub>Lógica, POO, SO e IA</sub><br/><img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/> <img src="https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white"/><img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-squared&logo=googlegemini&logoColor=white"></td>
    <td align="center"><a href="https://github.com/GustavoA-byte"><img src="./assets/team/gustavo-azenha.png" width="110" alt="Gustavo Azenha"/><br/><b>Gustavo Azenha</b></a><br/><sub>Experiência do Usuário</sub><br/><img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white"/></td>
  </tr>
</table>

### 🚀 2º Ano — Desenvolvedores

<table align="center">
  <tr>
    <td align="center">
    <a href="https://github.com/Lucas6323"><img src="./assets/team/lucas-fabiano.jpg" width="110" alt="Lucas Fabiano"/><br/><b>Lucas Fabiano</b></a><br/><sub>Modelagem & Banco de Dados II</sub><br/> <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/> <img src="https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white"/></td>
    <td align="center"><a href="https://github.com/gabPeotta"><img src="./assets/team/gabriel-peotta.jpeg" width="110" alt="Gabriel Peotta"/><br/><b>Gabriel Peotta</b></a><br/><sub>IA & Business Intelligence</sub><br/><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white"/></td>
    <td align="center"><a href="https://github.com/EnzoHerrera"><img src="./assets/team/enzo-herrera.jpg" width="110" alt="Enzo Herrera"/><br/><b>Enzo Herrera</b></a><br/><sub>Desenvolvimento II & DevOps</sub><br/><img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=springboot&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Brenoz001"><img src="./assets/team/breno.jpeg" width="110" alt="Breno"/><br/><b>Breno</b></a><br/><sub>Aplicações Dinâmicas & UX</sub><br/><img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/> <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white"/></td>
    <td align="center"><a href="https://github.com/Carlos-droid-max"><img src="./assets/team/carlos-amaral.jpeg" width="110" alt="Carlos Amaral"/><br/><b>Carlos Amaral</b></a><br/><sub>Mobile</sub><br/><img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white"/> <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/></td>
    <td align="center"><a href="https://github.com/Davi-O-Belo"><img src="./assets/team/davi-liu.jpeg" width="110" alt="Davi Liu"/><br/><b>Davi Liu</b></a><br/><sub>Eng. de Software & UX</sub><br/><img src="https://img.shields.io/badge/UML-0B3D2E?style=flat-square"/> <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white"/><img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square &logo=redis&logoColor=white"></td>
  </tr>
</table>

## 📦 Repositórios

| | Repositório | O que contém |
|:---:|---|---|
| 📱 | [volta-mobile](https://github.com/app-volta/volta-mobile) | Aplicativo mobile (Android nativo) |
| ⚙️ | [volta-api](https://github.com/app-volta/volta-api) | API principal do sistema (Spring Boot) |
| 🏆 | [volta-api-redis](https://github.com/app-volta/volta-api-redis) | API para ranking dinâmico (Redis) |
| 💬 | [volta-api-mongo](https://github.com/app-volta/volta-api-mongo) | API para interação conversacional (MongoDB, FastAPI) |
| 🗄️ | [volta-database](https://github.com/app-volta/volta-database) | Modelagem e banco de dados relacional (SQL) |
| 🤖 | [volta-chatbot](https://github.com/app-volta/volta-chatbot) | Módulo de Inteligência Artificial (FastAPI) |
| 📊 | [volta-business-inteligence](https://github.com/app-volta/volta-business-inteligence) | Análises e dashboards de BI |
| 🌐 | [volta-landing-page](https://github.com/app-volta/volta-landing-page) | Página/aplicação web do projeto |
| 🖥️ | [volta-website-dad](https://github.com/app-volta/volta-website-dad) | Website para uso do gerente |
| 🐳 | [volta-devops](https://github.com/app-volta/volta-devops) | Infraestrutura, containers e deploy |
| 📚 | [volta-docs](https://github.com/app-volta/volta-docs) | Documentação, diagramas e metodologia |
| 🔧 | [.github](https://github.com/app-volta/.github) | Configurações padrão da organização |

---

<div align="center">

<img src="./assets/mascote.png" alt="Mascote do VOLTA" width="70"/>

**Quer entender a fundo?** Arquitetura, funcionalidades e regras de negócio estão em [volta-docs](https://github.com/app-volta/volta-docs).

<sub>Feito com 💚 pela equipe VOLTA — porque todo resíduo merece uma segunda volta. ♻️</sub>

</div>
