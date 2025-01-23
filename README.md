# Análise do Catálogo de Séries do Globoplay

Este repositório contém um projeto de análise de dados focado no catálogo de séries do Globoplay, dividido em duas etapas principais: **coleta de dados** e **análise exploratória**.

## Estrutura do Repositório

1. **[GLOBOPLAY_WEB_SCRAPING-OBTER_DADOS.ipynb](https://github.com/opablodantas/globoplay-series-analytics/blob/develop/GLOBOPLAY_WEB_SCRAPING-OBTER_DADOS.ipynb)**  
   Este notebook contém a lógica para extração de dados do site do Globoplay.  
   **Principais pacotes utilizados:**  
   - `selenium` (para navegação automatizada)  
   - `BeautifulSoup` (para parsing de HTML)  
   - `requests` (para requisições HTTP)  
   - `pandas` (para manipulação de dados)  

2. **[GLOBOPLAY_WEB_SCRAPING-ANALYTICS.ipynb](https://github.com/opablodantas/globoplay-series-analytics/blob/develop/GLOBOPLAY_WEB_SCRAPING-ANALYTICS.ipynb)**  
   Após consolidar os dados em um único dataframe, neste notebook realizamos análises exploratórias para responder perguntas-chave e gerar insights estratégicos.  
   **Principais bibliotecas utilizadas:**  
   - `pandas` (manipulação de dados)  
   - `seaborn` e `matplotlib` (visualizações gráficas)

## Objetivos do Projeto

- Explorar padrões no catálogo do Globoplay, como:
  - Gêneros predominantes;
  - Distribuição por décadas e classificações etárias;
  - Subgêneros e seu impacto no público.  
- Entender as possíveis estratégias da plataforma para atender seu público-alvo.

## Principais Descobertas

- **Predominância de Dramas:** O gênero mais presente, voltado para adolescentes e adultos.  
- **Foco em Conteúdos Recentes:** A maior parte das séries é das décadas de 2010 e 2020.  
- **Baixa Representação de Séries Antigas:** Apenas 8,4% são de antes dos anos 2000.  
- **Distribuição de Gêneros por Faixa Etária:** Comédia e Infantil dominam as classificações livres; Drama e Suspense aparecem mais em faixas etárias altas.

## Próximos Passos

Caso métricas adicionais do Globoplay estivessem disponíveis, algumas perguntas poderiam ser investigadas:

- Quais gêneros e classificações etárias possuem maior engajamento?  
- Séries com múltiplos subgêneros atraem públicos mais diversificados?  
- Como o consumo varia entre regiões?  
- Qual é a popularidade de séries clássicas versus recentes?  

## Contribuições

Sinta-se à vontade para colaborar! Adicione análises, proponha melhorias ou faça sugestões para aprimorar este projeto.
