# Projeto Gemini Notebook: Formação em Análise de Dados

Repositório de estudos estruturado para capacitação no ciclo de vida completo de **Análise e Ciência de Dados**, integrando fundamentos teóricos, metodologias de mercado, plataformas em nuvem e comunicação estratégica.

---

## 📌 Tema e Objetivo

* **Tema:** Este notebook aborda a **Formação Completa em Análise e Ciência de Dados**, reunindo conteúdos sobre:
  * **Programação e Consultas:** Fundamentos da linguagem Python e consultas relacionais em SQL/T-SQL.
  * **Tratamento e Preparação de Dados:** Métodos de limpeza, diagnóstico e imputação de dados ausentes (*missing data*), remoção de ruídos e seleção de atributos.
  * **Plataformas e Engenharia em Nuvem:** Arquiteturas analíticas e ferramentas modernas como Microsoft Azure, Microsoft Fabric e Databricks.
  * **Visualização, IA e Storytelling:** Construção de relatórios e dashboards interativos no Power BI, aplicação de recursos de Inteligência Artificial/Copilot e técnicas de *Data Storytelling* para apresentações executivas.

* **Objetivo:** Capacitar o profissional no ciclo de vida analítico de ponta a ponta. O material estrutura o aprendizado desde a ingestão, limpeza, modelagem dimensional e governança de dados brutos até a entrega de relatórios visuais e *insights* acionáveis para apoiar decisões estratégicas de negócios.

---

## 🔬 Referências e Confiabilidade Técnica

O material foi construído a partir de fontes verificadas e complementares:

### 1. Documentações Oficiais de Tecnologias e Nuvem
* **Fontes:** Documentação oficial da *Python Software Foundation* e trilhas oficiais do *Microsoft Learn* (Azure, Microsoft Fabric, Power BI, T-SQL, DAX e Copilot).
* **Fundamentação:** Desenvolvidas diretamente pelos criadores e mantenedores das ferramentas, garantindo conformidade com arquiteturas recomendadas, padrões de segurança e sintaxes oficiais.

### 2. Publicações Científicas e Literatura Acadêmica
* **Fontes:** Artigos de repositórios acadêmicos (como *arXiv*, incluindo estudos da *Deakin University*) e referências estatísticas formais (*Bookdown*, *R-bloggers*).
* **Fundamentação:** Rigor matemático e validação por pares para o diagnóstico e tratamento de dados ausentes sem introdução de viés analítico.

### 3. Frameworks de Processo e Padrões da Indústria
* **Fontes:** Guias metodológicos consolidados (*CRISP-DM*, *SEMMA*, *TDSP da Microsoft*, *OSEMN*), manuais técnicos de corporações como *IBM* e *Snowflake*, além de diretrizes do *NIST* (*National Institute of Standards and Technology*).
* **Fundamentação:** Padrões operacionais que asseguram reprodutibilidade, governança e prevenção de armadilhas críticas em ambientes produtivos (ex.: *data leakage*).

### 4. Obras de Data Storytelling e Comunicação Executiva
* **Fontes:** Obras de Cole Nussbaumer Knaflic (*Storytelling with Data*), Barbara Minto (*O Princípio da Pirâmide*) e estudos aplicados de psicologia cognitiva e percepção visual.
* **Fundamentação:** Princípios de comunicação técnica eficiente voltados à redução de carga cognitiva e orientação clara para tomada de decisão.

### 5. Cursos e Plataformas Especializadas
* **Fontes:** Trilhas e formações de instituições como *Coursera*, *freeCodeCamp* e especialistas da área de dados.
* **Fundamentação:** Conteúdo focado na prática de mercado e resolução de problemas analíticos reais.

---

## 📌 Perguntas Realizadas, Respostas e Fontes Utilizadas

### Pergunta
Quais os principais tópicos da análise de dados?

### Resposta
Os principais tópicos da análise de dados abrangem todo o ciclo de vida da informação, desde a sua captura até a comunicação estratégica dos resultados:

1. **Ingestão e Coleta de Dados:**
   - Extração de dados de fontes relacionais e não relacionais utilizando linguagens de consulta como SQL.
   - Ingestão contínua em lote (*batch*) e em tempo real (*streaming*) para repositórios como *Data Lakes*, *Data Warehouses* e *Lakehouses*.

2. **Limpeza e Pré-processamento (*Data Cleaning*):**
   - Tratamento de ruídos, inconsistências e formatação dos dados brutos.
   - Diagnóstico e tratamento de dados ausentes (*missing data*), avaliando seus mecanismos estatísticos (MCAR, MAR, MNAR) e aplicando técnicas de imputação.
   - Identificação e tratamento de valores discrepantes (*outliers*).

3. **Análise Exploratória de Dados (EDA) e Estatística:**
   - Aplicação de estatística descritiva, verificação de distribuições e análise de correlações entre variáveis.
   - Seleção e engenharia de atributos (*feature selection* e *feature engineering*) para identificar as variáveis mais informativas e evitar o sobreajuste (*overfitting*).

4. **Programação, Modelagem e Métricas:**
   - Uso de linguagens essenciais como **Python** (para manipulação e tratamento de dados) e **SQL** (para extração e gerenciamento).
   - Modelagem de dados dimensional organizando informações em tabelas Fato e Dimensão.
   - Construção de fórmulas e métricas de negócios com **DAX** no Power BI.

