# WDM. Lab. 1. Wprowadzenie do Python

Zapoznaj się z zawartością notatnika Jupyter umieszczonego w repozytorium  i wykonaj zawarte w nim ćwiczenia.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/IS-UMK/wdm_lab_01/blob/master/01_Wprowadzenie.ipynb) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/IS-UMK/wdm_lab_01/master?filepath=01_Wprowadzenie.ipynb)

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

Rozwiązanie umieść w notatniku z zajęć. Zapisz notatnik i wyślij  do repozytorium GitHub lub umieść w Moodle pod adresem [https://moodle.umk.pl/mod/assign/view.php?id=291467](https://moodle.umk.pl/mod/assign/view.php?id=291467)

---
## Materiały:

* https://www.varsitytutors.com/hotmath/hotmath_help/topics/line-of-best-fit
