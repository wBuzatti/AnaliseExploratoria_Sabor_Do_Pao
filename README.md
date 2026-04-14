# Projeto de Ciência de Dados III: Análise Exploratória - Sabor do Pão LTDA

## Sobre o Projeto
Este repositório contém o código-fonte, scripts de ETL e as análises exploratórias (EDA) desenvolvidos para esse projeto do curso de Ciência de Dados e Inteligência Artificial, da PUC Minas. O objetivo principal é reestruturar o fluxo de dados operacionais da empresa parceira Sabor do Pão LTDA, desenvolvendo uma solução de BI (Business Inteligence) para auxiliar no processo de tomada de decisão da fábrica.

O projeto consolida dados de três frentes operacionais (Produção, Vendas e Notas Fiscais) em uma arquitetura de **Data Marts**, resultando em painéis interativos no Power BI para acompanhamento de métricas essenciais, como perdas e custos de produção.

## Arquitetura e Tecnologias
* **Linguagem Principal:** Python 3
* **Manipulação de Dados:** Apache HOP
* **Visualização Final:** Power BI Service
* **Metodologia:** Ágil (Scrum adaptado)

## Estrutura do Repositório
Para garantir a organização e a segurança dos dados da empresa parceira, o projeto final deve seguir a seguinte estrutura:

```text
├── data/
│   ├── raw/               # Planilhas originais (NÃO SOBE PARA O GIT)
│   └── limpos/         # Dados limpos após o ETL (NÃO SOBE PARA O GIT)
├── docs/                  # Documentação do projeto, Dicionário de Dados e templates em Excel
├── src/                   # Pipeline do Apache HOP (ETL)
├── dashboards/            # Referências visuais e documentação dos painéis
├── .gitignore             # Segurança dos dados
└── README.md              # Este arquivo
