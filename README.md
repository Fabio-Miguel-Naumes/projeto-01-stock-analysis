# 🚀 Projeto 1 – Análise Exploratória de Ações

[![Python](https://img.shields.io/badge/python-3.9+-blue)](https://www.python.org/) [![License: MIT](https://img.shields.io/badge/License-MIT-green)](LICENSE)

## 🎯 Objetivo
Coletar, limpar e visualizar dados históricos de ações via Yahoo Finance. Entender tendências, picos e vales para embasar decisões quantitativas.

## 🛠️ Ferramentas & Tecnologias
- **Python 3.9+**  
- **Pandas**: manipulação de séries temporais  
- **yfinance**: download de dados reais  
- **Matplotlib**: visualização gráfica

## 🚀 Funcionalidades
1. Download de dados históricos (`Open`, `High`, `Low`, `Close`, `Volume`)  
2. Análise exploratória: estatísticas descritivas  
3. Gráfico de preço de fechamento com annotations

## 📈 Demonstração
![performance_plot](images/performance_plot.png)

## 📝 Como Rodar
```bash
git clone https://github.com/SEU_USUARIO/projeto-01-stock-analysis.git
cd projeto-01-stock-analysis
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python src/analysis.py


