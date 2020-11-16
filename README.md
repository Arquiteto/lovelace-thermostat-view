# Karta termostatów

Mój sposób na bardziej kompaktową kartę do zarządzania termostatami.
Karta oparta na repozytoriach (dostępne w HACS):
- https://github.com/jcwillox/lovelace-paper-buttons-row
- https://github.com/benct/lovelace-multiple-entity-row
- https://github.com/thomasloven/lovelace-slider-entity-row

# Konfiguracja

- Karta wymaga stworzenia dla każdego termostatu template sensora, który będzie odzwierciedlał aktualny status termostatu. Termostat przechowuje informacje o stanie w kilku różnych atrybutach, bez dodatkowej encji nie byłoby możliwości kolorowania aktywnego trybu działania. Przykładowa konfiguracja sensora dla encji typu generic thermostat w pliku configuration.yaml
- Kliknięcie przycisku wywołuje skrypt, który przełącza termostat w pożądany tryb. Przykładowy skrypt znajduje się w pliku scripts.yaml
