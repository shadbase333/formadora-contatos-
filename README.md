Projeto Contatos - Ionic + Firebase

📱 Sobre o Projeto

Este projeto foi desenvolvido como parte da Avaliação Formadora 3 do curso Análise e Desenvolvimento de Sistemas, no módulo Desenvolvimento de Aplicativos Mobile.

O objetivo é criar uma aplicação simples de gerenciamento de contatos utilizando Ionic, Firebase e Git, aplicando os conceitos de:

Gerência de configuração
Controle de versão
Criação de páginas e componentes
Consumo de API RESTful
Operações CRUD
Geração de build para produção
🚀 Funcionalidades Implementadas

Página listar-contatos
Página adicionar-contato
Componente contato-item
Consumo de API REST: https://jsonplaceholder.typicode.com/users
Integração com Firebase (Realtime Database)
Adicionar contatos
Listar contatos
Build para produção gerado na pasta www
🛠 Tecnologias Utilizadas

Ionic Framework (Angular)
TypeScript
Firebase Realtime Database
HTML / SCSS
Git e GitHub
API REST externa (JSONPlaceholder)
📂 Estrutura Inicial do Projeto

Criado com:

ionic start projeto-contatos blank
Páginas:

ionic generate page listar-contatos
ionic generate page adicionar-contato
Componente:

ionic generate component contato-item
Serviços:

api.service.ts  → Consumo da API REST
firebase.service.ts → CRUD no Firebase
🌐 API REST Utilizada

A aplicação consome dados da seguinte API pública:

https://jsonplaceholder.typicode.com/users
Na página listar-contatos são exibidos:

Nome
E-mail
🔥 Integração com Firebase

O Firebase Realtime Database foi configurado com as chaves fornecidas pelo console do Firebase.

O serviço inclui:

addContato() → adiciona um novo contato
getContatos() → retorna a lista de contatos
As bibliotecas utilizadas são do AngularFire.

🏗 Scripts de Build

No arquivo package.json foram adicionados:

"start": "ionic serve",
"build": "ionic build --prod"
O build de produção é gerado executando:

npm run build
O resultado fica na pasta:

www/
🧾 Controle de Versão (Git)

Commits realizados:

“Versão inicial - Configuração de projeto”
Commits intermediários (criação de páginas, componentes, serviços)
“Versão estável - Build gerado com sucesso”
📘 Aluno

Jean Silva Aragão
