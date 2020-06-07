Explicar Conceitos
Rotas e Recursos
Métodos de Requisições HTTP
Tipos de Parâmetros
request.body
request.params
request.query.filtro
Utilizar o Insominia/PostMan
Qual Banco de Dados será Utilizado no Projeto
SQL:
Postgres
MySQL
SQL Server
SQLite -
 Arquivo Físico database.sqlite
NoSQL:
MongoDB, CouchDB

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
  https://unsplash.com/s/photos/market
  https://github.com/expressjs/multer
  npm install multer
  npm install @types/multer -D
   Serialização
   API Transform

 Criar DropZone no React
  https://react-dropzone.js.org/
  https://github.com/react-dropzone/react-dropzone
  npm install --save react-dropzone
  yarn add react-dropzone

Validar Entrada de Dados
 FrontEnd
  https://github.com/jquense/yup
 BackEnd
  https://github.com/arb/celebrate
  https://github.com/hapijs/joi

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
 https://localhost:19000
 exp://192.168.1.66:19000
 LAN (Selected)
 Mesma LAN entre o Mobile e o PC (API/DEV)
 Baixar App Expo no Google Play Store(Android)/Apple App Store(iOS)
 QRCode (Abrir no App Expo Client)
Configurar Emulador (Como Necessário)
 YouTube (Emulador Expo)
 Emulador Expo Rockeseat
 Emulando React Native no iOS/Android com Expo | Code/Drops #03

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

Sempre que uma chamada para uma função receber parâmetros
Necessário transforma a chamada da função em uma Arrow Fuction
Exemplo:
 onPress={() => handleNavigateToDetail(point.id)}
