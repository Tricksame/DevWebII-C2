## Como Inicializar o Projeto

Siga estes passos para colocar o projeto em funcionamento:

1. Instale as dependências  
   ```bash
   npm install

2. Crie o arquivo .env na raiz do projeto e adicione o conteúdo abaixo:
   ```bash
   DATABASE_URL="file:./dev.db"

3. Gere o cliente Prisma executando:
   ```bash
   npx prisma generate

4. Inicie a aplicação em modo de desenvolvimento:
   ```bash
   npm run dev

#Pronto! Agora o projeto estará rodando localmente.
