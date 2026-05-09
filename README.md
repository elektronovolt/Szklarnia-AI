# Szklarnia AI

Projekt ESPHome dla automatyki szklarni.

## Wersje

Każda wersja firmware jest zapisywana w osobnym pliku:

- `szklarnia_1.3.4.yaml` - wersja bazowa
- `szklarnia_1.3.5.yaml` - dodana numeracja firmware
- `szklarnia_1.3.6.yaml` - nagłówek i historia wersji
- `szklarnia_1.3.7.yaml` - diagnostyka stanu automatyki
- `szklarnia_1.3.8.yaml` - polskie nazwy encji
- `szklarnia_1.3.9.yaml` - sekrety przeniesione do `secrets.yaml`
- `szklarnia_1.4.0.yaml` - sekrety urządzenia mają prefiks `szklarnia_`

## Sekrety

Prawdziwy plik `secrets.yaml` nie jest zapisywany w Git. Utwórz go lokalnie na podstawie `secrets.example.yaml`.

Sekrety specyficzne dla szklarni mają prefiks `szklarnia_`, żeby nie kolidowały z innymi urządzeniami ESPHome w Home Assistant.
