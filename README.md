# 📊 Análise de Churn e Engajamento em Plataforma SaaS (CRM B2B)

Este projeto analisa o comportamento de cancelamento de clientes (churn) em uma plataforma SaaS B2B de CRM. Com base em dados reais simulados, foram extraídos insights sobre engajamento, satisfação e padrões de evasão, por meio de análise exploratória e visualizações orientadas ao negócio.

# 📊 Análise de Churn e Engajamento em Plataforma SaaS (CRM B2B)

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg)]()

---

## 🎯 Objetivo

Identificar padrões e variáveis associadas ao churn de clientes, com base em dados comportamentais e demográficos, para orientar ações estratégicas de retenção.

---

## 🧰 Tecnologias Utilizadas

- Python 3.10+
- Pandas, NumPy
- Matplotlib, Seaborn
- Scipy (testes estatísticos)
- Google Colab (ambiente)

---

## 🧪 Metodologia

- Leitura e limpeza dos dados
- Análise exploratória (EDA)
- Feature engineering
- Testes estatísticos (Mann–Whitney U)
- Visualizações com Seaborn
- Exportação de gráficos em alta resolução

---

## 📊 Principais Descobertas

- **Churn geral:** 44,9% dos clientes cancelaram
- **Plano Free:** maior taxa proporcional de cancelamento
- **Empresas Pequenas:** concentram maior evasão
- **Satisfação:** cancelados têm média ~3.1 | ativos ~3.8
- **Login e Engajamento:** inatividade impacta fortemente
- **Tempo como cliente:** levemente menor nos que cancelaram
- **Sazonalidade:** churn flutua mês a mês com picos identificáveis

---

## 🧠 Testes Estatísticos

Foi aplicado o teste de **Mann–Whitney U** para comparar a distribuição de satisfação entre clientes ativos e cancelados.  
➡️ Resultado: **p < 0.05**, confirmando diferença estatisticamente significativa.

---

## 💡 Recomendações Estratégicas

- Alertas para inatividade e baixa satisfação
- Reforço no onboarding de clientes Free e pequenos
- Estratégia de upsell para planos pagos com valor agregado
- Monitoramento temporal para prever sazonalidade de churn

---

## 📁 Estrutura do Projeto

```text
projeto-churn-saas/
├── crm_churn_dataset.csv
├── Análise_de_Churn_e_Engajamento_de_Clientes_em_uma_Plataforma_SaaS_de_CRM_B2B.ipynb
├── imagens/
│   ├── grafico_churn_geral.png
│   ├── grafico_churn_por_plano.png
│   ├── grafico_churn_por_empresa.png
│   ├── grafico_boxplot_satisfacao.png
│   ├── grafico_heatmap_correlacao.png
│   ├── grafico_churn_temporal.png
│   ├── grafico_tempo_cliente_boxswarm.png

👤 Sobre o Autor
Rodrigo de Souza Silva

**Rodrigo de Souza Silva**  
Profissional de Tecnologia da Informação com formação em Sistemas de Informação e pós-graduação em Data Science & Machine Learning. Atua no desenvolvimento de projetos práticos com Python, APIs REST, automações e análise de dados, aplicando os conhecimentos adquiridos em formação técnica e cursos especializados.

Apaixonado por dados, boas práticas de código e soluções que unem lógica, organização e utilidade real.

- [LinkedIn](https://www.linkedin.com/in/rodrigodesouzasilva)  
- [GitHub](https://github.com/rodrigodesouza7)

---

## 📄 Licença

Este projeto está licenciado sob os termos da licença [MIT](https://opensource.org/licenses/MIT).  
Você pode usar, modificar e distribuir com os devidos créditos ao autor.

