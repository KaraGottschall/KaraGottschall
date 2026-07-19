# Kara Gottschall Martins | Desenvolvedora Fullstack

Desenvolvedora Fullstack (.NET e Vue.js/Razor) com atuação em portal corporativo da Caixa Assistência (Portal Polaris): Service Desk/GTicket, gestor de campanhas, sprints/Kanban com dashboard operacional e painel administrativo. Entrego módulos end-to-end — da modelagem e APIs à UI — com foco em código manutenível, segurança web e performance com Dapper. Formação jurídica complementa a prática de LGPD e conformidade no desenvolvimento.

## Experiência Profissional

### Studio Brasuka | Desenvolvedora de Sistemas

**Setembro 2024 – Presente**

Atuação no **Portal Polaris (Caixa Assistência)** e em plataforma interna de procurement (Handover). Fullstack .NET 8/10 & Vue.js/Razor na modernização de legados monolíticos para arquitetura em camadas, com resiliência de conexões, Dapper e Server-Side Hydration para dados fiscais e operacionais.

#### Principais Entregas — Portal Polaris (Caixa Assistência)

- **Service Desk / GTicket:** Ciclo completo de chamados (abertura, status, chat, anexos, filtros e paginação) em .NET + Vue/Razor, com otimização de carga e consultas SQL.
- **Sprints e operação ágil:** Modelagem e APIs de sprints/tarefas/Kanban (status, ordenação, detalhes), vínculo ticket↔sprint, backlog e cálculo de progresso — substituindo mocks por persistência real.
- **Dashboard operacional:** KPIs, heatmap, gráficos de alteração de datas, produtividade, auditoria, check-in e logs dedicados para acompanhamento da operação.
- **Gestor de Campanhas:** Gestão fullstack de campanhas (listagem/filtros, editor TinyMCE, anexos/mídia e fluxos de e-mail com MailKit assíncrono).
- **Painel administrativo:** Gestão de acessos/permissões, cargos, departamentos, funcionários, notícias e horários de expediente.
- **Produtos e regras de negócio:** Cadastro com periodicidade, vigência/renovação, upload de imagens e configurações de app/vantagens.
- **GBlock e gestão fiscal:** APIs e telas de bloqueio/desbloqueio de hardware corporativo (jornada e solicitações) e gestão de notas/diferimentos com volumes densos de dados.
- **Arquitetura, performance e segurança:** Migração de módulos legados (T-SQL/ASP.NET) para .NET 8 + Vue; padrão Execute Around; Dapper; proteção CSRF e CSP/nonce; qualidade via SonarQube/Quality Gates.

#### Principais Entregas — Plataforma de Gestão de RFQs (Handover)

- **Plataforma de Gestão de RFQs (Handover):** Desenvolvimento fullstack end-to-end de sistema de ciclo de vida de requisições de cotação em ASP.NET Core MVC (.NET 10), Dapper e MySQL, cobrindo criação, análise, cotação, aprovação de fornecedor e acompanhamento operacional, com arquitetura em camadas (Controller → Service → Repository).
- **Workflow e Autorização Multi-perfil:** Implementação de fluxo por status e flags de edição, com Cookie Authentication, policies/claims e telas condicionadas por perfil (Controladoria, Requisitante, Suprimentos e Operações), incluindo detalhamento e painéis específicos para Controladoria.
- **Portal Externo de Fornecedores:** Entrega de acesso público via token GUID para envio de cotações, anexos e questionários, sem login corporativo, com validação de token e trava pós-envio.
- **Armazenamento em Nuvem (AWS S3):** Integração de upload/exclusão de anexos, requisitos, cotações e fotos de campo, com resolução via URLs pré-assinadas.
- **Operações de Campo:** Módulo operacional para medição e desmontagem de itens vinculados à RFQ, com upload/galeria de fotos, histórico e visão de itens pendentes.
- **Planilhas e Integração ERP:** Processamento de planilhas com ClosedXML (geração/importação) e campos de integração TOTVS (GTC/SC/PC/PM) com regras de permissão por área.
- **Alertas e Auditoria:** Sistema de notificações por área e log de auditoria de ações sensíveis (login, mudanças de status, uploads), reforçando rastreabilidade e governança.

### Grupo GPS | Analista de Sistemas de TI (Efetivada após destaque em Estágio)

**Julho 2022 – Junho 2024 (2 anos)**

Iniciei no setor Jurídico e fui promovida à área de Tecnologia após desenvolver automações em Python que reduziram custos operacionais. Como Analista, atuei com autonomia na modernização da governança de dados, utilizando Angular e NestJS para centralizar relatórios estratégicos. Implementei fluxos automatizados via Power Automate para operação nacional e assegurei a conformidade de sistemas à LGPD, utilizando minha base jurídica para acelerar o acesso à informação pela diretoria.

