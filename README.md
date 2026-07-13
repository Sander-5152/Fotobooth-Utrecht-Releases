# Fotobooth Utrecht — Releases

Officiële downloads en automatische updates voor de **Fotobooth Utrecht**
photobooth-app (Linux):

* **Releases** (rechts op deze pagina), per versie:
  * `FotoboothUtrecht-Klantpakket-<versie>.zip` — **voor nieuwe
    installaties**: het programma, de starter, het installatiescript
    (`install.py`) en de handleidingen in één download. Uitpakken en
    `python3 install.py` draaien — zie INSTALLATIE.md in de zip.
  * `FotoboothUtrecht` — alleen het programma (dit bestand halen
    geïnstalleerde apps zelf op bij een update).
* **`manifest.json`**: het ondertekende update-manifest. Geïnstalleerde
  apps controleren dit bestand bij het opstarten en werken zichzelf bij
  de volgende start bij.
* **ARM (bv. Raspberry Pi 5):** zodra beschikbaar hebben ARM-versies een
  `-arm64`-achtervoegsel in de bestandsnaam en een eigen
  `manifest-arm64.json`. Download altijd de versie die bij de processor
  van de pc past — het installatiescript controleert dit ook.

## Hoe updates werken

1. De app haalt `manifest.json` op en controleert de **digitale
   handtekening** van de maker én de **SHA-256** van de download.
2. Alleen als beide kloppen wordt de nieuwe versie klaargezet en bij de
   volgende start toegepast. Niemand anders kan dus updates aanbieden.
3. Zonder internet draait de app gewoon door op de huidige versie.

## Licentie

De app werkt met een licentiesleutel per pc, geldig voor een afgesproken
periode. Interesse of een sleutel nodig? Neem contact op met Fotobooth Utrecht
