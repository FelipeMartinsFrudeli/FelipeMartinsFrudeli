# Felipe Frudeli

**Engenheiro de Software Backend / Full Stack**  
TypeScript · Node.js · NestJS · Java · Spring Boot · PostgreSQL · Redis · Docker

Backend, arquitetura e confiabilidade de sistemas. Experiência com aplicações em produção, SaaS multi-tenant, APIs, processamento assíncrono, integrações externas, aplicações offline-first e modernização de sistemas legados.

## Tecnologias

**Backend**  
TypeScript · Node.js · NestJS · Java · Spring Boot · APIs REST · WebSockets

**Dados**  
PostgreSQL · SQL · Redis · TypeORM · Weaviate

**Arquitetura**  
Arquitetura Hexagonal · SaaS Multi-tenant · Use Cases · IoC · Filas · Workers · RBAC · RAG · Agentes de IA · Eventos de Domínio · Observers

**IA / Observabilidade**  
LangChain · Langfuse · APISIX AI Gateway · LLMs · Busca Vetorial · SonarQube

**Infraestrutura**  
Docker · Linux · CI/CD · Jenkins · AWS

**Frontend**  
React · React Native

## Experiência em destaque

### AGROOPS — Plantoo

Plataforma multi-tenant para operações do agronegócio.

- Migrei um **backend legado em Express.js**, com regras de negócio acopladas aos controllers, para **Spring Boot 21 com arquitetura hexagonal**.
- Distribuí responsabilidades entre **entidades de domínio ricas, casos de uso e infraestrutura desacoplada por interfaces e IoC**, aumentando a testabilidade.
- Reduzi a dívida de manutenibilidade em **45%**.
- Adicionei **testes unitários e de integração** e acompanhei métricas de qualidade com **SonarQube**.
- Desenvolvi módulo de **controle de ponto com geolocalização e geofences**.
- Implementei reconhecimento facial com **AWS Rekognition + Amazon S3**.
- Desenvolvi funcionalidades **offline-first em React Native** para operações agrícolas com conectividade instável.

### IA Flow — Petri Tecnologia

SaaS multi-tenant de atendimento, tickets e automação com agentes de IA.

- Integrei conexões **WhatsApp via Baileys**, isolando a dependência externa em uma **facade** e propagando mudanças por meio de **eventos de domínio e observers**, reduzindo acoplamento entre a integração e as regras de negócio.
- Desenvolvi agentes de atendimento com **RAG, LangChain e Weaviate**.
- Estruturei bases de conhecimento com escopo por **empresa, agente, canal e fila**.
- Implementei ferramentas de agente, handoff para humanos e transferências entre filas.
- Integrei **APISIX como AI Gateway** para acesso a LLMs, quotas, tokens e custos por empresa.
- Utilizei **Langfuse** para observabilidade dos fluxos de IA.
- Implementei processamento assíncrono com **filas e workers**.
- Desenvolvi ciclo de vida de tickets, lembretes, auto-close, transferências e proteção contra duplicidade.
- Estruturei isolamento **multi-tenant** de dados, configurações e conhecimento.
- Desenvolvi testes automatizados de agentes, ferramentas e escalonamento para atendimento humano.

### Inovent — Petri Tecnologia

ERP com módulos administrativos e fiscais.

- Usuários, perfis, permissões e auditoria.
- Fluxos fiscais e emissão de **NF-e**.
- Gestão de entidades, produtos e operações administrativas.

### Comodoro — Petri Tecnologia

Plataforma de entregas.

- Fluxos de solicitações de entrega.
- Operação de restaurantes e entregadores.
- Rotinas de despacho integrando backend e aplicação web.

## Atualmente estudando

- C++17/20
- Estruturas de dados e algoritmos
- Arquitetura de computadores
- Sistemas operacionais
- Performance
- Sistemas distribuídos

## Direção técnica

Meu foco atual é continuar como engenheiro Backend enquanto avanço para **C++ e hardware, especialmente software industrial e aplicações relacionadas à indústria de semicondutores.**

## Formação

**Técnico em Desenvolvimento de Sistemas**  
ETEC Sales Gomes — Tatuí/SP · Concluído em 2025

## Contato

[LinkedIn](https://linkedin.com/in/felipe-frudeli/) · [E-mail](mailto:contato@felipefrudeli.com) · [GitHub](https://github.com/FelipeMartinsFrudeli)