#### Principais Entregas e Trajetória

- **Desenvolvimento de Sistemas (Fase Analista):** Responsável pela construção da interface de aplicações internas utilizando Angular (com colaborações em NestJS), focando na centralização e controle robusto de acesso a relatórios gerenciais para diversas áreas da companhia.
- **Inteligência de Dados e Automação:** Desenvolvimento de scripts em Python para análise de dados contratuais, resultando na identificação de oportunidades para redução de custos. Implementação de fluxos via Power Automate para coleta e distribuição de relatórios semanais automatizados para regionais em todo o Brasil.
- **Compliance e LGPD (Fase Inicial):** Atuação na análise de riscos contratuais e adequação de cláusulas à Lei Geral de Proteção de Dados (LGPD), garantindo a conformidade nos processos de integração de dados.
- **Transição e Evolução:** Migração estratégica do jurídico para o time de sistemas, aplicando conhecimentos de lógica e tratamento de dados para contornar divergências em relatórios complexos e acelerar o acesso às informações da diretoria.

## Projetos Pessoais

### [GeoStrike](https://github.com/KaraGottschall/GeoStrike)

Motor MMORTS explorando o ecossistema moderno da Microsoft e padrões avançados de domínio.

- **Stack:** .NET 10, C# 14, Blazor WebAssembly, MudBlazor, EF Core, SQL Server
- **Arquitetura:** Clean Architecture, DDD e fatias verticais (Vertical Slices)
- **Performance:** serialização em tempo de compilação com `JsonSerializerContext`
- **Qualidade:** FluentValidation, xUnit/Shouldly e CI via GitHub Actions

## Competências Técnicas

### Desenvolvimento Fullstack

- **Backend:** C# (.NET Core/8/10) com padrões assíncronos, ASP.NET Core MVC e APIs REST; envio de e-mail com MailKit.
- **Frontend:** Vue.js + Razor (híbrido), componentização e state hydration, JavaScript (ES6+), AJAX, CSS/Bootstrap; editor TinyMCE em fluxos de conteúdo; Blazor Wasm em projetos pessoais.
- **Arquitetura:** Design Patterns (Repository, Execute Around, Response Envelope), DTOs, Clean Architecture/DDD e injeção de dependências.

### Dados & Persistência

- **ORM & Performance:** Dapper para consultas otimizadas e mapeamento de objetos complexos; EF Core em projetos pessoais.
- **SQL Server:** Modelagem relacional, queries complexas (joins, agregações) e integridade de dados.
- **MySQL:** Persistência relacional em aplicações MVC com queries explícitas via Dapper.
- **Migração:** Transição de dados e módulos legados para estruturas modernas.

### Cloud & Integrações

- **AWS S3:** Upload, exclusão e acesso via URLs pré-assinadas para documentos e imagens (Handover).
- **Excel (ClosedXML):** Geração e importação de planilhas com layouts de cotação (Handover).
- **DevOps:** GitHub Actions, Docker, Postman.

### Domínio & Negócio

- **Portais corporativos:** Service Desk/tickets, sprints/Kanban, dashboards (KPI/heatmap/produtividade), campanhas de marketing, cadastro de produtos e painel admin (RBAC).
- **Segurança web:** CSRF, CSP/nonce e Quality Gates (SonarQube) no ciclo de entrega.
- **Workflow multi-área:** Ciclos de aprovação com múltiplos perfis, portal B2B de fornecedores e operações de campo (Handover).
- **Compliance:** Aplicação prática de LGPD e segurança da informação no desenvolvimento de software.
- **Documentação:** Guias técnicos e documentação de arquitetura para manutenção.

## Formação Acadêmica

- **Bacharelado em Ciência da Computação** | Anhanguera Osasco  
  Previsão de conclusão: 2028

> **Nota:** A graduação quase completa em Direito (5 semestres, Anhanguera Osasco — trancada) me permite uma visão analítica diferenciada, unindo a lógica de programação à compreensão de normas, contratos e segurança da informação (LGPD).

---

### Metrics

<p align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=KaraGottschall&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true" alt="GitHub Stats" height="165" />
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=KaraGottschall&layout=compact&theme=tokyonight&hide_all_commits=false&count_private=true" alt="Top Languages" height="165" />
</p>

---

### Connection

<p align="center">
  <a href="https://www.linkedin.com/in/kgottschall" target="_blank">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:kara.gottschall@gmail.com">Gmail</a> &nbsp;·&nbsp;
  <a href="https://github.com/KaraGottschall" target="_blank">GitHub</a>
</p>
