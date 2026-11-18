# coffee-quality-dashboard

Dashboard interativo desenvolvido para apresentar os indicadores de qualidade, análise sensorial e rankings de cafés especiais das espécies **Arábica** e **Robusta**.

## Origem dos Dados

Os dados exibidos neste painel foram extraídos e limpos em Python, carregados em uma base de dados no Microsoft SQL Server e consultados por meio de queries SQL através do projeto:
**[coffee-quality-etl](https://github.com/gabrielpecanharamos/coffee-quality-etl)**

## Estrutura do Projeto

```text
coffee-quality-dashboard/
├── index.html      # Painel interativo gerado com apoio do Gemini
├── PROMPT.md       # Documentação dos prompts utilizados
└── README.md       # Documentação do repositório
```