# Brunno Xavier de Oliveira
**Software Engineer | Full Stack Specialist**

Estremoz, Portugal • [Brunno.mkti@gmail.com](mailto:Brunno.mkti@gmail.com) • [LinkedIn](https://linkedin.com) • [GitHub](https://github.com/Brunnomk)

---

## 📌 Resumo Profissional

Engenheiro de Software com foco em desenvolvimento **Full Stack**, especializado em arquitetura de sistemas corporativos, microsserviços e aplicações web resilientes. Domínio no ecossistema **Java (Spring Boot)** para desenvolvimento backend e frameworks reativos (**Angular** e **React**) para o frontend, aliado à modelagem e otimização de bancos de dados relacionais (**PostgreSQL**).

Experiência no desenho de soluções alinhadas aos princípios de **Clean Architecture**, **Domain-Driven Design (DDD)** e **Padrões de Projeto (Design Patterns)**, garantindo manutenibilidade, escalabilidade e alta disponibilidade.

---

## 🛠️ Domínio Técnico

| Categoria | Tecnologias e Ferramentas |
| :--- | :--- |
| **Linguagens de Programação** | Java (17+), TypeScript, JavaScript (ES6+) |
| **Backend & Frameworks** | Spring Boot, Spring Security, Spring Data JPA, RESTful APIs, Node.js |
| **Frontend & UI Architecture** | Angular, React, RxJS, HTML5, CSS3, SCSS, Tailwind CSS |
| **Bancos de Dados & ORM** | PostgreSQL, MySQL, Hibernate |
| **Arquitetura & Metodologias** | Clean Architecture, DDD, Programação Orientada a Objetos (POO), OAuth2 / JWT |
| **DevOps & Ferramentas** | Docker, Git, GitHub, Maven, Postman, IntelliJ IDEA, VS Code |

---

## 🚀 Projetos de Engenharia em Destaque

### 🍽️ MesaLivre — Plataforma de Gestão e Reservas Empresariais
Sistema Full Stack desenvolvido para gerenciar e otimizar reservas em restaurantes, resolvendo problemas de consistência de dados em cenários de acessos simultâneos.

* **Decisões de Arquitetura:**
  * Implementação de estratégias de *Locking* (Otimista e Pessimista) no PostgreSQL para prevenção de conflitos de reserva e *overbooking*.
  * Camada de autenticação e autorização centralizada via Spring Security utilizando **JWT** com controle de acesso baseado em papéis (RBAC).
  * Otimização de desempenho com paginação de dados e uso de DTOs (*Data Transfer Objects*) para evitar o problema de consulta $N+1$.
* **Tecnologias:** Java 17, Spring Boot, PostgreSQL, Angular, RxJS, Tailwind CSS.

---

### 🗳️ VoteLive — Sistema de Votação em Tempo Real com Alta Volumetria
Engenharia de sistema voltada para processamento de votos e exibição de dashboards analíticos com baixa latência.

* **Decisões de Arquitetura:**
  * Utilização de **WebSockets** para comunicação bidirecional e atualização de métricas em tempo real no frontend, eliminando a necessidade de requisições contínuas (*polling*).
  * Modelagem de dados voltada para consistência de escritas concorrentes durante picos de tráfego.
* **Tecnologias:** Java, Spring Boot, React, WebSockets, PostgreSQL.

---

### 📦 RouteFlow — Motor de Otimização e Planejamento Logístico
Aplicação voltada para o planejamento, organização e otimização visual de circuitos e rotas de entrega.

* **Decisões de Arquitetura:**
  * Algoritmos de ordenação e distribuição espacial para otimização do tempo de despacho logístico.
  * Integração com APIs de geolocalização para renderização e manipulação interativa de rotas.
* **Tecnologias:** JavaScript (ES6+), Leaflet API, HTML5/CSS3.

---

### 🛡️ CodeClash — Plataforma de Avaliação Assíncrona de Código
Ambiente para execução e benchmarking de desafios técnicos de programação.

* **Decisões de Arquitetura:**
  * Isolamento de ambiente para execução segura de código via *containers* efêmeros em Docker.
  * Cálculo assíncrono de pontuação e ranking de desempenho.
* **Tecnologias:** Java, Spring Boot, Docker Engine API, React.

---

## 📊 Estatísticas e Atividade no GitHub

<table align="center" width="100%">
  <tr>
    <td width="50%" align="center">
      <img src="https://github-readme-stats.vercel.app/api?username=Brunnomk&show_icons=true&theme=flat&hide_border=true&title_color=0969da&icon_color=0969da&text_color=24292f&bg_color=ffffff" width="100%" alt="GitHub Stats" />
    </td>
    <td width="50%" align="center">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Brunnomk&layout=compact&theme=flat&hide_border=true&title_color=0969da&text_color=24292f&bg_color=ffffff" width="100%" alt="Top Languages" />
    </td>
  </tr>
</table>

---

## 📐 Princípios de Desenvolvimento

1. **Simplicidade e Manutenibilidade:** Código limpo e autodocumentado é prioridade sobre soluções excessivamente complexas.
2. **Design Orientado ao Domínio:** O modelo de dados e as regras de negócio devem refletir com precisão os processos do mundo real.
3. **Segurança por Padrão:** Garantia de proteção de dados e autenticação robusta em todas as camadas da aplicação.
4. **Qualidade Contínua:** Testes automatizados e revisão contínua de código para prevenir débitos técnicos.
