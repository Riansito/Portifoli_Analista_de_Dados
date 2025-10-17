

# 📊 Portfólio de Análise de Dados — Rian Freires

Bem-vindo ao meu portfólio de projetos em **Análise de Dados**!
Aqui você encontrará estudos de caso reais envolvendo **SQL, Power BI, Python e Excel**, com foco em **organização de dados, criação de dashboards interativos e geração de insights estratégicos**.
Cada projeto demonstra minha capacidade de transformar dados brutos em decisões de negócio por meio de análises estatísticas, modelagem de métricas e visualizações eficientes.

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


