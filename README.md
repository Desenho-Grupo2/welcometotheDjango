# PlanUp

### Executando a aplicação

Para os depois métodos de executar a aplicação é necessário clonar o repositório e entrar na pasta raiz:<br>

          `$ git clone https://github.com/Desenho-Grupo2/welcometotheDjango.git`<br>
          `$ cd PlanUp/`

Agora há duas opções: utilizando Docker (recomendado) ou pip + ambiente virtual do Python.

**Utilizando o Docker:**

1) Instale o docker<br>
2) Execute o comando a seguir no terminal (testado apenas no linux)

          `$ sudo sh build_run.sh`

**Utilizando o pip + ambiente virtual:**

1) Crie um ambiente virtual python:<br>

          `$ python3 -m venv .virtualenvs/planup`

2) Ative o ambiente criado:

          `$ source .virtualenvs/bin/planup`

3) Instale as dependências Python do projeto:

          `$ pip install -r requirements.txt`

4) Execute o script responsável por "subir" o servidor:

          `$ sudo sh run.sh`

**Entrando na aplicação (Docker ou pip)**:

O passo a seguir é válido tanto para o Docker quanto para o pip.<br>
Pelo seu browser favorito, entre na seguinte URL:

          `0.0.0.0:8000/`

Pronto!
