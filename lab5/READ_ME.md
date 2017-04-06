# PRM, laboratorium 5, semestr letni 2016/2017

----------------------------------------------

*Zakres materia�u*: Proste algorytmy sortowania (sortowanie b�belkowe, sortowanie przez wstawianie). (__5 pkt__)

----------------------------------------------

## __Zadanie 1.__ Analiza prostych algorytm�w sortowania.

1. W katalogu `prm4` utworzy� nowy projekt `zad1` i do g��wnego pliku projektu skopiowa� zawarto�� pliku �r�d�owego [zad1.c](zad1.c) i zapozna� si� z dzia�aniem programu.
2. Zapozna� si� z dzia�aniem obydwu algortym�w sortowania (funkcje `babelki` i `wstawianie`).
3. Odpowiedzie� na nast�puj�ce pytania:
	1. Ile por�wna� musi wykona� ka�dy z algorytm�w sortowania dla 5 elementowego ci�gu odwr�conego (np. 10, 5, 3, 1, 0) i ju� posortowanego (np. 0, 1, 3, 5, 10)? Wskaz�wka: wprowadzi� globaln� zmienn� zliczaj�ce liczb� wywo�a� funkcji `porownaj`.
	2. Jaka warto�� znajdzie si� na ko�cu tablicy tablica po pierwszej iteracji p�tli `do-while` w algorytmie `babelki`? Jak opieraj�c si� na tej obserwacji mo�na przyspieszy� algorytm?
	3. Dlaczego w warunku p�tli `while` w algorytmie `wstawianie` najpierw sprawdzany jest warunek na zmienn� `j`, a nast�pnie dopiero jest wywo�ywana funkcja `porownaj`?
	4. Jaka prosta modyfikacja pozwoli zmieni� porz�dek sortowanie obydwy algorytm�w z rosn�cego na malej�cy?

## __Zadanie 2.__ Wykorzystanie algorytm�w.

Tre�� zadania zostanie podana przez prowadz�cego w trakcie zaj��