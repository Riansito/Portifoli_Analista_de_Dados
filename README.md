

# 📊 Portfólio de Análise de Dados — Rian Freires

Bem-vindo ao meu portfólio de projetos em **Análise de Dados**!
Aqui você encontrará estudos de caso reais envolvendo **SQL, Power BI, Python, Excel/Google Sheets**, com foco em **organização de dados, criação de dashboards interativos e geração de insights estratégicos**.
Cada projeto demonstra minha capacidade de transformar dados brutos em decisões de negócio por meio de análises estatísticas, modelagem de métricas e visualizações eficientes.

_Observação: A seção de resultados apresenta apenas um recorte dos principais achados. Para acessar todos os insights, análises detalhadas e recomendações de ações, basta clicar no link, que direciona para o projeto completo._

---

## 📁 Projetos

---

### 🏢 **Estudo de Caso — Projeto de Dados Empresariais (SQL + Power BI)**

Este projeto simula um cenário real de negócio, no qual diferentes áreas da empresa precisavam de respostas analíticas para apoiar decisões estratégicas.
As solicitações vinham de áreas como **CFO, Marketing e Pricing**, exigindo integração e tratamento consistente dos dados antes da construção dos dashboards.

🔍 **Objetivos principais:**

* Consolidar dados brutos em um banco SQL e organizar em camadas utilizando a arquitetura Medalhão (Bronze → Silver → Golden).
* Criar visões otimizadas para responder às principais perguntas de negócio.
* Desenvolver dashboards dinâmicos e interativos no Power BI com métricas DAX.

⚙️ **Principais etapas:**

* **Subida dos dados via Python:** automação do carregamento dos arquivos para o banco SQL.
* **Camadas Bronze, Silver e Golden:** limpeza, transformação e modelagem relacional das tabelas.
* **Consultas SQL:** criação de visões para cálculo de receita média, ranking de entregadores e distribuição de distâncias.
* **Dashboard no Power BI:** páginas temáticas para CFO, Marketing e Pricing, com medidas em DAX e segmentações dinâmicas.

📈 **Resultados:**

* Dashboard interativo permitindo análise detalhada da **receita média e total por tipo de loja e estado**.
* Ranking automático dos **20 entregadores com maior distância percorrida**.
* Visualização da **distribuição da distância média por estado**, facilitando a análise de performance logística.

