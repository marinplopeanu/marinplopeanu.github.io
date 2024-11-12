<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>


![Text descriptiv Imagine](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=1100)

[Homepage](index.md)

***

# Cuprins pagina:

- [Implementarea legaturilor catre alte fisiere](#implementarea-legaturilor-catre-alte-fisiere)
- [Sintaxa unui link in Markdown](#sintaxa-unui-link-markdown)
    - [Linkurile *clasice*](#linkurile-clasice)
    - [Linkurile referentiate](#linkurile-referentiate)
    - [Varianta prescurtata a linkurilor referentiate](#varianta-prescurtata-a-linkurilor-referentiate)
- [Linkuri catre imagini (inserarea imaginilor)](#linkuri-catre-imagini-inserarea-imaginilor)

***

# Implementarea legaturilor (link-urilor) in Markdown

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

## Linkuri catre imagini (inserarea imaginilor)

**Markdown (sintaxa):**

```markdown
![Totalstation](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=1100)
```

**Markdown renderizat:**

![Totalstation](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=1100)

***

[Up](#cuprins-pagina)

[Homepage][index]
