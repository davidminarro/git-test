# CABECERAS
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6
# SUBRAYADOS
Underline 1
---
Underline 2
===
# Formatos de enfasis.
- _Letra itálica 1_.
- *Letra itálica 2*.
- **Formato Bold o Strong**.
- __Formato Bold o Strong__.
- ~~Tachado~~.
- Mezcla entre los estilos _italico_, **bold** y ~~tachado~~

# Listas

1. Item 1 Lista ordenada
2. Item 2 Lista ordenada
3. Item 3 Lista ordenada
4. Item 4 Lista ordenada
- Item 1 Lista no ordenada
- Item 2 Lista no ordenada
- Item 3 Lista no ordenada
- Item 4 Lista no ordenada
## Listas tabuladas
1. Item 1
    - Tabulado
2. Item 2
    - Tabulado 2
        - Tabulado 3
    1. Listado tabulado

# Links

- <a href="https://www.google.es">Esto es un link con HTML</a>
- [Esto es un link en Markdown](https://www.google.es)
- [Esto es un link a index.html](index.html)
# Imágenes
![Logo Githab](https://www.dmi.es/images/dmi/cabecera/logo.svg)
# Code Snippets
Código en Json
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
Código en JavaScript
```JavaScript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```
# Tablas
| Nombre | Apellido | Documento |
|--------|----------|-----------|
| David | Miñarro | index.html |
| Juan | García | estilos.css |
| Raul | Sanchez-Clemente  | js/acciones-de-javascript.js |

# Citas
Esto es un texto referente a una cita:
> Esto es la cita comentada en la línea anterior.

Esto es otro texto sin relación con lo anterior.
> Esto es otra cita.
# Linea divisora
Esto es un texto que será dividido.

---

La anterior forma tiene que ir separada por saltos de línea para no confundir con subryado (underline)
___
Esto es otro texto más
***
Hay estas 3 formas de separar con lineas
# Saltos de línea
Hay que hacer doble enter

Esto es otra linea

Y esto es la última línea