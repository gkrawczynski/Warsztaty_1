<img alt="Logo" src="http://coderslab.pl/svg/logo-coderslab.svg" width="400">


### Zadanie 1,  Gra w zgadywanie liczb

Napisz prostą grę w zgadywanie liczb. Komputer ma wylosować liczbę w zakresie od 1 do 100.
Następnie:
1. wypisać: "Zgadnij liczbę" i pobrać liczbę z klawiatury;

2. sprawdzić, czy wprowadzony napis, to rzeczywiście liczba i w razie błędu wyświetlić komunikat: "To
nie jest liczba", po czym wrócić do pkt. 1;

3. jeśli liczba podana przez użytkownika jest mniejsza niż wylosowana, wyświetlić komunikat: "Za
mało!", po czym wrócić do pkt. 1;

4. jeśli liczba podana przez użytkownika jest większa niż wylosowana, wyświetlić komunikat: "Za
dużo!", po czym wrócić do pkt. 1;

5. jeśli liczba podana przez użytkownika jest równa wylosowanej, wyświetlić komunikat: "Zgadłeś!", po
czym zakończyć działanie programu.



#### Zadanie 2

W pliku `Main2.java` stwórz metodę o sygnaturze `static int count(String fileName)`.

1. Uzupełnij ciało metody tak, aby zliczyła i zwracała ilość słów z pliku.

#### Zadanie 3

W pliku `Main3.java` napisz program, który:

1. Pobierze z konsoli nazwę pliku.
2. Wczyta dane w określonym formacie:

Nazwisko Imie RokUrodzenia Płeć np:

```
Kowalski Marek 1955 M
Krzak Marianna 1966 K
```

3. Stworzy i zwróci tablicę String (imię + nazwisko) osób które mogą przejść na emeryturę,
sygnatura metody `static String[] retirement()`.
Dla kobiet będzie to 60 lat, dla mężczyzn 65.

#### Zadanie 4

W pliku `Main4.java` stwórz metodę o sygnaturze `static int[] sortedArray()`.

1. Uzupełnij ciało metody tak, aby wczytała z konsoli ile liczb należy wylosować.
2. Stworzy tablicę oraz umieść w niej losowe wartości z zakresu [0,100].
3. Posortuje elementy tablicy a następnie ją zwróci.

#### Zadanie 5

W pliku `Main5.java` stwórz metodę o sygnaturze `static void printTriangle()`.

1. Uzupełnij ciało metody tak, aby wczytała z konsoli wartość typu int.
2. Wypisze na konsoli trójkąt zbudowany ze znaku `x`, w którym obie przyprostokątne będą równe wczytanej wartości
Przykład dla wczytanej wartości równej 5.
