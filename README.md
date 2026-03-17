# 📉 Predição de Churn — Model Fitness

Este projeto utiliza técnicas de Machine Learning para prever a rotatividade (churn) de clientes em uma rede de academias.

O objetivo é identificar clientes com maior risco de cancelamento e gerar insights estratégicos para retenção.

# 🎯 Problema de Negócio

A retenção de clientes é um dos principais desafios de empresas baseadas em assinatura.

Neste contexto, a Model Fitness busca entender:
- Quais clientes têm maior probabilidade de sair
- Quais fatores influenciam o churn
- Como agir de forma preventiva

🧰 Ferramentas

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- K-Means (clusterização)

📊 Etapas do Projeto

1. Análise exploratória dos dados (EDA)
2. Modelagem preditiva (classificação)
3. Avaliação de modelos
4. Segmentação de clientes (clusterização)
5. Geração de insights e recomendações

🤖 Modelos Utilizados

- Regressão Logística
- Random Forest

📈 Resultados dos Modelos

### Regressão Logística
- Accuracy: 0.916
- Precision: 0.873
- Recall: 0.782
- ROC-AUC: 0.969

### Random Forest
- Accuracy: 0.91
- Precision: 0.849
- Recall: 0.782
- ROC-AUC: 0.961

🔍 Principais Insights

- Clientes com baixa frequência recente têm maior risco de churn
- Contratos curtos estão fortemente associados à saída
- Clientes novos são mais propensos a abandonar a academia
- Engajamento (aulas, serviços adicionais) reduz churn

👥 Segmentação de Clientes

A clusterização revelou diferentes perfis:

- 🔴 Alto risco: clientes novos, pouco engajados
- 🟢 Baixo risco: clientes com contratos longos e alta frequência
- 🟡 Moderado: comportamento intermediário

💡 Recomendações

- Focar nos primeiros meses do cliente (onboarding)
- Incentivar contratos mais longos
- Monitorar queda de frequência
- Estimular engajamento social (aulas e indicações)

📎 Observações
Os dados utilizados são de ambiente educacional e não estão disponíveis publicamente neste repositório.
