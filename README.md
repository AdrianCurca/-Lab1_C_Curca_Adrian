Lucrarea de laborator nr. 1
Tema: Utilizarea instrucţiunilor de control şi ciclice în limbajul C

Scopul lucrării
Studierea și aplicarea instrucțiunilor de control (if, else if, else) și a instrucțiunilor ciclice (while) în limbajul C pentru tabularea funcției F(x) definită prin trei expresii condiționale.

Descriere succintă a programului
Programul citește valorile de intrare x1, x2, px, a, b, c, apoi calculează funcția F(x) pentru fiecare valoare a lui x din intervalul [x1, x2] cu pasul px.
În funcție de condițiile impuse, F(x) este calculată folosind una dintre cele trei formule. Programul utilizează instrucțiuni condiționale, cicluri repetitiv while și funcții matematice din biblioteca <math.h>.

Pentru compilarea programului în limbajul C utilizați comanda:
gcc main.c -o program -lm

Exemplu de rulare:
Introduceți x1, x2, px, a, b, c:
4 8 0.4 5 6 7

   n        x             F(x)
   1     4.000000     1.611143
   2     4.400000     1.526229
   3     4.800000     1.463906
   4     5.200000     1.418902
