# 📊 Tech Challenge - Análise de NPS

## Objetivo

Este projeto tem como objetivo analisar os fatores que mais influenciam o Net Promoter Score (NPS) de um e-commerce, identificando padrões de satisfação dos clientes e oportunidades de melhoria nos processos operacionais.

Foram realizadas análises exploratórias de dados (EDA), utilizando Python, Pandas e visualizações gráficas, para identificar fatores associados à satisfação dos clientes e gerar insights para apoiar a tomada de decisão.

---

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Estrutura do projeto

```text
TechChallenge-NPS/
│
├── data/
│   └── desafio_nps_fase_1.csv
│
├── notebooks/
│   └── 01_Analise_NPS.ipynb
│
├── reports/
│   └── Relatorio_Analise_NPS.pdf
├── slides/
│   └── Apresentacao_TechChallenge_NPS.pptx
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Análises realizadas

Durante o desenvolvimento foram analisados diversos indicadores relacionados à satisfação dos clientes:

- NPS
- Reclamações
- Contatos com atendimento
- Tempo de entrega
- Atraso na entrega
- Recompra em até 30 dias
- Ticket médio
- Comparação por região
- Comparação por faixa etária

---

## Principais conclusões

- Clientes que realizaram recompra apresentaram NPS significativamente superior aos que não retornaram.
- Reclamações, contatos com atendimento e atrasos na entrega apresentaram forte relação com a redução do NPS.
- A região Sudeste concentrou maior volume de reclamações, maior tempo médio de entrega e maiores descontos concedidos aos clientes.
- O Centro-Oeste apresentou maior atraso logístico, maior volume de contatos com o atendimento e maior ticket médio por pedido.
- A análise por faixa etária apresentou baixa variação entre os grupos avaliados, indicando que a idade, isoladamente, não explica diferenças relevantes na satisfação dos clientes.

---

## Como executar

Clone o repositório:

```bash
git clone https://github.com/seulenpaulapramos/TechChallenge-NPS.git
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

Abra o notebook:

```text
notebooks/01_Analise_NPS.ipynb
```

---

## Autora

**Suelen Ramos**

Projeto desenvolvido como parte do **Tech Challenge**, aplicando técnicas de Análise Exploratória de Dados (EDA) para investigar fatores relacionados ao Net Promoter Score (NPS) e apoiar a tomada de decisão baseada em dados.