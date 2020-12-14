---
title: "Hola"
date: 2020-12-12T13:13:42-04:00
draft: false
math: true
---

sdfasdfa

\begin{equation}
I = \int \rho R^{2} dV
\end{equation}
:kissing:

:kissing:

$$E_0 $$

Inline math: $$ \varphi = \dfrac{1+\sqrt5}{2}= 1.6180339887… $$

Block math:

`$ \sigma(t) = \cfrac{1}{1 + e^{-t}} $`

{{ if or .Params.math .Site.Params.math }}
{{ partial "math.html" . }}
{{ end }}