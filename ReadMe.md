Criação de Aplicativo com React WEB e React Native Mobile eColeta com API Servidor em NodeJS

Conceitos
Rotas e Recursos
Métodos de Requisições HTTP
Tipos de Parâmetros

Utilizar o Insominia/PostMan
Qual Banco de Dados será Utilizado no Projeto
SQLite -
 Arquivo Físico database.sqlite

Knex.JS
Biblioteca/Interface com Linguagem Unificada para todos os Bancos de Dados

Query em Formato SQL
Query Builder em Formato de JavaScript com Kenx.JS

Indentificar Entidades da Aplicação
Pontos de Coleta

Items para Coleta

Um ponto de Coleta pode Coletar vários Items
Um Item pode ser Coletado por Vários Pontos de Coleta
Relacionamento Muitos / Muitos N/N
Necessário Criar Tabela Pivô

Migrations => Histórico do Banco de Dados

Funcionalidades da Aplicação Web
 Cadastro de Ponto de Coleta
 Rota para Listar Items Disponíveis

Funcionalidade da Aplicação Mobile
 Cadastro de Ponto de Coleta
 Listar os Pontos de Coleta
 Listar os Pontos de Coleta (Filtro por Estado/Cidade/Items)
 Listar um Ponto de Coleta Específico

Construção do App
Adicionar CORS
npm install cors --save
npm install @types/cors -D

Funcionalidade Knex Seeds

Fixar Imagem para os Items

Funcionalidade de Upload de Imagens será tratada posteriormente.

Final da Aplicação BackEnd API
 Cobertura de Vários assuntos envolvidos em APlicações do Mundo Real.
  SQL
  Migrations
  Seeds
  Transactions
  TypeScript

Recursos Avançados
UpLoad de Imagens

 Configurar BackEnd
  npm install multer
  npm install @types/multer -D
   Serialização
   API Transform

 Criar DropZone no React
  npm install --save react-dropzone

Validar Entrada de Dados
 FrontEnd
  Yup
 BackEnd
  npm install celebrate
  npm install @types/hapi__joi -D

Adicionar Projeto no GitHub

Deploy de APlicações NodeJS (Onde Hospedar)
 BackEnd
  Heroku
  Digital Ocean
  AWS
 FrontEnd
  Netlify/Vercel
  Amazon S3 / Google Cloud Storage

Mobile do App eColeta
Instalar Expo CLI
 npm install expo-cli -g
Criar Projeto com Expo
 expo init mobile --npm
 blank (typescript)
 expo-template-blank-typescript

Executar Projeto
 Se não rodar tentar instalar o expo:
 npm start

 Mesma LAN entre o Mobile e o PC (API/DEV)
 Baixar App Expo no Google Play Store(Android)/Apple App Store(iOS)
 QRCode (Abrir no App Expo Client)

Diferenças do React Native para ReactJS
 Elementos
 Estilização
Criar Página Home
Configurar Navegação
Criar Página do Mapa
Cria Página do Detalhe
Buscar Items da API
Buscar Pontos da API
Busca Detalhe do Ponto da API
Busca de US e Cidade
