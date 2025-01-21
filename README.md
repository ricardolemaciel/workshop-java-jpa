# Workshop Java JPA

Este repositório contém o código desenvolvido durante o **Workshop de Java e JPA (Java Persistence API)**, que aborda conceitos fundamentais de persistência de dados com o uso do Hibernate e outras ferramentas do ecossistema JPA.

## 🔍 Sobre o Projeto

O objetivo do workshop é ensinar os fundamentos de persistência de dados utilizando **Java** com **JPA**, focando em:

- Mapeamento objeto-relacional (ORM)
- Configuração e uso do Hibernate como provedor JPA
- Criação de entidades e relacionamentos
- Operações de CRUD com repositórios JPA
- Controle de transações

## 🛠 Tecnologias Utilizadas

- **Java 17** ou superior
- **Spring Boot** (para simplificar a integração)
- **Hibernate** como implementação JPA
- Banco de dados **H2** para persistência em memória
- **Maven** para gerenciamento de dependências

## 📁 Estrutura do Projeto

O projeto está estruturado da seguinte forma:
```plaintext
src/
├── main/
│   ├── java/
│   │   └── com.example.workshopjpa/
│   │       ├── entities/          # Entidades JPA
│   │       ├── repositories/      # Repositórios JPA
│   │       ├── services/          # Lógica de negócio
│   │       └── Application.java   # Classe principal
│   └── resources/
│       ├── application.properties # Configuração da aplicação
│       └── data.sql               # Script SQL de inicialização
└── test/                          # Testes unitários e de integração

## 🚀 Como Executar o Projeto

### Pré-requisitos

- Java 17+
- Maven instalado

### Passos

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/ricardolemaciel/workshop-java-jpa.git
   cd workshop-java-jpa
   
2. **Compile e execute o projeto com Maven:**
   ```bash
   mvn spring-boot:run

