# Projeto de Criação da Annotation @Tabela em Java

Este projeto envolve a criação de uma annotation personalizada em Java chamada `@Tabela`. Essa annotation é utilizada para especificar o nome da tabela associada a uma entidade no contexto de um sistema de mapeamento objeto-relacional (ORM), como JPA.

## Tecnologias Utilizadas

- **Java**: Linguagem de programação principal do projeto.
- **Annotation**: Recurso do Java utilizado para adicionar metadados a código fonte.
- **Reflection**: Utilizado para ler metadados das annotations em tempo de execução.
- **JPA (Java Persistence API)**: Framework de persistência de dados em Java, onde essa annotation pode ser aplicada.

## Funcionalidades Implementadas

- **Criação da Annotation @Tabela**: Definição da annotation `@Tabela` com um atributo para receber o nome da tabela.
- **Uso da Annotation**: Aplicação da annotation em classes de entidade para especificar o nome da tabela correspondente no banco de dados.
- **Leitura em Tempo de Execução**: Utilização de reflection para ler o valor da annotation em tempo de execução, facilitando a integração com o framework de persistência.
