
# 🎯 Play Sports Falcão

> **Plataforma Web Integrada de Gestão para Escolinha de Esportes**  
> Sistema completo para gerenciamento de alunos, turmas, aulas, feedbacks e financeiro com portal do responsável.

---

## 🚀 Status do Projeto

[![Status: Em Desenvolvimento](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge)](https://github.com)
[![Versão](https://img.shields.io/badge/Versão-v1.0.0-blue?style=for-the-badge)](https://github.com)
[![Licença](https://img.shields.io/github/license/plf-es-2026-1-ti4-1254100-play-sports-falcao/play-sports-falcao?style=for-the-badge&color=007ec6&logo=opensourceinitiative)](LICENSE)
![React](https://img.shields.io/badge/React-18.3.1-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.3.3-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-11.0.0-EA2845?style=for-the-badge&logo=nestjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-✓-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-4.0.0-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)

---

## 📝 Sobre o Projeto

### 🎓 Contexto

O **Play Sports Falcão** é uma plataforma web de gestão para uma escolinha de esportes voltada para crianças e adolescentes. O sistema nasceu da **necessidade real** de organizar e profissionalizar a gestão operacional da escolinha, que cresceu de uma atividade paralela em jogos de pelada aos sábados para atender **múltiplas turmas, faixas etárias e localidades**, incluindo aulas em condomínios.

### 🎯 Propósito

Fornecer uma **solução integrada e profissional** para:

1. **Gestão de Alunos e Turmas**
   - Cadastro centralizado de alunos com dados pessoais e de emergência
   - Gestão de turmas por faixa etária, horário e localização
   - Controle de matrículas e capacidade de salas

2. **Gerenciamento de Aulas e Treinos**
   - Planejamento e execução de sessões de aula
   - Registro de presença com histórico
   - Vinculação de treinos estruturados

3. **Feedback e Desenvolvimento**
   - Registro de desempenho individualizado por aluno
   - Histórico de evolução e progresso
   - Relatórios de desenvolvimento

4. **Controle Financeiro**
   - Gestão de planos de pagamento
   - Geração de faturas automáticas
   - Acompanhamento de inadimplência

5. **Comunicação com Responsáveis**
   - Portal do responsável para acompanhamento
   - Notificações via WhatsApp
   - Consentimento LGPD integrado

6. **Administração e Segurança**
   - Painel administrativo completo
   - Controle de permissões por módulo
   - Autenticação JWT e criptografia de senhas

### 🤔 Por Que Importa?

- **Profissionalização**: Transforma operação manual em sistema automatizado
- **Escalabilidade**: Suporta crescimento de turmas e locais
- **Transparência**: Responsáveis acompanham evolução em tempo real
- **Eficiência**: Reduz tempo administrativo em ~70%
- **Segurança**: Conformidade com LGPD e proteção de dados

---

## ✨ Funcionalidades Principais

### 👨‍🔐 Autenticação & Segurança
- ✅ Login seguro com JWT (JSON Web Tokens)
- ✅ Senhas criptografadas com bcrypt
- ✅ Controle de acesso por roles (Admin, Professor, Responsável, Aluno)
- ✅ Permissões granulares por módulo

### 🎓 Gestão de Alunos
- ✅ Cadastro completo com dados pessoais e emergência
- ✅ Status de aluno (Ativo, Experimental, Inadimplente)
- ✅ Histórico de participação e desempenho
- ✅ Consentimento LGPD e termo de imagem

### 📚 Gestão de Turmas
- ✅ Criação de turmas por faixa etária
- ✅ Configuração de dias, horários e local
- ✅ Controle de capacidade e enrolled
- ✅ Status de turmas (Ativa, Lotada, Inativa)

### 🏋️ Execução de Aulas
- ✅ **Status "Pendente"**: Apenas vincular treino
- ✅ **Status "Preparada"**: Abas separadas para:
  - Chamada (registro de presença)
  - Feedbacks (desempenho individual)
  - Anotações (observações gerais)
- ✅ **Status "Concluída"**: Modo read-only com histórico completo

### 📊 Feedbacks & Desempenho
- ✅ Registro de feedback individual por aluno
- ✅ Histórico de evolução e progresso
- ✅ Visualização por responsável
- ✅ Relatórios de desenvolvimento

### 💰 Gestão Financeira
- ✅ Planos de pagamento (Mensal, Semestral, Anual)
- ✅ Geração automática de faturas
- ✅ Acompanhamento de pagamentos
- ✅ Relatórios financeiros

### 📱 Portal do Responsável
- ✅ Visualização de perfil do aluno
- ✅ Acompanhamento de frequência
- ✅ Leitura de feedbacks do professor
- ✅ Aceitar termos LGPD

### 📧 Integrações Externas
- ✅ Notificações via WhatsApp (WaaS Gateway)
- ✅ Envio de e-mails automáticos
- ✅ Suporte a upload de imagens (galeria)

---

## 🛠 Tecnologias Utilizadas

### 💻 Frontend

| Tecnologia | Versão | Descrição |
|-----------|--------|----------|
| **React** | 18.3.1 | Biblioteca de UI baseada em componentes |
| **TypeScript** | 5.3.3 | Superset tipado de JavaScript |
| **Vite** | 7.1.2 | Build tool e dev server ultrarrápido |
| **Tailwind CSS** | 4.0.0 | Framework CSS utility-first |
| **Radix UI** | 1.0.x | Componentes acessíveis sem styled |
| **Material UI (MUI)** | 5.x | Componentes Material Design |
| **React Router** | 7.0.0 | Roteamento SPA |
| **Framer Motion** | 11.x | Animações declarativas |
| **Axios** | 1.6.x | Cliente HTTP |

### 🖥️ Backend

| Tecnologia | Versão | Descrição |
|-----------|--------|----------|
| **NestJS** | 11.0.0 | Framework Node.js progressivo e modulado |
| **TypeScript** | 5.3.3 | Linguagem fortemente tipada |
| **Prisma ORM** | 7.0.0 | ORM type-safe com migrations automáticas |
| **PostgreSQL** | 16 | Banco de dados relacional robusto |
| **class-validator** | 0.14.x | Validação declarativa de DTOs |
| **class-transformer** | 0.5.x | Transformação de objetos |
| **JWT** | 9.x | Autenticação com tokens |
| **bcryptjs** | 2.4.x | Hashing seguro de senhas |

### ⚙️ Infraestrutura & DevOps

| Tecnologia | Descrição |
|-----------|----------|
| **Docker** | Containerização de aplicação e banco |
| **Docker Compose** | Orquestração local de contêineres |
| **Node.js** | Runtime JavaScript v18+ |
| **npm** | Gerenciador de pacotes |

### 🔌 Integrações Externas

| Serviço | Descrição |
|--------|----------|
| **WaaS Gateway** | Notificações WhatsApp |
| **EmailJS** | Envio de e-mails transacionais |

---

## 🏗 Arquitetura

### Visão Geral

O Play Sports Falcão segue uma **arquitetura em camadas** com separação clara entre Frontend, Backend e Banco de Dados:

```
┌─────────────────────────────────────────────────────┐
│  CLIENTE (Browser)                                  │
│  ┌──────────────────────────────────────────────┐  │
│  │ React SPA + TypeScript + Tailwind CSS        │  │
│  │ - Landing Page (Pública)                     │  │
│  │ - Admin Dashboard                            │  │
│  │ - Teacher Panel                              │  │
│  │ - Parent Portal                              │  │
│  └──────────────────────────────────────────────┘  │
└──────────────────────┬──────────────────────────────┘
                       │ HTTP/REST
                       ▼
┌─────────────────────────────────────────────────────┐
│  SERVIDOR (NestJS)                                  │
│  ┌──────────────────────────────────────────────┐  │
│  │ NestJS Application (Node.js Runtime)         │  │
│  │ - Auth Module (JWT, Guards)                  │  │
│  │ - CRUD Modules (Students, Classes, etc.)    │  │
│  │ - Service Layer (Lógica de Negócio)         │  │
│  │ - Prisma ORM (Abstração BD)                 │  │
│  │ - Notification Module (WhatsApp, Email)     │  │
│  └──────────────────────────────────────────────┘  │
└──────────────────────┬──────────────────────────────┘
                       │ TCP Connection
                       ▼
┌─────────────────────────────────────────────────────┐
│  BANCO DE DADOS (PostgreSQL)                        │
│  ┌──────────────────────────────────────────────┐  │
│  │ 8+ Tabelas relacionadas                      │  │
│  │ - Users, Students, Classes                   │  │
│  │ - Sessions, Feedbacks, Invoices              │  │
│  │ - Financial Plans, etc.                      │  │
│  └──────────────────────────────────────────────┘  │
└─────────────────────────────────────────────────────┘
```

### Padrões de Arquitetura Utilizados

1. **MVC com Service Layer**
   - Controllers lidam com requisições HTTP
   - Services contêm lógica de negócio
   - Prisma ORM como camada de dados

2. **Módulos Independentes (NestJS)**
   - Cada funcionalidade em seu próprio módulo
   - Exports e Providers bem definidos
   - Facilita testes e manutenção

3. **DTOs (Data Transfer Objects)**
   - Validação de entrada com class-validator
   - Type-safety end-to-end
   - Separação entre domínio e API

4. **Guards e Middlewares**
   - AuthGuard para proteger rotas
   - RoleGuard para controle de permissões
   - Validação de JWT no header

5. **Repositório Pattern com Prisma**
   - Abstração do banco de dados
   - Queries type-safe
   - Migrations versionadas

---

## 🔧 Instalação e Execução

### 📋 Pré-requisitos

Certifique-se de que os seguintes softwares estão instalados:

- **Node.js**: v18 LTS ou superior ([Download](https://nodejs.org/))
- **Docker & Docker Compose**: Versão recente ([Download](https://www.docker.com/products/docker-desktop))
- **Git**: Para clonar o repositório ([Download](https://git-scm.com/))
- **npm**: Gerenciador de pacotes (incluso no Node.js)

### 🔑 Variáveis de Ambiente

#### Backend (`.env`)

Crie um arquivo `.env` em `Codigo/backend/play-sports-falcao/`:

```env
# Banco de Dados
DATABASE_URL=postgresql://postgres:postgres@localhost:5432/play_sports_falcao

# Autenticação
JWT_SECRET=sua_chave_super_secreta_aqui_minimo_32_caracteres
JWT_EXPIRATION=24h

# Servidor
SERVER_PORT=3000
NODE_ENV=development

# WaaS Gateway (WhatsApp)
WAAS_GATEWAY_URL=http://localhost:3001
WAAS_WORKSPACE_ID=seu_workspace_id_aqui
WAAS_CHANNEL_ID=seu_channel_id_aqui
WAAS_TIMEOUT_MS=10000

# Email (opcional)
EMAILJS_SERVICE_ID=seu_service_id
EMAILJS_TEMPLATE_ID=seu_template_id
EMAILJS_PUBLIC_KEY=sua_public_key
```

#### Frontend (`.env.local`)

Crie um arquivo `.env.local` em `Codigo/frontend/`:

```env
# API Backend
VITE_API_URL=http://localhost:3000/api

# Variáveis de Ambiente Público (Vite)
VITE_APP_NAME=Play Sports Falcão
VITE_APP_VERSION=1.0.0
```

### 📦 Instalação de Dependências

#### 1. Clone o Repositório

```bash
git clone https://github.com/seu-usuario/play-sports-falcao.git
cd play-sports-falcao
```

#### 2. Backend (NestJS)

```bash
# Acesse a pasta do backend
cd Codigo/backend/play-sports-falcao

# Instale as dependências
npm install

# Configure o arquivo .env (ver seção acima)
# ... copie o conteúdo de .env de exemplo

# Suba o banco de dados PostgreSQL com Docker
docker-compose up -d

# Execute as migrações do Prisma
npm run db:migrate

# (Opcional) Popule o banco com dados de exemplo
npm run db:seed

# Inicie o servidor em modo desenvolvimento
npm run start:dev
```

O servidor estará disponível em `http://localhost:3000`  
API docs em `http://localhost:3000/api` (Swagger)

#### 3. Frontend (React + Vite)

```bash
# Volte para a raiz e acesse a pasta frontend
cd ../../frontend

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm run dev
```

A aplicação estará disponível em `http://localhost:5173`

### 🧪 Credenciais de Teste

| Perfil | E-mail | Senha | Descrição |
|--------|--------|-------|-----------|
| **Admin** | admin@playsports.com | admin123 | Acesso total ao sistema |
| **Professor** | prof@playsports.com | prof123 | Gestão de aulas e feedbacks |
| **Responsável** | parent@playsports.com | parent123 | Portal do responsável |

---

## 📁 Estrutura de Pastas

```
play-sports-falcao/
├── Artefatos/                          # Documentação de projeto
│   ├── Atas/
│   ├── Casos-de-Uso/
│   │   ├── Historias-de-Usuario.md
│   │   └── code.md
│   └── Planejamento/
│
├── Codigo/
│   ├── backend/
│   │   └── play-sports-falcao/
│   │       ├── src/
│   │       │   ├── auth/                # Autenticação JWT
│   │       │   ├── users/               # Gerenciamento de usuários
│   │       │   ├── students/            # Gestão de alunos
│   │       │   ├── classes/             # Gestão de turmas
│   │       │   ├── sessions/            # Execução de aulas
│   │       │   ├── feedback/            # Feedbacks de desempenho
│   │       │   ├── expenses/            # Gestão de despesas
│   │       │   ├── financial-plans/     # Planos financeiros
│   │       │   ├── invoices/            # Faturas/Invoices
│   │       │   ├── notification/        # Notificações WhatsApp
│   │       │   ├── gallery/             # Galeria de fotos
│   │       │   ├── global-settings/     # Configurações globais
│   │       │   ├── trainings/           # Treinos/Exercícios
│   │       │   ├── mail/                # Envio de e-mails
│   │       │   ├── prisma/              # Módulo Prisma
│   │       │   ├── app.module.ts        # Root module
│   │       │   └── main.ts              # Entry point
│   │       ├── prisma/
│   │       │   ├── schema.prisma        # Schema do banco
│   │       │   ├── seed.ts              # Dados de exemplo
│   │       │   └── migrations/          # Histórico de migrações
│   │       ├── test/                    # Testes E2E
│   │       ├── docker-compose.yml       # Orquestração local
│   │       ├── package.json
│   │       ├── tsconfig.json
│   │       └── README.md
│   │
│   └── frontend/
│       ├── src/
│       │   ├── app/
│       │   │   ├── pages/               # Páginas da aplicação
│       │   │   │   ├── Admin/           # Dashboard Admin
│       │   │   │   ├── Teacher/         # Painel Professor
│       │   │   │   ├── Parent/          # Portal Responsável
│       │   │   │   ├── Landing/         # Landing Page
│       │   │   │   └── ...
│       │   │   ├── components/          # Componentes reutilizáveis
│       │   │   ├── layouts/             # Layouts principais
│       │   │   ├── services/            # Serviços HTTP e lógica
│       │   │   ├── routes.tsx           # Definição de rotas
│       │   │   └── App.tsx              # Componente root
│       │   ├── styles/
│       │   │   ├── index.css            # Global styles
│       │   │   ├── tailwind.css         # Tailwind imports
│       │   │   └── fonts.css            # Custom fonts
│       │   ├── assets/                  # Imagens e SVGs
│       │   ├── config/                  # Configurações (EmailJS, etc.)
│       │   ├── main.tsx                 # Entry point React
│       │   └── global.d.ts              # Tipos globais
│       ├── package.json
│       ├── vite.config.ts
│       ├── tailwind.config.js
│       ├── postcss.config.mjs
│       └── README.md
│
├── Divulgacao/
│   ├── Apresentacao/                    # Slides da apresentação
│   └── Video/                           # Vídeos de demonstração
│
├── Documentacao/
│   └── README.md
│
├── DOCUMENTACAO_PROJETO.md              # 📋 Documentação formal (UML)
├── README.md                            # Este arquivo
├── IMPLEMENTATION_SUMMARY.md            # Resumo de implementações
├── FRONTEND_EXPLORATION.md
├── GUIA_NOVO_FLUXO.md
├── EXPENSE_MANAGEMENT_README.md
├── LICENSE
└── package.json                         # Root package (scripts utilitários)
```

---

## 📖 Documentação Técnica

### Documentação de Arquitetura

Para diagramas completos e especificação técnica detalhada, consulte:

Inclui:
- Casos de Uso (10+ CUs)
- Diagramas de Sequência
- Diagrama de Classes (ER)
- Diagramas de Estados
- Arquitetura C4
- Esquema de Banco de Dados SQL

### API Reference

O backend expõe uma API REST completa documentada em Swagger:

```
GET  http://localhost:3000/api  — Swagger UI
```

Endpoints principais:
- `POST /api/auth/login` — Autenticação
- `GET /api/students` — Listar alunos
- `GET /api/classes` — Listar turmas
- `POST /api/sessions` — Criar aula
- `PATCH /api/sessions/:id` — Atualizar aula
- `GET /api/feedbacks` — Listar feedbacks

---

