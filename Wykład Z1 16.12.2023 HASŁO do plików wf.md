Wykład Z1 16.12.2023 HASŁO do plików: wf
========================
KLASA TO TYP DANYCH
--
T: Wstępny wykład
---
Języki z przedmiotu: C++ i Java
Egzamin na ostatnim wykładzie (20.04 <- dwudziestego kwietnia (zerówka))
Polecane książki: 
* Bruce Eckel, Thinking in Java. Wydanie IV
* Marcin Lis, praktyczny kurs Java. Wydanie II

Strona gościa: www.jczerniak.ukw.edu.pl <- Strona wykładowcy

Java
---
* Wzięła składnie i wiele rzeczy  z C++ a maszynę wirtualną i kilka innych rzeczy z języka Smalltalk
* Java tworzy maszynę wirtualną która potem działa na każdym systemie operacyjnym


Polimorfizm, enkapsulacja i dziedziczenie
---
Polimorfizm: wskaźnik na klase rodzica jest w stanie wywołać odziedziczoną metodę z klasy dziecka
Enkapsulacja/hermetyzacja: modyfikatory dostępu (private, public, protected)
Dziedziczenie: czyli zachowanie konkretnych właściwości z klasy rodzica
Abstrakcja: Nie można stworzyć obiektu klasy abstrakcyjnej. Służy ona jako klasa rodzic aby w zaplanowany sposób połączyć wiele klas

W C++ jako w jedynym języku można dziedziczyć z więcej niż jednej klasy
W Javie jest jedna klasa Matka z której dziedziczą wszystkie nasze stworzone klasy. Oczywiście możesz stworzyć klasę która dziedziczy z twojej klasy ale nie zmieni to faktu że pierwszą bazową klasą będzie Klasa Object (Java)


