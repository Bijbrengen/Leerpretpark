# Reactielab - Archetypen Ronde 2

Webversie van de gerichte Round-2-aanvulling op de archetypenvragenlijst.

De pagina gebruikt dezelfde technische submitroute als ronde 1:

- toegangscode via `?id=...`
- Google Form-id via `&formID=...`
- antwoordpayload als JSON in `entry.40201663`

De hoofdmeting bestaat uit vier vergelijkbare meters:

- `weerstand`
- `resultaat`
- `routes`
- `houvast`

Daarnaast bevat ronde 2 een diagnostische meter:

- `instap`

`instap` is bedoeld voor de Verlater-drempel en vervangt de vier hoofdmeters niet.

## Assets

`assets/reactielab-hero.png` is lokaal gegenereerd voor deze vragenlijst.

De situatiebeelden staan in `assets/commons/` en de doelpersoonbeelden in `assets/personas/`. Beide reeksen komen uit Wikimedia Commons en zijn lokaal opgeslagen voor stabiele werking van de vragenlijst. Zie `ATTRIBUTION.md` voor maker, licentie en bronlink per beeld.

De eigen prototypebeelden in `assets/prototypes/` blijven voorlopig staan als fallback, maar de webpagina gebruikt voor de doelpersoonkaart nu de open Commons-beelden uit `vragenlijst.json`.
