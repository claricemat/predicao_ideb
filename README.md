# Predição do IDEB com Técnicas de Machine Learning e Econometria

## Descrição

Este projeto tem como objetivo analisar e prever o Índice de Desenvolvimento da Educação Básica (IDEB) dos municípios brasileiros, utilizando técnicas econométricas e de aprendizado de máquina.

A análise investiga a relação entre o financiamento educacional — especialmente os recursos do FUNDEB por aluno — e o desempenho educacional, considerando também características estruturais dos municípios.

---

## Objetivos

- Avaliar o impacto do financiamento educacional no IDEB  
- Comparar diferentes modelos econométricos  
- Identificar possíveis vieses de especificação  
- Construir um modelo preditivo para o desempenho educacional  

---

## Dados Utilizados

Os dados foram obtidos de fontes públicas:

- INEP (IDEB, Censo Escolar, SAEB)  
- Tesouro Nacional (Transferências do FUNDEB)  
- IBGE (Dados municipais)  

Período analisado: 2017 a 2023  

---

## Metodologia

Foram aplicados diferentes modelos econométricos:

### Regressão Linear (OLS)
Modelo inicial para análise da relação entre variáveis.

### Modelo de Efeitos Fixos (Two-Way Fixed Effects)
Controle de heterogeneidade não observada entre municípios e ao longo do tempo.

### Modelo de Efeitos Aleatórios

### Modelo Between
Análise das diferenças estruturais entre municípios.

---

## Testes Estatísticos

- Teste de Hausman  
- Teste de Breusch-Pagan (heterocedasticidade)  
- Teste F para efeitos fixos  

---

## Principais Resultados

- O modelo OLS apresentou coeficiente negativo para o financiamento, indicando possível viés por omissão de variáveis  
- O modelo de efeitos fixos revelou uma relação positiva e estatisticamente significativa entre financiamento por aluno e desempenho no IDEB  
- Evidência de heterogeneidade não observada entre municípios  
- O modelo de efeitos fixos se mostrou mais robusto para a análise proposta  

---

## Tecnologias Utilizadas

- Python (pandas, NumPy, statsmodels, scikit-learn)  
- Jupyter Notebook  
- Git e GitHub  

---

## Estrutura do Projeto
