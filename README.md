# CRUD-Farmacia

Este repositório contém um projeto desenvolvido como parte de uma atividade prática, visando a criação de um sistema de gestão para farmácias. O sistema é capaz de manipular os dados dos produtos, os quais são classificados por categoria.

## Sobre o Projeto

Este projeto foi desenvolvido utilizando o Spring Tool Suite (STS), seguindo as melhores práticas de desenvolvimento com o framework Spring. O objetivo é fornecer um sistema backend eficiente e integrado para otimizar operações diárias e melhorar a qualidade dos serviços oferecidos aos clientes de uma farmácia.

## Tecnologias Utilizadas

- **Spring Boot**: Para a criação do projeto e configuração do ambiente de desenvolvimento.
- **MySQL**: Como sistema de gerenciamento de banco de dados.
- **JPA / Hibernate**: Para o mapeamento objeto-relacional e interação com o banco de dados.
- **Maven**: Para gerenciamento de dependências e construção do projeto.

## Estrutura do Projeto

O projeto segue a estrutura padrão de um projeto Spring Boot, com pacotes separados para `models`, `repositories`, `controllers`, entre outros. As principais funcionalidades implementadas incluem:

- **Configuração do Projeto**: Configuração inicial do projeto, incluindo `application.properties` e `pom.xml`.
- **CRUD de Categoria**: Implementação do CRUD completo para o recurso Categoria, sem relacionamento de entidades.
- **CRUD de Produto**: Implementação do CRUD completo para o recurso Produto, incluindo o relacionamento com Categoria.

## Como Executar

Para executar este projeto localmente, é necessário ter o Java e o Maven instalados. Clone o repositório e, no diretório principal do projeto, execute o seguinte comando:

```bash
mvn spring-boot:run
