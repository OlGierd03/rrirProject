## rrirProject

Projekt zrealizowano w ramach przedmiotu *Równania Różniczkowe i Różnicowe* na AGH, rok akademicki 2023/24.

## Opis problemu

Należało znaleźć funkcję
$\varphi: [0,3] \to \mathbb{R}$
spełniającą następujące równanie różniczkowe:

$$
\frac{d^2 \varphi}{dx^2} = -\frac{\rho}{\varepsilon_r}
$$

z warunkami brzegowymi:

$$
\varphi'(0) + \varphi(0) = 5
$$

$$
\varphi(3) = 2
$$

oraz zadanymi parametrami:

$$
\rho = 1
$$

$$
\varepsilon_r =
\begin{cases}
10, & x \in [0,1] \\
5, & x \in (1,2] \\
1, & x \in (2,3]
\end{cases}
$$

## Struktura projektu

- [**`main.py`**](https://github.com/OlGierd03/rrirProject/blob/main/main.py) – skrypt rozwiązujący równanie różniczkowe
- [**`README.md`**](https://github.com/OlGierd03/rrirProject/blob/main/README.md) – ten plik, zawierający opis problemu
- [**`rrir_notebook.ipynb`**](https://github.com/OlGierd03/rrirProject/blob/main/rrir_notebook.ipynb) – notatnik zawierający rozwiązanie problemu wraz z otrzymanymi wynikami
- [**`sformułowanie_wariacyjne.pdf`**](https://github.com/OlGierd03/rrirProject/blob/main/sformu%C5%82owanie_wariacyjne.pdf) – obliczenia przekształcające sformułowanie silne na sformułowanie wariacyjne 

## Wymagania

- Python 3.x
- Biblioteki: NumPy, Matplotlib

## Uruchomienie

Instalacja wymaganych bibliotek:
```bash
pip install numpy matplotlib
