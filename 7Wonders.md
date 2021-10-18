##SevenWondersPointCounter

### Technologia
- Aplikacja consolowa
- C++
- Zapis w pliku txt

### uruchomienie aplikacji:

- użytkownik widzi menu z opcjami:
    - Zliczanie punktów
    - Historia


#### Zliczanie punktów
- Użytkownik podaje graczy po spacji np.
```text
Magda Kuba Marlena Bartek Alan
```
- następnie w kolejnosci są podawane punkty np.
```text
Gracz Magda (punkty militarne): -4
Gracz Kuba (punkty militarne): 2
itd.
```
- Kolejka jest wykonwyana do zaczytania wszystkich danych przez wszystkich userów

- Następnie występuje wyświetlenie wyniku np.
```text
Magda zwyciężyła / Bartek zwyciężył mając 60 punktów '<- rozpoznaj płeć gracza'
Marlena 32 punktów
Bartek 30 punktów
Kuba 14 punktów
```
- Następnie wyniki są zapisywane do pliku


#### Historia
- Użytkownik widzi listę:
 ```text
Gracze:
    Magda:
        Gier: 4
        Wygranych: 3
        Średnia ilość punktów: 60
        Maksymalna ilość punktów: 72
    Kuba: 
        Gier 3
        Wygranych: 3
        Średnia ilość punktów: 52
        Maksymalna ilość punktów: 60
        
```
- Graczę są posegregowani od ilości wygranych

