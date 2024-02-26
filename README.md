### Formulario Flask MySQL

##### Sistema de envio de formulários HTML usando Flask, Python e MySQL. Ele fornece uma solução abrangente para gerenciamento eficiente dos dados inseridos em formulários, garantindo uma conexão perfeita entre frontend e backend usando Flask.

#### PASSO 1 - Criar o ambiente virtual
	apt install python3.11-venv
	python3 -m venv env

#### PASSO 2 - Ative o ambiente virtual executando;
	source env/bin/activate
 
#### PASSO 3 - Dentro do ambiente virtual instalar o python e flask
	sudo apt install python3  
   	pip install flask

#### PASSO 4 - Instalar o conector Python MySQL, é uma biblioteca (Driver) para conectar Python com MySQL
	 pip install mysql-connector-python

#### PASSO 5 - Listar todos os meus pacotes
	 pip list  o pip freeze

#### PASSO 6 - Crie/atualize o arquivo requirements.txt:
	 pip freeze > requirements.txt

#### IMPORTANTE - para executar o projeto basta executar o arquivo requirements.txt para instalar as dependências do projeto.
pip install -r requirements.txt

#### Comando para atualizar o pip:
python -m pip install --upgrade pip

#### PASSO 7 - executar o projeto
python3 app/main.py

#### Para desativar o ambiente virtual:
(env)$ deactivate
