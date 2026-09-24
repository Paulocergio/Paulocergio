<h1 align="center">Olá, eu sou o Paulo Cergio 👋</h1>

<p align="center">
  Desenvolvedor de Software | .NET & Full Stack | Estudando Arquitetura de Software e Spec-Driven Development 🧠
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white"/>
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
</p>

---

## 💼 Sobre mim

Sou desenvolvedor de software com experiência no desenvolvimento de sistemas corporativos, APIs RESTful e aplicações web. No trabalho uso **C#**, **.NET**, **SQL Server**, **Docker** e **React**, aplicando **Clean Code**, **SOLID** e versionamento com Git.

Fora do trabalho, meu foco é **aprender a projetar software**, e não só a escrever código. Para isso mantenho projetos de estudo em que pratico **arquitetura de software** e **Spec-Driven Development (SDD)**: nenhuma feature vira código antes de existir uma especificação.

---

## 📚 O que estou estudando

### 🏛️ Arquitetura de Software
- **Clean Architecture**: camadas com dependências apontando para o domínio
- **CQRS com MediatR**: separação entre comandos (escrita) e queries (leitura)
- **DDD**: modelagem do domínio na linguagem do negócio
- **SOLID e design patterns**: Repository, injeção de dependência, handlers
- **Decisões técnicas documentadas**: registrar o *porquê* de cada escolha, não só o *como*

### 📋 Spec-Driven Development (SDD)
- **Constituição do projeto**: regras não-negociáveis de arquitetura, banco, nomenclatura e contrato da API
- **Fluxo `spec → design → tasks → código`** em cada feature
- **Spec como fonte da verdade**: se o requisito muda, a spec muda antes do código

```
constitution.md → spec.md → design.md → tasks.md → código
   (regras)      (o quê)    (como)    (ordem)
```

### 🔜 Próximos passos
- Testes automatizados derivados dos critérios de aceite das specs
- Multi-tenant, paginação e refresh token
- CI/CD com GitHub Actions

---

## 🚧 Projetos de estudo

### 🔷 ConnectaSys: laboratório de SDD e arquitetura
> Sistema **fictício** de gestão para oficinas mecânicas, com clientes, veículos, ordens de serviço, estoque e financeiro. Serve **apenas para aprendizado**: o domínio foi escolhido por ter regras de negócio suficientes para exercitar o fluxo SDD de ponta a ponta. Não é um produto comercial.

| Repositório | Papel | Stack |
|:--|:--|:--|
| ⚙️ [`connectasys_api`](https://github.com/Paulocergio/connectasys_api) | Backend | .NET 10 · C# · EF Core · PostgreSQL · MediatR (CQRS) · JWT + BCrypt · Docker |
| 🖥️ [`connectasys-hub`](https://github.com/Paulocergio/connectasys-hub) | Frontend | React 19 · TypeScript · TanStack Start/Router/Query · Tailwind v4 · shadcn/ui · Zod |

**O que pratiquei nele:**
- 🧱 Clean Architecture em 3 projetos (Core, Infrastructure, API), com controllers que só conhecem o `IMediator`
- 📋 Mais de 15 features especificadas antes de implementadas, cada uma com `spec.md`, `design.md` e `tasks.md`
- 🔐 Autenticação JWT, hash BCrypt, autorização por role e rate limiting no login
- 🔗 Regras de negócio integradas: a conclusão da OS gera a conta a receber, e os itens da OS dão baixa no estoque
- 🎨 Design system com tokens semânticos em `oklch`, dark/light mode e SSR em Cloudflare Workers
- ☁️ Deploy de demonstração: Cloudflare Workers + Azure Container Apps + Azure PostgreSQL

🌐 Demonstração: **[connectasys.com.br](https://connectasys.com.br)**

---

## ⚙️ Tecnologias que uso profissionalmente

- 💻 **Back-end**: C#, ASP.NET Core, REST APIs, Entity Framework Core
- 🛢️ **Banco de dados**: SQL Server (procedures, views, consultas otimizadas), PostgreSQL
- 🎨 **Front-end**: React (MUI, TailwindCSS), TypeScript
- 🐳 **Infraestrutura**: Docker, GitHub Actions
- 🔁 **Versionamento**: Git + GitHub (Git Flow)

---

## 📈 GitHub Stats

<div align="center">
  <img height="170em" src="https://github-readme-stats.vercel.app/api?username=Paulocergio&show_icons=true&theme=dark&include_all_commits=true&count_private=true"/>
  <img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Paulocergio&layout=compact&langs_count=7&theme=dark"/>
</div>

---

## 📫 Contato

- [![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/paulo-cergio-300926152/)
- 📧 Email: juniorcergio@gmail.com
- 📱 WhatsApp: +55 31 99062-4294

---

<p align="center">
  <sub>"Primeiro a especificação, depois o código."</sub>
</p>
