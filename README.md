# TCC-ROBERTO-WEB

Sistema WEB desenvolvido em Django para o cadastro de Usu�rios e senhas de Acesso para poder abrir a porta inteligente desenvolvida com Arduino. A p�gina Web acessa a tabela de registros e mostra quais foram abertas, por quem e quando.

# Pr�-requisitos

pip install django
pip install django-crispy-forms
pip install psycopg2

# Instru��es

Execute o comando python migrate.py makemigrations para criar o banco de dados. 

Deve-se ent�o criar um superusu�rio com o comando python manage.py createsuperuser

Para iniciar o servidor, execute python manage.py runserver.

Para criar um acesso para o usu�rio, basta acessar a p�gina de admin em localhost:8000/admin e criar um novo acesso associado ao usu�rio criado

Para executar o servidor, deve-se executar o comando python migrate.py runserver
