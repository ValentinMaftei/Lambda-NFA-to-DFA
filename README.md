# Lambda-NFA-to-DFA

[Română :romania:](#date)

[English :eu:](#data)

# Date

Daca exista mai multe trasee posibile, se va afisa doar primul gasit.

Datele de intrare contin pe prima linie n (numarul de noduri) si m (numarul de tranzitii). 
Pe urmatoarele m linii sunt descrise tranzitiile din fiecare automat.
Pe linia m + 2 se afla indicele starii initiale. Pe linia m + 3 se afla un numar nf (numarul de stari finale) urmat de indicii starilor finale respective, separate prin spatiu. Linia m+ 4 contine ni, numarul de string-uri de input, iar pe urmatoarele ni linii, string-urile respective.

Datele de iesire, pentru fiecare string: contin DA, daca cuvantul este acceptat si un traseu posibil, respectiv NU, in caz contrar.

Exemplu de date introduse în fisier:

```7 20
0 0 a
0 1 a
0 2 b
0 2 #
0 3 #
1 2 #
2 3 a
2 4 #
3 3 b
3 5 #
3 6 a
3 6 b
4 5 b
4 6 a
4 6 #
5 6 a
5 2 b
5 2 #
5 6 #
6 6 b
0
2 2 6
```

Automatul rezultat:

![6](https://user-images.githubusercontent.com/91968875/212747660-702dbeb8-8108-47c6-a0be-59dda33dcedc.png)


# Data

If there are multiple possible routes, only the first one found will be displayed.

The input data contains on the first line n (the number of nodes) and m (the number of transitions).
On the following m lines, the transitions of each automaton are described.
On line m + 2 is the index of the initial state. On line m + 3 is a number nf (the number of final states) followed by the indices of the final states, separated by a space. Line m+ 4 contains ni, the number of input strings, and on the following ni lines, the strings themselves.

The output data, for each string: contains YES, if the word is accepted and a possible route, or NO, otherwise.

Example input data in file:

```7 20
0 0 a
0 1 a
0 2 b
0 2 #
0 3 #
1 2 #
2 3 a
2 4 #
3 3 b
3 5 #
3 6 a
3 6 b
4 5 b
4 6 a
4 6 #
5 6 a
5 2 b
5 2 #
5 6 #
6 6 b
0
2 2 6
```

The resulting automaton:

![6](https://user-images.githubusercontent.com/91968875/212747660-702dbeb8-8108-47c6-a0be-59dda33dcedc.png)
