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
> Trabalhos relacionados
>

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

> Indicação (bastante resumida) da análise proposta
>
> Indicação (bastante resumida) dos resultados alcançados

# Slides

> Coloque aqui o link para o PDF da apresentação da parte 3.

# Fundamentação Teórica

> Fundamentação teórica do problema em saúde/biologia. Cite artigos tomados como base e em que problema.

A proposta desse projeto é utilizar a teoria dos grafos e algoritmos de análise de rede para construir redes metabólicas e identificar os principais metabólitos e vias metabólicas associadas à progressão do câncer de próstata. Essa proposta tem como base o TCC do integrante Francisco Augusto Gomes Santos: Câncer de Próstata e Diagnóstico.

A metodologia aplicada foi baseada na seguinte publicação: Metabolomics and correlation network analyses of core biomarkers in type 2 diabetes (https://pubmed.ncbi.nlm.nih.gov/32930872/), a qual faz a análise de metabólitos relacionados à diabetes tipo 2.

# Perguntas de Pesquisa
> Perguntas de pesquisa (revisadas e atualizadas) que o projeto responde ou hipóteses que foram avaliadas, enunciadas de maneira objetiva e verificável.
> Apresente aqui como o projeto ajudou a responder as perguntas de pesquisa.

 Objetivo: 

- Identificar os principais metabólitos e vias metabólicas associadas ao câncer de próstata.

Perguntas:

- Quais são os metabólitos candidatos a biomarcadores do câncer de próstata?
- Quais as funções desses metabólitos, e como estão relacionados com o desenvolvimento do câncer de próstata?

# Metodologia
> Proposta de metodologia incluindo especificação de quais as técnicas/métricas de Ciência de Redes que estão sendo usadas no projeto,
> tais como: detecção de comunidades, análise de centralidade, predição de links, ou a combinação de uma ou mais técnicas. Descreva o que perguntas pretende endereçar com a técnica escolhida.

1.  Obtenção de dados experimentais controle vs. câncer
2.  Análise estatística dos metabólitos: utilização de volcano plot para separar os metabólitos sobre e sub representados
3.  Enriquecimento das vias metabólicas: análise de sobrerrepresentação em cada um dos subgrupos de metabólitos
4.  Construção de redes de correlação entre metabólitos
5.  Análise comparativa da topologia das redes: utilização de métodos como medidas de centralidade (betweenness, degree, eigenvector, closeness), clusterização utilizando o algoritmo GLay
6.  Construção de redes de interação entre metabólitos e as vias enriquecidas
7.  Análise comparativa da topologia das redes: utilização de medida de centraliodade (betweenness) e clusterização utilizando o algoritmo GLay
   
## Bases de Dados e Evolução

> Para cada base, coloque uma entrada na tabela no modelo a seguir e depois detalhamento sobre como ela foi analisada/usada, conforme exemplo a seguir.

> Base de Dados | Endereço na Web | Resumo descritivo
> ----- | ----- | -----
> Metabolights MTBLS6039 | https://www.ebi.ac.uk/metabolights/editor/MTBLS6039/files | Base de dados de um estudo contendo dados de 20 homens saudáveis e 60 pacientes com prostatite, HBP ou CaP que foram identificados usando cromatografia líquida não direcionada-espectrometria de massa (LC-MS). 
> KEGG PATHWAY Database | [http://base2.org/](https://www.kegg.jp/kegg/pathway.html) | KEGG é uma coleção de bancos de dados que tratam de genomas, vias biológicas, doenças, medicamentos e substâncias químicas.

> Faça uma descrição sobre o que concluiu sobre esta base. Sugere-se que respondam perguntas ou forneçam informações indicadas a seguir:
> * O que descobriu sobre essa base?
> * Quais as transformações e tratamentos (e.g., dados faltantes e limpeza) feitos?

Os dados utilizados no projeto foram obtidos do estudo *MTBLS6039: Serum organic acid metabolites can be used as potential biomarkers to identify prostatitis, benign prostatic hyperplasia, and prostate cancer (Untargeted assay)*, o qual apresenta dados de 80 participantes no total: 20 homens saudáveis e 60 pacientes com prostatite, HBP ou CaP. Para o projeto foram utilizados os dados dos participantes saudáveis e dos diagnosticados com o câncer de próstata. Esses dados foram obtidos através da técnica da cromatografia líquida acoplada à espectrometria de massas, e a partir do espectro de massas resultante do método, 411 metabólitos diferentes foram identificados.

Os dados foram filtrados e normalizados dentro da própria ferramenta MetaboAnalyst. Aplicou-se um filtro para remoção de dados (nesse caso, metabólitos) cuja variância nas amostras mostrou-se inferior a 10% do intervalo interquartil. Em sequência, as intensidades desses picos foram normalizadas: os dados foram centralizados na mediana, e a amplitude foi redimensionada para o intervalo [0, 1] usando-se os valores máximo e mínimo.

Para a seleção de metabólitos presentes somente nas vias metabólicas significativamente alteradas, utilizou-se o banco de dados do KEGG. Os constituintes de cada uma dessas vias foram usado para filtragem dos metabólitos diferenciais encontrados na análise estatística dos dados.

## Modelo Lógico

Modelo lógico das redes de correlação:

![Modelo Lógico de Grafos](assets/images/modelo-logico-grafos.png)

Modelo lógico das redes de interação entre metabólitos e as vias enriquecidas:

![Modelo Lógico de Grafos Rede com Vias](assets/images/new/model_pathway_net.png)

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

### 1.  Obtenção de dados experimentais controle vs. câncer

Os dados utilizados no projeto foram obtidos do estudo *MTBLS6039: Serumorganicacidmetabolitescanusedas potentialbiomarkerstoidentifyprostatitis, benignprostatichyperplasia, andprostatecancer(Untargetedassay)*. A base de dados apresenta dados de 80 participantes, porém utilizamos dados de apenas 40 participantes, 20 do grupo controle (saudável) e 20 diagnosticados com câncer de próstata. Esses dados foram obtidos através da técnica da cromatografia líquida acoplada à espectrometria de massas, e a partir do espectro de massas resultante do método, 411 metabólitos diferentes foram identificados. Esses dados representam as intensidades dos picos correspondentes a cada um dos metabólitos identificados.

### 2.  Análise estatística dos metabólitos
### 3.  Enriquecimento das vias metabólicas
### 4.  Construção de redes de correlação entre metabólitos
### 5.  Análise comparativa da topologia das redes
### 6.  Construção de redes de interação entre metabólitos e as vias enriquecidas
### 7.  Análise comparativa da topologia das redes

## Evolução do Projeto

> Relatório de evolução, descrevendo as evoluções na modelagem do projeto, dificuldades enfrentadas, mudanças de rumo, melhorias e lições aprendidas. Referências aos diagramas, modelos e recortes de mudanças são bem-vindos.
> Podem ser apresentados destaques na evolução do modelo lógico. O modelo inicial e intermediários (quando relevantes) e explicação de refinamentos, mudanças ou evolução do projeto que fundamentaram as decisões.
> Relatar o processo para se alcançar os resultados é tão importante quanto os resultados.

# Ferramentas

> Panorama das ferramentas utilizadas incluindo discussão sobre o uso das mesmas.

- Python: processamento dos dados
- MetaboAnalyst (https://www.metaboanalyst.ca/): Análises estatísticas do dados, volcano plot, enriquecimento de vias
- Cytoscape
- Neo4j

# Discussão

> Discussão dos resultados. Relacionar os resultados com as perguntas de pesquisa ou hipóteses avaliadas.
>
> A discussão dos resultados também pode ser feita opcionalmente na seção de Resultados, na medida em que os resultados são apresentados. Aspectos importantes a serem discutidos: Por que seu modelo alcançou (ou não) um bom resultado? É possível tirar conclusões dos resultados? Quais? Há indicações de direções para estudo? São necessários trabalhos mais profundos?

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

