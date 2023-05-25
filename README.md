# Conceitos Básicos de Banco de Dados
Um banco de dados é uma coleção organizada de dados estruturados, armazenados eletronicamente em um sistema de computador. Ele é projetado para armazenar, gerenciar e recuperar informações de maneira eficiente. Um banco de dados é composto por tabelas, que são estruturas que contêm linhas e colunas. Cada tabela representa uma entidade específica (por exemplo, clientes, produtos, pedidos) e cada linha na tabela representa uma instância dessa entidade, contendo informações específicas.

As colunas da tabela representam os atributos ou características da entidade. Por exemplo, em uma tabela de clientes, você pode ter colunas como nome, endereço, número de telefone, e assim por diante. Os bancos de dados permitem que os dados sejam armazenados de forma persistente, o que significa que eles permanecem disponíveis mesmo após o desligamento do sistema. Isso facilita o acesso aos dados, a realização de consultas complexas e a manipulação das informações de forma segura e consistente.

Além disso, os bancos de dados oferecem recursos para garantir a integridade dos dados, como restrições de chave primária, chaves estrangeiras e regras de validação. Eles também oferecem recursos para consultas, como a capacidade de filtrar, classificar e combinar dados de várias tabelas.
Os bancos de dados são amplamente utilizados em uma variedade de aplicações e setores, incluindo sistemas de gerenciamento de conteúdo, sistemas de gerenciamento de relacionamento com o cliente (CRM), sistemas de gerenciamento de estoque, aplicativos bancários, sistemas de reservas, entre outros. Em resumo, um banco de dados é uma ferramenta essencial para armazenar, gerenciar e acessar grandes volumes de dados de maneira estruturada e eficiente.

## Conceito de SGBD
SGBD é a sigla para **Sistema de Gerenciamento de Banco de Dados**. Trata-se de um software responsável por gerenciar o armazenamento, organização, recuperação e segurança dos dados em um banco de dados. Um SGBD oferece um conjunto de recursos e funcionalidades que permitem aos usuários criar, manipular e consultar bancos de dados de forma eficiente. Algumas das principais características de um SGBD incluem:

* Criação e definição de estrutura: O SGBD permite criar a estrutura do banco de dados, incluindo a definição de tabelas, relacionamentos, restrições, índices e outros elementos que definem a organização dos dados.

* Manipulação de dados: O SGBD permite adicionar, modificar e excluir dados no banco de dados. Isso pode ser feito por meio de comandos SQL (Structured Query Language) ou interfaces gráficas fornecidas pelo sistema.

* Consultas e recuperação de dados: O SGBD oferece recursos para executar consultas complexas e recuperar dados de forma eficiente. Isso inclui filtragem, ordenação, junção de tabelas e outras operações para obter os resultados desejados.

* Controle de acesso e segurança: O SGBD possui mecanismos de controle de acesso que determinam quais usuários ou grupos de usuários têm permissão para acessar e manipular os dados. Além disso, ele pode fornecer recursos de segurança, como criptografia e auditoria, para proteger os dados contra acessos não autorizados.

* Concorrência e recuperação de falhas: O SGBD lida com situações de concorrência, onde múltiplos usuários acessam e modificam os dados simultaneamente, garantindo a consistência dos dados. Além disso, ele possui recursos de recuperação de falhas, que permitem restaurar o banco de dados em um estado consistente após uma falha do sistema.

Exemplos de SGBDs populares incluem o Oracle Database, MySQL, Microsoft SQL Server, PostgreSQL e MongoDB. Esses sistemas são amplamente utilizados em diferentes aplicações e setores para gerenciar eficientemente grandes volumes de dados.

## Modelagem de Dados
A **modelagem de banco de dados** é o processo de criar uma representação estruturada e organizada de um sistema de banco de dados. É uma etapa crucial no desenvolvimento de um sistema de gerenciamento de banco de dados (SGBD) e envolve a definição dos objetos do banco de dados, suas propriedades e os relacionamentos entre eles.

A modelagem de banco de dados é uma etapa fundamental antes da implementação do sistema de banco de dados, pois fornece uma representação clara e estruturada dos dados a serem armazenados. Isso permite que os desenvolvedores, administradores de banco de dados e outros profissionais envolvidos tenham uma visão abrangente do sistema e possam projetar e implementar o banco de dados de forma adequada às necessidades do sistema e dos usuários.

### Modelagem Conceitual
A modelagem conceitual é uma etapa inicial no processo de modelagem de banco de dados, onde o foco está na compreensão e representação dos conceitos e relacionamentos fundamentais do domínio de aplicação, independentemente das preocupações de implementação técnica.

O objetivo da modelagem conceitual é capturar os requisitos e as regras de negócio em um nível abstrato, fornecendo uma visão ampla e compreensível do sistema em questão. Ela busca identificar as principais entidades, atributos e relacionamentos que existem no domínio do problema, sem se preocupar com a estrutura física do banco de dados ou as tecnologias utilizadas.

A modelagem conceitual utiliza um modelo de dados conceitual, como o Modelo Entidade-Relacionamento (ER), para representar os conceitos do domínio. Nesse modelo, as entidades são representadas como objetos distintos e os relacionamentos entre essas entidades são definidos. A ênfase está na identificação das entidades principais, seus atributos relevantes e os relacionamentos entre elas.

A modelagem conceitual ajuda a estabelecer uma linguagem comum entre os usuários, analistas de negócios e desenvolvedores, facilitando a comunicação e o entendimento dos requisitos do sistema. Ela fornece uma visão geral do sistema, identificando as principais entidades e relacionamentos que precisam ser considerados na fase de implementação.

Algumas técnicas e ferramentas comuns usadas na modelagem conceitual incluem:

* Diagramas de Entidade-Relacionamento (DER): Representam graficamente as entidades, atributos e relacionamentos usando caixas (entidades) e linhas (relacionamentos).

* Diagramas de Classes: Utilizados em modelagem orientada a objetos para representar as classes, atributos e associações do sistema.

* Diagramas de Fluxo de Dados (DFD): Mostram a interação entre diferentes partes do sistema, representando como as informações fluem através dos processos.

A modelagem conceitual é uma etapa importante para estabelecer uma base sólida na modelagem de banco de dados, fornecendo uma representação clara e compreensível dos conceitos e relacionamentos essenciais no domínio do problema. A partir dessa base, é possível avançar para a modelagem lógica e física, onde os detalhes de implementação técnica são considerados.
## Comando Básicos SQL para banco MySql

### Comentários
os comentários são extremamente importantes para documentar e apoiar o 
```
CREATE DATABASE PROJETO;
```
