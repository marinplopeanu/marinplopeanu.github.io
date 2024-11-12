<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

![Text descriptiv Imagine](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=1100)

[Homepage](index.md)

***

# Cuprins pagina:

- [Scrierea matricelor `TeX` cu ajutorul `MathJax`](#scrierea-matricelor-tex-cu-ajutorul-mathjax)
    - [Posibilitati de scriere matrice](#posibilitati-de-scriere-matrice)
    - [Exemple](#alte-exemple)
- [Scrierea sistemelor de ecuatii](#scrierea-sistemelor-de-ecuatii)
    - [Varianta 1](#varianta-1)
    - [Varianta 2](#varianta-2)

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

## Varianta 1

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

## Varianta 2

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

***

[Up](#cuprins-pagina)

[Homepage](index)


