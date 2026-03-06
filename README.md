# portfolio_dados
Portfólio Área Data Analytics
📊 Monitoramento Estratégico de Indicadores de Saúde (SUS)

Este projeto apresenta uma análise técnica e estratégica de indicadores de desempenho da Atenção Primária à Saúde no Brasil, utilizando dados oficiais de monitoramento.



## 🎯 Objetivo do Projeto
Transformar dados brutos governamentais em inteligência analítica para:
* Identificar disparidades regionais no desempenho da saúde pública.
* Analisar a evolução temporal dos indicadores de 2016 a 2025.
* Auxiliar na tomada de decisão baseada em dados (Data-Driven Decision Making).

## 🛠️ Tecnologias Utilizadas
* **Python (Pandas):** Para limpeza e normalização dos dados.
* **SQL:** Para agregações complexas e cálculo de médias regionais.
* **Matplotlib/Seaborn:** Para visualização de tendências e gargalos.

## 📂 Dicionário de Dados (Principais Campos)
| Coluna | Descrição |
| :--- | :--- |
| `co_anomes` | Competência (Ano e Mês do dado) |
| `no_municipio` | Nome do município analisado |
| `vl_indicador_calculado_mun` | Valor do indicador alcançado pelo município |
| `no_regiao_saude` | Região de Saúde à qual o município pertence |



## 🚀 Etapas de Desenvolvimento
1. **Exploração:** Leitura do ficheiro `ccmec25a64.csv` e análise de tipos.
2. **Limpeza:** Tratamento de valores nulos e conversão de formatos de data.
3. **Análise:** Comparação entre o valor municipal e o valor da região de saúde (`vl_indicador_calculado_rs`).
4. **Visualização:** Criação de gráficos de linha para séries temporais.

---
**Bárbara * *Enfermeira & Analytics Engineer em formação*
