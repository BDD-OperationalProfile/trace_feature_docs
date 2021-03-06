# Trace Features BDD - Docs

<p align="center">
  <img src="https://trace-features-bdd.github.io/trace_feature_docs/img/mini-logo.png" width="200px" height="200px"/></p>

Documentação gerada para a Biblioteca em Python Trace Features BDD, implementada durante a disciplina de Desenho de Software, ministrada no curso de Engenharia de Software da Universidade de Brasília. Acesse os documentos [aqui!](https://BDD-OperationalProfile.github.io/trace_feature_docs/)

## Instalação
Para contribuir com a documentação, após clonar o repositório é necessário instalar os seguintes pacotes Python:
* mkdocs - Responsável por gerar o site a partir dos arquivos Markdown.
* mkdocs-material - Para a estilização do site.

Ambos os pacotes estão disponíveis através do gerenciador de pacotes do Python, o pip. É recomendado o uso de ambientes virtuais (virtualenv) para isolar a instalação dos pacotes do resto do ambiente. Informações sobre instalação e uso do virtualenv e virtualenvwrapper (ferramenta que auxilia no gerenciamento dos ambientes virtuais) podem ser encontradas nos seguintes links:
* [virtualenv](https://virtualenv.pypa.io/en/stable/installation/)
* [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/install.html/)

## Uso
Os documentos estão organizados em arquivos Markdown, de forma similar a uma wiki. Para visualizar o site localmente, basta utilizar o comando `mkdocs serve`. Ele inicializará um servidor local, que atualiza automaticamente com mudanças feitas nos arquivos.

Para publicar as modificações realizadas no Github Pages, após adicioná-las ao controle de versão, utilizar o comando `mkdocs gh-deploy`. Ele realizará automaticamente o _push_ das modificações para a branch gh-pages, e em alguns segundos as mudanças estarão disponíveis no site.
