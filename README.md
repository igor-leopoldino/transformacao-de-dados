## Projeto de Transformação e Manipulação de Dados

Este projeto foi desenvolvido como parte do curso de Transformação de Dados da Alura.
O objetivo principal é praticar técnicas de limpeza, transformação e manipulação de dados utilizando Python e a biblioteca Pandas.

### **Objetivo**:
O projeto utiliza dois conjuntos de dados em formato JSON relacionados a hospedagens e imóveis disponíveis.
O foco é aplicar transformações para:
  * Normalização de dados aninhados
  * Conversão de tipos de dados (string → numérico / datetime)
  * Tratamento de valores nulos
  * Padronização de texto
  * Explosão de colunas com listas
  * Agrupamentos e análises de disponibilidade

### **Tecnologias utilizadas**:
* Python 3
* Pandas
* NumPy
* Google Colab (ambiente original do desenvolvimento)

### **Estrutura do Projeto**:
* Carregamento de dados: leitura de arquivos JSON hospedados em URLs externas.
* Transformação do dataset de hospedagem:
  * Normalização dos dados aninhados com pd.json_normalize.
  * Conversão de colunas de texto monetário ($) para float.
  * Conversão de colunas numéricas para int64.
  * Padronização de textos (str.lower, remoção de caracteres especiais, tokenização).
  * Explosão e tratamento de listas de comodidades.
* Transformação do dataset de imóveis disponíveis:
  * Conversão de coluna de datas para o tipo datetime.
  * Agrupamento por mês para análise de vagas disponíveis.
  * Limpeza e conversão de preços.

### **Aprendizados**:
  * Técnicas de data cleaning e data wrangling.
  * Como normalizar JSONs complexos.
  * Boas práticas na manipulação de dados com Pandas.
  * Tratamento de colunas textuais e numéricas para análises posteriores.

### **Fonte de dados**:
Os dados utilizados foram disponibilizados pela [Alura Cursos](https://cdn3.gnarususercontent.com.br/2928-transformacao-manipulacao-dados/dados_locacao_imoveis.json).

### **Créditos**:
Projeto desenvolvido como exercício do curso Transformação e Manipulação de Dados da Alura.
