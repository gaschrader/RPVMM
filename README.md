# RPVMM
Este repositório contém o código fonte para a disciplina de Resolução de Problemas via Modelagem Matemática.

Para rodar o algoritmo, é recomendado baixar o .ipynb e o arquivo de entrada .xlsx e rodar no google colab, já que há textos descritivos para o funcionamento do código.

No momento que abrir o arquivo no colab, realizar o upload manual do arquivo 'estoque.xlsx', contido neste repositório, e rodar cada célula individualmente.

Temos 3 células de código, que devem ser rodados na ordem que segue: 
- A primeira roda o código e apresenta dados de cada onda gerada, como área de picking, SKUS contidos, número da onda, etc. Ao final desta célula, é printado a área média obtida.
- A segunda printa alguns gráficos com insights e informações sobre os dados obtidos anteriormente.
- A terceira e última cria uma nova base de dados, randomizando 'estoque.xlsx' e gerando um novo arquivo, chamado 'estoque_modificado.xlsx'.

Para rodar o arquivo modificado, é preciso alterar na primeira célula, na linha 5, o nome do arquivo a ser lido.
