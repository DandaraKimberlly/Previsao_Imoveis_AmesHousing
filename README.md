# 🏡 Predição Inteligente de Preços de Imóveis (Ames Housing)

Este projeto utiliza **Machine Learning** para resolver um dos problemas mais complexos do mercado imobiliário: a **precificação** precisa de ativos baseada em características arquitetônicas e de mercado.

## 🎯 Resultados de Negócio
- **R² Score: 0.926**: O modelo explica 92,6% da variabilidade dos preços.
- **Precisão em Simulação Real: 81.6%**: Capacidade de prever valores com alta confiabilidade mesmo em cenários isolados.
- **Erro Médio Reduzido**: Implementação de transformação logarítmica para equilibrar previsões entre casas populares e de luxo.

## 🛠️ O que foi feito?
- **Tratamento de Dados Contextual**: Valores nulos não foram apenas excluídos, mas interpretados conforme o negócio (ex: ausência de piscina interpretada como "valor zero" para o atributo).
- **Engenharia de Features**: Criação de métricas de idade e área útil que se provaram os maiores drivers de valor.
- **Pipeline de Produção**: O modelo foi serializado e está pronto para uso em tempo real através de um script de simulação.

## 📊 Insights Chave
<img width="1144" height="679" alt="img_grafico_influencias" src="https://github.com/user-attachments/assets/e0bf5640-12ae-416e-bed2-03982d6ae9fa" />

*A "Qualidade Geral" e a "Área Habitável" foram confirmadas como os fatores de maior impacto no ROI imobiliário.*
