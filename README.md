# RadarKorva

RadarKorva to prywatne narzędzie badawcze do monitorowania publicznych ofert marketplace przez oficjalne API oraz analizy historii cen na własne potrzeby.

## Cel aplikacji

Aplikacja służy do:

- pobierania publicznych metadanych ofert,
- porównywania cen i podstawowych parametrów ofert,
- budowania prywatnej historii obserwacji rynku,
- wspierania ręcznej decyzji zakupowej użytkownika.

## Czego aplikacja nie robi

- Nie kupuje automatycznie produktów.
- Nie wystawia ofert.
- Nie edytuje ofert.
- Nie wysyła wiadomości do sprzedawców.
- Nie pobiera ani nie przetwarza zamówień.
- Nie redystrybuuje publicznie danych z API.
- Nie jest publiczną usługą dla innych sprzedawców.

## Dostęp do danych

RadarKorva korzysta wyłącznie z oficjalnych API platform marketplace i wysyła identyfikowalny nagłówek User-Agent.

Planowany User-Agent:

```text
RadarKorva/0.1 (+https://krzysztofbaj-bot.github.io/radarkorva-info/)
