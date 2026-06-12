# projeto-bd-dados-suicidios
Trabalho aula dia 11_06_2026 - Banco de Dados


# Projeto de Banco de Dados: Análise de Mortalidade (2010-2019)

Este repositório contém a modelagem, os scripts de definição (DDL) e manipulação (DML), além das consultas (Views) referentes ao projeto de banco de dados baseado no dataset de suicídios no Brasil (2010 a 2019) disponibilizado no Kaggle pelo DATASUS.

Projeto desenvolvido como requisito para a **UC 15 - Administração de Sistemas de Banco de Dados** do 3º semestre do curso de **Análise e Desenvolvimento de Sistemas (ADS) - SENAC MS**.

# Estrutura do Projeto

O objetivo do projeto foi transformar dados brutos (CSV) em um modelo relacional normalizado. O banco de dados final (`db_suicidios`) é composto por:
* **Tabelas de Domínio:** `Estados`, `Estado_civil`, `Escolaridade`, `Causas`.
* **Tabela Fato:** `Suicidios` (com chaves estrangeiras vinculando as tabelas de domínio).
* **Views:** 7 consultas específicas para geração de relatórios e painéis analíticos.

# Como rodar o projeto

Para executar este projeto na sua máquina, você precisará do [MySQL](https://dev.mysql.com/downloads/installer/) e de um cliente SQL (como MySQL Workbench, DBeaver ou a própria extensão de banco do VS Code).

1. **Clone este repositório:**
   ```bash
   git clone [https://github.com/SEU-USUARIO/projeto-bd-dados-suicidios.git](https://github.com/SEU-USUARIO/projeto-bd-dados-suicidios.git)
