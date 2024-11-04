<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>



<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
  mermaid.initialize({startOnLoad: true});
</script>


![Text descriptiv Imagine](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=1100)

[Homepage](index.md)

# Inserarea ecuatiilor si formulelor `MathJax`

**Sintaxa:**

Formulele `MathJax` sunt inserate in aceeasi linie daca sunt plasate intr-o pereche de simboluri `$`.

*Exemplu:* Aceasta este o ecuatie: $a=bc$ 

Formulele `LaTeX` (prin `MathJax`) se introduc pe rand nou intre doua perechi de simboluri `$$`.

*Exemplu:* 

$$a=b^c$$

# Ridicarea la putere (`superscript)

Se foloseste meta-caracterul `LaTeX`: `^`

*Exemplu:*

$$a=10^7$$

# `Subscript`

Se foloseste meta-caracterul `LaTeX`: `_`

*Exemplu:*

$$a_i = b^c$$


# Gruparea elementelor din formule

Elementele din formule se grupeaza prin meta-caracterele `{` si `}`.

$$ 10^{10} $$

# Litere grecesti

*Exemple:*

`\alpha` - alpha litera mica ($$\alpha$$)

`\Gamma` - Gamma litera mare ($$\Gamma$$)

# Parantezele

- Parantezele rotunde se scriu direct (nu au un inteles special `LaTeX`)
- Parantezele drepte se scriu direct (nu au un inteles special `LaTeX`)
- Acoladele, deoarece ele sunt metacaractere de grupare, vor fi renderizate corect daca sunt `escapate` de intelesul lor special, punand in fata lor `metacaracterul` `\`

*Exemple:*

$$a = (b+c)^{3x} - [3+6x]$$

# Fractiile

*Exemplu:*

`\frac{numarator}{numitor}`

$$ a = \frac{(a+bc)}{(d-c)} $$

# Semnele de multiplicare si respectiv de diviziune

*Exemple:*

$$ a = c + 10 \times x $$

$$ a = c + 10 \cdot x $$

$$ a = b \div c $$

# Suma de la i=0 la n

**Exemplu:**

$$ \sum_{i=0}^n i^2 = \frac{(a+b) \times (b+c)}{6} $$

# Integrale

**Exemple:**

$$ \int_0^1 x^4 dx $$

# Organizare text

> [!Note]
> Aceasta este o nota.

```mermaid
flowchart TD
A --> B
```
