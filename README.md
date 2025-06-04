🩺 Doutor Agenda
Doutor Agenda é uma aplicação SaaS para agendamento de consultas em clínicas médicas. Desenvolvida com Next.js e TypeScript, a plataforma oferece funcionalidades modernas para gerenciamento de clínicas, médicos e horários de atendimento.

🚀 Tecnologias Utilizadas
Next.js

TypeScript

Tailwind CSS

Drizzle ORM

Shadcn/UI

Neon (banco de dados serverless)

📦 Instalação
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/FCaires/doutor-agenda.git
cd doutor-agenda
Instale as dependências:

bash
Copiar
Editar
npm install
# ou
yarn install
Configure as variáveis de ambiente:

Crie um arquivo .env.local com as variáveis necessárias, como a URL do banco de dados Neon.

Execute as migrações do banco de dados:

Utilize o Drizzle ORM para aplicar as migrações necessárias.

Inicie o servidor de desenvolvimento:

bash
Copiar
Editar
npm run dev
# ou
yarn dev
Acesse a aplicação:

Abra http://localhost:3000 no seu navegador para visualizar a aplicação.

📁 Estrutura do Projeto
ruby
Copiar
Editar
doutor-agenda/
├── public/             # Arquivos públicos (imagens, favicon, etc.)
├── src/                # Código-fonte principal
│   ├── app/            # Páginas e rotas da aplicação
│   ├── components/     # Componentes reutilizáveis
│   ├── lib/            # Configurações e utilitários
│   └── styles/         # Estilos globais
├── drizzle.config.ts   # Configuração do Drizzle ORM
├── next.config.ts      # Configuração do Next.js
├── tsconfig.json       # Configuração do TypeScript
└── package.json        # Dependências e scripts do projeto
🛠️ Funcionalidades
Autenticação de usuários (e-mail/senha e Google)

Cadastro e gerenciamento de clínicas

Gerenciamento de profissionais de saúde

Agendamento de consultas

Interface responsiva e moderna com Shadcn/UI
