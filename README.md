# IBOV PRO - OBINVEST
IBOV PRO é uma aplicação web interativa desenvolvida em Python com Streamlit, voltada ao apoio educacional e acadêmico na análise de ativos financeiros listados no Ibovespa. O projeto faz parte de uma iniciativa acadêmica desenvolvida em parceria com o grupo OBINVEST, visando a produção científica sobre visualização financeira, análise de mercado e educação financeira baseada em dados, explorando dashboards interativos e métodos quantitativos. O IBOV PRO oferece ferramentas visuais e estatísticas para apoiar a tomada de decisão de jovens investidores e estudantes de finanças.

acesse: https://cnpq-ibovpro1.streamlit.app/

---

# OBJETIVOS

- Facilitar a análise exploratória de ativos do Ibovespa  
- Introduzir conceitos de finanças quantitativas de forma visual e acessível  
- Fornecer uma ferramenta educacional para estudantes iniciantes de finanças
- Avaliar o impacto de dashboards interativos no aprendizado financeiro  

---

# FUNCIONALIDADES
  # Análise Individual de Ativos
  - Visualização histórica de preços (diária, mensal ou anual)
  - Gráficos interativos com estilo de terminal financeiro
  - Agregação dinâmica dos valores OHLC (Open, High, Low, Close)
  
  # Análise de Correlação
  - Cálculo de retornos logarítmicos
  - Geração de matriz de correlação entre múltiplos ativos
  - Heatmap interativo para análise de interdependência entre ativos
  
  # Ranking de Mercado
  - Scanner automático de ativos do Ibovespa
  - Identificação de líderes e retardatários do mercado com base no retorno logarítimico
  - Análise de desempenho em diferentes horizontes temporais

---

# METODOLOGIA

- Dados de mercado obtidos via Yahoo Finance (yfinance)
- Lista oficial de ativos do Ibovespa coletada via web scraping
- Uso de retornos logarítmicos para análises estatísticas
- Visualizações interativas com Plotly

---

# TECNOLOGIAS UTILIZADAS

- Python 3.13  
- Streamlit  
- Pandas  
- NumPy  
- Plotly  
- yFinance  
- Requests  

---

# COMO EXECUTAR O PROJETO
1. Clone este repositório:
   git clone https://github.com/JohnnyVieira671/IBOVPRO_OBINVEST.git

2. Acesse o diretório do projeto:
  cd ibov-pro

3. Instale as dependências:
  pip install -r requirements.txt

4. Execute a aplicação:
  streamlit run app.py
