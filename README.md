[![Status do Projeto](https://img.shields.io/badge/Status-Concluído-success.svg)]()
[![Tecnologias](https://img.shields.io/badge/Stack-Python_%7C_Pandas_%7C_HTML/JS_%7C_AI-blue)]()

# Dashboard de Vendas — CHAPA

## 📌 Descrição do Projeto

Projeto de análise de dados desenvolvido com o objetivo de transformar os registros de vendas do **CHAPA**, uma hamburgueria, em informações estratégicas para o acompanhamento do desempenho comercial e o apoio à tomada de decisões.

O projeto contempla todas as etapas do processo analítico, desde a extração e organização das bases de dados até o tratamento, a consolidação e a utilização dos dados na criação de uma dashboard interativa com auxílio de Inteligência Artificial (Meta AI).

A solução foi desenvolvida a partir de dados reais de operação, abrangendo o período de **maio a setembro de 2026**, com foco na análise de vendas, produtos, faturamento com frete e evolução do ticket médio.

## 🎯 Objetivos

- Consolidar os dados de vendas provenientes de diferentes bases de extração.
- Organizar e tratar os dados para garantir maior consistência nas análises.
- Desenvolver uma dashboard interativa para acompanhamento dos principais indicadores comerciais.
- Facilitar a identificação de padrões de vendas, produtos com maior saída e variações de desempenho ao longo do tempo.
- Aplicar ferramentas de análise de dados e Inteligência Artificial na construção de uma solução voltada a uma necessidade real de negócio.

## 🛠️ Tecnologias e Ferramentas Utilizadas

- **Python:** processamento, concatenação e consolidação dos arquivos de dados.
- **Pandas:** manipulação, organização e tratamento das bases.
- **Microsoft Excel:** inspeção, filtragem, conferência e validação dos dados durante a preparação da base analítica.
- **Meta AI:** apoio à construção da dashboard por meio de um prompt estruturado com os requisitos funcionais e visuais do projeto.
- **HTML, CSS e JavaScript:** estruturação, estilização e implementação da interface e das funcionalidades da dashboard.
- **Git e GitHub:** versionamento e documentação do projeto.

## 🔄 Etapas do Projeto

### 1. Extração e filtragem da base de dados

Os dados de vendas foram extraídos de forma fracionada, sendo necessário realizar a filtragem das informações para delimitar o período de análise entre maio e setembro de 2026.

Essa etapa teve como finalidade selecionar os registros pertinentes ao projeto, considerando o intervalo temporal e as informações necessárias para a construção dos indicadores comerciais.

### 2. Consolidação dos arquivos com Python e Pandas

Como a base precisou ser baixada em partes, foi necessário utilizar **Python e Pandas para concatenar os arquivos extraídos**, reunindo os registros em uma única base de trabalho.

Esse procedimento permitiu centralizar as informações e preparar uma estrutura unificada para as etapas seguintes, evitando a necessidade de realizar as análises separadamente em cada arquivo.

### 3. Tratamento e validação dos dados com Excel e Python

Após a consolidação, foi realizada a preparação da base analítica utilizando Python, Pandas e Microsoft Excel.

O processo envolveu a organização dos registros, a filtragem das informações relevantes e a conferência da consistência dos dados, preparando a estrutura para utilização nos indicadores e componentes da dashboard.

O Excel também foi utilizado como ferramenta de apoio à inspeção e validação das informações, complementando o processamento realizado em Python.

Essa etapa foi fundamental para reduzir inconsistências e garantir que os dados utilizados na visualização estivessem alinhados ao objetivo da análise.

### 4. Definição dos indicadores e requisitos da dashboard

Com a base preparada, foram definidos os indicadores, filtros e funcionalidades necessários para atender às necessidades de acompanhamento das vendas.

Entre os requisitos estabelecidos, destacam-se:

- Filtro por período mensal, com seleção do mês inicial e final da análise.
- Filtro por origem dos pedidos: PDV, iFood e 99Food.
- Identificação dos cinco produtos mais vendidos.
- Apuração do valor total faturado com frete.
- Acompanhamento da evolução mensal do ticket médio.
- Exibição das informações de acordo com os filtros selecionados.

A definição desses requisitos orientou a construção do prompt utilizado na etapa de desenvolvimento da interface.

### 5. Engenharia de prompt e desenvolvimento com Meta AI

Com os indicadores e as regras de negócio definidos, foi elaborado um prompt estruturado para orientar a Meta AI na criação da dashboard.

O prompt reuniu as especificações funcionais, a lógica dos filtros, os indicadores desejados e as orientações de interface e experiência do usuário (UI/UX).

A partir dessas instruções, a Inteligência Artificial foi utilizada como apoio à geração da estrutura da dashboard em HTML, CSS e JavaScript, buscando transformar a base consolidada em uma interface interativa para exploração dos dados.

Essa etapa permitiu aplicar técnicas de engenharia de prompt em um contexto prático, demonstrando como requisitos de negócio bem definidos podem orientar o desenvolvimento de soluções analíticas com o auxílio de IA.

### 6. Organização e apresentação dos resultados

A etapa final consistiu na organização dos indicadores e dos recursos de filtragem em uma interface visual, com o objetivo de facilitar a consulta das informações e a análise do desempenho comercial.

A dashboard permite explorar os dados por período e origem dos pedidos, oferecendo uma visão mais estruturada dos resultados da operação.

## 📊 Indicadores e Análises

| Indicador | Objetivo |
|---|---|
| Top 5 produtos mais vendidos | Identificar os produtos com maior volume de vendas. |
| Faturamento com frete | Acompanhar o valor total associado às cobranças de frete. |
| Evolução do ticket médio | Analisar a variação mensal do valor médio por pedido. |
| Vendas por período | Comparar os resultados dentro do intervalo mensal selecionado. |
| Vendas por origem | Permitir a análise dos pedidos provenientes de PDV, iFood e 99Food. |

## 💡 Principais Aprendizados

O desenvolvimento deste projeto proporcionou a aplicação prática de conhecimentos de análise de dados em um cenário real de negócio, envolvendo diferentes etapas do ciclo analítico.

Entre os principais aprendizados, destacam-se:

- **ETL e preparação de dados:** organização, consolidação e tratamento de arquivos provenientes de extrações fracionadas.
- **Manipulação de dados com Python e Pandas:** concatenação de bases e preparação dos registros para análise.
- **Validação com Excel:** conferência e inspeção das informações durante o processo de tratamento.
- **Análise de indicadores de negócio:** definição de métricas relevantes para o acompanhamento de vendas.
- **Engenharia de prompt:** tradução de requisitos analíticos e funcionais em instruções estruturadas para uma ferramenta de IA.
- **Desenvolvimento de dashboards:** aplicação de HTML, CSS e JavaScript na construção de uma interface para visualização e exploração de dados.
- **Resolução de problemas reais:** utilização de ferramentas distintas para superar desafios de extração, consolidação e apresentação das informações.

## 🚀 Conclusão

Este projeto demonstra a aplicação integrada de ferramentas de análise de dados, desde a preparação da base até a construção de uma solução visual para acompanhamento de indicadores comerciais.

Mais do que desenvolver uma dashboard, o trabalho envolveu compreender uma necessidade de negócio, estruturar os dados, definir métricas relevantes e utilizar Python, Pandas, Excel e Inteligência Artificial para transformar registros operacionais em informações úteis para a tomada de decisões.

A experiência reforça a importância de um processo analítico bem estruturado, no qual a qualidade dos dados, a definição dos indicadores e a clareza dos requisitos são essenciais para a construção de soluções de Business Intelligence.

---
