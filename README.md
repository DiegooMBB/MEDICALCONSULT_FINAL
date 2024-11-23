# Medical Consult API

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Java](https://img.shields.io/badge/Java-17-blue)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.0-green)
![License](https://img.shields.io/badge/license-MIT-blue)

## 📖 Sobre o Projeto
Medical Consult é uma API RESTful desenvolvida para gerenciar usuários, consultas e permissões de um sistema médico. O objetivo é facilitar a integração entre diferentes atores do ambiente clínico e melhorar a experiência dos usuários.

---

## 🚀 Tecnologias Utilizadas
- **Java 17**: Linguagem principal para desenvolvimento.
- **Spring Boot 3.0**: Framework para criação de APIs robustas e escaláveis.
- **Maven**: Gerenciamento de dependências e build.
- **Banco de Dados**: H2 para testes.

---

## ⚙️ Funcionalidades
- **Gerenciamento de Usuários**:
  - Cadastro, atualização e remoção.
  - Autenticação e permissões (Admin, Secretário, Paciente).

- **Gerenciamento de Consultas**:
  - Agendamento, cancelamento e histórico.

---

## 📂 Estrutura do Projeto

```plaintext
medicalConsult-master
├── src
│   ├── main
│   │   ├── java/br/com/diegom/medicalconsult
│   │   │   ├── domain    # Modelos de domínio
│   │   │   ├── services  # Regras de negócios
│   │   │   ├── controllers # Endpoints RESTful
│   │   │   ├── repositories # Interface com banco de dados
│   │   ├── resources
│   │   │   ├── application.yml # Configurações do Spring
│   ├── test  # Testes unitários
├── pom.xml  # Configuração do Maven
└── README.md # Documentação do projeto