🔗 [Ver projeto (Power BI + SQL)](https://github.com/Riansito/Case_Delivery_Center)

---

### 🚴 **Análise de Demanda de Bicicletas Elétricas — Yulu (Python + Excel)**
Projeto voltado para identificar os fatores que influenciam a demanda por bicicletas elétricas da empresa Yulu, analisando dados de clima, sazonalidade e comportamento temporal. A empresa enfrentava uma queda no número de aluguéis e buscava compreender quais variáveis impactavam normalmente a utilização das bicicletas, a fim de traçar estratégias eficazes para impulsionar a demanda e otimizar o uso da frota.

🔍 **Objetivos principais:**

* Descobrir os principais fatores que impactam a demanda diária de bicicletas.
* Aplicar análises estatísticas e inferências para validar hipóteses.
* Criar um dashboard de acompanhamento no Excel.

⚙️ **Principais etapas:**

* **Feature Engineering:** criação de variáveis temporais e codificação de clima e estação do ano.
* **Análise Exploratória (EDA):** análises univariadas, bivariadas e temporais com gráficos e estatísticas descritivas.
* **Análise Estatística e Inferencial:**

  * Probabilidade condicional para medir impacto de clima e sazonalidade.
  * Testes de Kruskal-Wallis e inferência causal com DoWhy.
* **Dashboard Excel:** visualização da demanda por hora, estação e condição climática.

📈 **Resultados:**

* Identificação de padrões sazonais e horários de pico (7h–20h).
* Comprovação de que **estações quentes e dias de clima limpo** aumentam significativamente a demanda.
* Recomendações estratégicas para **planejar a frota e campanhas de incentivo**.

🔗 [Ver projeto (Python + Excel)](https://github.com/Riansito/Analise-de-Uso-Das-Bicicletas-Da-YULU)

---

### 📊 **Estudo de Caso — Análise de Vendas Mundiais(Projeto BI) (SQL + Power BI)**

Este projeto simula um cenário real de uma empresa de comércio internacional, que precisava entender o desempenho financeiro, comportamento de clientes e performance regional para apoiar decisões estratégicas.

🔍 **Objetivos principais:**

* Analisar receita, custos, lucratividade, comportamento de clientes e performance regional.
* Aplicar lógica analítica e SQL avançado para extrair insights estratégicos a partir de dados brutos.
* Desenvolver um dashboard interativo no Power BI para visualização intuitiva das métricas.

⚙️ **Principais etapas:**

* **Consultas SQL em PostgreSQL:** utilização de SELECT, WHERE, GROUP BY, HAVING, CASE WHEN, CTEs e Window Functions (OVER, PARTITION BY, RANK, AVG, SUM) para cálculo de crescimento, médias móveis e ranking de vendas.
* **Análise por dimensões estratégicas:**

  * **Produtos:** faturamento, custo, lucro e margem por categoria, subcategoria e produto; identificação de produtos com alto volume/baixa margem e baixo volume/alta margem.
  * **Clientes:** comportamento por faixa etária e gênero, ticket médio, categorias mais compradas.
  * **Regional:** comparação entre países, estados e regiões; ranking de lucratividade e mapas interativos.
* **Dashboard no Power BI:** integração das consultas SQL em visualizações executivas e interativas, conectando análise técnica a insights estratégicos.

📈 **Resultados:**

* Identificação das principais fontes de lucro por produto, categoria, região e perfil de cliente.
* Ranking de desempenho regional, com análise detalhada de faturamento, margem e lucro médio por estado e país.
* Dashboard interativo facilitando a visualização de oportunidades de melhoria e tomada de decisão baseada em dados com Indicadores e KPI's estratégicos.


🔗 [Ver projeto (Power BI + SQL)](https://github.com/Riansito/Analise_Vendas_Globais)

---

### 🚗 **Regressão/Cluster — Precificação de Carros Usados**

O objetivo deste projeto é construir um modelo capaz de prever o preço de carros usados com base em características como ano, quilometragem, avaliações de motoristas, tipo de combustível, transmissão, tração e clusters de veículos.

🔍 **Objetivos principais:**

* Prever o preço estimado de carros usados com boa precisão.
* Entender o impacto de características do veículo e do mercado no preço.
* Oferecer insights sobre segmentação de veículos para suporte a decisões de compra, venda e marketing.

⚙️ **Principais etapas:**

* **Limpeza e preparação de dados:** tratamento de valores faltantes, outliers, codificação de variáveis categóricas.
* **EDA e visualizações:** análise detalhada de preços, quilometragem, ano e avaliações, utilizando gráficos como boxplots, histogramas e heatmaps.
* **Clusterização de veículos:** uso de K-Means para criar clusters como Carros Premium, Carros Custo-Benefício, Carros Luxos e Carros Populares. Os clusters foram usados também como **variáveis explicativas na regressão**, ajudando o modelo a capturar perfis de veículos.
* **Modelos utilizados:** Decision Tree Regressor, Random Forest, XGBoost, LGBM.
* **Ajuste de Hiperparâmetros:** RandomizedSearchCV para otimização de cada modelo, melhorando métricas como RMSE, MAE e R².
* **Métricas:** avaliação com R², RMSE, MAE e MSE para comparar performance dos modelos.
* **Insights:** veículos mais recentes e com baixa quilometragem são consistentemente mais caros; clusters ajudam a diferenciar perfis de mercado e melhoram a previsão do preço.

🔗 [Ver projeto](https://github.com/Riansito/Precificacao_Carros_ML.git)

---

### 📉 **Estudo de Caso — Análise de Churn (Excel + Python + Power Pivot)**

Este projeto simula um cenário real de uma **empresa de telecomunicações** que buscava compreender os **motivos de cancelamento de clientes (churn)**, identificando os **produtos, planos e comportamentos** que mais influenciam na perda de clientes e na rentabilidade.

🔍 **Objetivos principais:**

* Analisar os padrões de churn e o impacto sobre receita e desempenho.
* Identificar os produtos e planos com maiores taxas de cancelamento.
* Modelar e integrar os dados para análises dinâmicas e visuais no Excel (Power Pivot).

⚙️ **Principais etapas (Processo ETL):**

* **Extração dos dados:** coleta de informações de clientes, planos, dispositivos, receitas e status de cancelamento.
* **Transformação dos dados:** limpeza, tradução e padronização com **Python (Pandas)**; criação de IDs únicos e separação em **tabelas fato e dimensão** (modelo estrela).
* **Carga e análise:** integração no **Excel com Power Pivot**, criação de relacionamentos, **tabelas dinâmicas, gráficos e medidas DAX**.

📈 **Resultados:**

* Identificação dos **produtos e planos com maior taxa de churn**.
* Análise dos **principais motivos de cancelamento e seu impacto financeiro**.
* Compreensão do **perfil de clientes mais propensos a cancelar**.
* Apoio à **tomada de decisão estratégica**, auxiliando na criação de ações para **redução do churn e aumento da retenção de clientes**.

🔗 [Ver projeto (Excel + Python + Power Pivot)](https://github.com/Riansito/Analise_Churn_Telecomunicacoes)

---

### 🎬 **Projeto de Análise de Filmes com ETL, SQL e Dashboard Interativo**

Este projeto apresenta um cenário real de análise de dados, envolvendo todo o processo de **ETL (Extração, Transformação e Carga)**, armazenamento em **banco de dados SQL** e construção de um **dashboard interativo** para visualização dos principais insights sobre os filmes mais populares e bem avaliados da base do **TMDB (The Movie Database)**.

A análise busca compreender **padrões de popularidade**, **desempenho por gênero** e **tendências temporais**, fornecendo informações estratégicas que auxiliam plataformas de streaming na tomada de decisões sobre **curadoria de conteúdo** e **marketing**.

🔍 **Objetivos principais:**

* Extrair, transformar e carregar dados da API do TMDB para um banco de dados PostgreSQL.
* Limpar, padronizar e modelar os dados em camadas organizadas.
* Realizar consultas SQL para responder perguntas de negócio sobre popularidade e desempenho dos gêneros.
* Criar um dashboard interativo para análise visual e dinâmica dos resultados obtidos.

⚙️ **Principais etapas:**

**ETL — Extração, Transformação e Carga:**

* Coleta dos dados diretamente da API do TMDB, abrangendo diferentes gêneros cinematográficos.
* Limpeza de valores nulos, ajuste de datas, arredondamento de notas de avaliação e formatação dos links de pôsteres.
* Carga dos dados tratados para um banco de dados **PostgreSQL em nuvem**, garantindo performance e integração com ferramentas analíticas.

**EDA — Análise Exploratória de Dados (SQL):**

* Identificação dos **Top 3 filmes mais populares**.
* Análise dos **gêneros com maior popularidade e avaliação média**.
* Estudo da **popularidade dos filmes ao longo dos anos**, verificando se produções recentes possuem mais destaque.
* Criação de visões SQL para alimentar diretamente o dashboard interativo.

**Dashboard Interativo (Power BI / Plotly Dash):**

* Página com os **Top 3 filmes mais populares**.
* Visualizações de **gêneros mais populares** e **melhores avaliações médias**.
* Gráfico de **popularidade por ano de lançamento**.
* **Filtros dinâmicos** por gênero, ano e idioma original, permitindo análises personalizadas.

📈 **Resultados:**

* Dashboard interativo com análise detalhada da **popularidade e desempenho por gênero**.
* Identificação dos **gêneros com maior engajamento** e **melhores avaliações médias**.
* Visualização da **evolução da popularidade dos filmes ao longo dos anos**, revelando tendências de interesse.
* Base estruturada e atualizável, possibilitando **atualizações automáticas** e **insights em tempo real**.

🔗 [Ver projeto](https://github.com/Riansito/Analise_de_Filmes_com_Dados_da_TMDb-_Do_ETL_ao_Dashboard_Interativo)

---

### 🚨 **Estudo de Caso — Análise de Criminalidade Urbana (SQL + Análise Exploratória)**

Este projeto analisa dados reais de ocorrências criminais em Boston com o objetivo de identificar **padrões temporais, espaciais e por tipo de crime**, apoiando decisões estratégicas para ações preventivas e melhor alocação de recursos na segurança pública.

🔍 **Objetivos principais:**

* Identificar sazonalidade e horários críticos de criminalidade.
* Mapear os tipos de crimes mais recorrentes.
* Detectar concentração espacial das ocorrências em vias específicas.
* Apoiar ações orientadas por dados para redução de crimes.

⚙️ **Principais etapas:**

* **Análise em SQL (Google BigQuery):** agregações temporais, análise por hora do dia, crimes mais frequentes e uso de CTEs para segmentação dos dados.
* **Exploração espacial:** identificação das ruas com maior concentração de ocorrências.
* **Visualização dos dados:** criação de gráficos a partir de tabelas dinâmicas e análises pivot para facilitar a interpretação no google sheets.
* **Storytelling:** organização dos insights em uma narrativa visual clara e objetiva.

📈 **Resultados:**

* Identificação de **sazonalidade clara**, com aumento de crimes entre **junho e agosto**.
* Horários entre **10h e 20h** apresentam registros acima da média tendo um pico de crime das 16h às 18h.
* Crimes se concentram em poucas vias, com destaque para a **Washington St**.
* Evidência de que ações direcionadas podem reduzir ocorrências em **10% a 20%**.

🔗 [Ver Projeto](https://github.com/Riansito/Analise_Criminalidade_Boston)

---


## ⚙️ Tecnologias e Ferramentas

* **Linguagens:** SQL, Python
* **Bibliotecas Python:** Pandas, NumPy, Matplotlib, Seaborn, SciPy, DoWhy
* **Visualização e BI:** Power BI (com DAX), Excel, Google Sheets
* **Técnicas:** EDA, Inferência Estatística, Testes de Hipóteses, Criação de Métricas em DAX, Automação VBA
* **Banco de Dados:** MySQL, Postgres
* **Outros:** Git, GitHub, ETL, Arquitetura Medalhão, Dashboards Interativos

---

## 🌐 Contato

* 📧 Email: [rianfreires40@gmail.com](mailto:rianfreires40@gmail.com)
* 🔗 LinkedIn: [linkedin.com/in/rianfreires](https://www.linkedin.com/in/rian-freires-da-costa-silva-798813324)
* 📊 [Portfólio Power BI](https://sites.google.com/view/portifliorianpowerbi/in%C3%ADcio)
* 📃 [Portfólio Excel](https://sites.google.com/view/portiflioexcelrian/in%C3%ADcio)
* 💻 [GitHub](https://github.com/Riansito)

---

> *“Transformando dados em informação e informação em ação.”* 🚀

---


