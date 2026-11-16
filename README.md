# Olá, sou Isaías Castro 👋

Estudante de **Engenharia da Computação** no **Instituto Federal do Ceará (IFCE)**, com foco em **desenvolvimento back-end com Java e Node.js**, e interesse crescente em **DevOps** (containers, CI/CD e automação).

![Java](https://img.shields.io/badge/Java-21%20%7C%2024-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

---

## ☕ Java

Projetos desenvolvidos durante a capacitação Java do **Capacita Brasil / iRede** e na graduação, usando POO, camadas bem separadas (model / repository / service / controller), persistência com JDBC e Hibernate e testes com JUnit.

| Projeto | O que é | Stack |
|---|---|---|
| [**fintech**](https://github.com/Isaias00C/fintech) | Sistema financeiro com clientes e contas, organizado em camadas (models, repositories, services). | Java 24, Hibernate, PostgreSQL, JavaFX, JUnit 5, Maven |
| [**loja-jpa**](https://github.com/Isaias00C/loja-jpa) | Cadastro de produtos com JPA/Hibernate e padrão DAO. Banco e phpMyAdmin sobem com um `docker compose up`. | Java 24, Hibernate, MySQL 8.4, Docker Compose, Maven |
| [**taskmanager**](https://github.com/Isaias00C/taskmanager) | Gerenciador de tarefas com interface JavaFX, persistência via JDBC, testes unitários e pipeline de CI. | Java 21, JavaFX, JDBC, MySQL, JUnit 5, GitHub Actions |
| [**emprestimo-de-livro**](https://github.com/Isaias00C/emprestimo-de-livro) | Sistema de empréstimo de livros com hierarquia de usuários, exceções customizadas e validadores. | Java, POO, Maven |
| [**Projeto-SO**](https://github.com/Isaias00C/Projeto-SO) | Simulação visual do problema produtor/consumidor ("Brincadeira de Criança") com **threads e semáforos**. | Java 21, Swing, concorrência |
| [**Java-Game**](https://github.com/Isaias00C/Java-Game) | Jogo de RPG no terminal com jogador, mobs, armas e armaduras. | Java, POO |

## 🟩 Node.js / JavaScript / TypeScript

| Projeto | O que é | Stack |
|---|---|---|
| [**Gerenciador-de-Filas-com-Redis**](https://github.com/Isaias00C/Gerenciador-de-Filas-com-Redis) | API com **filas assíncronas** e workers separados (e-mail e chamadas de sistema), validação de payload e rota de health check. | Node.js, Express 5, BullMQ, Redis (ioredis), Zod, ESLint |
| [**biblioteca-express**](https://github.com/Isaias00C/biblioteca-express) | API REST de biblioteca (livros e usuários) com ORM, migrations versionadas e configuração por variáveis de ambiente. | Node.js, Express 5, Prisma |
| [**app_ponto_central**](https://github.com/Isaias00C/app_ponto_central) | PWA em produção para controlar o estoque de camisas de um projeto social, com login e regras de acesso no banco. Deploy automático a cada push. | React 19, TypeScript, Vite, Supabase, GitHub Pages |
| [**Tree-Library**](https://github.com/Isaias00C/Tree-Library) | Sistema de biblioteca sobre uma **árvore AVL** (busca, inserção e remoção em O(log n)). | JavaScript, estruturas de dados |

## 🛠️ DevOps

Venho aplicando práticas de DevOps nos meus próprios projetos:

- **Containers:** ambientes de banco reproduzíveis com **Docker Compose** (MySQL + phpMyAdmin/Adminer) em [`loja-jpa`](https://github.com/Isaias00C/loja-jpa) e [`taskmanager`](https://github.com/Isaias00C/taskmanager), incluindo *healthcheck* e script de inicialização do schema.
- **CI:** pipeline no GitHub Actions que compila e testa com Maven (Java 21 / Temurin) e envia o grafo de dependências ao GitHub, em [`taskmanager`](https://github.com/Isaias00C/taskmanager).
- **CD:** deploy contínuo no **GitHub Pages** a cada push na `main` (`npm ci` → build → publicação), em [`app_ponto_central`](https://github.com/Isaias00C/app_ponto_central).
- **Dev containers:** ambiente de desenvolvimento padronizado com `.devcontainer`, em [`Tree-Library`](https://github.com/Isaias00C/Tree-Library).
- **Configuração e segurança:** variáveis de ambiente com `.env.example`, segredos fora do código, migrations versionadas (Prisma e SQL) e políticas de acesso no banco (Supabase).
- **Em estudo:** Kubernetes, Terraform e observabilidade.

## 🏆 Programação competitiva

Pratico lógica e algoritmos em C++ e participo de contests. As soluções ficam em [Programacao-competitiva](https://github.com/Isaias00C/Programacao-competitiva).

[LeetCode](https://leetcode.com/u/isaiascastro2014/) · [Beecrowd](https://judge.beecrowd.com/pt/profile/145283) · [Neps Academy](https://neps.academy/br/user/372) · [AtCoder](https://atcoder.jp/home) · [Codeforces](https://codeforces.com/)

## 🔬 Outros interesses

Visão computacional e Machine Learning ([MachineLearn](https://github.com/Isaias00C/MachineLearn), [computer-vision](https://github.com/Isaias00C/computer-vision)), sistemas embarcados com ESP32 ([esp32-project](https://github.com/Isaias00C/esp32-project)) e Swift ([taskmind-cli](https://github.com/Isaias00C/taskmind-cli)).

## 📊 Estatísticas do GitHub

![Estatísticas do GitHub](https://github-readme-stats.vercel.app/api?username=Isaias00C&show_icons=true&theme=radical)
![Linguagens mais usadas](https://github-readme-stats.vercel.app/api/top-langs/?username=Isaias00C&layout=compact&theme=radical)

![GitHub](https://img.shields.io/github/followers/Isaias00C?label=Seguidores&style=social)
