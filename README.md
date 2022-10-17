# Kaufman_Roberts_in_Python

<p align="center">
<img width="747" alt="Zrzut ekranu 2022-10-17 o 16 19 15" src="https://user-images.githubusercontent.com/61777542/196201575-b3fab542-fd10-4af8-b6a4-07127da5565d.png">
</p>

## Analizując wyniki programu obserwujemy:
- Blokada w wiązce doskonałej dla zgłoszeń klasy i występuje tylko wtedy, gdy wiązka nie dysponuje ti wolnymi podstawowymi jednostkami pasma, niezbędnymi do obsługi obsługi zgłoszeń tej klasy. Prawdopodobieństwo blokady dla zgłoszeń klasy i może być zatem określone na podstawie następującego wzoru:

<p align="center">
<img width="205" alt="Zrzut ekranu 2022-10-17 o 18 25 45" src="https://user-images.githubusercontent.com/61777542/196231424-760653e5-2f05-4715-a039-42660eade120.png">
</p>


- Od pojemności V, czyli liczby kanałów zależy prawdopodobieństwo blokady dowolnego strumienia zgłoszeń, im więcej kanałów tym mamy mniejszą szansę na blokadę (dla pojemności V kierującej się do 0 b(i) leci do 1, analogicznie V dążącego do nieskończoności b(i) dąży do 0)

- Prawdopodobieństwo blokady dla klasy 2 przyjmuje wartość 1, oznacza to że blokada będzie miała miejsce

<p align="center">
<img width="299" alt="Zrzut ekranu 2022-10-17 o 18 28 14" src="https://user-images.githubusercontent.com/61777542/196231938-59cda967-6207-469c-9833-bb4d4be6d3fc.png">
</p>

- Prawdopodobieństwo blokady dla obu klas, gdy V=10 jest znacznie niższe niż poprzednio, ponieważ V to liczba kanałów (kolokwialnie mówiąc mamy więcej miejsca)

<p align="center">
<img width="722" alt="Zrzut ekranu 2022-10-17 o 18 28 40" src="https://user-images.githubusercontent.com/61777542/196232033-1dfcbf48-5625-49f1-bf2d-46437d6b1614.png">
</p>

- Podobna sytuacja ma miejsce z natężeniem ruchu. Gdy zwiększamy wartość natężenia ruchu zwiększa się prawdopodobieństwo blokady, wtedy też rośnie prawdopodobieństwo sytuacji, w której zajęta jest część lub wszystkie kanały

<p align="center">
<img width="546" alt="Zrzut ekranu 2022-10-17 o 18 29 13" src="https://user-images.githubusercontent.com/61777542/196232143-efed41db-9152-4868-bae7-e5c698839afd.png">
</p>

- Gdy porównujemy b(i) dla różnych zestawów danych a(i) nasze prawdopodobieństwo blokady znacznie się zwiększyło
