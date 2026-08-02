<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:00ff41,100:000000&height=180&section=header&text=MesaLivre%20API&fontColor=ffffff&fontSize=38&animation=fadeIn)

# 🍽️ MesaLivre — Enterprise Reservation Engine

[![Build Status](https://img.shields.io/badge/Build-Passing-00ff41?style=for-the-badge&logo=github&logoColor=000000)](https://github.com/Brunnomk)
[![Java Version](https://img.shields.io/badge/Java-17%2B-000000?style=for-the-badge&logo=openjdk&logoColor=00ff41)](https://openjdk.org)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-000000?style=for-the-badge&logo=springboot&logoColor=00ff41)](https://spring.io)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15%2B-000000?style=for-the-badge&logo=postgresql&logoColor=00ff41)](https://postgresql.org)

<p align="center">
  <b>Plataforma de orquestração e gestão de reservas em restaurantes projetada para alta concorrência e consistência transacional.</b>
</p>

</div>

---

## 🛠️ Arquitetura e Decisões de Engenharia

O **MesaLivre** foi concebido para resolver o problema clássico de *overbooking* em plataformas de agendamento em tempo real. A aplicação adota os princípios de **Clean Architecture** e **Domain-Driven Design (DDD)**.

### 🎯 Diferenciais Técnicos:
* **Controle de Concorrência:** Implementação de estratégias de *Optimistic Locking* (`@Version` no JPA) para evitar escritas conflitantes em picos de concorrência.
* **Segurança Granular:** Autenticação via **JWT (JSON Web Token)** e autorização por papéis (*RBAC*) com Spring Security.
* **Prevenção N+1 Query:** Mapeamento otimizado de entidades e uso de projeções DTO/Queries customizadas no Spring Data JPA.
* **Frontend Reativo:** Interface reativa construída em Angular com manipulação de fluxos de dados assíncronos via **RxJS**.

---

## 💻 Tech Stack

| Camada | Tecnologia |
| :--- | :--- |
| **Backend Framework** | Java 17, Spring Boot 3.x, Spring Data JPA, Spring Security |
| **Database** | PostgreSQL, Flyway (Database Migration) |
| **Frontend Framework** | Angular 16+, RxJS, TypeScript |
| **Styling & UI** | Tailwind CSS / SCSS |
| **Testing & Tools** | JUnit 5, Mockito, Postman, Docker |

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
* Java 17+
* Node.js 18+ & Angular CLI
* Docker & Docker Compose

### 1. Clocar o Repositório
```bash
git clone [https://github.com/Brunnomk/MesaLivre.git](https://github.com/Brunnomk/MesaLivre.git)
cd MesaLivre
