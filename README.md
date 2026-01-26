# 🏘️ Organização de Dados por Bairro

Este projeto automatiza a organização de dados em planilhas Excel, separando informações de pessoas por **bairro**.  
A partir de uma aba chamada **"Base de Dados"**, o script percorre todas as linhas e distribui os registros em novas abas correspondentes a cada bairro encontrado.

## 🚀 Funcionalidades
- Criação automática de abas para cada bairro.
- Copia os dados de **Data de Nascimento**, **Pessoa** e **Bairro** para a aba correspondente.
- Mantém o estilo do cabeçalho original.
- Gera um novo arquivo Excel com os dados organizados.

## 🛠️ Tecnologias Utilizadas
- [Python 3](https://www.python.org/)
- [openpyxl](https://openpyxl.readthedocs.io/en/stable/) → manipulação de arquivos Excel.
- Biblioteca `copy` para replicar estilos de células.

## 📂 Estrutura do Projeto


## 📋 Exemplo de Uso
1. Coloque os dados na aba **Base de Dados** do arquivo `Bairros.xlsx` com as colunas:
   - Data de Nascimento  
   - Pessoa  
   - Bairro  

2. Execute o script:
   ```bash
   python desafio_bairros.py

📁 Bot_excel
├── 📄 README.md                 # Documentação do projeto
├── 📄 desafio_bairros.py         # Código principal em Python
├── 📊 Bairros.xlsx               # Base de dados original (entrada)
└── 📊 Bairros_organizados.xlsx   # Arquivo gerado com abas organizadas (saída)
   