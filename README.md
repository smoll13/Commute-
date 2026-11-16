# Commute+ v0.6 — Sport Performance

GitHub Pages PWA met het gekozen Sport Performance-design. Alle bestaande kalender-, periode-, jaarkeuze-, streak-, berekenings- en JSON-back-upfuncties zijn behouden. Nieuw: lokaal opgeslagen fietsillustratie en een visuele fiets/auto-verdeling.

## Installatie op GitHub Pages

1. Maak eerst een JSON-back-up vanuit je bestaande Commute+-app.
2. Upload **de bestanden uit deze map** rechtstreeks naar de hoofdmap van je repository `commute-plus` (niet de ZIP zelf).
3. Controleer `Settings → Pages`: `Deploy from a branch`, `main`, `/(root)`.
4. Wacht op een geslaagde deployment bij `Actions` en herlaad de pagina.
5. Als de oude versie blijft verschijnen: sluit de PWA volledig af, vernieuw de pagina en wacht op de nieuwe service worker.

## Gegevens

De app bewaart registraties lokaal in dezelfde browser/op hetzelfde toestel als de vorige versie. Browserdata kan verloren gaan; bewaar geregeld een JSON-back-up. GitHub Pages biedt geen accountsynchronisatie.

De headerillustratie is lokaal (`cycling-hero.svg`), dus geen externe foto of internetafhankelijkheid.
