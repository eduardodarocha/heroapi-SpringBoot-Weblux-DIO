## Gerenciador de super heróis numa API reativa com Spring Boot / Webflux / Library Reactor / DynamoDb / Postman Documenter / Swagger

#### API/Repositório criado no Desafio de projeto do Bootcamp Inter Java Developer da Digital Innovation One
- Desenvolvimento de uma API de gerenciamento de heróis utilizando:
	- Spring Boot;
	- Spring Webflux;
	- Biblioteca reativa Reactor;
	- Banco de dados DynamoDb (local);
	- JUnit para testes unitários da API;
	- Postman para requests;
	- Postman Documenter para criação de documentação;
	- Swagger para criação de documentação, visualização e interação com API.
	
	
- Etapas da criação, instalação e uso da API:
	- criar arquivo de configuração no spring initializr (https://start.spring.io/);
	- instalar AWS CLI (https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-chap-install.html);
	- abrir conta na AWS(https://aws.amazon.com/pt/); 
	- configurar o AWS CLI (https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-chap-configure.html);
		- anotar os dados criados na configuração do seu AWS CLI:
			- AWS Access Key ID [None]: AKIAIOSFODNN7EXAMPLE
			- AWS Secret Access Key [None]: wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
			- Default region name [None]: us-west-2 (sua escolha)
			- Default output format [None]: json
	- instalar e iniciar o DynamoDB localmente (https://docs.aws.amazon.com/pt_br/amazondynamodb/latest/developerguide/DynamoDBLocal.DownloadingAndRunning.html);
	- fazer o download da API e inicializar a aplicação HeroApiApplication.java;
	- criar uma tabela usando HeroesTable.java
	- inserir alguns itens na tabela com HeroesData.java
	- criar requisições no Postman (Get all heroes, Get hero by id, Create new hero, Delete hero by id);
	- criar documentação no Postman e publicar(https://documenter.getpostman.com/view/14419684/Tz5qbHT3);
	- executar os testes HeroApiApplicationTest.java
	- abrir a documentação do Swagger (http://localhost:8080/webjars/swagger-ui/index.html?configUrl=/v3/api-docs/swagger-config); 	

#### Instrutora: Kamila Santos
