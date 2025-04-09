# Projeto IA – Análise de Dados de Transações Financeiras

Este repositório apresenta um projeto de **Inteligência Artificial** focado na **análise exploratória** de **transações financeiras** e identificação de **possíveis fraudes**.

---

## Estrutura do Repositório

```
.
├── datasets/
│   ├── credit_card_2023.csv
│   ├── creditcard.csv
│   └── paysim.csv
├── eda.ipynb
├── Relatório.pdf
└── README.md
```

1. **`datasets/`**: pasta que contém os arquivos CSV (datasets) usados na análise.
2. **`eda.ipynb`**: notebook **Jupyter** principal onde é feita a análise exploratória (EDA) dos dados.
3. **`Relatório.pdf`**: arquivo que descreve o projeto, detalhando a metodologia e resultados esperados.

---

## Descrição Geral

- **Objetivo**: analisar transações financeiras e identificar fraudes/anomalias, além de investigar padrões relevantes.
- **Motivação**: a segurança e confiabilidade em operações financeiras requer métodos robustos para detecção de transações suspeitas.
- **Metodologia**:
  1. **Análise Exploratória** – leitura, estatísticas descritivas, distribuição de classes, etc.
  2. **Pré-processamento** – limpeza, normalização, balanceamento de classes.
  3. **Modelagem** – algoritmos de Machine Learning / Deep Learning para detecção de anomalias.

---

## Como Executar

1. **Clonar** este repositório:
   ```bash
   git clone https://github.com/seu-usuario/projeto-IA-fraudes.git
   ```
2. **Baixe os datasets** para a pasta datasets.

3. **Instalar dependências** (por exemplo, caso use Python):

   ```bash
   pip install -r requirements.txt
   ```

4. **Executar o Notebook**:
   - Abra o **`eda.ipynb`** no Jupyter Notebook/Lab ou Google Colab.
   - Ajuste os caminhos dos arquivos CSV caso necessário (referentes à pasta `datasets/`).
   - Execute as células para gerar os gráficos e relatórios de análise exploratória.

---
