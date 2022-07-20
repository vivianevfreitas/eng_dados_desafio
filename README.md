# Engenheiro de dados
Código feito como proposta de solução do desafio para vaga de engenheiro de dados. A linguagem de programação escolhida foi Python e o banco de dados é o sqlite3.

Código construído em ambiente docker com a imagem do anaconda. Entendendo que já tenha o Docker Desktop instalado, segue o código de instalação da imagem do anaconda:
docker run -it -p 8888:8888 -v "%cd%/notebooks:/home" continuumio/anaconda3 /bin/bash

Para rodar o jupyter notebook, utilizamos o código:
jupyter notebook --ip='*' --port=8888 --no-browser --allow-root &

Com esse código você acessa os notebooks apresentados.

Segue vídeo curto explanando o código: 
https://www.loom.com/share/5cd644804b1640f5ad1798ba939fcaec

