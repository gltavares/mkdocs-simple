# Code

Fences are muted surfaces with a large radius. Inline code is a small chip. Copy stays in the corner; syntax colors stay readable on both palettes.

Inline: `pip install mkdocs-material` should never look like a button.

## Fence

```python
def fibonacci(n):
    a, b = 0, 1
    for _ in range(n):
        yield a
        a, b = b, a + b

for num in fibonacci(10):
    print(num)
```

## Named file

```yaml title="mkdocs.yml"
theme:
  name: material
  font: false
  palette:
    - scheme: default
      primary: custom
      accent: custom
    - scheme: slate
      primary: custom
      accent: custom

extra_css:
  - stylesheets/extra.css
```

## Shell

```sh
pip install mkdocs-material
mkdocs serve -a 127.0.0.1:43147
```

Long blocks scroll inside the rounded frame instead of stretching the page.
