Crie a venv local com:
python -m venv venv

ative a venv com:
.\venv\Scripts\activate

instale as bibliotecas com:
pip install -r requirements.txt
///////////////////////////////////////


PASTA OFICIAL DO PROJETO do DJANGO: ticontrol.

dentro de ticontrol haverá UMA SUBPASTA (ticontrol) que contem arquivos do django.

manage.py oq é? : carrega as configurações que estão dentro dos arquivos

////////////////////////////////////////

Para rodar o servidor local do projeto: python manage.py runserver // para que quando estivermos desenvolvendo, possamos ver o projeto rodando na ar.

////////////////////////////////////////

DIFERENÇA DO djangoadmim e manage.py = diferente do djangoadmin, o manage.py carrega os arquivos do settings.py, onde todas as configurações que o django precisa estam lá.

///////////////////////////////////////

Especificando arquivos que estão dentro da pagina do projeto (ticontrol)

1) pycache - cahe do python, ignorem. 
2) __init__.py -  geralmente vem vazio (sem conteúdo nenhum) serve para inicializar algum pacote.
3) asgi.py e wsgi.py servem para fazer a ligação do django e de um servidor web externo.
4) settings.py - são as configurações do django, lá mostra como o Django deve se comportar no nosso projeto. Nele podemos realizar alterações ao longo do desenvolvimento.
5) urls.py - é a porta de entrada da nossa aplicação. 



