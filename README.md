# 📊 MVP Machine Learning & Analytics - Predição do Impacto de Publicações Científicas Brasileiras em Medicina (2005–2021)

## Análise Supervisionada para Classificação e Regressão do Impacto Científico Baseado em Colaboração Internacional, Acesso Aberto e Perfil de Autoria

Este repositório contém o desenvolvimento de um **Minimum Viable Product (MVP)**, realizado no contexto da disciplina de ML da PUC-Rio no curso de pós graduação em em **Ciência de Dados & Analytics**.  
Este projeto implementa modelos de Machine Learning supervisionado para predição do impacto de publicações científicas brasileiras na área de Medicina, dando continuidade à análise exploratória realizada no MVP anterior (Análise de Dados e Boas Práticas). Utilizamos o dataset consolidido e tratado para construir modelos preditivos que identificam os fatores determinantes do impacto científico medido através de citações.

---

## 🚀 Objetivos do Projeto

## 🎯 Objetivo
Desenvolver e comparar modelos supervisionados de regressão e classificação para prever o impacto de publicações científicas com base em variáveis-chave identificadas na análise exploratória inicial:

- Regressão: Prever o número exato de citações (citedby_count)
- Classificação: Categorizar o impacto em Baixo, Médio ou Alto com base nas citações

## 📊 Dataset
Continuação do trabalho anterior - Utilizamos o dataset tratado e enriquecido do MVP de Análise Exploratória:

🔗 Acesse o dataset completo no link público do Google Drive (https://drive.google.com/file/d/1fOpCZXMsiPxXhi9U9U4eJwlQo8yHZia8/view?usp=drive_link)
Escopo: Publicações com pelo menos um autor afiliado ao Brasil na área da Medicina (2005-2021)
Formato: CSV tratado e limpo, aproximadamente 250 mil registros
Variáveis selecionadas: 5 variáveis mais relevantes identificadas na análise exploratória

## 🧠 Hipóteses Testadas
- Colaboração Internacional → Maior impacto e visibilidade
- Acesso Aberto → Mais citações por maior disseminação
- Número de Autores → Correlação positiva com impacto científico
- Ano de Publicação → Efeito temporal no acúmulo de citações

## ⚙️ Metodologia Técnica
Modelos Implementados

REGRESSÃO (Valor contínuo)
- Random Forest Regressor
- Linear Regression
  
CLASSIFICAÇÃO (Categorias)
- Random Forest Classifier  
- Logistic Regression

---

## 📂 Etapas do MVP 

- 1: CONFIGURAÇÕES DO AMBIENTE E IMPORTAÇÕES
- 2: ⁠CARGA DE DADOS
- 3: PREPARAÇÃO DOS DADOS PARA MODELAGEM
- 4: ANÁLISE EXPLORATÓRIA DOS DADOS
- 5: TESTE DAS HIPÓTESES
- 6: TRATAMENTO DE DADOS
- 7: PREPARAÇÃO PARA MODELAGEM
- 8: MODELAGEM - REGRESSÃO
- 9: ANÁLISE DOS MODELOS DE REGRESSÃO - RESULTADOS CONSOLIDADOS
- 10: MODELAGEM - CLASSIFICAÇÃO
- 11: OTIMIZAÇÃO DE HIPERPARÂMETROS
- 12: ANÁLISE COMPARATIVA DOS MODELOS (CLASSIFICAÇÃO + REGRESSÃO)
- 13: CONCLUSÕES FINAIS E RECOMENDAÇÕES
- 14: LIMITAÇÕES E PRÓXIMOS PASSOS
- 15: CHECKLIST
  












