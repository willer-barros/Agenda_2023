iniciar projeto django

-> criar pasta 
-> criar ambiente virtual
    python -m venv venv
-> ativar ambiente virtual 
    caminho_arquivo/venv/scripts/activate
-> pip install django

#criar app
python manage.py startapp nome_app


Configurar gitHub
git config --global user.name 'Seu nome'
git config --global user.email 'Seu email'
git config --global init.defaultBranch main

#configurar o .gitignore antes de seguir para os proximos passos
git init
git add .
git commit -m 'mensagem'
git remote add origin URL_GIT