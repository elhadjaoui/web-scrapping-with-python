_In English and e em Português._

**UNDER CONSTRUCTION // EM CONSTRUÇÃO**

# EN: Web Scrapping with Python

Study notes on Web Scraping using Python, **Beautiful Soup** and **Requests**. "Web Scrapping" is the art of accurately and quickly extract data from a web page. In order to do this, we use intelligent automation with Python.

The idea is to create a "scraper" program that does data extraction from web pages.

These notes are based on the course **Web Scraping and API Fundamentals in Python 2021** by _Nikola Pulev_. It's on Udemy.

**THIS REPOSITORY'S TABLE OF CONTENTS**

FILES | CONTENTS
:--- | :--------
01_WORKING_WITH_APIs.md | What is an API; the HTTP Protocol; GET/POST requests; JSON format (Python Dictionary and Lists); Pandas Library; API Pagination; len(r.json()); results.extend(r.json()); EDAMAM API Example; headers=headers; json=recipe; pd.DataFrame(capp_info["totalNutrients"]).transpose(); export to csv file.
02_EX_CURRENCY_API.md | Import requests; response.ok; response.status_code (200 and 404); response.text (text); response.content (bytes); response.json() (dict); response.json().keys(); json.loads(); json.dumps()
03_HTML_AND_BEAUTIFUL_SOUP.md | Data extraction; HTML tags and attributes; character encodings; Beautiful Soup (Python Library); Five steps: 1. inspect the page, 2. obtain the HTML, 3. choose a parser, 4. create a BeautifulSoup object to manipulate and extract data, 5. (optional) export the HTML to a file (highly recommended); Searching and navigating the HTML Tree: through methods `.find()` and `.find_all()`, through attributes and values, to extract data, to extract text.
04_TABLES_AND_PANDAS.md | pandas documentation; creating a DataFrame; undo truncate info; export to CSV and export to Excel

---
# PT: Web Scrapping usando Python
Notas de estudo sobre Web Scraping usando Python, **Beautiful Soup** e **Requests**. O "Web Scrapping" é uma forma de mineração que permite a extração de dados de sites da web. Ou seja, é uma técnica de coleta de informações. Para fazer isso, a gente usa a automação inteligente com Python.

A ideia é criar um programa "scraper" que faz a extração de dados das páginas web.

Essas anotações são baseadas no curso **Web Scraping and API Fundamentals in Python 2021** do _Nikola Pulev_. Você pode encontrar o curso dele na Udemy.

**TABELA DE CONTEÚDOS DO REPOSITÓRIO**

ARQUIVOS | CONTEÚDOS
:------ | :---------
01_TRABALHANDO_COM_APIs.md | O que é são APIs; o protocolo HTTP; requisições do tipo GET/POST; formato JSON (similar ao Dicionário e a Lista de Python); biblioteca Pandas; Paginação API; len(r.json()); results.extend(r.json()); EDAMAM API exemplo; headers=headers; json=recipe; pd.DataFrame(capp_info["totalNutrients"]).transpose(); salvar em arquivo csv
02_EX_API_CONVERSAO_MOEDA.md | Import requests; response.ok; response.status_code (200 and 404); response.text (text); response.content (bytes); response.json() (dict); response.json().keys(); json.loads(); json.dumps()
03_HTML_E_BEAUTIFUL_SOUP.md | Extração de dados; tags HTML e atributos; encodings de caracteres; Beautiful Soup (biblioteca Pyton); Cinco passos: 1. inspecionar a página, 2. obter o HTML, 3. escolher o parser, 4. criar um objeto BeautifulSoup para manipular e extrair dados, 5. (opcional) exportar o HTML para um arquivo (altamente recomendado); Procurando e navegando na árvore HTML: por meio dos métodos `.find()` e `.find_all()`, por meio dos atributos e valores, para extrair dados, para extrair texto.
04_TABELAS_E_PANDAS.md | documentação pandas; criando um DataFrame; desfazendo informação truncada; exportando os dados para arquivos CSV e para arquivos Excel

