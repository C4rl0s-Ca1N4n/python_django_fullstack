# Aplicação WEB FULL-STACK com PYTHON E DJANGO.
Desenvolver de ponta a ponta, um sistema de gestão para clínicas de psicologia organizarem e gerenciarem seus pacientes, utilizando Python e Django.

# Para Criação do ambiente
## Primeiro devemos criar o ambiente virtual:
# Criar
	# Linux
		python3 -m venv venv
	# Windows
		python -m venv venv
​
Após a criação do venv vamos ativa-lo:
# Ativar
	# Linux
		source venv/bin/activate
	# Windows
		venv\Scripts\Activate

# Caso algum comando retorne um erro de permissão execute o código e tente novamente:
    Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
​
# Agora vamos fazer a instalação das bibliotecas necessárias:
     pip install sqlmodel
     
# Agora vamos fazer a instalação do Django e as demais bibliotecas:
    pip install django
    pip install pillow

# Vamos criar o nosso projeto Django:
    django-admin startproject core .
​
# Rode o servidor para testar:
    python manage.py runserver
​
# Crie o app usuario:
    python manage.py startapp pacientes

# Para aplicar as migracoes dos BD
    python manage.py makemigrations
    python manage.py migrate

    
