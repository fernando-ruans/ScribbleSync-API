# Backend do Projeto ScribbleSync

## Descrição
O backend do ScribbleSync é desenvolvido em Node.js e utiliza uma variedade de bibliotecas para fornecer serviços de autenticação, gerenciamento de arquivos e comunicação com o banco de dados SQLite.

## Objetivos
- Fornecer serviços de autenticação seguros para os usuários.
- Gerenciar o armazenamento e a recuperação de dados no banco de dados SQLite.
- Facilitar a comunicação entre o frontend e o banco de dados.

## Funcionalidades Principais
1. **Autenticação com JWT**: Permite aos usuários autenticarem-se de forma segura e acessarem recursos protegidos.
2. **Gerenciamento de Arquivos**: Utiliza a biblioteca Multer para lidar com o upload e o armazenamento de arquivos.
3. **Comunicação com o Banco de Dados**: Utiliza o Knex para realizar operações de CRUD no banco de dados SQLite.
4. **Segurança com Bcrypt**: Protege as senhas dos usuários através do hash com a biblioteca Bcrypt.
5. **CORS**: Configuração para permitir requisições HTTP de origens diferentes.
6. **Testes com Insomnia**: Utiliza o Insomnia para realizar testes e depuração dos endpoints da API.

## Tecnologias Utilizadas
- **Node.js**: Ambiente de execução JavaScript do lado do servidor.
- **Express**: Framework web para Node.js que facilita a criação de APIs.
- **Bcrypt**: Biblioteca para hashing de senhas.
- **Cors**: Middleware para express que permite requisições de diferentes origens.
- **Jsonwebtoken**: Implementação de JSON Web Tokens para autenticação.
- **Knex**: Construtor de consultas SQL para Node.js.
- **Multer**: Middleware para lidar com multipart/form-data, usado para upload de arquivos.
- **SQLite**: Banco de dados SQL embutido.
- **Insomnia**: Ferramenta para testar e depurar APIs.
- **PM2**: Gerenciador de processos avançado para Node.js que permite gerenciar e manter aplicativos Node.js em execução em um ambiente de produção. Ele fornece recursos como monitoramento de processos, balanceamento de carga, recuperação de falhas e muito mais.

## Próximos Passos
- Implementar endpoints adicionais para outras funcionalidades do aplicativo.
- Refatorar o código para torná-lo mais modular e escalável.
- Introduzir testes automatizados para garantir a qualidade do código.
- Implementar rotinas de backup e recuperação de dados para garantir a integridade do banco de dados.

Este é apenas um esboço inicial.

[![img.jpg](https://i.postimg.cc/t4ZHWM4c/img.jpg)](https://postimg.cc/Bj0yGND5)
