# Schooltuinkalender

Interactieve jaarkalender voor de schooltuin. Kies groenten en fruit, en zie:

- een jaaroverzicht met per gewas wanneer je binnen start, buiten zaait, uitplant, verzorgt, water geeft en oogst;
- wat je deze maand en volgende maand kunt zaaien of planten;
- per maand wat er moet gebeuren;
- plantgegevens: zaaidiepte, afstand, water bij droogte en tijd tot oogst.

Met de knop **PDF maken** krijg je een uitdraai met het jaaroverzicht, een pagina per gekozen gewas en een pagina per maand.

## Online zetten met GitHub Pages

1. Maak een openbare repository aan, bijvoorbeeld `schooltuinkalender`.
2. Upload de inhoud van deze map (`index.html`, `icons/`, `README.md`) naar de hoofdmap van de repository.
3. Ga naar **Settings → Pages**, kies bij *Source* de branch `main` en de map `/ (root)`, en klik op **Save**.
4. Na een minuut staat de kalender op `https://<gebruikersnaam>.github.io/schooltuinkalender/`.

De pagina werkt ook als je `index.html` direct opent in een browser. Er is een internetverbinding nodig voor de lettertypes en de PDF-module (jsPDF).

## Gewassen aanpassen

De gewassen en taken staan in `index.html` in de lijst `VEG`. Elke taak is
`['type', vanMaand, totMaand, 'uitleg']`, met maanden 1 t/m 12 en als type
`binnen`, `buiten`, `plant`, `zorg`, `water` of `oogst`.

De icoontjes staan als losse SVG-bestanden in `icons/`.

De maanden gelden voor een gemiddeld jaar in Nederland.
