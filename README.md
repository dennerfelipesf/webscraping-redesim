# Web Scraping - REDESIM

Processo de Web Scraping das Planilhas da RedeSim Estatística (Tempo de Abertura de uma Empresa)

No desenvolvimento foi utilizado MozillaFirefox + Selenium + Python 

Uma segunda versão será enviada via Dockerfile para que não seja necessária a visualização da página.

* Instalar os requiriments.txt via pip

Para os usuários Windows, deixar o geckodriver ao lado do jupyter notebook.

No ubuntu, enviar para o /usr/local/bin: 
1. Obter o arquivo
`` wget https://github.com/mozilla/geckodriver/releases/download/v0.31.0/geckodriver-v0.31.0-linux64.tar.gz``

2. Descompactar
`` tar -tvf geckodriver-v0.31.0-linux64.tar.gz``

3. Enviar para o /usr/local/bin
`` sudo cp geckodriver /usr/local/bin ``

Os dados estão disponíveis na [FONTE](https://estatistica.redesim.gov.br/tempos-abertura).


