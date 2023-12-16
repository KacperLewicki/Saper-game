# Dokumentacja Gry "Saper"

## Przegląd

"Saper" to klasyczna gra logiczna, w której zadaniem gracza jest oczyszczenie pola z min, unikając ich detonacji. Gra oferuje różne poziomy trudności, które wpływają na rozmiar pola i liczbę ukrytych min.

## Instalacja

Aby uruchomić grę lokalnie:

1. Pobierz cały katalog gry.
2. Upewnij się, że masz lokalne środowisko serwera do obsługi plików gry. Jeśli nie, jednym z powszechnie używanych narzędzi jest `live-server`, który można zainstalować za pomocą npm.
3. Otwórz katalog gry w wybranym edytorze kodu.
4. Uruchom `live-server` lub równoważne narzędzie, aby rozpocząć grę.

## Jak Grać

### Rozpoczęcie Gry

- Otwórz grę "Saper" na swoim urządzeniu.
- Wybierz poziom trudności: Łatwy, Średni, Expert
- Rozpocznie się nowa gra z losowo rozmieszczonymi minami.

### Rozgrywka

- Kliknij lewym przyciskiem myszy na pola, aby je odkryć.
- Prawym przyciskiem myszy oznacz pola, na których podejrzewasz miny.
- Liczby wyświetlane na odkrytych polach wskazują, ile min znajduje się w ośmiu polach dookoła danego pola.
- Aby wygrać, oznacz wszystkie miny i odkryj wszystkie pozostałe pola.

### Zakończenie Gry

- Gra kończy się wygraną, gdy wszystkie pola bez min będą odkryte, a wszystkie miny będą oznaczone.
- Gra kończy się przegraną, gdy gracz kliknie na pole z miną.

## Sterowanie

- **Lewy przycisk myszy** : Odkryj pole.
- **Prawy przycisk myszy** : Oznacz/odznacz minę.
- **Oba przyciski myszy** : Odkryj sąsiednie pola (jeśli liczba oznaczonych min zgadza się z liczbą na polu).

## Szczegóły Techniczne

Gra "Saper" jest napisana w JavaScript + html + css
