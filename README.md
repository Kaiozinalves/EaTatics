# EATatics 🎮

EATatics is an AI-powered platform for EA FC players that unifies tactical microlearning, transfer market monitoring, and team matchmaking. This repository contains the academic project developed for the Detailed Software Design course at IMD - UFRN.

---

## 🚀 Visão Geral
O objetivo do sistema é unificar as informações dispersas da comunidade e utilizar Inteligência Artificial para atuar como um treinador particular e olheiro, focando em corrigir erros de gameplay e otimizar a economia de moedas do usuário. O sistema atende tanto jogadores do modo **Ultimate Team** quanto do **Pro Clubs**.

## ✨ Principais Funcionalidades

* **Microlearning Pós-Derrota (IA):** Análise de estatísticas da partida para diagnosticar falhas e prescrever treinos rápidos de correção.
* **Oráculo do Mercado:** Monitoramento inteligente da wishlist com alertas de queda de preço para cartas do Ultimate Team.
* **Matchmaking de Sinergia (IA):** Algoritmo que conecta o estilo de jogo do usuário com equipes de Pro Clubs que precisam daquela exata função tática.
* **Central de Tutoriais:** Curadoria automática de vídeos de fundamentos consumindo a API do YouTube.

## 🛠️ Tecnologias Utilizadas

**Back-end:**
* Java 17+
* Spring Boot (Spring Web, Spring Data JPA)
* PostgreSQL


**Front-end:**
* React.js 

## 📅 Cronograma de Sprints (MVP)

- **Sprint 1 (Fundação):** Autenticação de usuários, criação de perfis (Ultimate Team/Pro Clubs) e persistência de dados estatísticos iniciais.
- **Sprint 2 (Visualização e Integração):** Dashboards de evolução, integração com a API do YouTube e lógica inicial da Wishlist de mercado.
- **Sprint 3 (Inteligência Artificial):** Integração com a API do Gemini para rodar o Matchmaking de Sinergia e as predições do Microlearning.

---
*Projeto desenvolvido para fins acadêmicos.*
