# POC IA Previsão de Risco de Crédito

**Objetivo**  
Prova de conceito que demonstra pipeline de dados e modelo de classificação para previsão de risco de crédito usando dataset público.

**Tecnologias**  
Python, pandas, scikit‑learn, Jupyter Notebook, Docker (opcional).

**Entregáveis**  
- Notebook com ETL, engenharia de features, treino e avaliação do modelo.  
- Script para inferência em CSV de entrada.  
- Relatório com métricas (AUC, precisão, recall) e recomendações.

**Como executar**  
1. Abrir `notebooks/poc_credit.ipynb`.  
2. `pip install -r requirements.txt`  
3. Rodar células do notebook para reproduzir resultados.  
4. `python infer.py --input sample.csv --output predictions.csv`

**Métricas de exemplo**  
- AUC: 0.78 (exemplo).  
- Relatório com matriz de confusão e métricas por classe.

**Evidências**  
- Gráficos de importância de features.  
- Notebook com passos reproduzíveis.
