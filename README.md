# RepositorioTemplate

Repositório que deve ser utilizado como template inicial pelos grupos da matéria de Arquitetura e Desenho de Software.

## Introdução

Este repositório traz um template de repo de documentação a ser seguido pelos grupos de arquitetura e desenho de software.

## Tecnologia

A geração do site estático é realizada utilizando o [MkDocs](https://www.mkdocs.org/) com o tema [Material](https://squidfunnel.github.io/mkdocs-material/).

### Instalando as dependências

É recomendado criar um ambiente virtual Python antes de instalar:

```shell
python -m venv venv
```

Ative o ambiente virtual:

```shell
# Windows
venv\Scripts\activate

# Linux/macOS
source venv/bin/activate
```

Instale as dependências:

```shell
pip install -r requirements.txt
```

### Executando localmente

Para iniciar o site localmente, utilize o comando:

```shell
mkdocs serve
```

O site estará disponível em `http://127.0.0.1:8000/`.
