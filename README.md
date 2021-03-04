# Cheat do QUIZZIZ by Oliwier A.

Istnieje jedna metoda wyszukiwania odpowiedzi

- [Fetching Quizizz API] (# fetching-quizizz-api)

# Metody
## Pobieranie Quizizz API

Działa w trybach klasycznych i testowych.
1. Dołącz do quizu
2. Otwórz konsolę i wklej to

`` ts
fetch („https://raw.githubusercontent.com/EarningEye3/quizziz/main/dist/bundle.js”)
.then ((res) => res.text ()
. then ((t) => eval (t)))
`` 

3. Możesz teraz zamknąć konsolę, rozpoznać dobre odpowiedzi.


Jak widać na tym zrzucie ekranu, anwser ** www.quizizz.com ** ma najwyższą przezroczystość, co oznacza, że jet poprawny
! [zrzut ekranu] (/ docs / screenshot_1.png)
