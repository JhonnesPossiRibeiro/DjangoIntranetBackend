<h1>Intranet Django (Python)</h1>
<p>Projeto de backend da intranet</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Oracle-DB-red?style=for-the-badge&logo=oracle&logoColor=white"/>  
  <img src="https://img.shields.io/badge/Git_Bash-Terminal-orange?style=for-the-badge&logo=git&logoColor=white"/>
</p>

## Projeto Django (Python)

Para o projeto, seguir os passos abaixo:

1. Criar um ambiente virtual com o nome **.venv**: `python -m venv .venv `;
2. Ative o ambiente virual .venv`: `.\.venv\Scripts\active`;
3. Instale o pacote Django: `pip install django `;
4. Criar um projeto pai com o nome **setup**: `django-admin startproject setup .`;
5. Criar o arquivo requirements.txt: `pip freeze > requirements.txt`;
6. Em settings.py iremos alterar o **TimeZone e a Linguage** do Sistema, para isso adicione o código:
   ```
   LANGUAGE_CODE = "pt-br"
   TIME_ZONE = "America/Sao_Paulo"
   USE_L10N = True
   USE_TZ = True
   ```
