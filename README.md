
# Zero Waste

Projeto pessoal criado em **Java + Angular** que simula uma rede social voltada para o **ODS 2 da ONU — Fome Zero e Agricultura Sustentável**.  
O objetivo é conectar pessoas, instituições e comunidades em ações que promovam doação de alimentos e incentivo à agricultura sustentável.

---

## Índice

1. [Visão Geral](#visão-geral)  
2. [Funcionalidades](#funcionalidades)  
3. [Arquitetura & Tecnologias](#arquitetura--tecnologias)  
4. [Estrutura do Projeto](#estrutura-do-projeto)  
5. [Requisitos & Instalação](#requisitos--instalação)  
6. [Uso](#uso)  
7. [Testes](#testes)  
8. [Possíveis Melhorias](#possíveis-melhorias)  
9. [Como contribuir](#como-contribuir)  
10. [Licença](#licença)  

---

## Visão Geral

Zero Waste é uma aplicação full‑stack, composta por backend em **Java (Spring Boot)** e frontend em **Angular**.  
Usuários podem criar postagens indicando pontos de coleta de alimentos, servindo como meio de contato / visibilidade entre quem doa, quem coleta e instituições.

---

## Funcionalidades

- Cadastro de usuário (login / autenticação)  
- Criação, edição e visualização de postagens:  
  - descrição do ponto de coleta  
  - localização (endereço ou coordenadas)  
  - imagens (se aplicável)  
- Listagem de postagens, filtro ou ordenação  
- Interface responsiva

---

## Arquitetura & Tecnologias

| Componente | Tecnologias |
|------------|-------------|
| Backend    | Java + Spring Boot |
| Frontend   | Angular |
| Autenticação | JWT / OAuth2 |
| Banco de Dados | MySQL / PostgreSQL |
| Containers | Docker |
| Infraestrutura | Linux / Apache |

---

## Estrutura do Projeto

```
zero-waste/
├── backend/            # API REST (Java, Spring Boot)
├── frontend/           # Aplicação Angular
├── README.md           # Documentação
```

---

## Requisitos & Instalação

### Requisitos

- Java JDK 11+  
- Node.js + npm  
- Banco de Dados (MySQL ou PostgreSQL)  
- Docker (opcional)  

### Instalação

```bash
# Clonar repositório
git clone https://github.com/renanbaratella/zero-waste.git
```

**Backend**

```bash
cd backend
mvn clean install
mvn spring-boot:run
```

**Frontend**

```bash
cd frontend
npm install
ng serve
```

---

## Uso

- Acesse `http://localhost:4200`  
- Cadastre-se ou faça login  
- Crie e visualize postagens de pontos de coleta de alimentos  

---

## Testes

**Backend:**

```bash
mvn test
```

**Frontend:**

```bash
ng test
```

---

## Possíveis Melhorias

- Diferenciação de perfis de usuário (doador, instituição, admin)  
- Geolocalização com mapa interativo  
- Upload de imagens mais robusto  
- Notificações (email/push)  
- CI/CD com Docker e GitHub Actions  
- Internacionalização (i18n)  

---

## Como contribuir

1. Faça um fork do projeto  
2. Crie uma branch para sua feature (`git checkout -b feature/nome-feature`)  
3. Commit suas alterações (`git commit -m 'feat: nova feature'`)  
4. Push para a branch (`git push origin feature/nome-feature`)  
5. Abra um Pull Request  

---

## Licença

Este projeto está sob a licença [MIT](LICENSE).

---
