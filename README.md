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
- `szklarnia_1.4.1.yaml` - diagnostyka VPD i wilgotność ograniczona do 0-100%
- `szklarnia_1.4.2.yaml` - progi podlewania + ręczna kalibracja czujników gleby (min/max)
- `szklarnia_1.4.3.yaml` - tryb wentylatora (temp / temp+RH / temp+VPD) + progi w HA
- `szklarnia_1.4.4.yaml` - poprawka kompilacji (konflikt nazwy fan_mode)
- `szklarnia_1.4.5.yaml` - kalibracja gleby: 2 wspólne suwaki (MIN mokro / MAX sucho)
- `szklarnia_1.4.6.yaml` - kalibracja gleby: zakresy pod czujnik (mokro~950, sucho~3200)
- `szklarnia_1.4.7.yaml` - encje pomocnicze do dashboardu (Status gleby, Wentylator zablokowany)
- `szklarnia_1.4.8.yaml` - mocniejsze filtrowanie szumow odczytow wilgotnosci gleby

## Sekrety

Prawdziwy plik `secrets.yaml` nie jest zapisywany w Git. Utwórz go lokalnie na podstawie `secrets.example.yaml`.

Sekrety specyficzne dla szklarni mają prefiks `szklarnia_`, żeby nie kolidowały z innymi urządzeniami ESPHome w Home Assistant.
