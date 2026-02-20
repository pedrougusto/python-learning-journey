# 🐍 Python — From Fundamentals to Production APIs

> **Complete Python learning journey:** From core language fundamentals through data structures, OOP, databases, and production-ready API development with Flask, Django and FastAPI.

---

## Overview

This repository documents my **complete Python learning path**, covering everything from language fundamentals to building full-stack web applications and asynchronous APIs.

Each module contains exercises, challenges, and practical implementations that progressively build on each other — from basic syntax and data structures all the way to production-grade API development with Flask, Django, and FastAPI.

The repository reflects a structured, incremental learning approach: each module introduces new concepts that are applied in subsequent ones, culminating in three different API development frameworks that reinforce the same REST principles from different angles.

---

## Modules

| # | Module | Topics |
|---|---|---|
| 00 | **Fundamentals** | Variables, data types, control flow, functions |
| 01 | **Data Structures** | Lists, dicts, sets, tuples, comprehensions |
| 02 | **Object-Oriented Programming** | Classes, inheritance, encapsulation, polymorphism |
| 03 | **Decorators, Iterators & Generators** | `@decorator`, `yield`, lazy evaluation, custom iterators |
| 04 | **Date & Time** | `datetime`, `timedelta`, timezone handling, formatting |
| 05 | **File Manipulation** | Reading/writing files, CSV, JSON, context managers |
| 06 | **Package Management & Best Practices** | `pip`, virtual environments, `requirements.txt`, PEP8 |
| 07 | **Databases** | SQL, SQLite, ORM basics, CRUD operations |
| 11 | **API Development with Flask** | REST APIs, routing, blueprints, request/response cycle |
| 12 | **Full-Stack with Django** | MVT pattern, models, views, templates, admin panel |
| 13 | **Async APIs with FastAPI** | `async/await`, Pydantic, automatic docs, performance |

---

## Learning Path

```
Fundamentals
    │
    ▼
Data Structures ──► OOP
                      │
                      ▼
            Decorators / Iterators / Generators
                      │
                      ▼
            Date & Time · File Handling
                      │
                      ▼
            Package Management & Best Practices
                      │
                      ▼
                  Databases
                      │
                      ▼
         ┌────────────┼────────────┐
         ▼            ▼            ▼
       Flask        Django      FastAPI
    (REST API)   (Full-Stack)  (Async API)
```

---

## Tech Stack

| Technology | Purpose |
|---|---|
| **Python 3.x** | Core language |
| **Flask** | Lightweight REST API framework |
| **Django** | Full-stack web framework (MVT pattern) |
| **FastAPI** | Modern async API framework with auto-documentation |
| **SQLite / SQLAlchemy** | Database layer and ORM |
| **Pydantic** | Data validation and serialization (FastAPI) |

---

## Key Concepts Covered

**Object-Oriented Programming**
Full OOP implementation including class design, inheritance hierarchies, encapsulation, and polymorphism — the foundation for Django models and Flask/FastAPI application structure.

**Decorators, Iterators & Generators**
Advanced Python patterns used extensively in web frameworks: `@app.route`, `@login_required`, lazy data pipelines with `yield`, and custom iterator protocols.

**Asynchronous Programming (FastAPI)**
`async/await` patterns for non-blocking I/O, crucial for high-performance APIs that handle concurrent requests efficiently.

**REST API Design**
Implemented across three frameworks (Flask, Django REST, FastAPI), reinforcing how HTTP methods, status codes, request/response cycles, and resource modeling work regardless of the tool.

---

## Repository Structure

```
python-complete-course/
├── 00 - Fundamentos/
├── 01 - Estrutura de dados/
├── 02 - Programação Orientada a Objetos/
├── 03 - Decoradores, Iteradores e Geradores/
├── 04 - Data e hora/
├── 05 - Manipulação de arquivos/
├── 06 - Gerenciamento de pacotes e boas práticas/
├── 07 - Banco de dados/
├── 11 - Desenvolvimento de APIs com Flask/
├── 12 - Desenvolvimento fullstack com Django/
└── 13 - APIs Assíncronas com FastAPI/
```

---

## License

This project is licensed under the **MIT License**.

---

# 🐍 Python — Dos Fundamentos a APIs em Produção

> **Jornada completa de aprendizado em Python:** Dos fundamentos da linguagem até estruturas de dados, POO, bancos de dados e desenvolvimento de APIs com Flask, Django e FastAPI.

