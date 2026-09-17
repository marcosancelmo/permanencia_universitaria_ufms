# Permanência Universitária em Foco: Diagnóstico da Evasão nos Cursos da UFMS

Este repositório contém o projeto de extensão desenvolvido para a disciplina de Análise Organizacional e Soluções Tecnológicas, vinculado ao Programa de Extensão UFMS Digital (95DX7.200525)[cite: 1].

## 📌 Resumo do Projeto
Este trabalho aborda a evasão estudantil no ensino superior por meio da análise quantitativa de dados educacionais. O objetivo é investigar o comportamento temporal das taxas de abandono na Universidade Federal de Mato Grosso do Sul (UFMS), identificando cursos críticos e tendências de crescimento a partir da base do Portal de Dados Abertos da instituição. 

A iniciativa busca transformar dados abertos em diagnósticos objetivos, fornecendo indicadores visuais para subsidiar políticas públicas institucionais de retenção e orientar ações preventivas.

## 🎯 Objetivos
* **Objetivo Geral:** Investigar o comportamento histórico e as tendências de evasão estudantil nos cursos de graduação da UFMS, utilizando técnicas de análise exploratória de dados para subsidiar ações de permanência discente.
* **Objetivos Específicos:**
  * Coletar e estruturar os microdados educacionais das bases históricas de matrículas e desligamentos.
  * Mapear taxas de evasão ao longo do tempo e identificar padrões em cursos e unidades acadêmicas.
  * Elaborar diagnósticos e dashboards para suporte a coordenações de curso e gestores universitários.

## 🛠️ Ferramentas e Tecnologias Utilizadas
* **Linguagem de Programação:** Python 3 (Anaconda / Google Colab)
* **Bibliotecas Analíticas:** `pandas`, `numpy`, `matplotlib`, `seaborn`
* **Visualização de Dados (BI):** Microsoft Power BI Desktop ou Google Looker Studio
* **Apoio e Validação:** Microsoft Excel

## 🗂️ Metodologia e Etapas
O projeto está estruturado em 4 grandes etapas:

1. **Coleta de Dados:** Download de arquivos CSV referentes à "Graduação - Alunos da UFMS" no Portal de Dados Abertos ou via API CKAN.
2. **Tratamento e Estruturação:** Limpeza da base bruta com tratamento de valores nulos, normalização de nomenclaturas, remoção de duplicidades e descarte de atributos irrelevantes usando Python.
3. **Análise Exploratória:** Cálculo de taxas de desligamento e validação estatística da hipótese temporal, avaliando picos de abandono, especialmente em cursos de Ciências Exatas e Tecnológicas.
4. **Dashboard e Comunidade:** Modelagem de dados e construção de um painel interativo dinâmico, seguido de uma apresentação presencial/virtual para acadêmicos e gestores debaterem os achados e proporem ações de acolhimento.

## 📊 Fonte de Dados
Os dados analisados neste repositório são públicos e provenientes do [Portal de Dados Abertos da UFMS](https://dadosabertos.ufms.br/dataset/graduacao-alunos).

## 👨‍💻 Autor
* **Nome:** Marcos Ancelmo
* **Formação:** 4º Semestre de Ciência de Dados