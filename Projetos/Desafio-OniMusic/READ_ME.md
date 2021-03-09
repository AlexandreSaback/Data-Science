## Desafio Data Science - OniMusic ##

O objetivo de tal projeto é criar um relatório simples. Tal relatório apresentará informações sobre um determinado artista da OniMusic.

Para resolver tal desafio utilizei a API do [Deezer](https://deezer-python.readthedocs.io/en/stable/) em conjunto com a linguagem de programação Python. Além disso, utilizei diversas bibliotecas para facilitar a conclusão do projeto.

### Bibliotecas:

- **Pandas**: Permite trabalhar com arquivos de diversos tipos com mais facilidade, em um formato tabular, que lembra as tabelas do Excel.
- **Notebook**: Permite utilizar o Jupyter Notebook para a realização do projeto.
- **Deezer-python** (API): Biblioteca necessária para realizar as chamadas de forma mais simples utilizando Python.
- **Xlsxwriter**: Permite transformar DataFrames em planilhas com múltiplas abas.

Todo o código foi realizado dentro do editor de código-fonte **Visual Studio Code** utilizando as extensões adequadas para realizar o projeto em Jupyter Notebooks. Além disso, foi necessário criar um ambiente virtual (venv) para a realização do projeto.

A criação do **venv** foi feita no cmd do próprio **VSCode** através dos comandos:

- python -m venv `nome do ambiente` : Comando necessário para criar o ambiente virtual.
- \ `nome do ambiente`\Scripts\Activate.bat: Comando necessário para ativar o **venv** no cmd. Caso seja utilizado no Power Shell, a extensão **.ps1** deve ser utilizada no lugar da extensão **.bat**


Ao final do projeto, foram exportados dois DataFrames do Pandas para uma planilha Excel(.xlsx). O primeiro DataFrame contêm as músicas do determinado artista e o segundo contêm os albúns daquele artista. Para colocar cada DataFrame em uma aba na planilha, a biblioteca **Xlsxwriter** foi utilizada.

## Conclusão ##
Sou grato por ter participado deste desafio, utilizei poucas API's na minha trajetória e, portanto, através desse desafio pude conhecer um pouco mais sobre como é trabalhar com uma interface de programação de aplicações, e obtive novos conhecimentos que com certeza irão me auxiliar na minha jornada como Data Scientist.
