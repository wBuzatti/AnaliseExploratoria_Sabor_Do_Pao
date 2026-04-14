# Projeto de Ciência de Dados III: Análise Exploratória - Sabor do Pão LTDA

## Sobre o Projeto
Este repositório contém o código-fonte, scripts de ETL e as análises exploratórias (EDA) desenvolvidos para o projeto de extensão do curso de Ciência de Dados e IA. O objetivo principal é reestruturar o fluxo de dados operacionais de uma indústria alimentícia parceira (focada em panificação), contornando a fragmentação do sistema ERP atual através de rotinas de engenharia de dados e disponibilizando inteligência de negócios.

O projeto consolida dados de três frentes operacionais (Produção, Vendas e Notas Fiscais) em uma arquitetura de **Data Marts**, culminando em painéis interativos no Power BI para acompanhamento de métricas cruciais, como perdas por *shelf-life* (validade) e custos de produção.

## Arquitetura e Tecnologias
* **Linguagem Principal:** Python 3
* **Manipulação de Dados:** Apache HOP
* **Visualização Final:** Power BI Service
* **Metodologia:** Ágil (Scrum adaptado)

## Estrutura do Repositório
Para garantir a organização e a segurança dos dados da empresa parceira, o projeto segue a seguinte estrutura de diretórios:

```text
├── data/
│   ├── raw/               # Planilhas originais de coleta (NÃO SOBE PARA O GIT)
│   └── processed/         # Dados limpos após o ETL (NÃO SOBE PARA O GIT)
├── docs/                  # Documentação do projeto, Dicionário de Dados e templates em Excel
├── notebooks/             # Jupyter Notebooks com a Análise Exploratória de Dados (EDA)
├── src/                   # Scripts Python definitivos (Pipeline de ETL)
├── dashboards/            # Referências visuais e documentação dos painéis
├── .gitignore             # Arquivo essencial de segurança de dados
├── requirements.txt       # Lista de dependências Python
└── README.md              # Este arquivo
