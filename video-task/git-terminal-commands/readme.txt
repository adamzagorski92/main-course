Komendy:
- pwd // sprawdzamy w którym miejscu jesteśmy
- cd // (skrót od change directory) - przenosi tam gdzie chcemy
- cd ~ // ten skrót przenosi do folderu domowego
- strzałki pozwalają wracać do ostatnich instrukcji,
- clear // czyści okienko, jesli mamy mnóstwo instrukcji to warto czasem je wyczyścić
- cd .. // ten znak powoduje, że przechodzimy folder wyżej,
- ls // listuje zawartość obecnego folderu
 - ls -a // listuje również pliki ukryte
 - ls -l // listuje szczegóły plików
 - można łączyć komendy, na przykład ls -la // listuje wszystkie pliki i szczegóły
 - mkdir nazwa-katalogu // tworzy nowy katalog
 - cd nazwa-katalogu // przechodzi do katalogu jeśli podamy dobrą nazwę 
    (wskazówka, jeśli raz kliknę TAB po wpisaniu literki, to wyskoczy mi
     nazwa katalogu jesli na taką literkę jest jakiś katalog,
     dodatkowo jeśli jest więcej katalogów na tę literkę, to
     po pierwszym kliknięciu TAB nie wyskoczy nic, natomiast po drugim
     razie rozwinie się lista do wyboru)
 - touch nazwa-pliku.rozszerzenie // tworzy plik
 - rm nazwa-pliku.rozszerzenie // usuwa plik
 - rm -r nazwa-katalogu.rozszerzenie // usuwaj rekursywnie, czyli usuń również,
    wszystko co znajduje się w katalogu (zwykłe rm dla katalogu nie zadziała)
 - cp nazwa-pliku.rozszerzenie /ścieżka/do/katalogu/kopii // (jeśli plik
    znajdowałby się w innym  miejscu, niż katalog, w którym aktualnie
    jesteśmy, to należy najpierw podać jego ścieżkę i nazwę, a następnie,
    podać ścieżkę, gdzie ten plik ma zostać skopiowany)
 - mv // (konstrukcja jest identyczna jak cp, tylko ta funkcja move przenosi plik)
 - mv nazwa-pliku.rozszerzenie nowa-nazwa-pliku.rozszerzenie // (zmienia nazwę),
    gdybym podał jeszcze nowy adres katalogu, to funkcja jednocześnie
    przeniosłaby zmieniony plik w to miejsce
 - cat nazwa-pliku.rozszerzenie // wylistuje zawartość tego pliku
 - echo "tekst, który chcę dodać" > nazwa-pliku.rozszerzenie // (towrzy plik i dodaje tekst do niego)
 - echo "tekst, który chcę dodać" >> nazwa-pliku.rozszerzenie // (dodaje tekst do już stworzonego pliku)
 - cat > nazwa-pliku.rozszerzenie // dodaje większy blok tekstu (po wpisaniu ctrl+D)
 - cat nazwa-pliku.rozszerzenie // listuje zawartość pliku 


 

