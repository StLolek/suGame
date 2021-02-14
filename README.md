# Gra tekstowa typu SUD

## Podstawy
Gracz tworzony na podstawie klasy z bazowymi statystykami dostosowanymi do wybranego typu postaci oraz płci. Statystyki postaci można rozbudować, na podstawie przedmiotów założonych na postaci. Gracz posiada inwentarz, który pokazuje przedmioty obecnie założone przez gracza, oraz plecak, w którym gracz przechowuje pozostałe przedmioty, np. jedzenie, notatki itp. Gracz będzie również posiadał level, zwiększany poprzez doświadczenie dostawane podczas walk oraz wykonywania innych czynności.
## Dostępne typy postaci
### Rycerz
1. **Bazowe silne strony:**
    - Siła
    - Wytrzymałość
    - Szczęście
2. **Bazowe słabe strony:**
    - Zręczność
    - Inteligencja
### Mag
1. **Bazowe silne strony:**
    - Inteligencja
    - Wytrzymałość
    - Szczęście
2. **Bazowe słabe strony:**
    - Siła
    - Zręczność

## Co oznaczają statystyki gracza w walce
1. **Siła** - będzie składać się z dwóch wartości. Główna statystyka potrzebna rycerzowi.
      - minimalna wartość, którą można zadać podczas ataku bronią białą.
      - maksymalna wartość, którą można zadać podczas ataku bronią białą.
   
   Bazowa wartość siły będzie ustalana na podstawie poziomu postaci oraz zwiększana poprzez założone przedmioty.
   
2. **Wytrzymałość** - wartość zdrowia, składająca się z dwóch wartości.
      - wartość maksymalna — wartość zdrowia, którą maksymalnie może osiągnąć postać w danym momencie.
      - wartość obecna — wartość zdrowia obecnego, zmniejszana podczas walki przez ataki przeciwnika.
   
   Bazowa wartość wytrzymałości będzie ustalana na podstawie poziomu postaci gracza oraz zwiększana poprzez przedmioty założone przez postać.
3. **Inteligencja** - główna statystyka magów. Działa podobnie jak siła u rycerza, jednak dotyczy ona różdżek.

4. **Szczęście** - szansa na zadanie trafienia krytycznego. Działa dla obu typów tak samo. Jego siłą będzie wyznaczana na podstawie procenta siły/inteligencji. **(W przyszłości dopracować)**

5. **Zręczność** - procentowa szansa na zrobienie uniku. Działa dla obu typów tak samo.

## Typy NPC   
### Typy wrogie:
   - **Rycerz** — silne i słabe strony jak wyżej, statystyki przypadkowe, zależne od etapu gry
   - **Mag** — silne i słabe strony jak wyżej, statystyki przypadkowe, zależne od etapu gry
   - **Różne zwierzęta** — posiadający tylko siłę, zręczność oraz wytrzymałość. Statystyki przypadkowe.

### Typy przyjazne:
   - **Kowal** — pozwala poprawić statystyki broni białej, mając przy okazji szanse zepsuć całkowicie bądź częściowo dany przedmiot.
   - **Kowal od różdżek (nazwa do zmiany)** - pozwala poprawić statystyki różdżek, mając przy okazji szanse zepsuć całkowicie bądź częściowo dany przedmiot.  
   - **Sklepikarz** — sprzedaje podstawowy sprzęt oraz pożywienie.
   - **Handlarz** — działa jak sklepikarz, jednak można kupić ulepszone przedmioty. (czarny rynek)
   - **Mieszkańcy** — przypadkowe osoby, które mogą pomóc z nakierowaniem fabularnym.
   
## Miasta
Świat gry będzie składał się z 3 miast, jedno magiczne, w którym „rodzimy” się wybierając ścieżkę maga, drugie „rycerskie”, w którym „rodzimy” się wybierając ścieżkę rycerza, oraz jedno wspólne.

