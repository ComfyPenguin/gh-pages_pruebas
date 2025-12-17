---
title: "Pruebas de MkDocs: Índice"
description: "Documentación falsa para probar características de MkDocs (mermaid, código, front-matter, tablas, etc.)"
keywords: ["mkdocs", "pruebas", "mermaid", "documentación", "index"]
author:
    name: "Andy Pruebas"
    email: "andy@example.com"
date: 2025-12-16
tags: ["demo", "test", "index"]
category: "demo"
permalink: "/"
draft: false
hide: false
toc: true
---

# Pruebas: Índice

Breve página de prueba para verificar que MkDocs renderiza metadatos, mermaid, bloques de código y otros elementos.

## Contenido rápido

- Mermaid
- Bloques de código (bash, python, yaml, html)
- Tablas, listas y admoniciones
- Ejemplos de front-matter y enlaces

## Mermaid (diagrama de flujo)

```mermaid
flowchart LR
    A[Inicio] --> B{¿Build exitoso?}
    B -->|Sí| C[Desplegar]
    B -->|No| D[Revisar logs]
    D --> E[Corregir errores]
    E --> A
```

## Código de ejemplo

Bash (iniciar servidor local):

```bash
# instalar dependencias y servir
pip install mkdocs mkdocs-material
mkdocs serve
```

Python (fragmento de ejemplo):

```python
def saludo(nombre: str) -> str:
        return f"Hola, {nombre}!"

print(saludo("MkDocs"))
```

Fragmento YAML (porciones de mkdocs.yml):

```yaml
site_name: "Mi Sitio de Pruebas"
theme:
    name: "material"
plugins:
    - search
    - mermaid2
nav:
    - Home: index.md
```

HTML embebido (solo prueba):

```html
<div class="demo-box">
    <strong>Nota:</strong> contenido HTML en Markdown.
</div>
```

## Admoniciones

!!! note
    Esto es una nota de ejemplo usando la sintaxis de admonición (compatible con MkDocs Material).


!!! warning
    Advertencia: comprueba que el plugin de mermaid esté habilitado si no ves los diagramas.


## Tabla y listas

| Característica | Estado |
|---|---:|
| Mermaid | ✓ |
| Bloques de código | ✓ |
| Front-matter | ✓ |
| Imágenes | opcional |

Lista de verificación:

- [x] Lorem ipsum dolor sit amet, consectetur adipiscing elit
- [ ] Vestibulum convallis sit amet nisi a tincidunt
    * [x] In hac habitasse platea dictumst
    * [x] In scelerisque nibh non dolor mollis congue sed et metus
    * [ ] Praesent sed risus massa
- [ ] Aenean pretium efficitur erat, donec pharetra, ligula non scelerisque

## Enlaces y recursos

- Documentación MkDocs: https://www.mkdocs.org/
- Plugin mermaid (si aplica): https://github.com/brandon-rhodes/mermaid

## Notas finales

Inline code: `mkdocs build` — enfatizado *rápido* y **visible**.

![alternative text](https://www.plantuml.com/plantuml/png/XP9VJiCm3CRVSmehBuD9lG2QfZq0BxoWNQ3ocj16ofygSM7Jngau0XV3NQHsgrRsqjgVdS-_EjqamaYTis81pmRhY0xXPGl9kDPgQ34YT1vsDjH2Q4-63Y2xf6EIW0dE4Hm5mD8eU0BZ2LQhzxVrcgMYu8T7fxdmYR5gCBAW7HfxfLHH8sbL8h6iE2JZjFWUvxKXKPxNHxFpUfZoGdwzm60ZUysn2-h00kazSTPsEsjIynz55PpZE8FaP9wb1vsmt4EiWYUs79ZkxuMmpZGSp99CBc2ordBmoDbWT4udRWFlallwugqg3rZ0LbkiJF0wmOCFnF7lZuSgXgz5WeyG2B2DOMySAdmK-IywdOeY7FCLix74ZfeGfSX2hevxvuO6aynd9zNvu-D7SWU_QwsaEEStEzXSbSPB8JRQgyxPFm00)

<!-- imagen de ejemplo (ruta relativa) -->
![Placeholder de ejemplo](images/placeholder.png)
