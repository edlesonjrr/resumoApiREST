# Api Rest e RestFul

O **REST (Representational State Transfer)** é uma arquitetura de software que define um conjunto de restrições a serem utilizadas na criação de serviços web. Um serviço web que adere aos princípios do REST é chamado de **API REST (Application Programming Interface - Representational State Transfer)**.

Por outro lado, **RESTful** refere-se à implementação de uma API que segue os princípios do REST. Uma API RESTful é caracterizada pela utilização dos métodos HTTP corretos, como GET, POST, PUT e DELETE, para realizar operações em recursos identificados por URLs.

## Diferenças entre REST e RESTful

A principal diferença entre REST e RESTful é que REST é uma arquitetura de software, enquanto RESTful é a implementação prática dessa arquitetura em uma API.

# HTTP Verbs

Os **verbos HTTP** são métodos que indicam a ação a ser realizada em um recurso. As operações básicas em uma API RESTful são mapeadas para os seguintes verbos HTTP:

- **GET**: Recuperar informações de um recurso.
- **POST**: Criar um novo recurso.
- **PUT**: Atualizar um recurso existente.
- **DELETE**: Remover um recurso.

# HTTP Status Code

Os **códigos de status HTTP** indicam o resultado de uma operação no servidor. Alguns códigos comuns incluem:

- **200 OK**: A solicitação foi bem-sucedida.
- **201 Created**: A solicitação foi bem-sucedida e um novo recurso foi criado.
- **204 No Content**: A solicitação foi bem-sucedida, mas não há conteúdo para enviar.
- **400 Bad Request**: A solicitação não pôde ser compreendida ou foi malformada.
- **404 Not Found**: O recurso solicitado não foi encontrado.
- **500 Internal Server Error**: Indica um erro no servidor.

Esses conceitos formam a base para o design e implementação de APIs RESTful, proporcionando uma abordagem eficiente e escalável para o desenvolvimento de serviços web.


