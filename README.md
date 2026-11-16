# Commute+ — eerste GitHub Pages-versie (v0.4)

Een installeerbare PWA gebaseerd op de bestaande Commute+ v0.3-test. Bevat de kalendergegevens van 2026, week/maand/jaar, fietsstreaks, financiële berekeningen, ontbrekende werkdagen en JSON-back-ups.

## Publiceren via GitHub Pages
1. Maak op GitHub een nieuwe repository, bijvoorbeeld `commute-plus`.
2. Upload **de vier bestanden in deze map** naar de hoofdmap (niet de zip zelf): `index.html`, `manifest.webmanifest`, `icon.svg`, `sw.js`.
3. Ga naar **Settings → Pages → Build and deployment**. Kies **Deploy from a branch**, branch `main`, map `/(root)` en sla op.
4. Open de GitHub Pages-link die GitHub toont. Op Android kun je via Chrome **Toevoegen aan startscherm** gebruiken.

## Belangrijk
- Dit is een bèta. De historische gegevens zijn testgegevens en staan bij eerste gebruik vooraf ingevuld.
- Je dagregistraties en instellingen worden **alleen op het apparaat in de browser** opgeslagen. GitHub slaat je persoonlijke registraties niet op. Maak regelmatig een JSON-back-up.
- Foto's in de header en de financiële kaart worden vanaf Unsplash geladen als je internet hebt. Zonder internet blijft de donkerblauwe achtergrond zichtbaar. Controleer licentie en vervang de afbeeldingen door eigen/gelicentieerde foto's voor commerciële publicatie.
- Voor een betrouwbare installeerbaarheid op alle telefoons zijn later PNG-iconen in meerdere resoluties aanbevolen.
- Er is nog geen automatische cloud-back-up of accountsysteem.
