# 🍷 Análise do Mercado de Importação de Vinhos (2008–2023)

## 📌 Visão Geral

Este projeto apresenta uma análise do **mercado de importação de vinhos** no período de **2008 a 2023**, com foco especial no **Brasil**.

O estudo utiliza dados históricos de volume (litros) e valor financeiro (USD), com o objetivo de identificar tendências de mercado, principais parceiros comerciais e oportunidades estratégicas para o setor vitivinícola.

O projeto foi desenvolvido no contexto de uma **pós-graduação**, integrando análise de dados, contexto econômico e visualização analítica.

---

## 🎯 Objetivos

- Consolidar bases históricas de importação de vinhos  
- Analisar volume importado e valor financeiro  
- Avaliar o posicionamento do Brasil no cenário global  
- Identificar tendências de crescimento e retração  
- Gerar projeções a partir de dados históricos  

---

## 📂 Estrutura do Repositório

```text
analise_vinhos.py
base_importacao_completa_2008_2023.csv
O Mercado de Vinho - Relatorio.pdf
README.md
```

---

## 📄 Descrição dos Arquivos

### `analise_vinhos.py`
Script principal do projeto, responsável por:
- Tratamento e limpeza dos dados
- Consolidação das bases históricas
- Análises globais e específicas do Brasil
- Geração de gráficos e visualizações
- Projeção das importações para 2024

### `base_importacao_completa_2008_2023.csv`
Base de dados consolidada no formato analítico, contendo:
- País  
- Ano  
- Quantidade importada (litros)  
- Valor importado (USD)  

### `O Mercado de Vinho - Relatorio.pdf`
Relatório analítico que contextualiza:
- Panorama da vitivinicultura global e nacional
- Impactos climáticos no setor
- Produção, consumo, importação e exportação
- Insights estratégicos para o mercado brasileiro

---

## 🔄 Pipeline de Dados

1. Importação das bases históricas  
2. Padronização e limpeza dos dados  
3. Conversão para formato analítico (ano a ano)  
4. Consolidação em uma base única  
5. Análise exploratória e visualização  

---

## 📊 Análises Realizadas

### 🌍 Mercado Global
- Países com maior volume total importado
- Países com maior valor financeiro importado
- Comparação entre volume físico e valor agregado

### 🇧🇷 Brasil
- Evolução anual das importações
- Análise de variações ao longo do tempo
- Identificação de padrões de crescimento e retração

### 📈 Evolução Temporal
- Análise conjunta de:
  - Quantidade importada (barras)
  - Valor financeiro (linha)
- Identificação de tendências de longo prazo

### 🔮 Projeção para 2024
- Aplicação de regressão linear
- Estimativa de volume e valor de importação
- Visualização histórica com projeção futura

> ⚠️ As projeções são estimativas estatísticas e não substituem análises econômicas aprofundadas.

---

## 📌 Principais Insights

- O Brasil apresenta crescimento consistente no consumo de vinhos importados  
- Chile, Argentina, Portugal e França se destacam como principais fornecedores  
- O mercado brasileiro demonstra amadurecimento ao longo dos anos  
- Há oportunidades estratégicas para diferenciação e agregação de valor  

---

## 🛠️ Tecnologias Utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🚀 Como Executar

1. Clone o repositório:
```bash
git clone <url-do-repositorio>
```

2. Instale as dependências:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Execute o script:
```bash
python analise_vinhos.py
```

---

## 🎓 Contexto Acadêmico

Projeto desenvolvido como parte de uma **pós-graduação**, com foco em:
- Análise de dados
- Inteligência de mercado
- Apoio à tomada de decisão no setor vitivinícola
