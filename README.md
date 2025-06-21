🧠 Análise de Risco Cardiovascular com K-Means
Este projeto foi desenvolvido como parte do Bootcamp Arquiteto(a) de Big Data, com o objetivo de aplicar algoritmos de machine learning para identificar padrões de risco cardiovascular em pacientes com base em peso e colesterol.

💡 Objetivo
Utilizar o algoritmo de clusterização K-means para segmentar pacientes em três grupos:

Baixo risco
Risco moderado
Alto risco
Esses agrupamentos ajudam na tomada de decisão clínica, permitindo intervenções personalizadas e prevenção de complicações graves.

📁 Estrutura do Projeto
📁 dados

dados_clinicos.csv
estado_regiao.csv
dados_pacientes.csv
📁 Análise e tratamento dos dados

Scripts Python com funções reutilizáveis
Tratamento e limpeza dos dados
Algoritmo de K-means e visualizações
📊 Tecnologias Utilizadas

Python 3.9+
Pandas 1.5.2
Matplotlib 3.6.2
Seaborn 0.12.1
Scikit-learn 1.2.0
Plotly 5.11.0
📈 Resultados Com a aplicação do K-means (k=3, random_state=42), foi possível identificar três agrupamentos bem definidos no gráfico de dispersão entre peso x colesterol, revelando diferentes níveis de risco cardiovascular.

🧹 Tratamento de Dados

Dados ausentes numéricos: preenchidos com média arredondada
Dados ausentes categóricos: preenchidos com moda
🩺 Impacto Essa análise contribui para a detecção precoce de riscos cardíacos, permitindo uma atuação mais rápida e eficaz por parte da equipe médica. Demonstramos como ciência de dados pode ser aplicada diretamente na saúde com resultados reais e práticos.

Feito por Caio Montes — Cientista de Dados & Analista de Dados
