# Näidis lehekülg

Nii lihtne ja tore on tegelikult doci kirjutada. Isegi pikemaid tekste on mugav kirjutada.

## Ja see on alampealkiri

Veidi juttu siia ka.

## Õpetus, kuidas kirjutada Markdowni Atomis

Aitab seadistada Atomit, et oleks mugav Markdowni kirjutada
https://www.portent.com/blog/content-strategy/atom-markdown.htm

## Proovin teha siia tabeli (TODO: ei tööta pdf-is)

Selleks on vaja teha paar lisasammu

1. Installi lisavidin

`pip install sphinx-markdown-tables`

2. Lisa see conf.py-sse

```python
extensions = [
    'sphinx_markdown_tables',
]
```

| Koostisosa | 1 inim | 2 inim | 3 inim | 4 inim |
|------------|--------|--------|--------|--------|
| Jahu       | 100g   | 200g   | 300g   | 400g   |
| Munad      | 1      | 2      | 3      | 4      |
