# Odido

Website voor het inruilen van iPhones en het bekijken van accessoires. Gewone HTML, CSS en JavaScript, dus er is geen build of installatie nodig.

## Online zetten met GitHub Pages
1. Maak op github.com een nieuwe **publieke** repository. Heet je gebruikersnaam `odido` en noem je de repo `odido.github.io`, dan wordt het adres `https://odido.github.io`. Bij een andere naam wordt het `https://GEBRUIKERSNAAM.github.io/REPONAAM`.
2. Klik op **uploading an existing file** en sleep alle bestanden en de map `images` uit deze map erin. Kies daarna **Commit changes**.
3. Ga naar **Settings → Pages**. Kies bij *Source* **Deploy from a branch**, kies de branch **main** en de map **/ (root)**, en klik op **Save**.
4. Na een minuut of twee staat de site online. Je ziet het adres bovenaan de Pages-pagina.

## Bestanden
- `index.html` homepage en inruilflow (`script.js`: modellen, prijzen en berekening)
- `accessoires.html` accessoires (prijzen staan in het script onderaan het bestand)
- `login.html` en `dashboard.html` demo van het beheer
- De opmaak (CSS) staat in het `<style>`-blok bovenaan elk HTML-bestand. `images/` bevat alle foto's en logo's

## Let op
De inloggegevens in `login.html` staan leesbaar in de code en zijn dus voor iedereen zichtbaar. Gebruik daar nooit een wachtwoord dat je ook elders gebruikt. Het dashboard is een demo en geen echte beveiliging.
