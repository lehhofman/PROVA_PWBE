## Desafio

Este é um desafio para desenvolver operações CRUD (Create, Read, Update, Delete) para diferentes entidades em um banco de dados. As funcionalidades a serem desenvolvidas incluem:

- CRUD de Clientes
- CRUD de Telefones
- CRUD de Veículos
- CRUD de Aluguéis

Além disso, é necessário implementar rotas adicionais para os aluguéis, incluindo funcionalidades READ específicas:

1. Mostrar veículos reservados
2. Mostrar veículos alugados
3. Mostrar relatório completo de todos os aluguéis

## Entregas

Este repositório contém os seguintes itens:

### 1. Script SQL

O script de criação e população do banco de dados com dados de teste está localizado na pasta `testes`.

- `script.sql`

Este script deve ser utilizado para criar o banco de dados e popular com dados de teste.

### 2. API back-end

A API back-end com os CRUDs no padrão MVC está localizada na pasta `api`.

Nesta API, os CRUDs estão organizados seguindo o padrão MVC (Model-View-Controller).

### 3. Arquivo Insomnia

O arquivo `insomnia.json` contém todas as rotas de teste para a API. Ele está localizado na pasta `testes`.

Este arquivo pode ser importado no Insomnia para testar as rotas da API.

Para importar no Insomnia, siga estes passos:

1. Abra o Insomnia.
2. Vá para `File` > `Import`.
3. Selecione o arquivo `insomnia.json` deste repositório.
4. As rotas serão importadas e estarão disponíveis para teste no Insomnia.

### Modo de Testar

Após importar as rotas no Insomnia, você pode testar as funcionalidades CRUD e as rotas específicas dos aluguéis conforme necessário.

Certifique-se de que o servidor da API está em execução e configurado corretamente para se conectar ao banco de dados.
