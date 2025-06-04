<h1 align="center">🩺 Doutor Agenda</h1> <p align="center"> <strong>Uma plataforma moderna de agendamento médico.</strong><br/> Desenvolvido com Next.js, TypeScript, Drizzle ORM, Tailwind CSS e Shadcn/UI. </p> <p align="center"> <img src="https://img.shields.io/github/license/FCaires/doutor-agenda" alt="License"> <img src="https://img.shields.io/github/languages/top/FCaires/doutor-agenda" alt="Top Language"> <img src="https://img.shields.io/github/last-commit/FCaires/doutor-agenda" alt="Last Commit"> </p>
✨ Visão Geral
Doutor Agenda é uma aplicação SaaS pensada para facilitar o gerenciamento de clínicas e consultórios médicos. A plataforma permite o cadastro de clínicas, médicos, agendamento e controle de consultas, utilizando tecnologias modernas e escaláveis.

🛠️ Tecnologias e Ferramentas
⚡️ Next.js — Framework React para produção

🟦 TypeScript — Tipagem estática

🎨 Tailwind CSS — Estilização utilitária

🛡️ Shadcn/UI — Componentes de interface modernos

🗄️ Drizzle ORM — ORM leve e typesafe

🛢️ Neon — Banco de dados PostgreSQL serverless

🚀 Começando
✅ Pré-requisitos
Node.js >= 18

npm ou yarn

Conta no Neon ou outro banco PostgreSQL

Variáveis de ambiente configuradas

⚙️ Instalação
Clone o repositório

bash
Copiar
Editar
git clone https://github.com/FCaires/doutor-agenda.git
cd doutor-agenda
Instale as dependências

bash
Copiar
Editar
npm install
# ou
yarn install
Configure as variáveis de ambiente

Crie um arquivo .env.local na raiz e adicione:

env
Copiar
Editar
DATABASE_URL=postgresql://<usuario>:<senha>@<host>/<database>
NEXTAUTH_SECRET=uma_chave_secreta
NEXTAUTH_URL=http://localhost:3000
Rode as migrações

Configure e execute as migrações com o Drizzle ORM.

Inicie o servidor de desenvolvimento

bash
Copiar
Editar
npm run dev
# ou
yarn dev
Acesse a aplicação

http://localhost:3000

🗂️ Estrutura do Projeto
ruby
Copiar
Editar
├── public/            # Arquivos estáticos
├── src/
│   ├── app/          # Rotas e páginas
│   ├── components/   # Componentes reutilizáveis
│   ├── lib/          # Configurações, clientes e utilitários
│   └── styles/       # Estilos globais
├── drizzle.config.ts # Configuração do Drizzle ORM
├── next.config.js    # Configurações do Next.js
├── tsconfig.json     # Configurações do TypeScript
└── package.json      # Scripts e dependências
📌 Funcionalidades
✅ Autenticação (e-mail/senha, Google OAuth)

✅ Cadastro e gerenciamento de clínicas

✅ Gestão de profissionais

✅ Sistema de agendamento de consultas

✅ Dashboard intuitivo

✅ Interface responsiva e acessível

🤝 Contribuindo
Faça um fork.

Crie uma branch: git checkout -b minha-feature

Commit: git commit -m 'feat: minha nova feature'

Push: git push origin minha-feature

Abra um Pull Request!

