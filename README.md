# Portfólio - Andressa

<div align="center">
      
![](/src/static/IMGS/LOGO.png)
      
</div>

## Projeto Portifólio Design Digital 

**Descrição das Pastas:**
* src: Pasta com os códigos
* doc: Pasta com Documentação relacionada ao Projeto, na qual se encontra as wireframes


## Executando o projeto

### Primeiro Instale o [Python](https://www.python.org/downloads/)

Depois de baixar o python e clonar o projeto (ou baixá-lo) pelo link https://github.com/Andressafatec/Portf-lio---Andressa.git:

``` powershell
# Acesse a pasta do projeto por meio do terminal
cd  Portf-lio---Andressa

# Acessar o ambiente virtual 
venv\Scripts\activate

# Instale as dependências
pip install -r requirements.txt

# Acesse a pasta de código do projeto
cd src
      
# Habilitar recurso de desenvolvimento
set FLASK_APP=app.py

# Executar a aplicação
flask run
