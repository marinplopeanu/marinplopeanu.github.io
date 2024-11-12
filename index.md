![Total Station Demo](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=1100)

# Harta site:

[Markdown 1: Crearea legaturilor Markdown](index.md)

[Markdown 2: Elemente avansate de Markdown (demo 'md' page)](avansate.md)

[Markdown 3: Elemente de Markdown - completare](/markdown2.md)

[MathJax 1: Formule cu TeX si MathJax](mathjax.md)

[MathJax 2: Matrice si ecuatii cu TeX si MathJax](mathjax2.md)

[Diagrame Mermaid](/diagrame/mermaid.md)

***

# Implementarea legaturilor (linku-urilor) in Markdown

## Implementarea legaturilor catre alte fisiere

Fisierele accesate prin link-uri pot fi:
1. Gazduite pe *alte servere* (de ex.: accesarea unui alt site)
2. Gazduite pe *serverul site-ului curent*.

De asemenea, prin aceste linkuri se pot accesa si sectiuni din pagina curenta sau sectiuni din alte pagini ale aceluiasi site.

## Sintaxa unui link Markdown 

Tipuri de linkuri in Markdown:
1. Linkuri *clasice* (normale)
2. Linkuri *referentiate*

### Linkurile *clasice*

**Markdown (sintaxa):**

```markdown
[Link google.com](https://google.com/)
[Link google.com cu text alternativ](https://google.com/ "Accesare site Google")
```

**Markdown renderizat:**

[Link google.com](https://google.com/)

[Link google.com cu text alternativ](https://google.com/ "Accesare site Google")

***

### Linkurile referentiate

**Markdown (sintaxa):**

```markdown
Iata un [link][link1] catre site-ul Google.

[link1]: https://google.com/
```

**Markdown renderizat:**

Iata un [link][link1] catre site-ul Google.

[link1]: https://google.com/

***

### Varianta prescurtata a linkurilor referentiate:

**Markdown (sintaxa):**

```markdown
Iata un link [important] catre site-ul Google.

[important]: https://google.com/
```

**Markdown renderizat:**

Iata un link [important] catre site-ul Google.

[important]: https://google.com/

***

### Linkuri catre imagini (inserarea imaginilor)

**Markdown (sintaxa):**

```markdown
![Totalstation](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=1100)
```

**Markdown renderizat:**

![Totalstation](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=1100)

