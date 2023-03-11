# SELETI.VE
Aplicação desenvolvida para gerenciar suas vagas em processos seletivos de empresas.
--------------------------------------------------------------------------------------------------------
Projeto do curso online ''PYLAB 2022'', onde aprendemos a desenvolver um site utilizando PYTHON e DJANGO.    


![Screenshot_1](https://user-images.githubusercontent.com/117609505/201569834-2aabb4e6-8fbd-4571-a50e-e4630fe18fcb.jpg)
![image](https://user-images.githubusercontent.com/117609505/201570539-570f463e-d717-4f98-8f2a-94ed49a56f97.png)
![Screenshot_2](https://user-images.githubusercontent.com/117609505/201569964-6c01070f-d1e8-4e07-b957-25dd6a5e5ddd.jpg)
![image](https://user-images.githubusercontent.com/117609505/201570447-c5cca298-9f1a-4883-93f7-bac94b196d27.png)
![Screenshot_3](https://user-images.githubusercontent.com/117609505/201570375-7c8e1c81-3f8d-4fee-ac2f-0d03a7571353.jpg)
![Screenshot_4](https://user-images.githubusercontent.com/117609505/201570384-4a1b787d-5fb8-4623-a238-486b07a7c722.jpg)

Instalar o projeto usando o venv é recomendado, porém é possível instalar sem usá-lo também.

Ative o virtualenv no projeto:

    $ virtualenv project-env
    $ source project-env/bin/activate

Caso não tenha o django instalado ainda execute:

    $ pip3 install django
    
# Começando

Primeiramente clone esse repositório do Github e entre em seu diretório:

    $ git https://github.com/iMiojo/SELETI.VE.git
    $ cd Seletive
    
Instale os requirements:

    $ pip install requirements.txt
    
    
Aplique as migrações do banco de dados:

    $ python manage.py migrate
    

Agora, basta apenas rodar o servidor localmente:

    $ python manage.py runserver

Sinta-se livre para contribuir com o projeto!
