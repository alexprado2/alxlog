## Sobre o projeto

Esta **API**, desenvolvida utilizando **Node.js** juntamente com **TypeScript**. Tem como principal objetivo ser uma API de gestão de restaurante, com abertura de mesas aos clientes ao chegar, registro de pedidos conforme o cardápio e envio, detalhamento de itens pedidos e fechamento de conta, com os dados sendo armazenados de forma segura em um banco de dados  **PostgreSQL**, juntamente com **Docker** criando um ambiente isolado e portátil que contém tudo o que é necessário para executar um aplicativo.

A arquitetura da **API** baseia-se em **REST**, utilizando métodos **HTTP** padrão para uma comunicação eficiente e simplificada. Além disso, é complementada por uma documentação **Insomnia**, que proporciona descrição de endpoints e métodos HTTP, exemplos de requisições e respostas, informações sobre autenticação e autorização, Descrição de erros e exceções.


Dentre os pacotes Node.js utilizados, **Express** é o responsável por fornecer uma estrutura flexível e minimalista para criar aplicações web robustas e escaláveis. O **Zod** é o responsável pela validação de dados, suporte a tipos de dados, suporte a arrays e objetos e mensagens de erro personalizádas. Por fim, o **Prisma** atua como um ORM (Object-Relational Mapper) que simplifica as interações com o banco de dados, permitindo o uso de objetos para manipular dados diretamente, sem a necessidade de lidar com consultas SQL.
<!-- 
![hero-image]
-->

### Features

- **Gerenciamento de Logs**: Crie, leia, atualize e exclua registros de log de forma eficiente e segura.
- **Autenticação de Usuário**: Registre-se e faça login de forma segura, com uma autenticação robusta e protegida contra ataques.
- **Integração com Banco de Dados**: Utilize o Prisma para operações com o banco de dados, garantindo uma integração segura e eficiente, com  armazenamento de dados em um banco de dados PostgreSQL . 
- **RESTful API com Documentação Insomnia**: Interface documentada que facilita a integração e o teste por parte dos desenvolvedores.

### Construído com

![badge-type]
![badge-express]
![badge-visual-studio]
![badge-zod]
![badge-postgres]
![badge-node]
![badge-insomnia]
![bagge-jwt]
![badge-prisma]
![badge-docker]
![badge-jest]

## Getting Started

Para obter uma cópia local funcionando, siga estes passos simples.

### Requisitos

* Visual Studio code versão 2022+ ou Visual Studio Code
* Windows 10+ ou Linux/MacOS com [NodeJs SDK][node-sdk] instalado
* [Docker SDK][docker-sdk] instalado
* PostgreSQL

### Instalação

1. Clone o repositório:
    ```sh
    gh repo clone alexprado2/alxlog
    ```

2. Confirure o `.env` conforme as informaçoes necessárias.
3. Inicie o NPM instalando as dependências `npm install`.
4. Configure o banco de dados com Docker `docker-compose up -d`.
5. Execute as migrações do banco de dados `npx prisma migrate dev`.
6. Inicie o servidor `npm run dev`.
7. Execute a API e aproveite o seu teste :)



<!-- Links -->
[node-sdk]: https://nodejs.org/pt
[docker-sdk]: https://docs.docker.com/desktop/setup/install/windows-install/

<!-- Images 
[hero-image]: images/heroimage.png
 -->

<!-- Badges -->
[badge-express]: https://img.shields.io/badge/Express-red?style=for-the-badge&logo=express
[badge-visual-studio]: https://img.shields.io/badge/VISUAL%20STUDIO%20CODE-blue?style=for-the-badge
[badge-zod]: https://img.shields.io/badge/Zod-black?style=for-the-badge&logo=zod
[badge-postgres]: https://img.shields.io/badge/PostgreSql-white?style=for-the-badge&logo=postgresql
[badge-node]: https://img.shields.io/badge/Node.Js-gren?style=for-the-badge&logo=node.js
[badge-insomnia]: https://img.shields.io/badge/insomnia-purple?style=for-the-badge&logo=insomnia
[bagge-jwt]:https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=jsonwebtokens
[badge-prisma]:https://img.shields.io/badge/prisma-blue?style=for-the-badge&logo=prisma
[badge-type]:https://img.shields.io/badge/typescript-white?style=for-the-badge&logo=typescript
[badge-docker]:https://img.shields.io/badge/docker-blue?style=for-the-badge&logo=docker
[badge-jest]:https://img.shields.io/badge/jest-purple?style=for-the-badge&logo=jest



