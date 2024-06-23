# Projeto Metabolômica no Câncer de Próstata

# Descrição Resumida do Projeto

> Descrição resumida do tema do projeto. Sugestão de roteiro (cada item tipicamente tratado em uma ou poucas frases):
>
> Contextualização do projeto
>
> Caracterização do problema
>
> Motivação
>
> Relevância
>

**Deixar mais claro como técnicas de rede vão contribuir**

### Câncer de Próstata 

Câncer é um termo que abrange mais de 200 diferentes doenças malignas, trazendo como característica geral o crescimento desordenado das células. O câncer apresenta uma origem multifatorial, através de mutações genéticas espontâneas ou induzidas (Neppel, 2017). A proliferação celular pode ser de forma controlada, originando as hiperplasias, metaplasias e displasias e caso esse crescimento ocorra de forma basicamente autônoma, ou seja, não controlada, temos as neoplasias, que são os cânceres *in situ* e os cânceres invasivos (INCA, 2020).

As neoplasias, que podem ser benignas ou malignas, se apresentam como uma fuga parcial ou total do controle do organismo, tendendo à autonomia e à perpetuação. Os tumores benignos se apresentam com limites bem nítidos e um crescimento de forma expansiva, organizada e lenta. Já os malignos, possuem maior grau de autonomia e resistência, possuindo a capacidade de invadir tecidos vizinhos, provocar metástases e a morte do hospedeiro (INCA, 2020).

O Instituto Nacional do Câncer estimou para o triênio de 2023 a 2025 um número de 483 mil novos casos de câncer, sendo o de próstata o mais frequente nos homens e o de mama nas mulheres. Além disso, o número estimado de casos de câncer de próstata, nesse mesmo período, é de 71730.

O câncer de próstata é o segundo tipo de câncer mais comum no mundo, apresentando-se como a segunda principal causa de morte entre os homens. Esse tipo de câncer apresenta a evolução lenta, dificultando o aparecimento de sintomas e a busca por exames diagnósticos.

### Metabolômica

Os metabólitos são  qualquer substância química que desempenhe funções em uma determinada célula, seja através da sua ingestão ou síntese. Esses, representam a parte final do fluxo de informações dentro do organismo humano, demonstrando-se como a resposta final que o organismo irá apresentar à agentes externos.

Esses metabólitos são cruciais em grande parte das funções e reações intracelulares, sendo importantes para refletir o estado fisiológico de uma amostra coletada. Em razão de fatores de sensibilidade, são necessárias amostras multicelulares em métodos que utilizam ressonância magnética nuclear (RMN), apesar de que a heterogeneidade das células passe despercebida. Dessa forma, alguns estudos apresentaram que a metabolômica consegue fornecer informações com relação a heterogeneidade do tumor (Trock BJ, 2011).

O desequilíbrio do metabolismo está direto e fortemente relacionado com o desenvolvimento e progressão do câncer de próstata, de modo que o perfil usado na análise dos metabólitos seja muito atraído pelos marcadores deste tipo de câncer (Gomez-Cebrián, 2019). Um indivíduo com síndrome metabólica, apresenta uma próstata com concentrações altas dos marcadores de inflamação, o que pode favorecer o desenvolvimento do tumor. Já uma próstata saudável apresenta um metabolismo único na produção de PSA, espermina e citrato. Consequentemente, com um metaboloma específico gerado pelas alterações metabolômicas e exclusivas das células do câncer de próstata, os marcadores específicos acabam sendo um fácil alvo para os perfis metabolômicos e para sua captura (Kdadra M, 2019).

Os metabólitos exercem funções em todo o nicho "ômico", seja como mecanismo de modificação química metabólica das macromoléculas ou como mecanismo de interação entre o próprio metabólito e uma macromolécula determinada. Na atividade biológica dos metabólitos, há descobertas de que seu acúmulo module células cancerígenas através da interação existente entre proteína e proteína. Além de serem usados como marcadores tumorais, inibidores enzimáticos e modificadores de DNA, podem agir na proliferação de células cancerígenas por meio de alterações na atividade enzimática e na pós-tradução proteica.

> Trabalhos relacionados
> 
> Indicação (bastante resumida) da análise proposta
>
> Indicação (bastante resumida) dos resultados alcançados

# Slides

> Coloque aqui o link para o PDF da apresentação da parte 3.

# Fundamentação Teórica

> Fundamentação teórica do problema em saúde/biologia. Cite artigos tomados como base e em que problema.

A proposta desse projeto é utilizar a teoria dos grafos e algoritmos de análise de redes para construir redes metabólicas e identificar os principais metabólitos e vias metabólicas associadas ao desenvolvimento do câncer de próstata. Essa proposta tem como base o TCC do integrante Francisco Augusto Gomes Santos: Câncer de Próstata e Diagnóstico.

