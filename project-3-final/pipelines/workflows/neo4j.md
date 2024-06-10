# Redes de correlação entre metabólitos

## Construção das redes

### Modelo lógico

| Controle | Câncer |
| :--------: | :------: |
| ![](../../assets/images/healthy_neo4j_model.png) | ![](../../assets/images/cancer_neo4j_model.png) |

### Propriedades de nós e arestas

Para a construção de cada um dos modelos, os seguintes arquivos foram utilizados no mapeamento de nós e arestas:

||Controle|Câncer|
|--|--|--|
|Nós|[`metabolites_from_pathways.csv`](../../data/processed/metabolites_from_pathways.csv)|[`metabolites_from_pathways.csv`](../../data/processed/metabolites_from_pathways.csv)|
|Arestas|[`healthy_corr_edges.csv`](../../data/processed/healthy_corr_edges.csv)|[`cancer_corr_edges.csv`](../../data/processed/cancer_corr_edges.csv)|

Como propriedades, as seguintes colunas foram utilizadas:

| Nós | Arestas |
| :--------: | :------: |
| <img src="../../assets/images/node_properties.png" width="200"> | <img src="../../assets/images/edge_properties.png" width="200"> |

### Redes importadas

Ao todo, 42 nós e 400 relações foram importados.

| Nós | Arestas |
| :--------: | :------: |
| ![](../../assets/images/healthy_imported.png) | ![](../../assets/images/cancer_imported.png) |


## Visualização das redes

```
MATCH (c1:Healthy)-[c:HealthyCorrelates]-(c2:Healthy)
WHERE  abs(c.correlation) > 0.6 AND c1 > c2
RETURN c1, c2, c
```
> ![](../../assets/images/healthy_neo4j_net.png)

```
MATCH (c1:Cancer)-[c:CancerCorrelates]-(c2:Cancer)
WHERE abs(c.correlation) > 0.6 AND c1 > c2
RETURN c1, c2, c
```
> ![](../../assets/images/cancer_neo4j_net.png)


## Tabelas 

Finalmente, os modelos foram exportados como tabelas. Somente as arestas cuja correlação foi superior a 0.5 foram selecionadas.

```cypher
MATCH (c1:Healthy)-[c:HealthyCorrelates]-(c2:Healthy)
WHERE  abs(c.correlation) > 0.5 AND c1 > c2
RETURN c1.name, c2.name, c.correlation, c1.KEGG, c2.KEGG
```
> [`neo4j_query_table_data_healthy.csv`](../../data/processed/neo4j_query_table_data_healthy.csv)

| c1.name            | c2.name    | c.correlation | c1.KEGG | c2.KEGG |
| ------------------ | ---------- | ------------- | ------- | ------- |
| 2-ketobutyric acid | putrescine | 0.661833856   | C00109  | C00134  |
| l-cysteine         | putrescine | 0.545271146   | C00097  | C00134  |
| ... | | |


```
MATCH (c1:Cancer)-[c:CancerCorrelates]-(c2:Cancer)
WHERE abs(c.correlation) > 0.5 AND c1 > c2
RETURN c1.name, c2.name, c.correlation, c1.KEGG, c2.KEGG
```
> [`neo4j_query_table_data_cancer.csv`](../../data/processed/neo4j_query_table_data_cancer.csv)

| c1.name                | c2.name    | c.correlation | c1.KEGG | c2.KEGG |
| ---------------------- | ---------- | ------------- | ------- | ------- |
| gamma-glutamylcysteine | putrescine | 0.579247      | C00669  | C00134  |
| l-tyrosine             | putrescine | 0.50044       | C00082  | C00134  |
| ... |||