# Gerenciador de Produtos - API RESTful

Este é um projeto CRUD (Create, Read, Update, Delete) desenvolvido com o Spring Framework para gerenciar produtos.

## Recursos

- **Criação de produtos**: Adicione novos produtos ao sistema.
- **Visualização de produtos**: Veja a lista de produtos disponíveis.
- **Atualização de produtos**: Atualize as informações de um produto existente.
- **Exclusão de produtos**: Remova um produto do sistema.

## Preparação do Ambiente

Para rodar este projeto, você precisará das seguintes ferramentas:

- JDK 17
- Maven
- Postman (para testar os endpoints da API)
- PgAdmin (para gerenciar o banco de dados Postgres)

## Como rodar o projeto

1. Clone este repositório para a sua máquina local.
2. Navegue até a pasta do projeto e execute o comando `mvn spring-boot:run`.
3. A API estará disponível no endereço `http://localhost:8080`.

## Testando a API

Você pode usar o Postman para testar os endpoints da API. Aqui estão alguns exemplos de requisições que você pode fazer:

- **GET /produtos**: Retorna uma lista de todos os produtos.
- **POST /produtos**: Cria um novo produto.
- **PUT /produtos/{id}**: Atualiza o produto com o ID especificado.
- **DELETE /produtos/{id}**: Exclui o produto com o ID especificado.

Espero que você encontre este projeto útil e interessante. Se tiver alguma dúvida ou sugestão, sinta-se à vontade para abrir uma issue. Obrigado!
