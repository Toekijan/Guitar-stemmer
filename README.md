# Gitaarstemmer

Een gitaarstemmer in één HTML-bestand. Luistert via de microfoon, toont de gemeten
frequentie (Hz), de dichtstbijzijnde noot en de afwijking in cent. Het scherm wordt
**groen** zodra de toon binnen ±5 cent zit.

## Gebruik

1. Open `index.html` in een browser (Chrome, Edge, Firefox, Safari).
   Microfoontoegang werkt alleen via `https://` of lokaal (`file://` / `localhost`).
2. Druk op **Start** en geef toestemming voor de microfoon.
3. Speel een snaar. Kies **Auto** voor de dichtstbijzijnde noot, of tik op een snaar
   (E A D G B e) om daar gericht op te stemmen.
4. Optioneel: pas de referentietoon A4 aan (standaard 440 Hz).

| Snaar | Noot | Frequentie |
|-------|------|-----------:|
| 6 | E2 | 82,41 Hz |
| 5 | A2 | 110,00 Hz |
| 4 | D3 | 146,83 Hz |
| 3 | G3 | 196,00 Hz |
| 2 | B3 | 246,94 Hz |
| 1 | E4 | 329,63 Hz |

Kleuren: groen = gestemd (≤ 5 cent), oranje = bijna (≤ 15 cent), rood = ernaast.
