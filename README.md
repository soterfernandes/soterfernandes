<h1 align="center">Olá, eu sou o Sóter Fernandes 👋</h1>
<h3 align="center">Desenvolvedor .NET · Blazor Server · Sistemas financeiros</h3>

<p align="center">
  <a href="https://br.linkedin.com/in/eusotf" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:sot.famcred@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/soterfernandes" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>

---

### 👨‍💻 Sobre mim

Desenvolvedor focado em **aplicações corporativas** para o setor financeiro (consignado), com experiência em:

- **CRM multi-camadas** — Domain, Data, Service, API e frontend Blazor Server
- **APIs REST** com JWT, Identity e autorização por perfil
- **MySQL** com EF Core + Dapper em queries de alto volume
- **Background Services** — processamento de arquivos, exportação Excel, jobs agendados
- **Automação** — Selenium WebDriver para consulta de margem em portais governamentais
- **Integrações** — AWS S3, APIs parceiras, importação CSV e relatórios NPOI

Busco sempre código limpo, segurança em dados sensíveis (LGPD) e arquitetura escalável.

---

### 🛠 Stack principal

<p align="center">
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#"/>
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET"/>
  <img src="https://img.shields.io/badge/Blazor-512BD4?style=for-the-badge&logo=blazor&logoColor=white" alt="Blazor"/>
  <img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="ASP.NET Core"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/Entity_Framework-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="EF Core"/>
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white" alt="Selenium"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS"/>
</p>

---

### 📌 Projetos em destaque

| Projeto | Descrição |
|---------|-----------|
| [**dotnet-crm-fintech-showcase**](https://github.com/soterfernandes/dotnet-crm-fintech-showcase) | Arquitetura de CRM financeiro em .NET — camadas, padrões e decisões técnicas |
| **FamCred CRM** *(privado)* | CRM de consignado em produção — propostas, margem, exportações analíticas e robôs |

> Confira os repositórios fixados abaixo para mais detalhes.

---

### 🏗 Visão geral da arquitetura (projeto principal)

```mermaid
graph TB
    subgraph Frontend
        SITE[Blazor Server<br/>MudBlazor + Radzen]
    end

    subgraph Backend
        API[ASP.NET Core API<br/>JWT + Identity]
        SVC[Service Layer<br/>Regras de negócio]
    end

    subgraph Data
        DATA[Repositories<br/>EF Core + Dapper]
        DB[(MySQL 8)]
    end

    subgraph Jobs
        WORKER[Windows Service<br/>Captcha + Arquivos]
        MARGEM[WinForms<br/>Consulta Margem]
        ROBOS[Selenium Robôs<br/>Portais consignado]
    end

    subgraph Cloud
        S3[AWS S3]
    end

    SITE -->|HttpClient| API
    API --> SVC
    SVC --> DATA
    DATA --> DB
    WORKER --> SVC
    MARGEM --> API
    ROBOS --> DB
    SVC --> S3
```

---

### 📊 GitHub Stats

<p align="center">
  <img src="github-metrics.svg" alt="GitHub Metrics" width="100%"/>
</p>

---

### 🐍 Contribuições

<p align="center">
  <img src="output/github-contribution-grid-snake.svg" alt="Snake animation"/>
</p>

---

### 💡 Áreas de expertise

| Área | Tecnologias / práticas |
|------|------------------------|
| **Backend** | ASP.NET Core 6/8, Dapper, Dommel, Repository Pattern |
| **Frontend** | Blazor Server, MudBlazor, Radzen, JWT Session |
| **Banco** | MySQL, migrações EF, SQL otimizado, índices |
| **Automação** | Selenium Edge/Chrome, NCrontab, BackgroundService |
| **Relatórios** | NPOI Excel, CsvHelper, pipelines de exportação |
| **Segurança** | LGPD, mascaramento de CPF, JWT, perfis de acesso |

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=soterfernandes&color=blueviolet&style=flat-square" alt="Profile views"/>
</p>

<p align="center">
  <i>"Código que resolve problemas reais de negócio."</i>
</p>
