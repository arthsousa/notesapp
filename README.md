📝 Notes App - Full Stack com React + AWS Amplify

Aplicação full stack desenvolvida com React utilizando Vite no frontend e AWS Amplify no backend. O projeto permite autenticação de usuários e gerenciamento de notas com suporte a upload de imagens.

🚀 Funcionalidades
Cadastro e login de usuários (autenticação)
Criação de notas
Listagem de notas
Exclusão de notas
Upload de imagens associadas às notas
Deploy automático com integração ao GitHub
🛠️ Tecnologias utilizadas
React + Vite
AWS Amplify
AWS Amplify UI
GraphQL (via Amplify Data)
JavaScript
Node.js
📦 Instalação e execução

Clone o repositório:

git clone https://github.com/seu-usuario/notesapp.git

Acesse a pasta do projeto:

cd notesapp

Instale as dependências:

npm install

Execute o projeto:

npm run dev
☁️ Configuração do backend (AWS Amplify)

Para configurar o backend, execute:

npm create amplify@latest

Depois, inicie o ambiente sandbox:

npx ampx sandbox
🔄 Deploy

O deploy é feito automaticamente via AWS Amplify ao conectar o repositório do GitHub.

A cada git push, uma nova versão da aplicação é publicada automaticamente.

📁 Estrutura do projeto
/src → código frontend React
/amplify → configurações do backend (auth, data, storage)
amplify_outputs.json → configuração gerada do backend
📚 Aprendizados

Este projeto foi desenvolvido com base em um tutorial prático da AWS, abordando:

Integração entre frontend e backend serverless
Autenticação com Amplify
CRUD completo (Create, Read, Update, Delete)
Upload e gerenciamento de arquivos
Deploy contínuo (CI/CD)
📌 Observações
É necessário ter uma conta na AWS para rodar o backend completo
O projeto pode gerar custos caso ultrapasse o Free Tier da AWS