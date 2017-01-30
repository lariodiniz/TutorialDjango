# TutorialDjango

O Tutorial Padrão do Django:
    https://docs.djangoproject.com/en/1.10/intro/

* Dependências
    * Python 3.6
    * Django 1.10.5
    * VirtualEnv
    
* Instalação
    
1 - Instale na sua máquina o Python e o PIP para instalações de pacotes.
    * [Instalar no Windows][0]
    * [Instalar no Mac ou Linux (via pyend)][1]
    
2 - Instale o VirtualEnv. (No Python 3.x o VirtualEnv já vem embutido).
    
3 - Baixe o projeto

```
git clone https://github.com/lariodiniz/TutorialDjango.git
cd TutorialDjango
```

4 - Crie o virtualenv com o Python 3.x

```
python -m venv .venv
```

    
5 - Execute o comando de ativação do virtualenv

No Terminal do Linux/Mac:

```
source .venv/bin/activate
```

No Windows:

```
.venv\Scripts\activate.bat
```

6 - Faça a migração do banco

```
python manage.py migrate
```

7 - Tutorial rodando.

```
python manage.py runserver
```
     
* Ambiente de desenvolvimento
    * Sistema operacional: Ubuntu
    * Controlador de Versão: Git
    * Editor de texto de sua preferência

[0]: https://www.python.org/downloads/
[1]: http://blog.abraseucodigo.com.br/instalando-qualquer-versao-do-python-no-linux-macosx-utilizando-pyenv.html