5. **Visualização de Dados e Design de Dashboards:**
   - Construção de relatórios visuais e interativos.
   - Escolha do visual correto para cada tipo de análise (como gráficos de linhas para evolução temporal e gráficos de barras para *rankings*).
   - Aplicação de boas práticas de diagramação e usabilidade, como o padrão de leitura em Z.

6. **Data Storytelling e Comunicação Executiva:**
   - Tradução de análises técnicas em narrativas de negócios direcionadas à tomada de decisão.
   - Estruturação de apresentações usando frameworks consagrados como **SCQA** (Situação, Complicação, Questão, Resposta), a **Pirâmide de Minto** e a estrutura **"O Que? E Daí? E Agora?"**.

7. **Metodologias de Projetos e Governança:**
   - Adição de processos estruturados e iterativos como **CRISP-DM**, **SEMMA** e **TDSP**.
   - Aplicação de regras de governança, segurança, privacidade de dados (como a LGPD) e monitoramento operacional (*DataOps* e *MLOps*).

---

### Fontes Consultadas

Para sintetizar os principais tópicos do ciclo de vida da análise de dados, foram consultadas diferentes fontes do notebook categorizadas por temas específicos:

#### 1. Metodologias, Ciclos de Vida e Governança
- **Documento em Markdown:** *Metodologias, Governança e Arquiteturas para Análise de Dados Corporativa*
- **Guias de Processos:** *What is CRISP DM?*, *What is SEMMA?* e *Data Science Methodologies and Frameworks Guide*
- **Vídeo:** *Ciência de dados do zero: fundamentos em uma aula*

#### 2. Limpeza e Tratamento de Dados Ausentes (*Missing Data*)
- **Artigos Acadêmicos:** *A Comprehensive Review of Handling Missing Data: Exploring Special Missing Mechanisms* e *A Practical Guide to Modern Imputation*
- **Guias de Análise:** *Chapter 17 Imputation (Missing Data) | A Guide on Data Analysis* e *Handling Missing Data in R: A Comprehensive Guide*

#### 3. Engenharia e Seleção de Atributos (*Feature Selection*)
- **Artigos Técnicos:** *An Introduction to Feature Selection* (MachineLearningMastery.com), *Feature Engineering: The Decisions That Shape ML Model Quality* (Snowflake) e *What is Feature Selection?* (IBM / Articsledge)
- **Plataformas de Aprendizado:** *What is Feature Engineering? Methods, Tools and Best Practices* (Great Learning)

#### 4. Plataformas de Nuvem, SQL e Ingestão de Dados
- **Microsoft Learn:** Roteiros de aprendizagem oficiais como *Comece a usar o Microsoft Fabric*, *Implementar um data warehouse*, *Implementar uma solução com Azure Databricks* e *Introdução aos conceitos de dados do Azure*
- **Vídeo de SQL:** *O que você precisa saber para começar a fazer consultas com SQL?*

#### 5. Visualização de Dados, Dashboards e Data Storytelling
- **Microsoft Learn (Power BI):** *Criar relatórios eficazes no Power BI*, *Dados de modelo com o Power BI* e *Usar DAX em modelos semânticos*
- **Guias de Comunicação Executiva:** *Master Data Storytelling with AI* (Radiant Institute)
- **Vídeos Práticos:** Aulas de Power BI e design de dashboards (Hashtag Treinamentos e Thon Silva)

#### 6. Linguagens de Programação
- **Python:** Cursos práticos como *[CURSO DE PYTHON FREE] Python para análise de dados* e os guias formais da documentação da linguagem.

---

## 🔗 Acesso ao Notebook e Recursos

Acesse o material de estudo e os artefatos nos links abaixo:

* 📓 **Notebook Principal:** [Notebook do Projeto no Google NotebookLM](https://notebook.google.com/notebook/0ef546b5-a56c-42da-b07b-000308383915)
* 🧠 **Mapa Mental:** [Visualizar Mapa Mental](https://notebook.google.com/notebook/0ef546b5-a56c-42da-b07b-000308383915/artifact/0a27c944-8e77-4045-9773-64f7b077a794?utm_source=nlm_web_share&utm_medium=google_oo&utm_campaign=art_share_1&utm_content=&utm_smc=nlm_web_share_google_oo_art_share_1_)
* 📖 **Guia de Estudos:** [Acessar Guia de Estudos](https://notebook.google.com/notebook/0ef546b5-a56c-42da-b07b-000308383915/artifact/21183ebd-fbed-4900-9d9b-759494506cc0?utm_source=nlm_web_share&utm_medium=google_oo&utm_campaign=art_share_1&utm_content=&utm_smc=nlm_web_share_google_oo_art_share_1_)
* 🎥 **Material Multimídia / Vídeo:** [Assistir ao Conteúdo](https://notebook.google.com/notebook/0ef546b5-a56c-42da-b07b-000308383915/artifact/1329b151-5d9e-4da2-baed-16131c09bebe?utm_source=nlm_web_share&utm_medium=google_oo&utm_campaign=art_share_1&utm_content=&utm_smc=nlm_web_share_google_oo_art_share_1_)
* 🖼️ **Foto 1:** [Visualizar Imagem](assets/Captura%20de%20tela%20de%202026-10-02%2020-53-24.png)
* 🖼️ **Foto 2:** [Visualizar Imagem](assets/Captura%20de%20tela%20de%202026-10-02%2021-51-54.png)
