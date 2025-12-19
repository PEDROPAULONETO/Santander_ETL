# Bootcamp Santander API - Pipeline ETL com IA Generativa

![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Gemini](https://img.shields.io/badge/Google%20AI-Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white)

## 📖 Sobre o Projeto

Este projeto foi desenvolvido como parte do desafio final do **Bootcamp Santander**. O objetivo foi construir um pipeline de dados **ETL (Extract, Transform, Load)** robusto, integrando uma API RESTful com Inteligência Artificial Generativa.

O sistema automatiza o processo de marketing bancário:
1.  **Extract:** Coleta dados de clientes (IDs) de uma API do Santander (Santander Dev Week).
2.  **Transform:** Utiliza a API do **Google Gemini** para gerar mensagens de marketing personalizadas e exclusivas para cada cliente, baseadas em seus dados financeiros.
3.  **Load:** Envia as mensagens geradas de volta para a API, atualizando o registro do cliente.

## 🛠️ Tecnologias e Ferramentas

*   **Python 3:** Linguagem base para o script de automação.
*   **Pandas:** Manipulação e análise de dados tabulares (ETL).
*   **Google Gemini API:** Integração com LLMs (Gemini) para geração de conteúdo.