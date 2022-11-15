## Projeto de Agendamento para Clinicas e Consultorios;

Em que consite este projeto:
- Administrar de medicos e enfermeiros e suas especialidades.
- Criar um sistema de agendamento
- Permitir o usuario escolher uma consulta em dia e horario de acordo com agenda dos medicos e enfermeiros.
## Configurando o ambiente para executar a aplicação web.
Faça o download deste repositorio: disponível em:
```
$ git clone git@github.com:brunodlucka/proxximo.py
```

Crie um maquina virtual e instale a bibliotecas disponiveis no 
arquivo:
```
$ requirementes.txt:
```
Entre na pasta criada e inicie um ambiente virtual:
```
$ cd proxximo.py (pasta do projeto)
$ pip install virtualenv
$ py -m venv venv
```
Depois voce deve ativa-lo com o seguinte comando:
```
$
```
Após ativado, instale as bibliotecas necessárias para executar o projeto:
```
 (venv) $ pip install -r requirements.txt
```
```
Para poder ter o primeiro acesso e pode configurar o aplicação vamos executar o comando 
'migrate' para gerar o banco de dados padrão do Django(SQLite). E depois criar o superusuario:
```
```
(venv)$ py ./manage.py migrate
(venv)$ py ./manage.py createsuperuser
Apelido/Usuário: admin
E-mail: admin@gmail.com
Password: 
Password (again):
```
```
Para iniciar o servidor depois deste passo você deve:
```
```
(venv)$  py ./manage.py runserver
```


Para visualizar se tudo esta executando como esperado vamos acessar o seguinte endereço:
[http://localhost:8000/](http://localhost:8000/)

Ou você pode ter acesso a admin do Django:
[http://localhost:8000/admin](http://localhost:8000/admin)

"# proxximo-py" 
