🧩 Projeto CRUD com Java e Spring Boot

Este projeto é uma aplicação CRUD (Create, Read, Update, Delete) desenvolvida com Java e Spring Boot, que demonstra os principais conceitos de desenvolvimento de APIs RESTful.
O objetivo é fornecer uma base sólida para criação de sistemas que envolvem manipulação de dados, integrando boas práticas e uma arquitetura limpa.

🚀 Tecnologias Utilizadas

☕ Java 17+

🌱 Spring Boot

🧩 Spring Data JPA

🧰 Hibernate

🗄️ PostgreSQL

📦 Maven

🧪 Spring Web / Spring Validation

🧭 Swagger / Springdoc OpenAPI (opcional, para documentação da API)

⚙️ Funcionalidades

✅ Criar novos registros

🔍 Listar todos os registros

📄 Buscar um registro por ID

✏️ Atualizar registros existentes

🗑️ Excluir registros

(Adicione mais funcionalidades específicas conforme seu projeto evoluir.)

🧱 Estrutura do Projeto
src/
├── main/
│   ├── java/
│   │   └── com.vitordutra/
│   │       ├── controller/
│   │       ├── model/
│   │       ├── repository/
│   │       └── service/
│   └── resources/
│       ├── application.properties
│       └── data.sql (opcional)
└── test/

🧩 Como Executar o Projeto

Clonar o repositório

git clone https://github.com/vitordutra/docker.git


Acessar o diretório do projeto

cd docker


Configurar o banco de dados PostgreSQL

No arquivo src/main/resources/application.properties, configure:

spring.datasource.url=jdbc:postgresql://localhost:5432/nomedobanco
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true


Executar o projeto

mvn spring-boot:run


Acessar a aplicação

API: http://localhost:8080

Swagger (se configurado): http://localhost:8080/swagger-ui.html

🧾 Exemplos de Endpoints
Método	Endpoint	Descrição
GET	/api/...	Lista todos os registros
GET	/api/.../{id}	Busca por ID
POST	/api/...	Cria um novo registro
PUT	/api/.../{id}	Atualiza um registro existente
DELETE	/api/.../{id}	Remove um registro
🧑‍💻 Autor

Vitor Dutra 
📧 vitordutra1125@gmail.com


🪪 Licença

Este projeto está sob a licença MIT — sinta-se à vontade para usá-lo e modificá-lo conforme necessário.
