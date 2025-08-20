**Roteiro**

**D1:**

- Criação do arquivo de inicialização

- Download

- Importação no Eclipse

- execução no Eclipse e teste no browser

- Configuração do plugin Maven

- Configuração do application.properties

- Configuração do application-test.properties

- Criar a classe Game

- Executar o projeto e acessar http://localhost:8080/h2-console

- Criar arquivo de Seed: import.sql

- Reiniciar o projeto para validar a população da tabela TB_GAME no H2

- Criar o DTO GameMinDTO

- Criar objeto Repository (extends JpaRepository)

- Criar camada de Serviço (Service) - responsável pelas regras de negócio (componente registrado)

- Criar o Controlador 


**D2:**

- Relacionamentos: muitos para muitos, classe extra de associação com dados extras (Belonging)

- Implementar modelo de domínio: implementar classes GameList, Belonging

- Atualizar o seed da base de dados

- Implementar GameDTO, busca game por id

- Implementar busca de todas as listas em /listss


**D3:**

- Configuração de perfis (test/Homologação/produção)

- Levantar um BD Postgres + PgAdmin

- Criar perfis para HML local (projeto, gerar script da base de dados, criar BD de HML, rodar app no modo dev e validar)

-




