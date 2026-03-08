# WDM. Lab. 1. Wprowadzenie do Python

* [01_Wprowadzenie.ipynb](01_Wprowadzenie.ipynb) - notatnik z materiałem i ćwiczeniami z laboratorium  
* [zadanie.ipynb](zadanie.ipynb) - notatnik, w którym powinno znaleźć się rozwiązanie zadania z laboratorium

---

## Zad. 1. Metoda najmniejszych kwadratów

Napisz program, który wyznaczy współczynniki $a$ i $b$ funkcji liniowej $f(x) = ax+b$ dopasowanej do danych pomiarowych za pomocą metody najmniejszych kwadratów.

|Dane pomiarowe |||||||||||
|-|-|-|-|-|-|-|-|-|-|-|
| **x** | 8 | 2  | 11 | 6 | 5 | 4 | 12 | 9 | 6 | 1  |
| **y** | 3 | 10 | 3 | 6 | 8 | 12 | 1  | 4 | 9 | 14 |

Dla danych pomiarowych $[x_1, x_2, \ldots, x_n]$ oraz $[y_1, y_2, \ldots, y_n]$ wykonaj nastepujace kroki:

1. Wyznacz wartości średnie
   $$\bar{x}=\frac{1}{n}\sum_{i=1}^n x_i, \qquad \bar{y}=\frac{1}{n}\sum_{i=1}^n y_i$$
2. Wyznacz wsp. nachylenia prostej
   $$a = \frac{\sum_{i=1}^n\left(x_i-\bar{x}\right)\left(y_i-\bar{y}\right)}{\sum_{i=1}^n\left(x_i-\bar{x}\right)^2}$$
3. Wyznacz wyraz wolny z równania
   $$b = \bar{y} - a\bar{x}$$

Do rozwiązania zadania użyj podstawowych funkcji języka Python (instrukcje warunkowe, pętle, funkcje, listy). Nie używaj bibliotek takich jak NumPy, SciPy, Pandas itp.

Rozwiązanie umieść w notatniku [zadanie.ipynb](zadanie.ipynb).  Zapisz notatnik i umieść w repozytorium GitHub.

---
## Materiały:

* https://www.varsitytutors.com/hotmath/hotmath_help/topics/line-of-best-fit
