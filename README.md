# 📊 Gerador de Dados Fictícios com Python (Faker e Pandas)

Este projeto demonstra a criação e manipulação de um conjunto de dados fictícios em grande escala usando as bibliotecas **Faker** e **Pandas** em Python.

Os dados gerados são ideais para testes de software, prototipagem, demonstrações ou para popular rapidamente um banco de dados de desenvolvimento.

---

## 🚀 Tecnologias Utilizadas

* **Python**: Linguagem de programação principal.
* **Faker**: Biblioteca para gerar dados fictícios (nomes, endereços, e-mails, datas de nascimento, etc.).
* **Pandas**: Biblioteca para manipulação e análise de dados, utilizada para estruturar os dados gerados em um `DataFrame`.
* **Exportação CSV e Formatação Excel**: O resultado final é exportado para um arquivo CSV e posteriormente formatado no Excel para visualização e ajustes básicos.

## ✨ Funcionalidades Principais

* **Geração de Dados Realistas**: Cria **100 registros** de dados pessoais e profissionais, incluindo as seguintes colunas:
    * `NOME` (Nome Completo)
    * `EMPRESA` (Nome da Companhia)
    * `CIDADE` (Cidade)
    * `PAIS` (País)
    * `CARGO` (Cargo Profissional)
    * `ENDEREÇO` (Endereço Completo)
    * `EMAIL` (Endereço de E-mail)
    * `DATA_NASCIMENTO` (Data de Nascimento)
* **Estruturação em DataFrame**: Organiza todos os dados gerados em uma estrutura `DataFrame` do Pandas para fácil manipulação.
* **Exportação para CSV**: Salva o conjunto de dados em um arquivo `.csv` para portabilidade.
* **Formatação Básica**: Demonstra um fluxo de trabalho onde os dados são ajustados externamente (no Excel) para refinamento final.
