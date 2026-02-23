

# **Analiza sprzedaży i zachowań zakupowych klientów ZARA – Dashboard w Excelu**  
**wersja:** 1.0.0  
**dostępne języki:** English | Polski  

Projekt pokazuje, jak przy użyciu Power Query i Excela przeprowadziłem analizę sprzedażową, analizę sezonowości oraz ocenę wpływu promocji na zachowania klientów sieci Zara.

**Źródło danych:** dane pochodzą ze strony kaggle.com  

---

## **Podsumowanie**

Przeprowadzona analiza dotyczy wpływu sezonowości na sprzedaż, określenia stopnia promocji na oferowane towary oraz wpływu rozmieszczenia towaru w sklepie na wysokość sprzedaży.

---

## **Kontekst biznesowy / Pytania do projektu**

1. Które kategorie produktów generują największy przychód?  
2. Czy produkty promocyjne generują większy przychód niż te nieobjęte promocją?  
3. Jak pozycja produktu w sklepie wpływa na sprzedaż?  
4. Które produkty są na topie pod względem przychodu?  
5. Czy produkty sezonowe sprzedają się lepiej niż niesezonowe?

---

## **Wykorzystywane narzędzia i techniki**

- Power Query – czyszczenie i transformacja danych (ETL)  
- Excel – główne narzędzie analizy i wizualizacji  
- Tabele i wykresy przestawne – agregacja danych i tworzenie interaktywnych wizualizacji  
- Segmentatory (Slicery) – filtrowanie wyników wg rodzaju oferowanych produktów  
- Wykresy:  
  - KPI w kafelkach (przychód całkowity, całkowita wielkość sprzedaży, liczba kategorii produktowych)  
  - wykres liniowy – porównanie sprzedaży towarów sezonowych i niesezonowych w czasie  
  - wykres słupkowy – sprzedaż produktów promocyjnych i niepromocyjnych z podziałem na kategorie produktowe  
  - wykres combo – przychód z podziałem na kategorie i procentowy udział w przychodach całkowitych  
- UX w dashboardzie – 2 strony tematyczne, kafelki KPI u góry, segmentator w widocznym miejscu dla wygody użytkownika

---

## **Kluczowe wnioski**

- **Struktura przychodów**  
  - Łączny przychód wynosi 28,01 mln USD, wygenerowany z 31 473 transakcji.  
  - Średni przychód na jedną transakcję to około 890 USD.

- **Koncentracja przychodów wg kategorii**  
  - Kategoria *Jackets* odpowiada za około 60–65% całkowitego przychodu.  
  - Przychód z tej kategorii jest ponad pięciokrotnie wyższy niż w drugiej największej kategorii.  
  - Pozostałe cztery kategorie łącznie generują 35–40% przychodu.  
  - **Wniosek:** przychody są mocno skoncentrowane w jednej dominującej kategorii.

- **Analiza wolumenu – najlepiej sprzedające się produkty**  
  - Top 10 produktów osiąga wyniki na poziomie 2 000–12 000 sprzedanych sztuk każdy.

---

## **Rekomendacje**

- Priorytetem powinna być dalsza optymalizacja kategorii *Jackets*, ponieważ generuje największą część przychodów i najmocniej wpływa na wynik ogólny.  
- Warto wzmocnić pozostałe kategorie, aby zmniejszyć zależność od jednego segmentu i poprawić stabilność przychodów.  
- Najlepiej sprzedające się produkty (Top 10) mają duży potencjał — zwiększenie ich dostępności może szybko podnieść wolumen sprzedaży.  
- Rekomendowane jest przeprowadzenie analizy sezonowości, ponieważ dominacja jednej kategorii może oznaczać wahania popytu w różnych okresach.  
- Warto przygotować stały monitoring KPI (udział kategorii, wolumen, średni przychód), ponieważ regularne śledzenie trendów ułatwi szybkie reagowanie na zmiany w sprzedaży.

---

## **Historia rozwoju projektu**

| Wersja | Data       | Opis             |
|--------|------------|------------------|
| 1.0.0  | 14.02.2026 | Wersja pierwotna |

