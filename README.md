# Arquitetura de Sistemas Java - Projeto delivery API

Sistema de delivery desenvolvido com **Java** e **Spring Boot**.

Link para [material do curso e referências](https://github.com/adrianoenache/Arquitetura-de-Sistemas-Java).

## 🚀 Tecnologias

- Java **21.0.9**
- Spring Boot **3.5.10**
- Spring Web
- Spring Data JPA
- H2 Database
- Maven

## ⚡ Recursos Modernos Utilizados

- Records (Java **14+**)
- Text Blocks (Java **15+**)
- Pattern Matching (Java **17+**)
- Virtual Threads (Java **21**)

## 🏃‍♂️ Como executar

1. Pré-requisitos: **JDK 21** instalado
2. Clone o repositório [https://github.com/adrianoenache/delivery-api-adrianoenache](https://github.com/adrianoenache/delivery-api-adrianoenache)
3. Acesse a pasta e execute na raiz: `mvnw spring-boot:run`
4. Acesse: [http://localhost:8080/health](http://localhost:8080/health)

## 📋 Endpoints

- GET [/info](http://localhost:8080/info) - Status da aplicação (inclui versão Java)
- GET [/health](http://localhost:8080/health) - Informações da aplicação
- GET [H2 console](http://localhost:8080/h2-console/) - Console do banco H2

## 🔧 Configuração

- Porta: **8080**
- Banco: **H2 em memória**
- Profile: **development**

## 👨‍💻 Desenvolvedor

Adriano Enache - TI2601 03731 Arquitetura de Sistemas

Desenvolvido com **JDK 21** e **Spring Boot 3.5.10**
