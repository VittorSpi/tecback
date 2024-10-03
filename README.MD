Projeto API Rest - Solo
Detalhamento do Projeto
Este projeto foi desenvolvido individualmente por Vittor Gabriel de Oliveira Soares com o objetivo de implementar um CRUD completo (excluindo o método PATCH) para diversas entidades. O projeto inclui a criação de Services, Repositories e Models, todos anotados com @Entity.

Contribuições
1. Filme
Endpoints:
GET /filmes: Obtém a lista de todos os filmes.
POST /filmes: Cria um novo filme.
PUT /filmes/{id}: Atualiza as informações de um filme existente.
DELETE /filmes/{id}: Remove um filme pelo ID.
Implementações:
FilmeService: Lógica de negócio para operações relacionadas a filmes.
FilmeRepository: Interação com o banco de dados para a entidade Filme.
Model Filme: Classe anotada com @Entity representando a tabela de filmes no banco de dados.
2. Diretor
Endpoints:
GET /diretores: Obtém a lista de todos os diretores.
POST /diretores: Cria um novo diretor.
PUT /diretores/{id}: Atualiza as informações de um diretor existente.
DELETE /diretores/{id}: Remove um diretor pelo ID.
Implementações:
DiretorService: Lógica de negócio para operações relacionadas a diretores.
DiretorRepository: Interação com o banco de dados para a entidade Diretor.
Model Diretor: Classe anotada com @Entity representando a tabela de diretores no banco de dados.
3. Ator
Endpoints:
GET /atores: Obtém a lista de todos os atores.
POST /atores: Cria um novo ator.
PUT /atores/{id}: Atualiza as informações de um ator existente.
DELETE /atores/{id}: Remove um ator pelo ID.
Implementações:
AtorService: Lógica de negócio para operações relacionadas a atores.
AtorRepository: Interação com o banco de dados para a entidade Ator.
Model Ator: Classe anotada com @Entity representando a tabela de atores no banco de dados.
4. Gênero
Endpoints:
GET /generos: Obtém a lista de todos os gêneros.
POST /generos: Cria um novo gênero.
PUT /generos/{id}: Atualiza as informações de um gênero existente.
DELETE /generos/{id}: Remove um gênero pelo ID.
Implementações:
GeneroService: Lógica de negócio para operações relacionadas a gêneros.
GeneroRepository: Interação com o banco de dados para a entidade Gênero.
Model Genero: Classe anotada com @Entity representando a tabela de gêneros no banco de dados.
Conclusão
Todos os endpoints, serviços e repositórios foram desenvolvidos e testados de maneira independente, garantindo a funcionalidade de um projeto completo de API Rest. Este projeto serve como uma base sólida para qualquer aplicação que necessite de gerenciamento de filmes, diretores, atores e gêneros.