A metodologia aplicada foi baseada na seguinte publicação: *Metabolomics and correlation network analyses of core biomarkers in type 2 diabetes* (https://pubmed.ncbi.nlm.nih.gov/32930872/), que fez a análise diferencial de redes de metabólitos relacionados à diabetes tipo 2.

# Perguntas de Pesquisa
> Perguntas de pesquisa (revisadas e atualizadas) que o projeto responde ou hipóteses que foram avaliadas, enunciadas de maneira objetiva e verificável.
> Apresente aqui como o projeto ajudou a responder as perguntas de pesquisa.

**Escolher como alvo coisas mais específicas relacionadas ao método**

 Objetivo: 

- Identificar os principais metabólitos e vias metabólicas associadas ao câncer de próstata.

Perguntas:

- Com base na análise topológica diferencial de redes de metabólitos na condição saudável e câncer de próstata, quais são os metabólitos candidatos a biomarcadores da doença?
- Quais as funções desses metabólitos, e como estão relacionados com o desenvolvimento do câncer de próstata?

# Metodologia
> Proposta de metodologia incluindo especificação de quais as técnicas/métricas de Ciência de Redes que estão sendo usadas no projeto,
> tais como: detecção de comunidades, análise de centralidade, predição de links, ou a combinação de uma ou mais técnicas. Descreva o que perguntas pretende endereçar com a técnica escolhida.

A metodologia adotada neste projeto foi inspirada no estudo realizado por XYZ, em que potenciais biomarcadores de diabetes tipo 2 foram identificados utilizando redes construídas a partir correlação entre metabólitos associados às vias enriquecidas e significativamente alteradas na doença. Para tanto, os seguintes passos foram considerados: 

1.  Obtenção de dados experimentais.
2.  Análise estatística dos metabólitos para identificação de diferenças entre o grupo saudável e o com câncer:
    - Utilização de *volcano plot* para separar os metabólitos com alterações significativas e expressivas em dois subgrupos:  sobre e sub-representados em indivíduos com câncer em relação aos saudáveis.
3.  Enriquecimento das vias metabólicas usando a Análise de Sobrerrepresentação em cada um dos subgrupos de metabólitos.
4.  Construção de quatro redes de correlação entre metabólitos associados às vias mais significativas:
    - Uma rede para cada condição (saudável ou câncer) em cada subgrupo de metabólitos (sobre ou sub-representado).
5.  Construção de duas redes de interação entre metabólitos e as vias metabólicas enriquecidas associadas a eles.
6.  Análise comparativa da topologia das redes:
    - Determinação dos principais metabólitos em cada rede com a análise de centralidade dos nós (*betweenness*, *degree*, *eigenvector*, *closeness*).
    - Detecção de comunidades de metabólitos, possivelmente pertencentes a uma mesma via metabólica ou com papel chave em mais de uma via, utilizando o algoritmo GLay.

Ao final do processo, os resultados das análises de cada rede foram interpretados do ponto de vista da biologia e dos mecanismos associados ao desenvolvimento do câncer de próstata.

## Bases de Dados e Evolução

> Para cada base, coloque uma entrada na tabela no modelo a seguir e depois detalhamento sobre como ela foi analisada/usada, conforme exemplo a seguir.

Base de Dados | Endereço na Web | Resumo descritivo
 ----- | ----- | -----
Metabolights MTBLS6039 | https://www.ebi.ac.uk/metabolights/editor/MTBLS6039/files | Base de dados de um estudo contendo dados de 20 homens saudáveis e 60 pacientes com prostatite, HBP ou CaP que foram identificados usando cromatografia líquida não direcionada-espectrometria de massa (LC-MS). 
KEGG PATHWAY Database | [http://base2.org/](https://www.kegg.jp/kegg/pathway.html) | KEGG é uma coleção de bancos de dados que tratam de genomas, vias biológicas, doenças, medicamentos e substâncias químicas.

> Faça uma descrição sobre o que concluiu sobre esta base. Sugere-se que respondam perguntas ou forneçam informações indicadas a seguir:
> * O que descobriu sobre essa base?
> * Quais as transformações e tratamentos (e.g., dados faltantes e limpeza) feitos?

Os dados utilizados no projeto foram obtidos do estudo *MTBLS6039: Serum organic acid metabolites can be used as potential biomarkers to identify prostatitis, benign prostatic hyperplasia, and prostate cancer (Untargeted assay)*, o qual apresenta dados de 80 participantes no total: 20 homens saudáveis e 60 pacientes com prostatite, HBP ou CaP. Para o projeto foram utilizados os dados dos participantes saudáveis e dos diagnosticados com o câncer de próstata. Esses dados foram obtidos através da técnica da cromatografia líquida acoplada à espectrometria de massas, e a partir do espectro de massas resultante do método, 411 metabólitos diferentes foram identificados.

Os dados foram filtrados e normalizados dentro da própria ferramenta *MetaboAnalyst*. Aplicou-se um filtro para remoção de dados (nesse caso, metabólitos) cuja variância nas amostras mostrou-se inferior a 10% do intervalo interquartil. Em sequência, as intensidades desses picos foram normalizadas: os dados foram centralizados na mediana, e a amplitude foi redimensionada para o intervalo [0, 1] usando-se os valores máximo e mínimo.

Para a seleção de metabólitos presentes somente nas vias metabólicas significativamente alteradas, utilizou-se o banco de dados do KEGG. Os constituintes de cada uma dessas vias foram usados para filtragem dos metabólitos diferenciais encontrados na análise estatística dos dados.

## Modelo Lógico

### Modelo lógico das redes de correlação:

<center>

| ![Modelo Lógico de Grafos](assets/images/modelo-logico-grafos.png) |
| :--: |
| Figura 1. Modelo lógico para a rede homogênea formada por metabólitos. As arestas indicam o valor da correlação entre os metabólitos. |

</center>

### Modelo lógico das redes de interação entre metabólitos e as vias enriquecidas:

<center>

| ![Modelo Lógico de Grafos Rede com Vias](assets/images/new/model_pathway_net.png) |
| :--: |
| Figura 2. Modelo lógico para a rede heterogênea formada por vias metabólicas ligadas aos metabólitos pertences a elas. |

</center>

## Análises Realizadas e Resultados

> Descrição dos resultados mais importantes obtidos.
>
> Apresente os resultados da forma mais rica possível, com gráficos e tabelas. Mesmo que o seu código rode online em um notebook, copie para esta parte a figura estática. A referência a código e links para execução online pode ser feita aqui ou na seção de Análises Realizadas (o que for mais pertinente).
> Apresente aqui uma análise dos dados.
> 
> Utilize gráficos que descrevam os aspectos principais da base que são relevantes para as perguntas de pesquisa consideradas.
>
> Nesta seção podem aparecer destaques de código como indicado a seguir. Note que foi usada uma técnica de highlight de código, que envolve colocar o nome da linguagem na abertura de um trecho com `~~~`, tal como `~~~python`.
>
> Os destaques de código devem ser trechos pequenos de poucas linhas, que estejam diretamente ligados a alguma explicação. Não utilize trechos extensos de código. Se algum código funcionar online (tal como um Jupyter Notebook), aqui pode haver links. No caso do Jupyter, preferencialmente para o Binder abrindo diretamente o notebook em questão.

~~~python
df = pd.read_excel("/content/drive/My Drive/Colab Notebooks/dataset.xlsx");
sns.set(color_codes=True);
sns.distplot(df.Hemoglobin);
plt.show();
~~~

### 1. Obtenção de dados experimentais controle vs. câncer

Os dados utilizados no projeto foram obtidos do estudo *MTBLS6039: Serum organic acid metabolites can be used as potential biomarkers to identify prostatitis, benign prostatic hyperplasia, and prostate cancer (Untargeted assay)*. A base de dados apresenta dados de 80 participantes, porém foram utlizados os dados de apenas 40 participantes, 20 do grupo controle (saudável) e 20 diagnosticados com câncer de próstata. Esses dados foram coletados no soro sanguíneo dos participantes e processados através da técnica da cromatografia líquida acoplada à espectrometria de massas, e a partir do espectro de massas resultante do método, 411 metabólitos diferentes foram identificados. Esses dados representam as intensidades dos picos correspondentes a cada um dos metabólitos identificados.

### 2. Análise estatística dos metabólitos

Com a ferramenta *MetaboAnalyst*, realizou-se a análise estatística univariada dos dados, que foram inicialmente filtrados e normalizados. Foram removidos os metabólitos cuja variância foi inferior a 10% do intervalo interquartil e a normalização utilizada foi a de centralização dos dados na mediana.

Após a filtragem e normalização desses dados, o *volcano plot* (Fig. 3) foi construído para determinação dos metabólitos que tiveram alterações significativas e expressivas entre os indivíduos de diferentes condições. Os metabólitos cujo valor do *log2(FC)* foi superior a 2 ou inferior a -2 e que tiveram p-valor inferior a 0.05 foram classificados como diferenciais.

<center>

| ![Volcano plot](assets/images/volcano_1_dpi72.png) |
| :--: |
| Figura 3. *Volcano plot* dos metabólitos entre as condições saudável e câncer de próstata. Para determinação daqueles mais significativos, foram adotados os critérios *log2(FC)* > 2 ou *log2(FC)* < 2 e p-valor < 0.05. |

</center>

Em sequência, os metabólitos foram divididos em dois subgrupos considerando o sinal do valor do *log2(FC)*: sobre, e sub-representados no grupo câncer em relação ao saudável, para valores positivos e negativos de *fold change*, respectivamente. Com isso, totalizam-se 133 metabólitos diferenciais, onde 56 estão sub-representados e 77, sobrerrepresentados.

### 3. Enriquecimento das vias metabólicas

As vias metabólicas associadas a partir dos dois subgrupos de metabólitos diferenciais foram determinadas com a Análise de Sobrerrepresentação de metabólitos, também na ferramenta *MetaboAnalyst*.

Cada subgrupo resultou em uma lista de vias enriquecidas: para os metabólitos sobrerrepresentados, as vias são mais ativas em indivídous com câncer do que em pessoas saudáveis, e para os sub-representados, vias que apresentam menor atividade em indivíduos com câncer. As Figuras 4 e 5 indicam os resultados do enriquecimento das vias para os metabólitos sub e sobrerrepresentados, respectivamente.

<center>

| ![Vias sub-representadas](assets/images/ora_0_dpi72_down.png) |
| :--: |
| Figura 4. Vias metabólicas sub-representadas no câncer de próstata. |

| ![Vias sobrerrepresentadas](assets/images/ora_0_dpi72_up.png)|
| :--: |
| Figura 5. Vias metabólicas sobrerrepresentadas no câncer de próstata. |

</center>

As vias com maior significância, considerando p-valores inferiores a 0.05, foram selecionadas para análise em cada um dos subgrupos, sendo elas:

Vias metabólicas sub-representadas:

1. *Arginine biosynthesis*
2. *Pantothenate and CoA biosynthesis*
3. *Purine metabolism*
4. *Valine, leucine and isoleucine biosynthesis*
5. *Glycine, serine and threonine metabolism*
6. *D-Amino acid metabolism*

Vias metabólicas sobrerrepresentadas:

1. *Arginine biosynthesis*
2. *Phenylalanine metabolism*
3. *Glutathione metabolism*
4. *Phenylalanine, tyrosine and tryptophan biosynthesis*
5. *Arginine and proline metabolism*
6. *Galactose metabolism*

### 4. Redes de correlação entre metabólitos

As interações entre os metabólitos presentes em vias sub e sobrerrepresentadas no câncer de próstata foram avaliadas através de correlações entre eles, buscando identificar padrões que diferenciem os mecanismos subjacentes ao desenvolvimento da doença. Isso pode ocorrer tanto pela menor atividade (nas vias sub-representadas) quanto pela maior atividade (nas vias sobrerrepresentadas). Para determinar os metabólitos mais cruciais na integração e regulação das vias metabólicas associadas ao câncer, utilizou-se uma medida de centralidade composta, que inclui *betweenness*, *closeness* e *eigenvector*.

#### 4.1. Construção das redes

Como 6 vias metabólicas sobre, e 6 sub-representadas, foram selecionadas para análise, somente os metabólitos diferenciais associados a elas foram considerados nas redes de correlação. Para isso, o identificador *Compound ID*, presente tanto no KEGG, quanto no resultado do enriquecimento de vias, foi utilizado para filtragem dos dados. A base de dados final, que indica metabólitos significativamente alterados relacionados às vias enriquecidas, conta com 25 metabólitos associados às vias sub-representadas e 23 às vias sobrerrepresentadas.

Após essa filtragem, foi determinada a correlação de Pearson entre os metabólitos nos seguintes grupos:

- Presentes nas vias sub-representadas:
    - Em indivíduos saudáveis
    - Em indivíduos diagnosticados com câncer de próstata

- Presentes nas vias sobrerrepresentadas:
    - Em indivíduos saudáveis
    - Em indivíduos diagnosticados com câncer de próstata

As Figuras 6 e 7 representam, de forma visual, essas correlações:

<center>

| ![Correlacao Vias sub-representadas](assets/images/corr_heatmap_down.png) |
| :--: |
| Figura 6. Correlação de Pearson entre os metabólitos das vias sub-representadas. |

| ![Correlacao Vias sobrerrepresentadas](assets/images/corr_heatmap_up.png) |
| :--: |
| Figura 7. Correlação de Pearson entre os metabólitos das vias sobrerrepresentadas. |

</center>

Com isso, quatro redes de correlação entre metabólitos são construídas, nas quais os metabólitos são os nós, e a correlação entre eles, a aresta que os ligam, seguindo o modelo lógico indicado na Fig. 1. Para essa construção, cada uma das quatro matrizes de correlação tornou-se uma rede, e foram consideradas somente as arestas cujo valor de correlação foi superior a 0.6 ou inferior a -0.6. Este mesmo valor foi utilizado no artigo de referência. Outros valores foram testados, mas a densidade da rede resultante tornou inviável análises posteriores.

#### 4.2. Redes de correlação entre metabólitos em duas condições, para metabólitos sub e sobrerrepresentados.

As Figuras 8 e 9 ilustram as redes resultantes. Para cada par, os mesmos metabólitos estão presentes para facilitar a comparação visual das redes. As arestas em vermelho indicam correlações positivas e, as azuis, negativas. Nós em cinza indicam metabólitos que não fazem parte da rede, mas que foram incluídos para uma rápida diferenciação das duas condições. A escala de cores dos nós indica a centralidade de *betweenness* daquele metabólito.

<center>

| ![Rede sub-representado cancer](assets/images/new/down_cancer.png) | ![Rede sub-representado saudavel](assets/images/new/down_healthy.png) |
| :--: | :--: |
| (a) Câncer de próstata | (b) Saudável |

Figura 8. Redes formadas por metabólitos sub-representados no câncer de próstata nas condições (a) câncer e (b) saudável. A escala de cores indica o valor da centralidade de *betweenness* do nó. Nós em cinza não fazem parte da rede, mas estão representados na figura para melhor comparação entre as duas condições.

| ![Rede sobrerrepresentado cancer](assets/images/new/up_cancer.png) | ![Rede sobrerrepresentado saudavel](assets/images/new/up_healthy.png) |
| :--: | :--: |
| (a) Câncer de próstata | (b) Saudável |

Figura 9. Redes formadas por metabólitos sobrerrepresentados no câncer de próstata nas condições (a) câncer e (b) saudável.

</center>

### 5. Redes de interação entre metabólitos e as vias enriquecidas

Para entender como diferentes vias metabólicas se relacionam no câncer e como um metabólito pode afetar mais de uma via, duas redes em que vias metabólicas são associadas a seus metabólitos foram construídas, a primeira para as vias sub-representadas e a segunda, para as sobrerrepresentadas.

#### 5.1. Construção das redes

Os metabólitos pertencentes a cada uma das vias foram obtidos do KEGG, da mesma maneira como descrito na seção [4.1](#41-construção-das-redes).

Para a construção da rede, as seguintes bibliotecas de Python foram utilizadas:
- *gseapy*: foi utilizada para construção das relações entre vias e metabólitos de cada rede.
- *networkx*: utilizada para salvar cada rede como um arquivo gml.

#### 5.2. Redes de interação entre metabólitos e vias enriquecidas nos subgrupos sub e sobrerrepresentados.

As redes resultantes estão ilustradas nas Figuras 10 e 11. Nas figuras, as vias metabólicas são os nós maiores em cinza. A escala de cores dos metabólitos indica a centralidade de *betweenness*.

<center>

| ![Rede com vias sub-representadas](assets/images/pathway_metabolites_down.png) |
| :--: |
| Figura 10. Rede de interação entre os metabólitos das vias sub-representadas. |

| ![Rede com vias sobrerrepresentadas](assets/images/pathway_metabolites_up.png) |
| :--: |
| Figura 11. Rede de interação entre os metabólitos das vias sobrerrepresentadas. |

</center>

### 6. Análise comparativa da topologia das redes

#### 6.1. Análise topológica das redes de correlação

Para a análise diferencial das redes de correlação, inicialmente foram calculadas as seguintes medidas de centralidade para cada nó: *betweenness*, *closeness* e *eigenvector*. Os resultados foram condensados em um gráfico em que cada eixo indica uma das medidas, de modo que os metabólitos mais distantes da origem, de modo geral, são aqueles com as maiores medidas. As Figuras 12 e 13 apresentam esses resultados.

<center>

| ![Gráfico sub-representado cancer](assets/images/3d_scatter_cancer_down.png) | ![Gráfico sub-representado saudavel](assets/images/3d_scatter_healthy_down.png) |
| :--: | :--: |
| (a) Câncer de próstata | (b) Saudável |

Figura 12. Centralidades de *betweenness*, *closeness* e *eigenvector* para os metabólitos sub-representados nas condições (a) câncer de próstata e (b) saudável. Observam-se como principais metabólitos *l-arginine* e *n-acetyl-l-glutamate 5-semialdehyde* no câncer, e *l-arginine*, *2-oxoarginine* e *diaminopimelic acid* nos indivíduos saudáveis.


| ![Gráfico sobrerrepresentado cancer](assets/images/3d_scatter_cancer_up.png) | ![Gráfico sobrerrepresentado saudavel](assets/images/3d_scatter_healthy_up.png) |
| :--: | :--: |
| (a) Câncer de próstata | (b) Saudável |

Figura 13. Centralidades de *betweenness*, *closeness* e *eigenvector* para os metabólitos sobrerrepresentados nas condições (a) câncer de próstata e (b) saudável. Observam-se como principais metabólitos *4-acetamidobutanoate*, *pyroglutamic acid*, *quinate*, *gamma-glutamylcysteine* e *citrulline* no câncer, e *putrescine*, *d-galactose* e *d-mannose* nos indivíduos saudáveis.

</center>

Com base nesses resultados, os principais metabólitos em cada condição e em cada subgrupo são:

1. *l-arginine* e *n-acetyl-l-glutamate 5-semialdehyde*, sub-representados no câncer;
2. *l-arginine*, *2-oxoarginine* e *diaminopimelic acid*, sub-representados nos indivíduos saudáveis;
3. *4-acetamidobutanoate*, *pyroglutamic acid*, *quinate*, *gamma-glutamylcysteine* e *citrulline*, sobrerrepresentados no câncer;
4. *putrescine*, *d-galactose* e *d-mannose*, sobrerrepresentados nos indivíduos saudáveis.

As relações entre os nós são ilustradas em detalhes nas Figuras 14 e 15. Os nós em vermelho são aqueles significativos na rede e, consequentemente, os candidatos a biomarcadores do câncer de próstata.

<center>

| ![Rede sub-representado cancer](assets/images/new/signif_cancer_down.png) | ![Rede sub-representado saudavel](assets/images/new/signif_healthy_down.png) |
| :--: | :--: |
| (a) Câncer de próstata | (b) Saudável |

Figura 14. Metabólitos de vias sub-representadas no câncer de próstata, significativamente mais correlacionados no grupo (a) câncer e (b) controle.

| ![Rede sobrerrepresentado cancer](assets/images/new/signif_cancer_up.png) | ![Rede sobrerrepresentado saudavel](assets/images/new/signif_healthy_up.png) |
| :--: | :--: |
| (a) Câncer de próstata | (b) Saudável |

Figura 15. Metabólitos de vias sobrerrepresentadas no câncer de próstata, significativamente mais correlacionados no grupo (a) câncer e (b) controle.

</center>

#### 6.2. Análise diferencial das redes de correlação

Em sequência, realizou-se uma análise diferencial das redes, considerando cada um dos metabólitos significativos tanto na rede de indivíduos com câncer quanto na de indivíduos saudáveis. Essa análise avaliou as discrepâncias encontradas para cada metabólito entre as duas redes, incluindo diferenças nas conexões observadas entre os grupos com câncer e os saudáveis. As Figuras 16-20 apresentam essas diferenças em detalhes. Uma interpretação biológica dessas diferenças será apresentada na seção seguinte.

<center>

| ![Rede sub-representado cancer](assets/images/new/view1_cancer_down.png) | ![Rede sub-representado saudavel](assets/images/new/view1_healthy_down.png) |
| :--: | :--: |
| (a) Câncer de próstata | (b) Saudável |

Figura 16. Diferença na conectividade de *n-acetyl-l-glutamate 5-semialdehyde* entre as condições (a) câncer e (b) saudável no subgrupo de metabólitos sub-representados. O metabólito encontra-se correlacionado a outros três no câncer, mas não apresenta relações significativas em indivíduos saudáveis.

| ![Rede sub-representado cancer](assets/images/new/view2_cancer_down.png) | ![Rede sub-representado saudavel](assets/images/new/view2_healthy_down.png) |
| :--: | :--: |
| (a) Câncer de próstata | (b) Saudável |

Figura 17. Diferença na conectividade de *diaminopimelic acid* entre as condições (a) câncer e (b) saudável no subgrupo de metabólitos sub-representados. O *diaminopimelic acid* encontra-se em quantidades inferiores na doença e não apresenta relações significativas com outros metabólitos nessa condição, sugerindo que sua redução ou ausência pode estar relacionada com o câncer.

| ![Rede sub-representado cancer](assets/images/new/view3_cancer_up.png) | ![Rede sub-representado saudavel](assets/images/new/view3_healthy_up.png) |
| :--: | :--: |
| (a) Câncer de próstata | (b) Saudável |

Figura 18. Diferença na conectividade de *pyroglutamic acid* entre as condições (a) câncer e (b) saudável no subgrupo de metabólitos sobrerrepresentados. O metabólito não apresenta relações significativas com outros metabólitos em indivíduos saudáveis, mas em pacientes diagnosticados com câncer, ele está ligado a outros oito compostos.

| ![Rede sub-representado cancer](assets/images/new/view4_cancer_up.png) | ![Rede sub-representado saudavel](assets/images/new/view4_healthy_up.png) |
| :--: | :--: |
| (a) Câncer de próstata | (b) Saudável |

Figura 19. Diferença na conectividade de *4-acetamidobutanoate* entre as condições (a) câncer e (b) saudável no subgrupo de metabólitos sobrerrepresentados. O metabólito apresenta poucas relações significativas com outros metabólitos em indivíduos saudáveis, mas em pacientes diagnosticados com câncer, ele está ligado a outros oito metabólitos.

| ![Rede sub-representado cancer](assets/images/new/view5_cancer_up.png) | ![Rede sub-representado saudavel](assets/images/new/view5_healthy_up.png) |
| :--: | :--: |
| (a) Câncer de próstata | (b) Saudável |

Figura 20. Diferença na conectividade de *gamma-glutamylcysteine* entre as condições (a) câncer e (b) saudável no subgrupo de metabólitos sobrerrepresentados. O metabólito interage de forma significativa somente em indivíduos com a doença.

</center>

#### 6.3. Clusterização das redes de correlação

O algoritmo GLay do Cytoscape foi utilizado para detecção de comunidades de metabólitos correlacionados. Os resultados dessa análise são apresentados nas Figuras 21 e 22. Dada a baixa densidade de conexões nas redes de correlação, somente em uma rede foi observada a formação de comunidades de metabólitos (Fig. 22a).

<center>

| ![Rede sub-representado cancer](assets/images/new/cluster_cancer_down.png) | ![Rede sub-representado saudavel](assets/images/new/cluster_healthy_down.png) |
| :--: | :--: |
| (a) Câncer de próstata | (b) Saudável |

Figura 21. Não há formação de comunidades entre os metabólitos sub-representados no câncer de próstata. Cada módulo já estava presente na rede original em ambos os casos.

**Clusterização das redes das vias  sobrerrepresentadas:**

| ![Rede sobrerrepresentado cancer](assets/images/new/cluster_cancer_up.png) | ![Rede sobrerrepresentado saudavel](assets/images/new/cluster_healthy_up.png) |
| :--: | :--: |
| (a) Câncer de próstata | (b) Saudável |

Figura 22. Três comunidades são formadas nos metabólitos sobrerrepresentados no câncer de próstata entre os indivíduos da condição (a) câncer.

</center>

#### 6.4. Análise topológica das redes de interação entre metabólitos e as vias enriquecidas

Com base na centralidade de *betweenness*, e pressupondo que nós com essa métrica elevada são aqueles que integram e regulam diferentes vias, por estarem no menor caminho entre elas, os seguintes metabólitos foram considerados mais significativos em cada rede:

1. Vias metabólicas sub-representadas:
    - *ornithine*
    - *putrescine*
    - *l-tyrosine*
    - *l-phenylalanine*

2. Vias metabólicas sobrerrepresentadas:
    - *l-arginine*
    - *2-oxoarginine*
    - *diaminopimelic acid*

A clusterização de cada rede utilizando o algoritmo GLay produziu as comunidades apresentadas nas Figuras 23 e 24.

<center>

| ![Vias cluster sub-representadas](assets/images/pathway_metabolites_down_clustered.png) |
| :--: |
| Figura 23. Comunidades detectadas nas vias metabólicas sub-representadas. Cada via se agrupou com seus próprios metabólitos, com exceção das vias de *Glycine, serine and threonine metabolism* e *Pantothenate and CoA biosynthesis*, que formaram um cluster único por compartilharem os metabólitos *l-cysteine* e *l-aspartic acid*. |


| ![Vias cluster sobrerrepresentadas](assets/images/pathway_metabolites_up_clustered.png) |
| :--: |
| Figura 24. Comunidades detectadas nas vias metabólicas sobrerrepresentadas. Novamente, cada via formou seu próprio cluster, com exceção de *Phenylalanine metabolism* e *Phenylalanine, tyrosine and tryptophan biosynthesis*, que foram agrupadas no mesmo cluster por compartilharem os metabólitos *l-phenylalanine* e *l-tyrosine*. |

</center>

### 7. Interpretação biológica


## Evolução do Projeto

> Relatório de evolução, descrevendo as evoluções na modelagem do projeto, dificuldades enfrentadas, mudanças de rumo, melhorias e lições aprendidas. Referências aos diagramas, modelos e recortes de mudanças são bem-vindos.
> Podem ser apresentados destaques na evolução do modelo lógico. O modelo inicial e intermediários (quando relevantes) e explicação de refinamentos, mudanças ou evolução do projeto que fundamentaram as decisões.
> Relatar o processo para se alcançar os resultados é tão importante quanto os resultados.

### 1. Base de dados

Duas outras bases de dados foram utilizadas antes da definição do estudo utilizado neste projeto, ambas provenientes do repositório do *Metabolomics Workbench*:

1. Estudo **ST001042**: *Non-targeted serum metabolomic profiling of prostate cancer patients (FI-TWIM-MS PCa)*
    - O estudo apresentou dados de pacientes diagnosticados com câncer de próstata e indivíduos saudáveis, 103 participantes ao todo, mas os metabólitos não foram identificados, somente o espectro de massas com a relação massa/carga e a intensidade normalizada do pico foi disponibilizado.

2. Estudo **ST002498**:	*Plasma Metabolomics Profiling of 580 Patients from the Weill Cornell Medicine Early Detection Research Network Prostate Cancer Cohort*
    - O estudo contou com um número elevado de participantes em cada grupo e apresentou, além das concentrações dos metabólitos identificados, metadados relacionados à severidade da doença. No entanto, as análises estatísticas não revelaram diferenças interessantes entre os grupos. Os metabólitos que se apresentaram como diferenciais foram medicamentos utilizados pelos pacientes diagnosticados com a doença.

### 2. Modelo lógico

Um segundo modelo lógico foi acrescentado para análise das interações entre os metabólitos de diferentes vias metabólicas associadas ao câncer de próstata. 

### 3. Modelagem do problema

Os metabólitos diferenciais, identificados através da análise estatística no *MetaboAnalyst*, foram divididos em dois grupos: aqueles sub-representados e sobrerrepresentados no câncer de próstata em comparação aos indivíduos saudáveis. Isso permitiria uma análise mais detalhada quanto a direção das alterações metabólicas, tornando possível relacionar a doença a um aumento ou uma diminuição significativa desses metabólitos.

# Ferramentas

> Panorama das ferramentas utilizadas incluindo discussão sobre o uso das mesmas.

- Python: processamento dos dados
- MetaboAnalyst (https://www.metaboanalyst.ca/): Análises estatísticas do dados, volcano plot, enriquecimento de vias
- Cytoscape
- Neo4j

# Discussão

> Discussão dos resultados. Relacionar os resultados com as perguntas de pesquisa ou hipóteses avaliadas.
>
> A discussão dos resultados também pode ser feita opcionalmente na seção de Resultados, na medida em que os resultados são apresentados. Aspectos importantes a serem discutidos:
> Por que seu modelo alcançou (ou não) um bom resultado?
> É possível tirar conclusões dos resultados? Quais?
> Há indicações de direções para estudo?
> São necessários trabalhos mais profundos?

# Conclusão

> Destacar as principais conclusões obtidas no desenvolvimento do projeto.
>
> Destacar os principais desafios enfrentados.
>
> Principais lições aprendidas.

# Trabalhos Futuros

> O que poderia ser melhorado se houvesse mais tempo?
> Quais possíveis desdobramentos este projeto pode ter?

# Referências Bibliográficas

> Lista de artigos, links e referências bibliográficas.
>
> Fiquem à vontade para escolher o padrão de referenciamento preferido pelo grupo.

NEPPEL, Tayonara Georgiane et al. CÂNCER: UMA DOENÇA MULTIFATORIAL1. PROPOSTAS DIDÁTICAS NA ABORDAGEM CIÊNCIA-TECNOLOGIA-SOCIEDADE: UMA PRODUÇÃO DO, p. 161.

MINISTÉRIO DA SAÚDE. INSTITUTO NACIONAL DO CÂNCER - INCA., 2020.

TROCK BJ. Application of metabolomics to prostate cancer. Urol Oncol. 2011 SepOct;29(5):572-81. doi: 10.1016/j.urolonc.2011.08.002. PMID: 21930089; PMCID: PMC3180907.

KDADRA M, Höckner S, Leung H, Kremer W, Schiffer E. Metabolomics Biomarkers of Prostate Cancer: A Systematic Review. Diagnostics (Basel). 2019 Feb 19;9(1):21. doi: 10.3390/diagnostics9010021. PMID: 30791464; PMCID: PMC6468767. KELL, Douglas B.; OLIVER, Stephen G. The metabolome 18 years on: a concept comes of age. Metabolomics, v. 12, n. 9, p. 1-8, 2016.

Wang JJ, Lei KF, Han F. Tumor microenvironment: recent advances in various cancer treatments. Eur Rev Med Pharmacol Sci. 2018

BRAY, Freddie et al. Estatísticas globais de câncer 2018: estimativas GLOBOCAN de incidência e mortalidade em todo o mundo para 36 cânceres em 185 países. CA: uma revista de câncer para clínicos, v. 68, n. 6, pág. 394-424, 2018.

CANUTO, Gisele AB et al. Metabolômica: definições, estado-da-arte e aplicações representativas. Química Nova, v. 41, p. 75-91, 2018.

ALBUQUERQUE NETO, Moacir Cavalcante de. Eficácia da análise metabonômica do soro de pacientes com câncer de próstata. 2021.

OLIVER, Stephen G. et al. Systematic functional analysis of the yeast genome. Trends in biotechnology, v. 16, n. 9, p. 373-378, 1998.

RINSCHEN, Markus M. et al. Identificação de metabólitos bioativos usando metabolômica de atividade. Nature Reviews Molecular Cell Biology, v. 20, n. 6, pág. 353-367, 2019.

YANG, Bo et al. Novel metabolic signatures of prostate cancer revealed by 1H-NMR metabolomics of urine. Diagnostics, v. 11, n. 2, p. 149, 2021.

GISKEØDEGÅRD, Guro F. et al. Metabolic markers in blood can separate prostate cancer from benign prostatic hyperplasia. British journal of cancer, v.113, n. 12, p.1712-1719, 2015.

SHAO Y, Ye G, Ren S, et al. Metabolomics and transcriptomics profiles reveal thedysregulation of the tricarboxylic acid cycle and related mechanisms in prostate cancer. Int J Cancer. 2018.

REN, Shancheng et al. Integration of metabolomics and transcriptomics reveals major metabolic pathways and potential biomarker involved in prostate cancer. Molecular&amp; Cellular Proteomics, v. 15, n. 1, p. 154-163, 2016.

LIMA, Ana Rita et al. NMR-based metabolomics studies of human prostate câncer tissue. Metabolomics, v. 14, n. 7, p. 1-11, 2018.

