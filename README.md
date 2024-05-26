# HerTech-Game
"HerTech &amp; Game" é mais que um app, é um ecossistema completo. Aqui, as mulheres se encontram!


# HerTech & Game

## Descrição
**HerTech & Game** é um aplicativo inovador projetado para oferecer um ambiente seguro e completo para mulheres que amam games e tecnologia. 
Nosso objetivo é empoderar mulheres na indústria de tecnologia e games, proporcionando um espaço onde possam se conectar, aprender e crescer profissionalmente.

## Funcionalidades Principais
### 1. Safe Zone
- Espaço livre de assédio.
- Grupos de jogo exclusivos.
- Chats moderados por IA e humanos.
- Ferramentas de segurança avançadas.

### 2. Portal de Educação
- Cursos online e tutoriais.
- Workshops e webinars ao vivo.
- Biblioteca de recursos educativos.

### 3. Mercado de Trabalho
- Bolsa de empregos e estágios.
- Perfis detalhados de vagas.
- Dicas de carreira.

### 4. Programa de Mentoria
- Conexão com mentores experientes.
- Solicitação de mentoria.
- Dicas de mentoria.

### 5. Comunidade
- Feed de notícias e eventos.
- Fórum de discussões.
- Compartilhamento de histórias de sucesso.

## Tecnologias Utilizadas
- **Front-end:** React, Redux, Material-UI
- **Back-end:** Node.js, Express.js
- **Banco de Dados:** MongoDB
- **Autenticação:** JWT (JSON Web Tokens)
- **Notificações:** Firebase Cloud Messaging (FCM)
- **Hospedagem:** Heroku, AWS

## Instalação e Configuração
### Pré-requisitos
- Node.js
- MongoDB
- Conta no Firebase para notificações

### Passos para Instalação
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/hertech-game.git
   cd hertech-game
Instale as dependências do back-end:

bash
Copiar código
cd backend
npm install
Configure as variáveis de ambiente:
Crie um arquivo .env na pasta backend com as seguintes variáveis:

env
Copiar código
PORT=5000
MONGO_URI=sua_uri_do_mongodb
JWT_SECRET=sua_chave_secreta_jwt
FCM_SERVER_KEY=sua_chave_do_firebase
Inicie o servidor back-end:

bash
Copiar código
npm start
Instale as dependências do front-end:

bash
Copiar código
cd ../frontend
npm install
Configure as variáveis de ambiente:
Crie um arquivo .env na pasta frontend com as seguintes variáveis:

env
Copiar código
REACT_APP_API_URL=http://localhost:5000
REACT_APP_FIREBASE_API_KEY=sua_api_key_do_firebase
REACT_APP_FIREBASE_AUTH_DOMAIN=sua_auth_domain_do_firebase
REACT_APP_FIREBASE_PROJECT_ID=sua_project_id_do_firebase
REACT_APP_FIREBASE_STORAGE_BUCKET=sua_storage_bucket_do_firebase
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=seu_messaging_sender_id_do_firebase
REACT_APP_FIREBASE_APP_ID=seu_app_id_do_firebase
Inicie o servidor front-end:

bash
Copiar código
npm start
Acesse a aplicação:
Abra o navegador e vá para http://localhost:3000

