# Banco de Dados Relacional e NoSQL

Os bancos de dados relacionais armazenam dados de acordo com esquemas específicos. Por outro lado, os sistemas NoSQL permitem que os dados sejam armazenados usando qualquer estrutura necessária, mas fornece uma maneira de atualizar esses dados ao alterar essa estrutura.

A linguagem SQL (Structured Query Language) é usada para executar comandos em bancos de dados relacionais, que são os bancos baseados em tabelas.

Bancos de dados relacionais, como os do MySQL e PostgreSQL, armazenam dados usando um esquema explícito. Um esquema descreve como gravar dados no banco de dados, particularmente descrevendo a estrutura, tipos e estruturas de tabelas e registros.

Os termos ‘SQL’ e ‘NoSQL’ referem-se essencialmente a como esses esquemas são definidos. Em um banco de dados relacional, os usuários usam as instruções SELECT, INSERT e DELETE para adicionar ou atualizar dados.

O banco de dados NoSQL refere-se a um banco de dados não relacional.

Um banco de dados relacional é um formato de banco de dados rigidamente estruturado, baseado em tabelas, como – por exemplo- o MySQL ou o Oracle. Os bancos de dados NoSQL são documentados e permitem que você armazene e recupere dados em formatos diferentes das tabelas. Plataformas Populares NoSQL incluem MongoDB, ElasticSearch e Redis.

As aplicações modernas utilizam e geram tipos de dados complexos e em evolução. Os bancos de dados relacionais não foram projetados para lidar com esse tipo de armazenamento e recuperação de dados. Os bancos de dados NoSQL são mais flexíveis e escaláveis.

Em um Banco de Dados NoSQL, você pode adicionar novos dados sem ter que pré-definido no esquema do banco de dados, permitindo o processamento rápido de grandes volumes de dados não estruturados, semiestruturados e estruturados.

O esquema dinâmico dos bancos de dados NoSQL aceita prontamente o desenvolvimento ágil, o que requer iterações significativas e rápidas.

O termo NoSQL possui duas definições com origens diferentes, uma fazendo referência ao banco de dados RELACIONAL que não utilizava linguagem SQL para queries (consultas) criado por Carlo Strozzi e outra relacionada ao movimento NoSQL que define um conjunto de ferramentas que não faz uso de uma estrutura relacional. Esse último foi definido como NoSQL por Eric Evans, commiter do projeto Cassandra.

O banco NoSQL criado por Strozzi é basicamente composto por um conjunto de arquivos, organizados no formato hierárquico de um banco de dados e que faz uso do Shell UNIX como ferramenta de interação.

Já os modelos de banco NoSQL que nasceram após o ano 2000, possuem estruturas completamente diferentes, utilizando cada um uma forma de consulta não compatível com os demais.

Existem 4 tipos de bancos de dados NoSQL definidos pela forma como armazenam os dados em suas estruturas, são eles:

- Documents
- Graphs
- Key-Value pairs
- Wide Column Store

## Documents

Um dos tipos mais versáteis que temos no mundo NoSQL, possuindo um schema definido como flexível que permite que os registros e documentos possuam campos com diferentes tipos e em diferentes quantidades sem a existência de um schema fixo. Tais documentos são definidos em formato JSON, utilizando conceitos próximos do modelo Orientado à Objetos onde o objeto aqui equivaleria a um documento. Novos campos podem ser adicionados facilmente, permitindo uma rápida evolução da aplicação em desenvolvimento. Exemplos: MongoDB e CouchDB.

## Graph

O modelo baseado em estruturas de grafos pode não ser o mais intuitivo, pois os dados são definidos dentro dos nós e vértices, mas permitem a resolução de um tipo específico de queries baseadas em relacionamento. Exemplos: Neo4J e AWS Neptune.

## Key-Value pairs

Bancos do tipo chave-valor são comumente utilizados para sistemas de cache e sessão. Sua estrutura é definida como campos chave mapeados para um objeto muitas vezes não estrutural, em que as consultas somente podem ser realizas pelo campo chave. Exemplos: Memcached, Redis e DynamoDB.

## Wide Column Store

Bancos do tipo Wide Column Store utilizam matrizes multi-dimensionais para armazenamento dos dados. São amplamente utilizadas para armazenar quantidades massivas de dados. Os dados são consultados utilizando chaves para cada columna. Exemplo: HBase e Cassandra.

Este tipo de banco de dados é utilizado para solucionar problemas onde o modelo relacional não se adequa, principalmente levando em consideração a quantidade massiva de dados que aplicações de redes sociais e serviços web recebem nos dias atuais. Para essa necessidade não só o modelo de armazenamento precisa ser mais dinâmico em algumas situações em que os dados não são estruturados, mas também a capacidade de escalar fez com que o NoSQL fosse amplamente adotado.
