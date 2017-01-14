# Como invocar o AQL
As consultas AQL podem ser executadas usando:

* Interface Web
* O Objeto _db_ ( Em _arangosh_ ou em um serviço _Foxx_ )
* Ou a API HTTP

Há sempre chamadas para a API do servidor, mas a interface web e o objeto _db_ abstraem os detalhes de comunicação de baixo nível e, portanto, são mais fáceis de usar.

A Interface Web do ArangoDB tem um guia específico para execução de querys AQL

Você pode executar querys AQL no ArangoDB Shell com o __query_ e __createStatement_ metodos do objeto _db_. Este capítulo também descreve como usar parâmetros de ligação, estatísticas, contagem e cursores com _arangosh_.

Se você esta usando Foxx, veja como [escrever consultas no danco de dados](https://docs.arangodb.com/3.1/Manual/Foxx/GettingStarted.html#writing-database-queries) para exemplos que incluem cadeias de modelos etiquetados.

Se você quer executar querys AQL em sua aplicação usando API HTTP RESET, veja a descrição completa da API em [Interface HTTP para Querys AQL Cursors](https://docs.arangodb.com/3.1/HTTP/AqlQueryCursor/index.html).