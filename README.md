# Sistema Catálogo de Carros

Bem-vindo ao Sistema Catálogo de Carros, um projeto desenvolvido com intuito didático no Curso Django Master ministrado pela PycodeBR, 
em Django, HTML, CSS e Javascript para facilitar o gerenciamento de um catálogo de Carros.
Este projeto possui integração com OPENAI para gerar a descrição dos carros automaticamente.
Este README fornece informações essenciais sobre como configurar e executar o projeto em seu ambiente local.
## Requisitos

Certifique-se de que você tenha os seguintes requisitos instalados em seu sistema:

    Python (versão recomendada: 3.7 ou superior)
    Django (instalado automaticamente ao seguir as instruções abaixo)
    Outras dependências listadas no arquivo requirements.txt

## Instalação das Dependências

Com o ambiente virtual ativado, instale as dependências do projeto usando o comando:
```
pip install -r requirements.txt
```
## Configurar chave OPENAI_KEY e OPENAI_MODEL
Criar na raiz do projeto em app o arquivo .env e colocar dentro as variáveis:
```
OPENAI_KEY=`sua_chave_aqui`
```
## Rodar o projeto

Após instalar as dependências, aplique as migrations no banco de dados com o comando:
```
python manage.py migrate
```
Agora o projeto jã pode ser inicializado com o comando:
```
python manage.py runserver
```
Após isso, o sistema estará pronto para ser acessado em: http://localhost:8000
