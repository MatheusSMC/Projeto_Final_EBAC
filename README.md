# Análise de Indicadores da Saúde

Projeto final desenvolvido durante a formação profissional em
Análise de Dados pela EBAC.

## Sobre o projeto

Este projeto teve como objetivo analisar indicadores públicos
relacionados à saúde, aplicando diferentes etapas de um processo
de análise de dados, desde a preparação das bases até a
visualização dos resultados em um dashboard interativo.

## Objetivos

- Explorar os dados relacionados aos indicadores de saúde;
- Identificar inconsistências e valores duplicados;
- Realizar o tratamento e preparação das bases;
- Cruzar diferentes fontes de dados;
- Identificar padrões, relações e possíveis anomalias;
- Desenvolver visualizações para apoiar a interpretação dos dados;
- Criar um dashboard interativo no Looker Studio.

## Tecnologias utilizadas

- Python
- Pandas
- Jupyter Notebook
- Looker Studio
- Análise Exploratória de Dados
- Visualização de Dados

## Fontes dos dados

Foram utilizadas bases públicas relacionadas a:

- Internações hospitalares (SIH);
- Leitos e capacidade hospitalar (CNES);
- Indicadores econômicos (IBGE).

## Etapas do projeto

### 1. Análise exploratória

Foi realizada uma análise inicial das bases para compreender
a estrutura dos dados, suas distribuições, relações e possíveis
inconsistências.

### 2. Tratamento dos dados

Durante a etapa de higienização foram identificados e removidos
2.284 registros duplicados.

Também foram realizados tratamentos relacionados a:

- valores inconsistentes;
- formatos de datas;
- datas inválidas;
- padronização das informações;
- alinhamento temporal das bases.

### 3. Análises

Foram realizadas análises envolvendo:

- distribuição dos dados;
- identificação de outliers;
- análise de dispersão;
- correlação entre variáveis;
- indicadores relacionados à capacidade e produção hospitalar.

### 4. Visualização

Os resultados foram apresentados por meio de gráficos e
visualizações desenvolvidos durante o projeto.

### 5. Dashboard

Foi desenvolvido um dashboard interativo no Looker Studio
para facilitar a interpretação dos principais indicadores
e resultados encontrados.

**[Acessar o Dashboard no Looker Studio](COLOCAR_LINK_AQUI)**

## Principais resultados

Durante a análise foram identificados diferentes padrões
e relações entre os indicadores estudados.

Entre os resultados analisados, destaca-se uma correlação
de 0,84 entre variáveis relacionadas à capacidade instalada.

As análises também permitiram observar a assimetria na
distribuição do tempo de permanência e a influência de
determinadas regiões nos resultados.

## Estrutura do projeto

```text
Projeto_Final_EBAC/
│
├── README.md
├── notebooks/
├── scripts/
├── data/
├── images/
└── docs/
