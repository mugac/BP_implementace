# Postkvantová kryptografie – Bakalářská práce

Interaktivní Jupyter notebooky demonstrující klíčové koncepty postkvantové kryptografie.

## Obsah

| Notebook | Téma |
|---|---|
| `Latice.ipynb` | Kryptografie založená na mřížkách – vizualizace dobrých a špatných bází, problém CVP |
| `LWE.ipynb` | Problém učení s chybami (Learning With Errors – LWE) |
| `Marrkle.ipynb` | Merkleho stromy (SHA-256) a jejich role v hash-based kryptografii (SPHINCS+) |

## Požadavky

- Python 3.9 nebo novější
- Jupyter Notebook / JupyterLab (nebo VS Code s rozšířením Jupyter)

## Instalace závislostí

Doporučuje se použít virtuální prostředí:

```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate

pip install -r requirements.txt
```

## Spuštění

### VS Code
Otevřit libovolný `.ipynb` soubor v VS Code a spustit buňky pomocí **Run All** (nebo postupně přes Shift+Enter/play tlačítko vedle buňky).

### Jupyter
```bash
jupyter notebook
```
Poté v prohlížeči otevřít požadovaný notebook.