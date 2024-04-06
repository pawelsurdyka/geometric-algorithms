Projekt

Przetwarzanie i przechowywanie opisu siatki trójkątnej na płaszczyźnie
Program powinien najpierw wczytać zawartość przykładowych triangulacji 2D, zapisanych w
postaci tekstowej jako lista punktów (dwie współrzędne rzeczywiste dla każdego punktu) oraz
lista elementów (każdy trójkąt opisany przez numery trzech wierzchołków, punkty
numerowane są od zera), a następnie zilustrować wczytaną siatkę. Kolejno program powinien
tworzyć odpowiednie struktury danych i odtwarzać brakujące obiekty/powiązania tak, aby
otrzymać reprezentację „Half Edge Data Structure”.

Porównać pod kątem kosztu pamięciowego i czasowego obie reprezentacje (bezpośrednio
pobraną z pliku – lista wierzchołków i tablica połączeń, oraz Half Edge Data Structure) przy
przeprowadzeniu następujących operacji (każdej z osobna):
  - OP1: wyznaczanie otoczenia dla wybranego wierzchołka (kolejne warstwy
  incydentnych wierzchołków – należy rozpatrzyć otoczenia składające się z jednej
  warstwy oraz dwóch warstw),
  - OP2: wyznaczanie otoczenia dla wybranego trójkąta (kolejne warstwy incydentnych
  trójkątów – należy rozpatrzyć otoczenia składające się z jednej warstwy oraz dwóch
  warstw),
  - OP3: przeglądanie incydentnych trójkątów od wybranego trójkąta w kierunku
  wybranego punktu (dla odszukania trójkąta zawierającego dany punkt).
  Program powinien mieć możliwość prezentowania w sposób graficzny etapów algorytmu dla
  wybranych przykładów (w celu objaśnienia działania algorytmu).
