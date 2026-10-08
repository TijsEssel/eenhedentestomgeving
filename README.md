# Eenvoudige eenhedenomzetter

Deze test bestaat uit twee noodzakelijke bestanden:

- `index.html`: de webpagina en omzettingslogica
- `eenheden.json`: alle instellingen, eenheden en factoren

Plaats beide bestanden in de hoofdmap van dezelfde GitHub-repository en activeer GitHub Pages voor de `main`-branch en de map `/ (root)`.

De HTML bevat geen eenheden of omzettingsfactoren. Een extra eenheid voeg je uitsluitend toe in `eenheden.json`.

Voorbeeld:

```json
"cm": {
  "name": "centimeter",
  "symbol": "cm",
  "factor_to_base": 0.01
}
```

Na publicatie van de gewijzigde JSON en het vernieuwen van de webpagina verschijnt de nieuwe eenheid automatisch.

Let op: wanneer je `index.html` rechtstreeks opent via `file://`, kan de browser het inlezen van het JSON-bestand blokkeren. Via GitHub Pages werkt dit wel.
