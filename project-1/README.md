# Projeto Metabolômica no diagnóstico do Câncer de Próstata

# Descrição Resumida do Projeto

### Câncer de Próstata 

Câncer é um termo que abrange mais de 200 diferentes doenças malignas, trazendo como característica geral o crescimento desordenado das células. O câncer apresenta uma origem multifatorial, através de mutações genéticas espontâneas ou induzidas (Neppel, 2017). A proliferação celular pode ser de forma controlada, originando as hiperplasias, metaplasias e displasias e caso esse crescimento ocorra de forma basicamente autônoma, ou seja, não controlada, temos as neoplasias, que são os cânceres *in situ* e os cânceres invasivos (INCA, 2020).

As neoplasias, que podem ser benignas ou malignas, se apresentam como uma fuga parcial ou total do controle do organismo, tendendo à autonomia e à perpetuação. Os tumores benignos se apresentam com limites bem nítidos e um crescimento de forma expansiva, organizada e lenta. Já os malignos, possuem maior grau de autonomia e resistência, possuindo a capacidade de invadir tecidos vizinhos, provocar metástases e a morte do hospedeiro (INCA, 2020).

Carcinogênese, ou oncogênese, é o nome dado ao processo de formação do câncer dentro do organismo se constituindo em um processo lento até a origem de um tumor visível. A carcinogênese é dividida em três estágios: iniciação, promoção e progressão. No estágio de iniciação, as células encontram-se iniciadas no processo carcinogênico e geneticamente alteradas pelas ações dos primeiros agentes cancerígenos. O estágio seguinte, de promoção, essas células geneticamente alteradas sofrem a ação dos oncopromotores, sendo transformadas de forma gradual e lenta, em células malignas. No último estágio da carcinogênese, o câncer já está instalado, sendo caracterizado pela irreversível e descontrolada multiplicação das células alteradas, e, pela evolução do estágio até o surgimento dos primeiros sintomas clínicos da doença (INCA, 2020).

O Instituto Nacional do Câncer estimou para o triênio de 2020 a 2022 um número de 450 mil novos casos de câncer, sendo o de próstata o mais frequente nos homens e o de mama nas mulheres.

O câncer de próstata é o segundo tipo de câncer mais comum no mundo, apresentando-se como a segunda principal causa de morte entre os homens. Esse tipo de câncer apresenta a evolução lenta, dificultando o aparecimento de sintomas e a busca por exames diagnósticos.

A área oncológico-geniturinária tem enfrentado desafios acerca de diagnóstico não invasivo, menos perigoso e mais eficaz, e a integração entre as áreas da bioinformática, biotecnologia e bioquímica analítica, junto com os avanços da ciência, da pesquisa clínica e epidemiológica, mostra-se como uma solução para os problemas do diagnóstico. Um método que vem ganhando cada vez mais espaço nesse segmento oncológico, é a utilização da análise metabolômica, ou seja, a análise dos metabólitos intracelulares, a fim de reconhecer biomarcadores indicativos do câncer.

### Metabolômica

Os metabólitos são  qualquer substância química que desempenhe funções em uma determinada célula, seja através da sua ingestão ou síntese. Esses, representam a parte final do fluxo de informações dentro do organismo humano, demonstrando-se como a resposta final que o organismo irá apresentar à agentes externos.

Esses metabólitos são cruciais em grande parte das funções e reações intracelulares, sendo importantes para refletir o estado fisiológico de uma amostra coletada. Em razão de fatores de sensibilidade, são necessárias amostras multicelulares em métodos que utilizam ressonância magnética nuclear (RMN), apesar de que a heterogeneidade das células passe despercebida. Dessa forma, alguns estudos apresentaram que a metabolômica consegue fornecer informações com relação a heterogeneidade do tumor (Trock BJ, 2011).

O desequilíbrio do metabolismo está direto e fortemente relacionado com o desenvolvimento e progressão do câncer de próstata, de modo que o perfil usado na análise dos metabólitos seja muito atraído pelos marcadores deste tipo de câncer (Gomez-Cebrián, 2019). Um indivíduo com síndrome metabólica, apresenta uma próstata com concentrações altas dos marcadores de inflamação, o que pode favorecer o desenvolvimento do tumor. Já uma próstata saudável apresenta um metabolismo único na produção de PSA, espermina e citrato. Consequentemente, com um metaboloma específico gerado pelas alterações metabolômicas e exclusivas das células do câncer de próstata, os marcadores específicos acabam sendo um fácil alvo para os perfis metabolômicos e para sua captura (Kdadra M, 2019).

Os metabólitos exercem funções em todo o nicho "ômico", seja como mecanismo de modificação química metabólica das macromoléculas ou como mecanismo de interação entre o próprio metabólito e uma macromolécula determinada. Na atividade biológica dos metabólitos, há descobertas de que seu acúmulo module células cancerígenas através da interação existente entre proteína e proteína. Além de serem usados como marcadores tumorais, inibidores enzimáticos e modificadores de DNA, podem agir na proliferação de células cancerígenas por meio de alterações na atividade enzimática e na pós-tradução proteica.


# Fundamentação Teórica

A proposta desse projeto é utilizar a teoria dos grafos e algoritmos de análise de rede para construir redes metabólicas e identificar os principais metabólitos e vias metabólicas associadas à progressão do câncer de próstata. Essa proposta tem como base o TCC do integrante Francisco Augusto Gomes Santos: Câncer de Próstata e Diagnóstico.

# Perguntas de Pesquisa

- Quais são as relações entre os metabólitos no câncer de próstata?
- Quais são os metabólitos candidatos a biomarcadores do câncer de próstata?
  
# Bases de Dados


 Base de Dados | Endereço na Web | Resumo descritivo
 ----- | ----- | -----
 The Human Metabolome Database (HMDB) | https://hmdb.ca/ | Banco de dados eletrônico com informações detalhadas sobre metabólitos de pequenas moléculas do corpo humano.
 Metabolomics Workbench | https://www.metabolomicsworkbench.org/ | Repositório internacional para dados e metadados metabolômicos e que fornece ferramentas de análise e acesso a padrões de metabólitos, protocolos, tutoriais, etc.

# Modelo Lógico

![Modelo Lógico de Grafos](images/modelo_logico.png)

# Metodologia

1. Busca em bases de dados por metabólitos coletados em indivíduos saudáveis e naqueles diagnosticados com câncer de próstata.

    a. Processamento para identificação daqueles com alterações significativas entre esses grupos.

2. Estruturação de uma rede de interações entre esses metabólitos para indivíduos saudáveis e com câncer.

3. Análise da topologia da rede e determinar a centralidade dos nós e a presença de hubs e comunidades.

4. Comparação das redes e identificação de metabólitos candidatos a biomarcadores.

5. Interpretação desses biomarcadores no contexto do desenvolvimento do câncer de próstata.

# Ferramentas

Neo4j

Cytoscape

Python

# Referências Bibliográficas


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

