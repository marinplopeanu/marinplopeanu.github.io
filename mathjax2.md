<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

![Text descriptiv Imagine](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=1100)

[Homepage](index.md)

***

# Cuprins pagina:

- [Scrierea matricelor `TeX` cu ajutorul `MathJax`](#scrierea-matricelor-tex-cu-ajutorul-mathjax)
    - [Posibilitati de scriere matrice](#posibilitati-de-scriere-matrice)
    - [Exemple](#alte-exemple)
- [Scrierea sistemelor de ecuatii](#scrierea-sistemelor-de-ecuatii)
    - [Sistem de cuatii cu numerotare automata](#sistem-de-cuatii-cu-numerotare-automata)
    - [Sistem de ecuatii, fara numerotare](#sistem-de-ecuatii-fara-numerotare)
    - [Sistem de ecuatii numerotat manual](#sistem-de-ecuatii-numerotat-manual)
    - [Sistem de ecuatii cu formule numerotate manual](#sistem-de-ecuatii-cu-formule-numerotate-manual)

***



# Scrierea matricelor `TeX` cu ajutorul `MathJax`

**Cod TeX:**

```latex
$$
A=
\begin{Vmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
\end{Vmatrix}
$$
```
**Cod TeX renderizat:**

$$
A=
\begin{Vmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
\end{Vmatrix}
$$

## Posibilitati de scriere matrice:
- `{pmatrix}`
- `{bmatrix}`
- `{Bmatrix}`
- `{vmatrix}`
- `{Vmatrix}`

## Alte exemple:

**Cod TeX:**

```latex
$$
A=
\begin{pmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
\end{pmatrix}
$$
```
**Cod TeX renderizat:**

$$
A=
\begin{pmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
\end{pmatrix}
$$

**Cod TeX:**

```latex
$$
A=
\begin{bmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
\end{bmatrix}
$$
```
**Cod TeX renderizat:**

$$
A=
\begin{bmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
\end{bmatrix}
$$

<p> </p>

[Up](#cuprins-pagina)

***

# Scrierea sistemelor de ecuatii

**Cod TeX:**

## Sistem de cuatii cu numerotare automata

```LaTeX
$$
\begin{align}
f(x) &= ax^2 \\
g(x) &= ax^2 + bx + c
\end{align}
$$
```
**Cod TeX renderizat:**

$$
\begin{align}
f(x) &= ax^2 \\
g(x) &= ax^2 + bx + c
\end{align}
$$

## Sistem de ecuatii, fara numerotare

**Cod TeX:**

```latex
$$
\begin{cases}
f(x) &= ax^2 \\
g(x) &= ax^2 + bx + c
\end{cases}
$$
```
**Cod TeX renderizat:**

$$
\begin{cases}
f(x) &= ax^2 \\
g(x) &= ax^2 + bx + c
\end{cases}
$$

## Sistem de ecuatii numerotat manual

```latex
$$
\begin{cases}
f(x) &= ax^2 \\
g(x) &= ax^2 + bx + c
\end{cases}
\tag{eq. 1}
$$
```
**Cod TeX renderizat:**

$$
\begin{cases}
f(x) &= ax^2 \\
g(x) &= ax^2 + bx + c
\end{cases}
\tag{eq. 10}
$$

## Sistem de ecuatii cu formule numerotate manual

```latex
$$
\begin{align}
f(x) &= ax^2 \tag{eq. 2} \\
g(x) &= ax^2 + bx + c \tag{eq. 3}
\end{align}
$$
```
**Cod TeX renderizat:**
$$
\begin{align}
f(x) &= ax^2 \tag{eq. 21} \\
g(x) &= ax^2 + bx + c \tag{eq. 22}
\end{align}
$$

***

[Up](#cuprins-pagina)

[Homepage](index)


