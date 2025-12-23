# Taedium

Taedium é uma plataforma web interativa focada em micro-entretenimento e gamificação. O objetivo da aplicação é oferecer aos usuários tarefas rápidas e criativas ("micro-missões") para aliviar momentos de tédio, utilizando um sistema de recompensas e progressão.

Este projeto foi concebido como um laboratório de aprendizado contínuo ("Learning Path Project"). Ele evolui progressivamente de uma página estática simples para uma aplicação Full Stack complexa, acompanhando minha jornada de estudos em desenvolvimento de software.

## Sobre o Projeto

A aplicação resolve o problema do tédio através de desafios rápidos (1 a 5 minutos) que estimulam a criatividade ou o raciocínio. O diferencial técnico reside na sua arquitetura evolutiva: o código é refatorado e expandido conforme novos conceitos (React, Node.js, Banco de Dados, CI/CD) são adquiridos.

## Roadmap de Desenvolvimento

O desenvolvimento segue uma abordagem incremental baseada em versões, simulando um ambiente real de produto:

### Fase 1: Fundação (Versão Atual)
Foco: Lógica de programação, manipulação de DOM e Estilização.
- Desenvolvimento de interface web responsiva (HTML5 e CSS3).
- Lógica de cronômetro e seleção aleatória de missões via JavaScript (ES6+).
- Persistência de dados volátil (Arrays/JSON locais).
- Sistema de "Missão do Dia" mockado.

### Fase 2: Frontend Moderno e Tipagem
Foco: Arquitetura de Componentes e Segurança de Tipos.
- Migração completa para React.
- Implementação de TypeScript para tipagem de dados (missões, estado do usuário).
- Gerenciamento de estado da aplicação.
- Componentização de UI (Timer, Cards, Modais).

### Fase 3: Backend e API
Foco: Protocolo HTTP e Desenvolvimento de Servidor.
- Substituição dos dados mockados por uma API REST real.
- Desenvolvimento de servidor Node.js.
- Criação de endpoints para consulta de missões e submissão de resultados.

### Fase 4: Persistência e Dados
Foco: Modelagem de Dados e SQL.
- Integração com banco de dados relacional (PostgreSQL).
- Criação de tabelas para Usuários, Missões e Ranking.
- Implementação de operações CRUD completas.

### Fase 5: Full Stack e Escalabilidade
Foco: Frameworks avançados e Funcionalidades Sociais.
- Migração para Next.js (SSR/SSG).
- Implementação de autenticação (OAuth).
- Funcionalidades em tempo real (Modo Colaborativo).
- Deploy e CI/CD.

## Funcionalidades Principais (Planejadas)

- Dashboard interativo com missões diárias.
- Timer de foco para execução de tarefas.
- Sistema de feedback visual (recompensas).
- Ranking global e entre amigos.
- Modo colaborativo via link de convite.

## Tecnologias Utilizadas

As tecnologias listadas abaixo representam a stack alvo final do projeto:

- Frontend: HTML5, CSS3, React, TypeScript, Next.js
- Backend: Node.js
- Banco de Dados: PostgreSQL
- Design: Figma (Prototipagem)
- Ferramentas: Git, VS Code


Desenvolvido por TheRazorBill