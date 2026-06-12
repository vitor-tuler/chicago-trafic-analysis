# Chicago Urban Mobility Analysis - November 2017

## 📋 Descrição
Análise exploratória de mobilidade urbana em Chicago usando dados de viagens por aplicativo.
O projeto examina hubs de alta demanda, desempenho de empresas de transporte e o impacto das condições climáticas na duração das viagens.

## 🎯 Objetivo
Identificar padrões de deslocamento urbano, compreender a concentração de viagens em locais-chave e testar hipóteses sobre a duração das viagens sob diferentes condições meteorológicas.

## 📊 Dados
- `moved_project_sql_result_01.csv` - Dados de viagens e de empresas de transporte
- `moved_project_sql_result_04.csv` - Dados agregados por local de desembarque e média de viagens
- `moved_project_sql_result_07.csv` - Dados de duração das viagens por condição climática

## 🚀 Como Executar
```bash
pip install -r requirements.txt
jupyter notebook analysis.ipynb
```

## 📈 Análises Realizadas
- Identificação dos 10 principais hubs de desembarque com maior volume de viagens
- Análise das empresas com maior número de viagens
- Comparação de duração de viagens em diferentes condições climáticas
- Teste de Levene e teste t para verificar diferenças estatísticas

## 🛠️ Tecnologias
- Python 3.8+
- pandas, numpy, matplotlib, seaborn, scipy
