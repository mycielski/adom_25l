# Sprawdzian 29.04.2025

## Laboratorium ADOM, sprawdzian 
 
Sprawdzian składa się z następujących zadań, które należy zrealizować w Pythonie (Jupter Notebook), :
 
1. Wczytaj i wyświetl otrzymany plik zawierający obraz wejściowy przydzielonego przez prowadzącego (mapa Polski) -> 1 pkt
2. Odczytać nazwę województwa referencyjnego -> 4 pkt
3. Wykonaj segmentację koloru obrazu wejściowego, w wyniku której powstanie obraz binarny zawierający wszystkie obszary mapy o kolorze takim jak kolor, jakim zaznaczono województwo, które masz wyodrębnić z obrazu wejściowego (województwo referencyjne)-> 4 pkt
4.  Obraz wynikowy należy przefiltrować tak, by składał się z obszarów jednolitych, tj. bez śladów po rzekach, nazwach państw i innych dodatków -> 4 pkt
5. Następnie należy spośród wszystkich takich obszarów wyodrębnić województwo referencyjne. W tym celu można ustawić wartość dokładnie jednego wybranego piksela obrazu (np. "im(100,100) = 1") lub wyznaczyć obraz zawierający prostokątną maskę o samodzielnie ustalonych rozmiarach -> 4 pkt
6. Wygeneruj obraz wynikowy, w którym wyodrębnione województwo zostanie pokolorowane kolorem takim jak na obrazie początkowym, zaś tło będzie kolorem dopełniającym tj. dla [r,g,b] kolorem takim jest [1-r,1-g,1-b] (jeśli $0\leq r$,g,$b\leq 1$) ->  3 pkt

Uwaga -- punkty 4 i 5 można wykonać w dowolnej kolejności.

Plik zgodny z poniższymi założeniami należy wgrać w miejsce wskazane przez prowadzącego

1. nazwa pliku: "ADOM_sprawdzian_Imię_Nazwisko" (każdy wpisuje swoje imię i nazwisko)

2. w pierwszej linii pliku, w komentarzu -- imię, nazwisko, datę, numer obrazu przydzielonego przez prowadzącego

3. Kod realizujący kolejno wykonane zadania, każde poprzedzone nagłówkiem z komentarzem "zadanie 1" itp
 