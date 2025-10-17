# FilmRegistry

Este repositório contém um conjunto de projetos de CRUD para cadastro e gerenciamento de filmes em Python. Ele foi desenvolvido com o objetivo de praticar **backend, manipulação de dados e integração com interfaces web**.

## Estrutura do Projeto

- **Múltiplos arquivos de CRUD**: 
  Cada arquivo é um CRUD independente que permite realizar operações de **inserção, leitura, atualização e exclusão (CRUD)** em um banco de dados SQLite.

- **CRUD principal com Streamlit**:  
  Existe um arquivo principal que integra todos os CRUDs utilizando **Streamlit**, criando uma interface web interativa e prática para gerenciar os filmes.  

## Tecnologias utilizadas

- Python 3.x
- SQLite
- Streamlit
- Pandas (para manipulação e exibição de dados, quando necessário)

## Funcionalidades

- Inserção de novos filmes no banco de dados
- Consulta de filmes cadastrados
- Atualização de informações de filmes
- Exclusão de filmes
- Interface web interativa para gerenciar os filmes via Streamlit

## Como executar

1. Clone o repositório:

```bash
git clone https://github.com/seuusuario/FilmRegistry.git


Instale as dependências:

pip install -r requirements.txt


Execute o CRUD principal com Streamlit:

streamlit run crud_principal.py
