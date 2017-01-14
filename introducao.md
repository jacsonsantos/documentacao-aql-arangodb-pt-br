# Introdução  

A linguagem de consulta do ArangoDB (AQL) pode ser usada para recuperar e modificar dados armazenados no ArangoDB. O fluxo geral quando uma consulta é executada é o seguinte:
 - Uma aplicação cliente envia uma consulta AQL para o servidor ArangoDB. O texto da consulta contém tudo que o ArangoDB precisa para compilar o resultado.  
 - O ArangoDB vai analisar a consulta, executar e compilar os resultados. Se a consulta for inválida ou não puder ser executada, o servidor retornará um erro ao qual o cliente pode processar e reagir. Se a consulta pode ser executada com sucesso, o servidor vai retornar o resultado da consulta (se houver) para o cliente.

AQL é principalmente uma linguagem declarativa, significando que a consulta expressa qual resultado deve ser alcançado, mas não como ele deve ser alcançado. A AQL pretende ser legível por humanos, e portanto, usa palavras-chave do idioma inglês. Outro objetivo de projeto da AQL foi a independência do cliente, o que significa que a linguagem e a sintaxe são as mesmas para todos os clientes, independentemente da linguagem de programação que os clientes possam usar. Outros objetivos de design da AQL foram o suporte a padrões de consulta complexas e os diferentes modelos de dados que o ArangoDB oferece.  

Em seu propósito, A AQL é similar a SQL (linguagem de consulta estruturada). AQL suporta leitura e modificação de coleções de dados, mas não suporta operações de definições de dados como a criação e exclusção de bancos de dados, coleções e indíces. É uma linguagem de manipulação de dados (DML) pura, não uma linguagem de definição de dados (DDL) ou linguagem de controle de dados (DCL).  

A sintaxe das consultas AQL são diferentes das SQL, mesmo que algumas palavras-chave sejam as mesmas. No entando, a AQL deve ser fácil de entender para qualquer pessoa com um pouco de experiência com SQL.

Para algumas consultas de exemplos, consulte as páginas [Consultas de dados](https://docs.arangodb.com/3.0/AQL/DataQueries.html) e [Padrões de consulta usuais](https://docs.arangodb.com/3.0/AQL/Examples/).
