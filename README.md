# Análise de Risco Cardiovascular com K-Means

Este projeto foi desenvolvido como parte do **Desafio Prático do Módulo 1** do bootcamp **Arquiteto(a) de Big Data**, e tem como foco a aplicação de técnicas de machine learning para identificação de riscos de saúde relacionados a doenças cardiovasculares.

---

## 🩺 Situação-Problema

Doenças cardiovasculares seguem como uma das principais causas de morte no mundo. A obesidade e os altos níveis de colesterol estão entre os principais fatores de risco. No entanto, nem sempre é viável realizar exames laboratoriais em larga escala, o que dificulta o diagnóstico precoce.

Diante disso, surge a seguinte pergunta:

> **É possível identificar pacientes com maior risco cardiovascular apenas com base em dados simples como peso e colesterol?**

Este projeto busca responder a essa pergunta utilizando **algoritmos de clusterização** para segmentar pacientes com perfis de risco semelhantes, permitindo intervenções antecipadas e personalizadas.

---

## 🧠 Objetivo do Projeto

Aplicar o algoritmo **K-Means** para agrupar pacientes em **três clusters distintos** com base nas variáveis de **peso** e **colesterol**, com o intuito de identificar padrões de risco cardiovascular:

- 🔵 **Baixo risco**  
- 🟠 **Risco moderado**  
- 🔴 **Alto risco**

---

## 📊 Base de Dados Utilizada

O projeto utilizou três bases integradas:

- `dados_clinicos.csv` — informações de peso e colesterol
- `dados_pacientes.csv` — dados demográficos
- `estado_regiao.csv` — informações regionais

Os dados foram integrados via `id_cliente`, e tratados conforme as instruções:

- Valores numéricos ausentes: preenchidos com a **média arredondada**
- Valores categóricos ausentes: preenchidos com a **moda**

---

## 🛠 Tecnologias e Bibliotecas
- Python 3.9+
- pandas 1.5.2
- seaborn 0.12.1
- matplotlib 3.6.2
- scikit-learn 1.2.0
- plotly 5.11.0

---

## ⚙️ Etapas do Projeto

1. Coleta e integração dos dados
2. Tratamento de dados ausentes e limpeza
3. Análise exploratória das variáveis de interesse
4. Aplicação do algoritmo **K-Means (k=3, random_state=42)**
5. Visualização dos clusters com gráfico de dispersão
6. Interpretação dos agrupamentos e padrões de risco

---

## ✅ Resultados Obtidos

- O modelo K-Means gerou **três agrupamentos bem definidos** com base em peso e colesterol.
- A visualização dos clusters indicou perfis distintos:
  - O grupo de **baixo risco** apresentou peso e colesterol dentro dos limites ideais.
  - O grupo de **risco moderado** teve valores intermediários.
  - O grupo de **alto risco** concentrou pacientes com **sobrepeso e colesterol elevado**.

Distribuição dos Pacientes por Cluster
- Grupo 0 (Alto Risco): 180 pacientes
- Grupo 1 (Baixo Risco): 206 pacientes
- Grupo 2 (Risco Moderado): 204 pacientes

🧹 Tratamento de Dados
- Dados ausentes numéricos: preenchidos com média arredondada
- Dados ausentes categóricos: preenchidos com moda

✅ Conclusão \
Essa análise contribui para a detecção precoce de riscos cardíacos, permitindo uma atuação mais rápida e eficaz por parte da equipe médica. Demonstramos como ciência de dados pode ser aplicada diretamente na saúde com resultados reais e práticos. \
O modelo de clusterização demonstrou ser eficaz na identificação de padrões claros entre peso corporal e colesterol, permitindo a segmentação da população em grupos de risco cardiovascular. Essa abordagem pode ser usada como ferramenta preventiva em ambientes de saúde, direcionando intervenções médicas mais personalizadas e antecipadas com base em dados simples.

Feito por Caio Montes — Cientista de Dados & Analista de Dados
