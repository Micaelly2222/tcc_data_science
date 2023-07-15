# TCC - Ciência de Dados

Este repositório contém o código e os dados utilizados no meu TCC (Trabalho de Conclusão de Curso) sobre Ciência de Dados realizado no MBA em Data Science da Universidade de São Paulo (USP). O projeto tem como foco analisar e prever o cumprimento da Lei de Responsabilidade Fiscal (LRF) pelos municípios de Mato Grosso, Brasil.

# Projeto de Previsão de Cumprimento da LRF em Municípios de Mato Grosso

Este projeto tem como objetivo identificar as características que influenciam o cumprimento dos limites estabelecidos pela Lei de Responsabilidade Fiscal (LRF) por parte dos municípios do estado de Mato Grosso, além de desenvolver um modelo preditivo capaz de prever o cumprimento da LRF com base em análise de dados.

## Dados

Os dados utilizados neste projeto abrangem o período de 2017 a 2022 e foram obtidos do Instituto Brasileiro de Geografia e Estatística (IBGE) e do Tribunal de Contas do Estado de Mato Grosso (TCE-MT). Eles incluem informações financeiras, socioeconômicas e educacionais dos municípios de Mato Grosso.

## Metodologia

O projeto utiliza técnicas de aprendizado de máquina para realizar a análise e previsão do cumprimento da LRF. A metodologia adotada envolve as seguintes etapas:

1. Coleta e pré-processamento dos dados: Os dados são coletados a partir das fontes mencionadas e passam por um processo de pré-processamento, incluindo tratamento de valores ausentes e codificação de variáveis categóricas.

2. Análise exploratória dos dados: É realizada uma análise exploratória dos dados para identificar padrões, correlações e insights importantes sobre as características que podem influenciar o cumprimento da LRF.

3. Desenvolvimento do modelo preditivo: É construído um modelo de aprendizado de máquina para prever o cumprimento da LRF com base nos dados disponíveis. Diferentes técnicas de modelagem podem ser exploradas, como regressão logística, random forest, entre outras.

4. Avaliação do modelo: O modelo desenvolvido é avaliado quanto à sua acurácia e outras métricas relevantes para medir sua performance na previsão do cumprimento da LRF.

5. Aplicação do modelo: O modelo final treinado pode ser aplicado para realizar previsões de cumprimento da LRF em municípios de Mato Grosso com base em dados recentes.

## Resultados Esperados

Espera-se que este projeto possa fornecer insights importantes sobre os fatores que influenciam o cumprimento da LRF por parte dos municípios de Mato Grosso. Além disso, espera-se obter um modelo preditivo com boa performance na previsão do cumprimento da LRF, o que pode auxiliar gestores públicos e tomadores de decisão na identificação e adoção de medidas para melhorar a gestão fiscal e o cumprimento da legislação.


## Utilização

Para executar o código e reproduzir os resultados, siga estas etapas:

1. Clone o repositório:

git clone https://github.com/Micaelly2222/tcc_data_science.git


2. Instale as dependências necessárias. É recomendado criar um ambiente virtual:

pip install -r requirements.txt


3. Abra e execute os Jupyter Notebooks na seguinte ordem:

- `web_scrapping.ipynb`
- `df_merged.ipynb`
- `tratamento_dados.ipynb`
- `novo_tratamento_dados.ipynb`
- `aplicacao_modelo.ipynb`
