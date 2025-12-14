# Análise de Sentimento de Resenhas com LLM

Projeto de estudo em Inteligência Artificial aplicada, utilizando modelos de linguagem para análise de sentimento de resenhas textuais do App ChatGPT.

## Descrição
O notebook realiza as seguintes etapas:

- Leitura de um arquivo `.txt` contendo resenhas
- Envio das resenhas a um modelo de linguagem via API (Groq)
- Extração estruturada das informações em formato JSON, incluindo:
  - ID do usuário
  - Resenha original
  - Resenha traduzida para português
  - Avaliação: Positiva, Negativa ou Neutra
- Conversão para estruturas Python (listas de dicionários)
- Criação de função que:
  - Conta a quantidade de avaliações positivas, negativas e neutras
  - Une todos os dicionários em uma única string separada por `#####`
- Visualização das avaliações usando dois gráficos com matplotlib:
  - Gráfico de barras mostrando a quantidade de cada tipo de avaliação
  - Gráfico de pizza mostrando a distribuição percentual das avaliações

## Tecnologias utilizadas
- Python
- Jupyter Notebook
- LLM via API (Groq)
- Manipulação de dados com listas e dicionários
- Visualização com Matplotlib
