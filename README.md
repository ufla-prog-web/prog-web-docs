# Documentação

Instalação do ambiente virtual:

```bash
python3 -m venv venv
```

Ativando o ambiente virtual:

```bash
source venv/bin/activate
```

Instalando o mkdocs:

```shell script
(venv) ... $ pip3 install mkdocs
(venv) ... $ pip3 install "mkdocstrings[python]"
(venv) ... $ pip3 install mkdocs-material
```

Criando o projeto utilização o mkdocs:

```bash
(venv) ... $ mkdocs new prog-web-docs
```

Executando a aplicação web:

```bash
(venv) ... $ mkdocs serve
```

## Comandos

* `mkdocs new [dir-name]` - Cria um novo projeto.
* `mkdocs serve` - Inicia um servidor da documentação com reloading.
* `mkdocs build` - Constroi a documentação do site.
* `mkdocs -h` - Imprime uma mensagem de ajuda e sai.

## Layout do Projeto

    mkdocs.yml    # Arquivo de configuração.
    docs/
        index.md  # Página inicial da documentação.
        ...       # Outras páginas markdown, imagens e outros arquivos.
