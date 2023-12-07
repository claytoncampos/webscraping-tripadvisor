### PROJETO DE WEB SCRAPING

##### Extrai os dados dos comentários das publicações do usuários no site tripadvisor

* Para executar o projeto em seu computador, primeiro faça git clone do repositório.

`https://github.com/claytoncampos/webscraping-tripadvisor.git` 

* Instale as dependências executando o comando abaixo.

`pip install -r requirements.txt` 

* Navegue até o diretorio \tripadvisor\tripadvisor\

`cd .\tripadvisor\tripadvisor\`

* Execute o comando abaixo para rodar o crawler.

`scrapy crawl comentarios -o teste.json`

<b>OBS:</b> <i>Mude a extensão do arquivo de acordo com sua necessidade <b>.json .xml ou .csv</b>

Após a execução o arquivo de extração será gerado no diretorio raiz do projeto


