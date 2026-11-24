<h1 align="left">Olá! 👋 Eu sou o Roberto Silva</h1>
<h3 align="left">Software Engineer · Full Stack · Desenvolvimento assistido por IA · DevOps</h3>
<p align="left">Entendo o problema de negócio antes de escrever a primeira linha de código, e levo a solução do código até o deploy em produção.</p>

<p align="left">
  <a href="https://www.linkedin.com/in/roberto-silva-dev-full-stack"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:robertosilva.comercial@gmail.com"><img src="https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"/></a>
  <a href="https://saveforge.com.br"><img src="https://img.shields.io/badge/Portf%C3%B3lio-SaveForge-111827?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfólio SaveForge"/></a>
</p>

---

## 🚀 Sobre mim

- 🧩 **Diferencial:** vim de negócios e vendas consultivas (hoje na **Balloon**, agência de marketing para hotelaria e turismo), então conecto produto, tecnologia e resultado
- ⚙️ **Stack:** TypeScript, React, Next.js, Node.js, Python, PostgreSQL e Docker
- 🤖 **IA como ferramenta de engenharia:** Claude Code, MCP e agentes para acelerar desenvolvimento, debugging e documentação, sempre com processo
- ☁️ **Infra:** Linux, Docker, Nginx, Coolify/Dokploy e Oracle Cloud, com CI/CD e foco em segurança
- ✍️ **Escrevo sobre segurança e DevOps** no [SaveForge](https://saveforge.com.br)
- 📍 São Paulo, Brasil · aberto a oportunidades presenciais, híbridas ou remotas

### 🔄 Como eu desenvolvo
**SDD (Spec-Driven Development)** → **Harness Engineering com Claude Code** → **CI/CD com GitHub Actions**<br>
Planejo por especificação, entrego em fases com Pull Requests, testes e verificações de segurança, e só então vai para produção.

---

## 🚩 Projetos em destaque

> Os repositórios abaixo marcados com 🔒 são privados (trabalho para clientes ou projetos em andamento). Posso apresentar o código e as decisões técnicas em conversa.

### 🌐 SaveForge · Portfólio, blog e painel administrativo 🔒
**[saveforge.com.br](https://saveforge.com.br)** · em produção<br>
Meu portfólio é uma aplicação full stack completa: site público, blog com artigos de segurança e DevOps, comentários com moderação e painel admin com **10 módulos** (analytics, leads, backup, logs de auditoria).
- 🔐 JWT + bcrypt, Helmet, rate limiting e validação com Zod
- 🧱 React + TypeScript + Vite no front, Node.js/Express + Prisma + PostgreSQL no back
- 🧪 Testes com Vitest e deploy em dois serviços no Railway

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

### 🎨 Kurio · Marketplace de NFTs (desafio técnico Jungle Gaming) 🔒
Front-end completo de marketplace: catálogo com filtros na URL, favoritos otimistas, carrinho com cupom, checkout **idempotente** e atualização de preço em **tempo real**.
- 💱 Aritmética monetária exata com bigint (18 casas decimais)
- 🔌 API simulada com **MSW** e WebSocket com **Socket.IO**, com 14 cenários determinísticos
- ✅ **22 testes E2E** com Playwright (desktop e mobile), regressão visual e **100 em Acessibilidade e Boas Práticas** no Lighthouse

![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![TanStack](https://img.shields.io/badge/TanStack_Query_%2B_Router-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

### 🏨 Quiz de Diagnóstico Hoteleiro · Balloon
**[diagnostico.balloonmkt.com.br](https://diagnostico.balloonmkt.com.br)** · em produção<br>
Landing interativa usada no stand da Balloon em Maresias: o hoteleiro responde 11 perguntas, recebe uma nota de 0 a 100 e deixa o lead para a equipe comercial.
- 🧮 Motor de pontuação validado contra as **177.147 combinações** possíveis de resposta
- 📈 Conversão rastreada com GA4 e Meta Pixel, com deduplicação de eventos
- 🔒 Regra de negócio recalculada no servidor (Google Apps Script) para evitar adulteração
- ⚡ Aplicação estática, ~76 kB de JS comprimido

![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Google Apps Script](https://img.shields.io/badge/Apps_Script-4285F4?style=flat-square&logo=google&logoColor=white)

### 📖 Apresentação Interativa Balloon 🔒
Apresentação comercial em formato de **livro com efeito de virar página**, navegável por clique e teclado, e exportável em PDF para enviar ao cliente após a reunião.
- 🛠️ Motor de virar página próprio (sem biblioteca), pensado para o PDF sair correto
- 🐳 Build multi-stage com Docker e Nginx, fontes self-hosted para não depender de internet na reunião

![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

### 🚛 JHC Guincho Pesado · Site institucional e captura de leads 🔒
Site focado em conversão para atendimento 24h (WhatsApp e ligação), com SEO local e documentação de produto.
- ⚙️ Next.js (App Router), TypeScript, Tailwind e shadcn/ui, com Prisma e PostgreSQL
- 🛡️ Build que falha de propósito sem a variável do WhatsApp, para nunca publicar número de placeholder
- 📚 Docs de discovery, PRD, escopo do MVP, deploy em VPS e proteção contra cliques inválidos em anúncios

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

### 📊 Ads Intelligence Dashboard 🔒 · 🚧 em desenvolvimento
Plataforma de **monitoramento, análise e otimização supervisionada** de campanhas de Google Ads e Meta Ads. Projeto em fase de arquitetura e planejamento, conduzido com SDD e harness de engenharia.

### 💈 FSW Barber · SaaS de barbearia 🔒
Aplicação de agendamento para barbearias em Next.js, construída durante o Full Stack Week.

### 🛠️ [DevForge](https://github.com/RobertoSilvaDevFullStack/DevForge) · 🚧 em evolução
Plataforma pessoal de aprendizagem voltada ao desenvolvimento técnico e acadêmico de estudantes de tecnologia.

### 🎓 [Sistema de Suporte (Java)](https://github.com/RobertoSilvaDevFullStack/SistemaSuporte_MAPA_Java)
Atividade acadêmica em Java sobre classes e tipos de dados, aplicada a um sistema de suporte técnico.

---

## 🛠️ Tech stack

### 🎨 Frontend
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="35" alt="TypeScript" title="TypeScript"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="35" alt="JavaScript" title="JavaScript"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="35" alt="React" title="React"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" height="35" alt="Next.js" title="Next.js"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vitejs/vitejs-original.svg" height="35" alt="Vite" title="Vite"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" height="35" alt="Tailwind CSS" title="Tailwind CSS"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="35" alt="HTML5" title="HTML5"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="35" alt="CSS3" title="CSS3"/>

### ⚙️ Backend & APIs
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="35" alt="Node.js" title="Node.js"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" height="35" alt="Express" title="Express"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nestjs/nestjs-original.svg" height="35" alt="NestJS" title="NestJS"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="35" alt="Python" title="Python"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="35" alt="Java" title="Java"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postman/postman-original.svg" height="35" alt="Postman" title="Postman"/>

### 🗄️ Dados
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="35" alt="PostgreSQL" title="PostgreSQL"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/prisma/prisma-original.svg" height="35" alt="Prisma" title="Prisma"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" height="35" alt="Redis" title="Redis"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg" height="35" alt="MySQL" title="MySQL"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/supabase/supabase-original.svg" height="35" alt="Supabase" title="Supabase"/>

### ☁️ Cloud, DevOps & IA
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" height="35" alt="Google Cloud" title="Google Cloud"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="35" alt="Docker" title="Docker"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nginx/nginx-original.svg" height="35" alt="Nginx" title="Nginx"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="35" alt="Linux" title="Linux"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="35" alt="Git" title="Git"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/githubactions/githubactions-original.svg" height="35" alt="GitHub Actions" title="GitHub Actions"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vercel/vercel-original.svg" height="35" alt="Vercel" title="Vercel"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="35" alt="VS Code" title="VS Code"/>
<img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" height="28" alt="n8n"/>
<img src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white" height="28" alt="Claude Code"/>

---

## 🏆 Certificações

### ☁️ Google Cloud (2026)
| 🏅 Certificação | 🏢 Emissor | 📅 Emissão |
|----------------|------------|-----------|
| **Cloud Engineering** | Google | Mai/2026 |
| **Google Cloud Computing Foundations Certificate** | Google | Mai/2026 |
| **Build a Secure Google Cloud Network** (Skill Badge) | Google | Mai/2026 |
| **Set Up an App Dev Environment on Google Cloud** (Skill Badge) | Google | Mai/2026 |
| **Implement Load Balancing on Compute Engine** (Skill Badge) | Google | Mai/2026 |

### 🎓 Formação complementar
| 🎓 Curso | 🏢 Instituição | 📅 Ano |
|----------|----------------|--------|
| **Git e GitHub** | Alura | 2025 |
| **Lógica de Programação com JavaScript** | Alura | 2024 |
| **Tailwind CSS: Classes Utilitárias** | Alura | 2024 |
| **HTML5 e CSS3** | Alura | 2023 |

---

## 🧠 Competências

### 🎯 Técnicas
- 🔧 **Full stack:** APIs REST, autenticação, modelagem de dados e front-end moderno
- 🧪 **Qualidade:** testes E2E com Playwright, testes unitários com Vitest e regressão visual
- 🤖 **IA aplicada e automação:** Claude Code, n8n, agentes e integrações com LLMs
- 🚀 **Deploy e infraestrutura:** Docker, Nginx, VPS, CI/CD e segurança (RBAC, rate limiting, gestão de segredos)
- ⚡ **Performance, SEO e conversão:** Core Web Vitals, mobile-first e rastreamento com GA4 e Meta Pixel

### 💡 Comportamentais
- 🤝 **Visão de negócio:** transformo briefing comercial em solução técnica
- 💬 **Comunicação clara** com cliente, time e liderança
- 🎯 **Resolução de problemas** com foco em resultado
- 📚 **Aprendizado contínuo** e adaptabilidade
- 🔍 **Atenção aos detalhes** e entrega com qualidade

---

## 🌐 Idiomas
🇧🇷 Português (nativo) · 🇺🇸 Inglês (intermediário, leitura técnica) · 🇪🇸 Espanhol (básico)

---

## 📊 GitHub em números

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=RobertoSilvaDevFullStack&show_icons=true&include_all_commits=true&count_private=true&theme=dracula&locale=pt-br&hide_border=true" height="170" alt="Estatísticas do GitHub"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs?username=RobertoSilvaDevFullStack&locale=pt-br&layout=compact&langs_count=6&theme=dracula&hide_border=true" height="170" alt="Linguagens mais usadas"/>
</div>

---

<p align="center">💬 Aberto a conversas sobre projetos, parcerias e oportunidades. <a href="https://www.linkedin.com/in/roberto-silva-dev-full-stack">Vamos conversar no LinkedIn</a>.</p>
