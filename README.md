# 🚀 API SpaceX

A motivação aqui foi fazer uma análise simples para praticar engenharia de dados, mas por um caminho um pouco diferente do outro trabalho.

## 🌐 Endpoints

Nesse caso, busquei as tabelas separadamente em seus endpoints e fiz a transformação em uma OBT dentro do Databricks.  

Os endpoints utilizados foram:

- `https://api.spacexdata.com/v4/rockets` → informações sobre os foguetes  
- `https://api.spacexdata.com/v4/launches` → informações sobre os lançamentos  
- `https://api.spacexdata.com/v4/capsules` → informações sobre as cápsulas  

📌 **Retorno:** algumas informações pertinentes para a análise, como dados de foguetes, lançamentos e cápsulas.

## 📂 Escolha dos Formatos

- **JSON** → utilizado para salvar os dados brutos da API (diferente do projeto anterior, que foi feito em CSV).  
- **Parquet** → utilizado para os dados tratados no Databricks, pela sua versatilidade e ampla compatibilidade com ferramentas de análise.

## ⚙️ Requisitos

Certifique-se de ter os seguintes itens instalados/configurados:

- [Python](https://www.python.org/downloads/)  
- [Jupyter Notebook](https://jupyter.org)  
- [Conta no Databricks Community](https://community.cloud.databricks.com/login.html)
