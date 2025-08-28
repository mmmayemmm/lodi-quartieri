# Lodi – Quartieri (pacchetto pronto per GitHub)

Questo pacchetto contiene **poligoni approssimativi** dei quartieri di Lodi, schede in PDF e Markdown e un KML **già personalizzato** per l'utente **mmmayemmm**.

## Struttura
- `geo/`
  - `neighborhoods.geojson`
  - `neighborhoods.kml` (popup con link a PDF/MD ospitati su GitHub)
- `md/` → schede descrittive in Markdown
- `pdf/` → schede in PDF con cartografia + segnaposti foto
- `README.md` (questo file)

## Avvertenza
I confini sono **indicativi** e NON ufficiali. Per una versione accurata servono shapefile ufficiali o una digitalizzazione puntuale.

## Come usare con Google My Maps
1. Carica questa cartella su GitHub nella repo pubblica `lodi-quartieri` dell'utente `mmmayemmm`.
2. Apri [Google My Maps](https://www.google.com/mymaps), crea una nuova mappa e importa `geo/neighborhoods.kml`.
3. Cliccando su ogni quartiere troverai i link alle schede PDF/MD (servono i file presenti in questa repo su GitHub).