---

## Visão Geral

Este repositório documenta minha **trilha completa de aprendizado em Python**, cobrindo desde os fundamentos da linguagem até a construção de aplicações web full-stack e APIs assíncronas.

Cada módulo contém exercícios, desafios e implementações práticas que evoluem progressivamente — desde sintaxe básica e estruturas de dados até desenvolvimento de APIs prontas para produção.

---

## Módulos

| # | Módulo | Tópicos |
|---|---|---|
| 00 | **Fundamentos** | Variáveis, tipos de dados, controle de fluxo, funções |
| 01 | **Estrutura de Dados** | Listas, dicts, sets, tuplas, comprehensions |
| 02 | **Programação Orientada a Objetos** | Classes, herança, encapsulamento, polimorfismo |
| 03 | **Decoradores, Iteradores e Geradores** | `@decorator`, `yield`, avaliação lazy, iteradores customizados |
| 04 | **Data e Hora** | `datetime`, `timedelta`, fusos horários, formatação |
| 05 | **Manipulação de Arquivos** | Leitura/escrita de arquivos, CSV, JSON, context managers |
| 06 | **Gerenciamento de Pacotes e Boas Práticas** | `pip`, ambientes virtuais, `requirements.txt`, PEP8 |
| 07 | **Banco de Dados** | SQL, SQLite, fundamentos de ORM, operações CRUD |
| 11 | **Desenvolvimento de APIs com Flask** | REST APIs, rotas, blueprints, ciclo request/response |
| 12 | **Desenvolvimento Full-Stack com Django** | Padrão MVT, models, views, templates, painel admin |
| 13 | **APIs Assíncronas com FastAPI** | `async/await`, Pydantic, documentação automática, performance |

---

## Trilha de Aprendizado

```
Fundamentos
    │
    ▼
Estrutura de Dados ──► POO
                         │
                         ▼
             Decoradores / Iteradores / Geradores
                         │
                         ▼
             Data e Hora · Manipulação de Arquivos
                         │
                         ▼
             Gerenciamento de Pacotes e Boas Práticas
                         │
                         ▼
                   Banco de Dados
                         │
                         ▼
          ┌──────────────┼──────────────┐
          ▼              ▼              ▼
        Flask          Django        FastAPI
     (REST API)     (Full-Stack)   (API Async)
```

---

## Stack

| Tecnologia | Finalidade |
|---|---|
| **Python 3.x** | Linguagem principal |
| **Flask** | Framework REST API leve |
| **Django** | Framework web full-stack (padrão MVT) |
| **FastAPI** | Framework de API async moderno com documentação automática |
| **SQLite / SQLAlchemy** | Camada de banco de dados e ORM |
| **Pydantic** | Validação e serialização de dados (FastAPI) |

---

## Conceitos-chave Abordados

**Programação Orientada a Objetos**
Implementação completa de POO incluindo design de classes, hierarquias de herança, encapsulamento e polimorfismo — a base para os models do Django e a estrutura de aplicações Flask/FastAPI.

**Decoradores, Iteradores e Geradores**
Padrões avançados de Python amplamente usados em frameworks web: `@app.route`, `@login_required`, pipelines de dados lazy com `yield` e protocolos de iteração customizados.

**Programação Assíncrona (FastAPI)**
Padrões `async/await` para I/O não-bloqueante, fundamentais para APIs de alta performance que lidam com requisições concorrentes de forma eficiente.

**Design de REST APIs**
Implementado em três frameworks (Flask, Django REST, FastAPI), reforçando como métodos HTTP, status codes, ciclos request/response e modelagem de recursos funcionam independente da ferramenta.

---

## Estrutura do Repositório

```
python-complete-course/
├── 00 - Fundamentos/
├── 01 - Estrutura de dados/
├── 02 - Programação Orientada a Objetos/
├── 03 - Decoradores, Iteradores e Geradores/
├── 04 - Data e hora/
├── 05 - Manipulação de arquivos/
├── 06 - Gerenciamento de pacotes e boas práticas/
├── 07 - Banco de dados/
├── 11 - Desenvolvimento de APIs com Flask/
├── 12 - Desenvolvimento fullstack com Django/
└── 13 - APIs Assíncronas com FastAPI/
```

---

## Licença

Este projeto está sob a **Licença MIT**.
