# SME0823 -  Modelos de Regressão e Aprendizado Supervisionado II - Avaliação 2

Repositório contendo a resolução da segunda avaliação da disciplina **SME0823 - Modelos de Regressão e Aprendizado Supervisionado II**, ministrada pela Profa. Cibele Russo no ICMC-USP.

> **Aluno:** Felipe Aparecido da Silva  
> **Dígito final do Nº USP:** 2

---

## Resumo da Avaliação

O objetivo deste trabalho é modelar dados de contagem referentes a um estudo clínico sobre rinite alérgica (dataset `sneeze2`), investigando fatores que influenciam o número de espirros diários.

O notebook aborda as seguintes etapas:

1.  **Análise Exploratória de Dados (EDA):**
    * Visualização da distribuição da variável resposta.
    * Associações com covariáveis (álcool, fumo, antihistamínicos, pólen e idade).
2.  **Modelagem Estatística:**
    * Ajuste de Modelos Lineares Generalizados (GLM) com função de ligação Log.
    * Comparação entre **Modelo de Poisson** e **Modelo Binomial Negativo** (para tratamento de superdispersão).
3.  **Seleção e Comparação:**
    * Uso de critérios de informação (AIC, BIC).
    * Teste da Razão de Verossimilhança (Likelihood Ratio Test).
4.  **Validação:**
    * Divisão dos dados em Treino (80%) e Teste (20%).
    * Análise de resíduos e métricas de erro (RMSE, MAE).
5.  **Predição:**
    * Estimativa do número esperado de espirros para perfis específicos de pacientes em cenários de baixa e alta concentração de pólen.

## Tecnologias Utilizadas

- **Linguagem:** Python 3
- **Bibliotecas:**
    - `pandas` (Manipulação de dados)
    - `seaborn` / `matplotlib` (Visualização)
    - `statsmodels` (Ajuste de modelos estatísticos - GLM)
    - `scikit-learn` (Métricas e separação de dados)
    - 
## Estrutura do Repositório

- **`SME0823_Avaliação_2.ipynb`**: Notebook contendo toda a rotina de análise, códigos e interpretações dos resultados.
- **`sneeze2.csv`**: Conjunto de dados utilizado nesta análise (selecionado com base no final do Nº USP: 2).
- **`sneeze[0-5].csv`**: Todas as variações do dataset fornecidas pela docente para a avaliação.
