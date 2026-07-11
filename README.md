# Fotobooth Utrecht — Releases

Officiële downloads en automatische updates voor de **Fotobooth Utrecht**
photobooth-app (Linux). De broncode is privé; deze repository bevat alleen:

* **Releases** (rechts op deze pagina): het programma `FotoboothUtrecht`
  als één uitvoerbaar bestand per versie.
* **`manifest.json`**: het ondertekende update-manifest. Geïnstalleerde
  apps controleren dit bestand bij het opstarten en werken zichzelf bij
  de volgende start bij.

## Hoe updates werken

1. De app haalt `manifest.json` op en controleert de **digitale
   handtekening** van de maker én de **SHA-256** van de download.
2. Alleen als beide kloppen wordt de nieuwe versie klaargezet en bij de
   volgende start toegepast. Niemand anders kan dus updates aanbieden.
3. Zonder internet draait de app gewoon door op de huidige versie.

## Licentie

De app werkt met een licentiesleutel per pc, geldig voor een afgesproken
periode. Interesse of een sleutel nodig? Neem contact op met
Fotobooth Utrecht (sander.build.things@gmail.com).
