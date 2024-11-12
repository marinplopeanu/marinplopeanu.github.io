<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>


![Text descriptiv Imagine](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=1100)

[Homepage](index.md)

***

# Cuprins pagina

- [Inserarea ecuatiilor si formulelor 'TeX' cu `MathJax`](#inserarea-ecuatiilor-si-formulelor-tex-cu-mathjax)
    - [Script MathJax](#script-mathjax)
    - [Sintaxa inserari MathJax](#sintaxa-formulelor-inserate-cu-mathjax)
- [Ridicarea la putere (superscript)](#ridicarea-la-putere-superscript)
- [Inserarea indicilor (subscript)](#inserarea-indicilor-subscript)
- [Gruparea elementelor din formule](#gruparea-elementelor-din-formule)
- [Literele grecesti](#literele-grecesti)
- [Parantezele in 'TeX'](#parantezele-in-tex)
- [Fractiile](#fractiile)
- [Semnele de 'multiplicare' si respectiv de 'diviziune'](#semnele-de-multiplicare-si-respectiv-de-diviziune)
- [`Suma` de la `i=0` la `n`](#suma-de-la-i0-la-n)
- [Integrale](#integrale)

***

# Inserarea ecuatiilor si formulelor 'TeX' cu `MathJax`

## Script MathJax

```javascript
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
```

Vezi: <https://www.mathjax.org/#gettingstarted>

## Sintaxa formulelor inserate cu `MathJax`:

> Formulele `MathJax` sunt inserate in aceeasi linie daca sunt plasate intr-o pereche de simboluri `$`.

*Exemplu:* 

**Cod TeX:**

```latex
Aceasta este o ecuatie: $a=bc$ 
```

**Cod TeX renderizat:**

Aceasta este o ecuatie: $a=bc$ 

> Formulele `LaTeX` (prin `MathJax`) se introduc pe rand nou intre doua perechi de simboluri `$$`.

*Exemplu:* 


**Cod TeX:**

```latex
$$a=b^c$$
```

**Cod TeX renderizat:**

$$a=b^c$$

<p> </p>

# Ridicarea la putere (superscript)

>Se foloseste meta-caracterul `LaTeX`: `^`

*Exemplu:*

**Cod TeX:**

```latex
$$a=10^7$$
```

**Cod TeX renderizat:**

$$a=10^7$$

<p> </p>

# Inserarea indicilor (subscript)

>Se foloseste meta-caracterul `LaTeX`: `_`

*Exemplu:*

**Cod TeX:**

```latex
$$a_i = b^c$$
```

**Cod TeX renderizat:**

$$a_i = b^c$$

<p> </p>

# Gruparea elementelor din formule

>Elementele din formule se grupeaza prin meta-caracterele `{` si `}`.

*Exemplu:*

**Cod TeX:**

```latex
$$ 10^{10} $$
```

**Cod TeX renderizat:**

$$ 10^{10} $$

<p> </p>

# Literele grecesti

*Exemple:*

`\alpha` - alpha litera mica:

**Cod TeX:**

```latex
$$\alpha$$
```
**Cod TeX renderizat:**

$$\alpha$$

`\Gamma` - Gamma litera mare 

**Cod TeX:**

```latex
$$\Gamma$$
```

**Cod TeX renderizat:**

$$\Gamma$$

<p> </p>

# Parantezele in 'TeX'

- Parantezele rotunde se scriu direct (nu au un inteles special `LaTeX`)
- Parantezele drepte se scriu direct (nu au un inteles special `LaTeX`)
- Acoladele, deoarece ele sunt metacaractere de grupare, vor fi renderizate corect daca sunt `escapate` de intelesul lor special, punand in fata lor 'metacaracterul' `\`

*Exemplu:*

**Cod TeX**

```latex
$$a = (b+c)^{3x} - [3+6x]$$
```

**Cod TeX renderizat:**

$$a = (b+c)^{3x} - [3+6x]$$

<p> </p>

# Fractiile

**Sintaxa TeX:**

```latex
\frac{numarator}{numitor}
```


**Cod TeX**

```latex
$$ a = \frac{(a+bc)}{(d-c)} $$
```

**Cod TeX renderizat**

$$ a = \frac{(a+bc)}{(d-c)} $$

<p> </p>

# Semnele de 'multiplicare' si respectiv de 'diviziune'

*Exemple:*

```latex
$$ a = c + 10 \times x $$
```

$$ a = c + 10 \times x $$

```latex
$$ a = c + 10 \cdot x $$
```

$$ a = c + 10 \cdot x $$

```latex
$$ a = b \div c $$
```

$$ a = b \div c $$

<p> </p>

# `Suma` de la `i=0` la `n`

*Exemplu:*

```latex
$$ \sum_{i=0}^n i^2 = \frac{(a+b) \times (b+c)}{6} $$
```

$$ \sum_{i=0}^n i^2 = \frac{(a+b) \times (b+c)}{6} $$

<p> </p>

# Integrale

*Exemplu:*

```latex
$$ \int_0^1 x^4 dx $$
```

$$ \int_0^1 x^4 dx $$

***

[Up](#cuprins-pagina)

[Homepage](index)