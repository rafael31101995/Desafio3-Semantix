# Desafio3-Semantix

Façam um programa python que quando executado, mostre dia e hora no formato YYYY-mm-DD HH:DD:SS
segue abaixo exemplo da chamada e saída esperados:

> python programa03.py
2020-03-26 19:16:02

Em seguida, coloquem no crontab para que execute a cada minuto, direcionando para um arquivo.

Este direcionamento de arquivo pode ser testado da seguinte forma:
> python programa03.py > saida.txt

Ao executar o comando acima, não aparecerá a saída na tela por que foi direcionada para o arquivo especificado (saida.txt)
Caso eu queira que ocorra append no arquivo, ao invés de sobbreposição, utilizo.

Vocês saberão se está correto ou não se for gerado um arquivo com várias datas e horas.

Obs: montem uma estrutura de diretório e utilizem para todos os projetos.
Por exemplo:  
/workspace/projeto_01 \
/workspace/projeto_02 \
: \
/workspace/projeto-nn

Obs2: o crontab precisa saber onde está seu programa, ou seja, ele precisa dos caminhos completos para funcionar.
