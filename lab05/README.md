# Aluno
* `193400`: `<Alan Freitas Ribeiro>`

## Tarefa de Cypher sobre Marcadores e Taxonomia

## Tarefa 1

Escreva em Cypher uma consulta que retorne os marcadores da categoria `Serviços`, sem considerar as categorias subordinadas.

### Resolução
~~~cypher
MATCH r=(n)-[:Pertence]->(:Categoria{id:"Serviços"})
RETURN r
~~~

## Tarefa 2

Escreva em Cypher uma consulta que retorne os marcadores da categoria `Serviços`, considerando as categorias subordinadas.

### Resolução
~~~cypher
MATCH r=(n1)-[:Pertence]->(:Categoria{id:"Serviços"})
MATCH u=(n2)-[:Superior]->(:Categoria{id:"Serviços"})
MATCH rl=(n3)-[:Pertence]->(c:Categoria)
WHERE c.id = n2.id OR c.id = "Serviços"
RETURN rl
~~~
