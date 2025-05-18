<p align="center">
  <img src="imagens/grafico_churn_geral.png" width="600">
</p>

# 📊 Análise de Churn e Engajamento em Plataforma SaaS (CRM B2B)

Este projeto tem como objetivo analisar o comportamento de cancelamento de clientes (churn) em uma plataforma SaaS B2B de CRM. Através de técnicas de análise de dados e visualização, foram extraídos insights valiosos que ajudam a entender os fatores que influenciam a evasão de clientes.

---

## 🎯 Objetivo

> Identificar padrões e variáveis associadas ao churn de clientes, com base em dados comportamentais e demográficos, para orientar ações de retenção.

---

## 🧰 Tecnologias Utilizadas

- Python 3.10+
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scipy
- Google Colab

---

## 🧪 Metodologia

- Leitura e tratamento de dados
- Análise exploratória (EDA)
- Criação de variáveis (feature engineering)
- Testes estatísticos de hipóteses (Mann–Whitney U)
- Visualizações profissionais com Seaborn
- Exportação de gráficos em alta resolução

---

## 📊 Principais Descobertas

- **Churn geral:** 44,9% dos clientes cancelaram.
- **Plano Free:** teve o maior volume proporcional de churn.
- **Empresas pequenas:** concentram mais cancelamentos.
- **Satisfação:** clientes com nota média ~3.1 cancelam mais; ativos ~3.8.
- **Tempo sem login:** quanto maior, maior a chance de churn.
- **Tempo como cliente:** levemente menor em clientes que cancelaram.
- **Linha do tempo:** churn flutua mês a mês, com picos pontuais.

---

## 🧠 Testes Estatísticos

O teste de Mann–Whitney U foi aplicado para comparar a satisfação entre clientes ativos e cancelados. O resultado mostrou diferença estatisticamente significativa (**p < 0.05**), validando que clientes satisfeitos permanecem mais tempo.

---

## 💡 Recomendações Estratégicas

1. Criar alertas para inatividade e baixa satisfação.
2. Reforçar o onboarding para clientes pequenos e do plano Free.
3. Incentivar upgrades para planos pagos com benefícios claros.
4. Monitorar sazonalidade do churn para prever picos.

---

## 📁 Estrutura

```
📦 projeto-churn-saas
├── crm_churn_dataset.csv
├── notebook_projeto.ipynb
├── imagens/
│   ├── grafico_churn_geral.png
│   ├── grafico_churn_por_plano.png
│   ├── grafico_churn_por_empresa.png
│   ├── grafico_boxplot_satisfacao.png
│   ├── grafico_heatmap_correlacao.png
│   ├── grafico_churn_temporal.png
│   ├── grafico_tempo_cliente_boxswarm.png
```

---

## 👤 Autor

Rodrigo de Souza 
Analista de Dados | Data-Driven | Foco em Negócios SaaS  
[LinkedIn] www.linkedin.com/in/rodrigodesouzasilva • [GitHub] https://github.com/rodrigodesouza7

