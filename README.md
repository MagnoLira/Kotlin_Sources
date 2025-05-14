# Kotlin Sources

A repository containing Kotlin study materials, and experiments. This space includes applications and reference resources focused on backend development and integration with frameworks like Spring.

---

## Technologies

- **Java**
- **Kotlin**
- **Spring Framework**
- **Spring Boot**
- **JPA / Hibernate**
- **Databases (PostgreSQL, MySQL, etc.)**

---

## Useful References (Kotlin + Spring)

-  [@Autowired and Dependency Injection in Spring (Medium)](https://medium.com/@leonardogiuliani/autowired-e-a-injeção-de-dependência-do-spring-d8864cc9af50)

- [Official Spring Documentation with Kotlin](https://docs.spring.io/spring-framework/reference/languages/kotlin.html)

- [Creating a Database Entity with Kotlin (Android + Room)](https://dev.to/theplebdev/creating-a-database-entity-with-android-and-kotlin-4mhc)

- [Using `CrudRepository` with Kotlin (Spring Boot)](https://kotlinlang.org/docs/jvm-spring-boot-using-crudrepository.html)

---

## Work in Progress

This repository is under active development. New projects and materials will be added as learning progresses.












# backend

Here it is structure suggestions:
        backend/
        ├── manage.py                    # Script para comandos do Django
        ├── backend/                     # Configurações principais do projeto
        │   ├── __init__.py
        │   ├── settings.py              # Configurações do projeto (usando .env)
        │   ├── urls.py                  # Rotas principais do projeto
        │   ├── asgi.py                  # Entrada para servidores ASGI (async)
        │   └── wsgi.py                  # Entrada para servidores WSGI (sync)
        ├── core/                        # App principal da aplicação
        │   ├── __init__.py
        │   ├── admin.py                 # Registro de modelos no Django Admin
        │   ├── apps.py                  # Configurações do app
        │   ├── models.py                # Modelos de dados
        │   ├── views.py                 # Views (lógicas de requisição)
        │   ├── urls.py                  # Rotas específicas do app
        │   └── migrations/              # Controle de migrações do banco de dados
        ├── requirements.txt             # Lista de dependências do projeto
        ├── .env                         # Variáveis de ambiente (não versionado)
        ├── Dockerfile                   # Imagem Docker do backend
        └── docker-compose.yml           # Orquestração com PostgreSQL e Django


