📊 Análise e Projeção de Indicadores Socioeconômicos das Subprefeituras de São Paulo
Este projeto tem como objetivo analisar, agrupar e projetar a evolução de indicadores socioeconômicos das subprefeituras do município de São Paulo, com foco na identificação de desigualdades regionais e suporte à tomada de decisão em políticas públicas.

Através de técnicas de Machine Learning Supervisionado e Não Supervisionado, foram realizadas projeções de tendências futuras dos indicadores, além da clusterização das subprefeituras conforme perfis socioeconômicos similares.

🗺️ Contexto
São Paulo é o maior município do Brasil, com cerca de 12 milhões de habitantes distribuídos em 32 subprefeituras e 96 distritos. Devido à sua grande heterogeneidade, há importantes disparidades em indicadores como renda, acesso a serviços básicos, saúde e educação.

🎯 Objetivos do Projeto
Analisar a evolução temporal de indicadores socioeconômicos em cada subprefeitura.

Projetar tendências futuras (horizonte de 5 anos) utilizando regressão.

Agrupar subprefeituras com características similares via clustering.

Apoiar visualmente a análise através de gráficos e mapas interpretáveis.

Fornecer subsídios para priorização de políticas públicas e alocação de recursos.

🛠️ Tecnologias e Bibliotecas
Python 3.x

Pandas (manipulação de dados)

NumPy (operações numéricas)

Matplotlib & Seaborn (visualização de dados)

Scikit-learn (modelos de Machine Learning)

Plotly (gráficos interativos)

Google Colab (ambiente de desenvolvimento)

🧪 Metodologia
1. Aprendizado Supervisionado
Modelo: Regressão Linear Simples.

Objetivo: Prever a evolução temporal de indicadores nas subprefeituras.

Métricas de Avaliação: R², MAE (Erro Absoluto Médio), MAPE (Erro Percentual Absoluto Médio).

2. Aprendizado Não Supervisionado
Modelos: K-Means e Agglomerative Clustering.

Objetivo: Agrupar subprefeituras conforme perfis socioeconômicos similares.

Validação: Silhouette Score e Davies-Bouldin Index.

Redução de Dimensionalidade: PCA (Análise de Componentes Principais).

📁 Estrutura do Projeto
kotlin
Copiar
Editar
├── data/
│   ├── indicadores_socioeconomicos.csv
├── notebooks/
│   ├── analise_projecao_indicadores.ipynb
│   ├── clustering_subprefeituras.ipynb
├── outputs/
│   ├── Projecoes_Subprefeituras.pdf
│   ├── Resumo_Metricas_Projecao_Subprefeituras.xlsx
├── README.md
📊 Resultados
Projeções temporais de indicadores em cada subprefeitura até 2030.

Segmentação das subprefeituras em 2 clusters principais, com perfis socioeconômicos contrastantes.

Visualização das regiões mais vulneráveis com base nos indicadores analisados.

🚀 Como Executar
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/seu-repositorio.git
Abra o notebook no Google Colab ou ambiente local.

Execute as células conforme indicado.

Os resultados serão exportados nas pastas outputs/.

📚 Referências
IBGE Censo 2022

DataSUS - Departamento de Informática do SUS

Machine Learning with Scikit-Learn & PyTorch (Sebastian Raschka)

An Introduction to Statistical Learning (Gareth James et al.)

📝 Licença
Este projeto está sob a licença MIT.

