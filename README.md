# 📘 Formulario: Sviluppi di Taylor

## 🔸 Sviluppo di Taylor intorno a `x = a`:

![Taylor Formula](https://latex.codecogs.com/svg.image?f(x)=\sum_{n=0}^{\infty}\frac{f^{(n)}(a)}{n!}(x-a)^n)

## 🔹 Sviluppo di Maclaurin (caso particolare con `a = 0`):

![Maclaurin Formula](https://latex.codecogs.com/svg.image?f(x)=\sum_{n=0}^{\infty}\frac{f^{(n)}(0)}{n!}x^n)

## 📌 Sviluppi Notevoli

| Funzione         | Sviluppo (intorno a 0)                                                                 | Raggio di Convergenza |
|------------------|----------------------------------------------------------------------------------------|------------------------|
| ![e^x](https://latex.codecogs.com/svg.image?e^x) | ![\sum_{n=0}^{\infty} \frac{x^n}{n!}](https://latex.codecogs.com/svg.image?\sum_{n=0}^{\infty} \frac{x^n}{n!}) | ![\infty](https://latex.codecogs.com/svg.image?\infty) |
| ![\sin x](https://latex.codecogs.com/svg.image?\sin x) | ![\sum_{n=0}^{\infty} (-1)^n \frac{x^{2n+1}}{(2n+1)!}](https://latex.codecogs.com/svg.image?\sum_{n=0}^{\infty} (-1)^n \frac{x^{2n+1}}{(2n+1)!}) | ![\infty](https://latex.codecogs.com/svg.image?\infty) |
| ![\cos x](https://latex.codecogs.com/svg.image?\cos x) | ![\sum_{n=0}^{\infty} (-1)^n \frac{x^{2n}}{(2n)!}](https://latex.codecogs.com/svg.image?\sum_{n=0}^{\infty} (-1)^n \frac{x^{2n}}{(2n)!}) | ![\infty](https://latex.codecogs.com/svg.image?\infty) |
| ![\ln(1 + x)](https://latex.codecogs.com/svg.image?\ln(1+x)) | ![\sum_{n=1}^{\infty} (-1)^{n+1} \frac{x^n}{n}](https://latex.codecogs.com/svg.image?\sum_{n=1}^{\infty} (-1)^{n+1} \frac{x^n}{n}) | ![|x|<1](https://latex.codecogs.com/svg.image?|x|<1) |
| ![\frac{1}{1 - x}](https://latex.codecogs.com/svg.image?\frac{1}{1 - x}) | ![\sum_{n=0}^{\infty} x^n](https://latex.codecogs.com/svg.image?\sum_{n=0}^{\infty} x^n) | ![|x|<1](https://latex.codecogs.com/svg.image?|x|<1) |
| ![(1 + x)^k](https://latex.codecogs.com/svg.image?(1+x)^k) | ![\sum_{n=0}^{\infty} \binom{k}{n} x^n](https://latex.codecogs.com/svg.image?\sum_{n=0}^{\infty} \binom{k}{n} x^n) | ![|x|<1](https://latex.codecogs.com/svg.image?|x|<1) |

## 🔻 Resto di Lagrange

![Resto di Lagrange](https://latex.codecogs.com/svg.image?R_n(x)=\frac{f^{(n+1)}(\xi)}{(n+1)!}(x-a)^{n+1},\quad\xi\in(a,x))
