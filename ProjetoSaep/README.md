# 📦 SAEP DB4 - Sistema Web com Spring Boot

## 📋 Sobre o Projeto

Este projeto consiste em um sistema web desenvolvido utilizando **Spring Boot**, seguindo o padrão de arquitetura MVC. A aplicação oferece funcionalidades completas de gerenciamento, incluindo cadastro e controle de usuários, produtos, tipos e movimentações.

O sistema já se encontra totalmente funcional, contando com scripts SQL (`schema.sql` e `data.sql`) responsáveis pela criação e população inicial do banco de dados automaticamente durante a execução.

---

## 🚀 Requisitos do Sistema

Para garantir o funcionamento ideal do projeto, é necessário que o ambiente possua os seguintes requisitos:

- **Sistema Operacional:** Windows, Linux ou macOS  
- **Java:** JDK 17 ou superior  
- **Gerenciador de Dependências:** Maven 3.8+ (ou uso do Maven Wrapper já incluído no projeto)  
- **Navegador Web:** Google Chrome (recomendado), Edge ou Firefox  

Além disso, o projeto já está preparado para configurar automaticamente o banco de dados ao iniciar. Caso seja necessário utilizar um banco externo (como MySQL), basta realizar os ajustes no arquivo `application.properties`.

---

## ⚙️ Execução do Projeto

A execução pode ser feita de forma simples através do terminal, diretamente na pasta raiz do projeto.

### Maven Wrapper (Recomendado)

**Windows:**
mvnw.cmd spring-boot:run

**Linux/Mac:**
./mvnw spring-boot:run

### Maven Instalado

mvn spring-boot:run

Após a inicialização, acesse:
http://localhost:8080

---

## 📁 Estrutura do Projeto

- `controller/` → Requisições HTTP  
- `service/` → Regras de negócio  
- `repository/` → Banco de dados  
- `model/` → Entidades  
- `config/` → Configurações  
- `templates/` → HTML (Thymeleaf)  
- `static/` → CSS e JS  
- `application.properties` → Configurações  
- `schema.sql` e `data.sql` → Banco de dados  

---

## 🔐 Segurança

O sistema possui autenticação e controle de acesso configurados na classe `SecurityConfig`.

---

## 📊 Funcionalidades

- Cadastro e login de usuários  
- Gerenciamento de produtos  
- Cadastro de tipos  
- Controle de movimentações  
- Interface web com Thymeleaf  

---

## 🧠 Tecnologias Utilizadas

- Java  
- Spring Boot  
- Spring MVC  
- Spring Data JPA  
- Thymeleaf  
- Maven  
- HTML, CSS e JavaScript  

---

## 🛠️ IDE Recomendada

- IntelliJ IDEA  
- VS Code  
- Eclipse  

---

## 💡 Observações

O projeto já está pronto para execução imediata, com banco configurado automaticamente.

---

## ⚡ Execução Rápida

cd saep_db4-main
./mvnw spring-boot:run

Acesse: http://localhost:8080
