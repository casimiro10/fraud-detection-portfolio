## ⚙️ Metodologia
1. **EDA** — Análise exploratória e visualizações
2. **Pré-processamento** — Normalização e balanceamento com SMOTE
3. **Modelagem** — Treinamento e comparação de 3 modelos
4. **Avaliação** — Métricas e conclusão de negócio

## 🤖 Modelos e Resultados

| Modelo | Precision | Recall | AUC-ROC |
|---|---|---|---|
| Regressão Logística | 6% | 92% | 0.9464 |
| Random Forest | 82% | 82% | 0.9080 |
| XGBoost | 73% | 89% | 0.9436 |

## 🏆 Melhor Modelo: Random Forest
- **Precision: 82%** — menos falsos alarmes
- **Recall: 82%** — detecta 82% das fraudes reais

## 💡 Conclusão de Negócio
- A cada 100 fraudes, o modelo detecta 82
- Reduz significativamente prejuízos financeiros
- Precision de 82% evita bloquear clientes legítimos
- Recomendado para uso em produção com monitoramento contínuo

## 👤 Autor
João Casimiro
- LinkedIn: [https://www.linkedin.com/in/jo%C3%A3o-raphael-casimiro-de-almeida-63681a23b/]
- GitHub: [https://github.com/casimiro10]