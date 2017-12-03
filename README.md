# Zadanie_domowe

Dwójkowy system liczbowy, system binarny – pozycyjny system liczbowy, w którym podstawą jest liczba 2. Do zapisu liczb potrzebne są tylko dwie cyfry: 0 i 1.
Powszechnie używany w elektronice cyfrowej, gdzie minimalizacja liczby stanów (do dwóch) pozwala na prostą implementację sprzętową odpowiadającą zazwyczaj stanom wyłączony i włączony oraz zminimalizowanie przekłamań danych. Co za tym idzie, przyjął się też w informatyce.
Jak w każdym pozycyjnym systemie liczbowym, liczby zapisuje się tu jako ciągi cyfr, z których każda jest mnożną kolejnej potęgi podstawy systemu. Np. liczba zapisana w dziesiętnym systemie liczbowym jako 7, w systemie dwójkowym przybiera postać 0111(2), gdyż:
0111(2) = 0·23 + 1·22 + 1·21 +1·20 = 0 + 4 + 2 + 1 = 7(10)
{\displaystyle 1\cdot 2^{3}+0\cdot 2^{2}+1\cdot 2^{1}+0\cdot 2^{0}=8+2=10.\;}


{\displaystyle 10101_{2}=21_{10}\;}
Ósemkowy system liczbowy – pozycyjny system liczbowy o podstawie 8. System ósemkowy jest czasem nazywany oktalnym od słowa octal. Do zapisu liczb używa się w nim ośmiu cyfr, od 0 do 7.
Jak w każdym pozycyjnym systemie liczbowym, liczby zapisuje się tu jako ciągi cyfr, z których każda jest mnożnikiem kolejnej potęgi liczby będącej podstawą systemu, np. liczba zapisana w dziesiętnym systemie liczbowym jako 100, w ósemkowym przybiera postać 144, gdyż:
1×82 + 4×81 + 4×80 = 64 + 32 + 4 = 100.
W matematyce liczby w systemach niedziesiętnych oznacza się czasami indeksem dolnym zapisanym w systemie dziesiętnym, a oznaczającym podstawę systemu, np. 1448 = 10010.

Szesnastkowy system liczbowy znany również pod nazwą system heksadecymalny – pozycyjny system liczbowy, w którym podstawą jest liczba 16. Do zapisu liczb w tym systemie potrzebne jest szesnaście znaków (cyfr szesnastkowych).
W najpowszechniejszym standardzie poza cyframi dziesiętnymi od 0 do 9 używa się pierwszych sześciu liter alfabetu łacińskiego: A, B, C, D, E, F (wielkich lub małych). Cyfry 0-9 mają te same wartości co w systemie dziesiętnym, natomiast litery odpowiadają następującym wartościom: A = 10, B = 11, C = 12, D = 13, E = 14 oraz F = 15.
Jak w każdym pozycyjnym systemie liczbowym, liczby zapisuje się tu jako ciągi znaków, z których każdy jest mnożnikiem kolejnej potęgi liczby stanowiącej podstawę systemu. Np. liczba zapisana w dziesiętnym systemie liczbowym jako 213, w systemie szesnastkowym przybiera postać D5, gdyż:

D5(16) = D·161 + 5·160 = 13·16 +5·1 = 213(10)
Z racji budowy komputerów, w której np. adresy są potęgą liczby 2 oraz dzielą się przez 8 i 16, często stosowany jest system heksadecymalny.
Wartość pojedynczego bajta można opisać używając tylko dwóch cyfr szesnastkowych i odwrotnie - dowolne dwie cyfry szesnastkowe można zapisać jako bajt. W ten sposób kolejne bajty można łatwo przedstawić w postaci ciągu cyfr szesnastkowych. Jednocześnie zapis 4 bitów można prosto przełożyć na jedną cyfrę szesnastkową, podczas gdy np. pozycyjny system dziesiętny nie ma własności stałej liczby bitów na cyfrę.
System szesnastkowy sprawdza się szczególnie przy zapisie dużych liczb, takich jak adresy pamięci, zakresy parametrów itp.
{\displaystyle 3\times 16^{2}+14\times 16^{1}+8\times 16^{0}=768+224+8=1000\;}


Zamiana z systemu dziesiętnego na binarny i odwrotnie

Metoda zamiany liczby z systemu dziesiętnego na dwójkowy polega na dzieleniu liczby przez 2 i zapamiętywanie reszty z tego dzielenia. Następnie dzielimy przez 2 wynik poprzedniego dzielenia aż do otrzymania liczby 0.

67
1

67:2
= 33 reszty 1
33
1

33:2
= 16 reszty 1
16
0
↑
16:2
= 8 reszty 0
8
0

8:2 = 4 reszty 0
4
0

4:2 = 2 reszty 0
2
0

2:2 = 1 reszty 0
1
1

1:2 = 0 reszty 1
0





1000011(2) = 1·26 +0·25 + 0·24 + 0·23 + 0·22 + 1·21 + 1·20 = 64 + 2 + 1 = 67(10)
Zamiana z systemu binarnego na szesnastkowy i odwrotnie

Dwójkowy




Szesnastkowy

0000
0


0001



1

0010
2


0011



3

0100
4


0101



5

0110
6


0111



7

1000
8


1001



9

1010




A

1011




B

1100




C

1101




D

1110




E

1111




F



DWÓJKOWY  SZESNASTKOWY

1110000010111011101(2) = ………………..(16)

Grupujemy po cztery cyfry (od prawej do lewej). Dopisujemy 0 na początku, aby powstała grupa czterech cyfr.


0111 0000 0101 1101 1101

7	0	5	D	D

Zapisujemy już w kolejności takiej samej.

    A więc 1110000010111011101(2) = 705DD(16)


SZESNASTKOWY  DWÓJKOWY

4D5A12(16) = ………………..(2)

Zamieniamy każdą z cyfr lub liter liczby szesnastkowej na jej odpowiednik binarny z tabelki.

4	D	5	A	1	2
0100 1101 0101 1010 0001 0010

Zapisujemy w takiej samej kolejności, a więc 4D5A12(16) = 010011010101101000010010(2)
