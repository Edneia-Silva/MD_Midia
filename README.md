# CONSUMO DE MÍDIA TRADICIONAL E DIGITAL NO BRASIL:

## Uma análise de mineração de dados e hábitos de informação

## 📌 Descrição do Projeto

Este projeto apresenta uma análise de mineração de dados aplicada ao consumo de mídia no Brasil, utilizando microdados da pesquisa TIC Domicílios 2025 e indicadores do Reuters Digital News Report 2025.

O objetivo principal foi identificar padrões de comportamento relacionados ao uso de mídias tradicionais e digitais, considerando fatores como conectividade, renda, escolaridade e acesso à internet.

Para isso, foram utilizadas técnicas de aprendizado não supervisionado, incluindo:

* K-Means
* Clustering Hierárquico (Ward)
* Regras de Associação com Apriori

O estudo permitiu identificar quatro perfis principais de consumo de mídia:

* Tradicional Puro
* Digital Urbano
* Digital Rural
* Digital Premium

---

# 🎯 Objetivos

## Objetivo Geral

Aplicar técnicas de mineração de dados para identificar e segmentar padrões de consumo de mídia da população brasileira.

## Objetivos Específicos

* Analisar infraestrutura tecnológica doméstica;
* Investigar hábitos de consumo de informação;
* Avaliar impactos da desigualdade digital;
* Identificar perfis de audiência por clustering;
* Descobrir padrões de associação entre conectividade e consumo de mídia.

# 🧠 Metodologia

A pesquisa foi desenvolvida com base na metodologia CRISP-DM, contemplando as seguintes etapas:

1. Compreensão do problema;
2. Compreensão dos dados;
3. Preparação dos dados;
4. Modelagem;
5. Avaliação;
6. Interpretação dos resultados.

# 📊 Técnicas Utilizadas

## K-Means

Utilizado para segmentação dos domicílios brasileiros em clusters de comportamento semelhante.

## Clustering Hierárquico (Ward)

Aplicado como método complementar de validação estrutural dos clusters.

## Algoritmo Apriori

Empregado para identificação de regras de associação entre variáveis sociodemográficas e hábitos de mídia.

# 🗂️ Base de Dados

## TIC Domicílios 2025

Microdados produzidos pelo CETIC.br / CGI.br contendo informações sobre:

* acesso à internet;
* dispositivos tecnológicos;
* conectividade;
* escolaridade;
* renda;
* hábitos digitais.

## Reuters Digital News Report 2025

Indicadores complementares sobre:

* consumo de notícias;
* confiança na informação;
* uso de plataformas digitais.

# ⚙️ Pré-processamento

As etapas de preparação dos dados incluíram:

* tratamento de valores ausentes;
* remoção de inconsistências;
* seleção de variáveis relevantes;
* transformação de variáveis categóricas com One-Hot Encoding.

A base final utilizada na modelagem contou com 25.233 registros válidos.

# 📈 Principais Resultados

Os resultados demonstraram:

* coexistência entre mídias tradicionais e digitais;
* forte crescimento do consumo digital audiovisual;
* relação entre renda, escolaridade e inclusão digital;
* presença de desigualdade estrutural no acesso à conectividade.
* Além disso, os algoritmos identificaram quatro perfis consistentes de audiência no Brasil.

# 🛠️ Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Mlxtend

# 📚 Referências Principais

* CARRO, Rodrigo. Brazil. Reuters Digital News Report 2025. 
* CASTELLS, Manuel. A Sociedade em Rede. 2009.
* CGI.br.TIC Domicílios 2025. Comitê Gestor da Internet no Brasil 2025.
* HAN, Jiawei; KAMBER, Micheline; PEI, Jian. Data Mining: Concepts and Techniques. 2011.
* JENKINS, Henry. Cultura da Convergência. 2009.
* LÉVY, Pierre. Cibercultura. 1999.
* SANTAELLA, Lucia. Culturas e Artes do Pós-Humano. 2003.


# 👩‍💻 Autoras

# Ednéia Silva e Sara Biotto
Projeto acadêmico desenvolvido para análise de consumo de mídia e transformação digital no Brasil utilizando técnicas de mineração de dados.


