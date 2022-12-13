# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

### Teste

:rocket:

### Código

```{.py3 hl_lines="2" linenums=1 title="arquivo.py"}
def teste():
    """Docstring"""
    return True
```

## Custom fences
```mermaid
flowchart LR
    A --o B
    B --x C
```    