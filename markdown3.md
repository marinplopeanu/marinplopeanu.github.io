<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>


![Text descriptiv Imagine](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=1100)

[Homepage](index.md)

***

# Cuprins pagina:

- [Inserarea codului de programare in Markdown si HTML](#inserarea-codului-de-programare-in-markdown-si-html)
    - [Cod 'in linie'](#cod-in-linie)
    - [Cod scris pe mai multe linii](#cod-scris-pe-mai-multe-linii)
- [Inserarea elementelor evidentiate (quotes/blockquote)](#inserarea-elementelor-evidentiate-quotesblockquote)
- [Avantajele HTML fata de Markdown (exemple)](#avantajele-html-fata-de-markdown-exemple)
- [Taguri HTML](#taguri-html)
- [Echivalentul unui link Markdown in HTML](#echivalentul-unui-link-markdown-in-html)

***


# Elemente de Markdown - Partea a doua

## Inserarea codului de programare in Markdown si HTML

### Cod 'in linie'

**Cod in linie cu Markdown:**

```markdown
Iata un fragment de cod scris pe aceeasi linie: `a = b**c`.
```

**Markdown renderizat:**

Iata un fragment de cod scris pe aceeasi linie: `a = b**c`.

**Cod in linie cu HTML:**

```html
<code> a=b**c </code>
```

**HTML renderizat:**

<code> a=b**c </code>

### Cod scris pe mai multe linii

**Cod evidentiat cu Markdown:**
````
```python
import pandas as pd
import numpy as np

a = 2
b = 3
```
````

**Markdown - renderizat:**

```python
import pandas as pd
import numpy as np

a = 2
b = 3
```

**Cod evidentiat cu HTML:**

```html
<pre>
import pandas as pd
import numpy as np

a = 2
b = 3
</pre>
```
**HTML - renderizat:**
<pre>
import pandas as pd
import numpy as np

a = 2
b = 3
</pre>

## Inserarea elementelor evidentiate (quotes/blockquote)

**Evidentiere Markdown:**

```markdown
> Acesta este un text evidentiat cu Markdown.
```

**Markdown - renderizat:**

> Acesta este un text evidentiat cu Markdown.

Acesta este un text ne-evidentiat.

**Evidentiere HTML:**

```html
<blockquote>
Acesta este un text evidentiat cu HTML.
</blockquote>
```

**HTML - renderizat:**

<blockquote>
Acesta este un text evidentiat cu HTML.
</blockquote>

<p> </p>

## Avantajele HTML fata de Markdown (exemple)

**Link imagine cu Markdown:**

```markdown
![Foto](images/mp.jpg)
```

![Foto](images/mp.jpg)

**Link imagine cu HTML:**

```html
<img src=images/mp.jpg width="200" border=10px>
```

**HTML renderizat:**

<img src="images/mp.jpg" width="200" border=10px>

**Linie orizontala Markdown:**

```markdown
***
```

***

**Linie orizontala HTML:**

```html
<hr style="height: 15px; background-color: black;">
```

<hr style="height: 5px; background-color: green;">

## Taguri HTML

**Tag HTML in pereche (cu continut), cu eticheta de deschidere si de inchidere:**

```html
<p>Acesta este un paragraf.</p>
```

**HTML renderizat**:

<p>Acesta este un paragraf.</p>

**Tag HTML auto-inchis (fara continut)**

```html
<hr>
etc.
```

**HTML renderizat**:

<hr>

## Echivalentul unui link Markdown in HTML

**Link Markdown:**

```markdown
[Link Markdown catre Google](https://google.com)
```
**Link Markdown renderizat:**

[Link Markdown catre Google](https://google.com)

**Link HTML:**

```html
<a href="https://google.com"> Link HTML catre Google </a>
```

**Link HTML renderizat:**

<a href="https://google.com"> Link HTML catre Google </a>

***

[Up](#cuprins-pagina)

Link [Homepage](index)

