# Version del curso
Version actual: v1.2.2

# Cabeceras

# Cabecera H1

## Cabecera H2

### Cabecera H3

#### Cabecera H4

##### Cabecera H5

###### Cabecera H6

# Underlines
Underline 1
-------------

Underline 2 
============

# Formatos de enfasis
- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.
- **formato bold a strong** de la primer forma.
- __formato bold a strong__ de la primer forma.
- ~~formato tachado~~, formato normal.
- aqui podemos usar *formato italico*, pero tambien **bold** y ~~tachado~~.

# Listas
1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links
- <a href="http://www.google.com"> Esto es un link html</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)

# Code Snippets
Codigo en JSON
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
Codigo en JavaScript
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
| raul | Va | ram |
| ras | soej | eddd |

# Citas
Esto es un texto referente a una cita:
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior..
>Esto es otra cita.

# Lineas Divisoras
Esto es un texto que será dividido por guiones medios

---
Esto es otro texto dividido dividido por asteriscos..
***

Esto es otro texto dividido por guiones bajos.

___

# Saltos de linea
Esto es nuestro primer pararfo.

Esto es nuestro segundo pararfo.

Esto es nuestro tercer pararfo.
- Lista
