# 1 - Descrição
    Deve-se criar uma aplicação de lista de atividades (TODO).
    A aplicação dever possuir os seguintes comportamentos:
* Criar tarefas
* Editar tarefas. 
* Excluir tarefas
* Concluir atividade e voltar elas da conclusão.

# 2 - Tecnologias

### 2.1 - Frontend
- [ ] Angular.io - https://angular.io/

### 2.2 - Backend
- [ ] NodeJS - https://nodejs.org/en/
- [ ] ExpressJS - https://expressjs.com/pt-br/
- [ ] Sequelize - https://sequelize.org/

### 2.3 - Banco de dados
- [ ] PostgreSql - https://www.postgresql.org/

# 3 - Requisitos

### 3.1 - Frontend
#### 3.1.1 - Descrição.
    A interface com o usuário deve permitir a manipulação da atividades tendo os seguintes recursos.
#### 3.1.2 - Recursos.
- [ ] Deve possibilitar o usuário criar uma nova atividade.
- [ ] Deve possuir uma lista com as atividades não concluídas.
    - [ ] A lista deve estar ordenada por ordem de criação decrescente.
    - [ ] No item da lista deve possuir a descrição da atividade.
    - [ ] No item da lista deve possuir uma forma de concluir a atividade.
    - [ ] No item da lista deve possuir uma forma de excluir a atividade.
- [ ] Deve possuir uma lista com as atividades já concluídas.
    - [ ] A lista deve estar ordenada por ordem de conclusão decrescente.
    - [ ] No item da lista deve possuir a descrição da atividade.
    - [ ] No item da lista deve possuir uma forma de voltar a a atividade para não concluída.
    - [ ] No item da lista deve possuir uma forma de excluir a atividade.

<!-- #### 3.1.3 Modelo
[TODO] = Adicionar o link da especificação da tela. -->

#### 3.1.3 - Observações
    A interface pode ser feita da forma que desejar atendendo os recursos listados na sessão #3.1.2.
<!-- Não sendo necessário seguir o modelo da sessão 3.1.3 -->
### 3.2 - Backend
#### 3.2.1 - Descrição.
    O backend deve possuir as seguintes funcionalidades.
#### 3.2.2 - Funcionalidades.
- [ ] Atividade
    - [ ] Criar atividade.
    - [ ] Atualizar atividade.
    - [ ] Excluir atividade.
    - [ ] Listar atividade.

#### 3.2.3 - Observações.
* Outras funcionalidades podem ser criadas para atender as necessidades do projeto.

### 3.3 Banco de dados
#### 3.3.1 - Descrição.
    A aplicação deve possuir as seguintes entidades de banco de dados:

#### 3.3.2 - Tabelas.
- [ ] Atividade
    - [ ] id - Inteiro, Auto incremento, NOT NULL
    - [ ] descrição - Texto, NOT NULL
    - [ ] concluído - Boolean , NOT NULL
    - [ ] data criação - Data , NOT NULL
    - [ ] data conclusão - Data


# 4 - Entrega.

    Para realizar a entrega do projeto siga as instruções abaixo:

* Clone o projeto para sua estação de trabalho.
* No diretório entregas, crie um novo diretório com seu nome.
* Dentro do diretório do seu nome adicione todos os arquivos do seu projeto.
* Crie um README.md com as instruções para rodar o projeto.
* Crie um pull request para realizar a entrega.
