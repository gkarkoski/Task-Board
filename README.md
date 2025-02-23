# Board de Tarefas
Um projeto de board de tarefas desenvolvido em Java, utilizando Gradle como gerenciador de dependências e Liquibase para versionamento do banco de dados.

# Funcionalidades

Criar, editar e excluir tarefas.

Organizar tarefas em colunas (ex: A Fazer, Em Progresso, Concluído).

Bloquear tarefas e registrar o motivo do bloqueio.

Gerenciar persistência dos dados utilizando um banco de dados relacional.


# Tecnologias Utilizadas

Java 17+ (ou versão compatível)

Gradle como gerenciador de dependências

Liquibase para versionamento do banco de dados

JDBC para conexão com o banco

DTOs (Data Transfer Objects) para abstração dos dados

Instalação e Execução

# Pré-requisitos

JDK 17+

Gradle

Banco de dados (ex: PostgreSQL, MySQL)

# Clonando o repositório

git clone https://github.com/seu-usuario/board-tasks.git
cd board-tasks

Configuração do banco de dados

Certifique-se de que seu banco de dados está rodando.

Configure as credenciais em src/main/java/br/com/dio/persistence/config/ConnectionConfig.java.

Executando o projeto

./gradlew build
./gradlew run

# Contribuindo

Se deseja contribuir para o projeto:

Fork o repositório.

Crie uma branch para sua feature (git checkout -b minha-feature).

Faça commit das suas mudanças (git commit -m 'Adiciona nova feature').

Envie para o repositório remoto (git push origin minha-feature).

Abra um Pull Request.
