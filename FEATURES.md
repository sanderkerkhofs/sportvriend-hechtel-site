# 🌟 Sportvriend Hechtel Website - Gedetailleerde Functieoverzicht

Dit document geeft een gedetailleerd overzicht van de functionaliteiten en technische implementaties van de Sportvriend Hechtel website.

## 🏠 Homepage (index.html)

### Welkomstsectie
- Introductietekst over de club met vriendelijke welkomsttoon
- Iconografie via Font Awesome voor visuele versterking

### Wedstrijdkalender
- Responsieve tabel met aankomende wedstrijden
- CSS Grid styling voor tabelweergave
- Hover-effecten voor verbeterde gebruikersinteractie
- Duidelijke structuur met datum, teams, tijd en locatie

### Nieuwsberichten
- Recente updates en aankondigingen
- Visueel onderscheid tussen nieuwsitems
- Datum-aanduidingen en categorisering
- "Lees meer" links voor uitgebreide artikelen

## 👥 Over Ons (over-ons.html)

### Clubgeschiedenis
- Uitgebreide informatie over de oorsprong van de club
- Details over de fusie tussen Sportvriend 74 en KWB 76
- Historische tijdlijn en belangrijke gebeurtenissen

### Kernwaarden
- Duidelijke uiteenzetting van clubfilosofie
- Beschrijving van de sportieve en sociale aspecten
- Visuele presentatie met iconen en highlights

### Teamoverzicht
- Informatie over bestuur, trainers en belangrijke contactpersonen
- Gestructureerde informatieweergave in tabelvorm
- Teamfoto's uit verschillende seizoenen

## 📸 Fotogalerij (fotos.html)

### Geavanceerde Galerij
- CSS Grid-gebaseerd fotoraster
- Lightbox-achtige functionaliteit voor vergrote weergave
- Custom popup-implementatie met pure CSS
- Hover-effecten met beeldtitels en beschrijvingen

### Gebeurteniscategorieën
- Wedstrijden
- Seizoensfoto's
- Toernooien
- Sociale gebeurtenissen
- Teamuitstappen

## 📞 Contact (contact.html)

### Contactgegevens
- Adres, telefoon en e-mail informatie
- Sociale media links
- Locatiekaart (PNG-afbeelding)
- Iconen voor visuele versterking

### Contactformulier
- Volledig responsief formulier
- Veldvalidatie met HTML5-attributen
- Custom styling voor formulierelementen
- Checkboxes voor privacy en nieuwsbrief
- Submit-knop met hover-effect (functioneert zonder back-end)

## 🎨 CSS Technieken

### CSS Variabelen
```css
:root {
    /* Kleurenpalet */
    --primary: #1e5631;     /* Donkergroen - primaire kleur */
    --primary-light: #3a7248;
    --secondary: #f8c91e;   /* Geel - secundaire kleur */
    --secondary-dark: #e8b200;
    --text-dark: #333333;
    --text-light: #ffffff;
    --gray-light: #f5f5f5;
    --gray-medium: #e0e0e0;
    --gray-dark: #666666;
    
    /* Typografie */
    --body-font: 'Roboto', 'Open Sans', sans-serif;
    --heading-font: 'Montserrat', 'Roboto', sans-serif;
    
    /* Spacing */
    --spacing-xs: 0.5rem;
    --spacing-sm: 1rem;
    --spacing-md: 2rem;
    --spacing-lg: 4rem;
    --spacing-xl: 6rem;
    
    /* Container breedtes */
    --container-width: 1200px;
}
```

### Flexbox Layouts
- Navigatie-menu
- Nieuwssecties
- Contactgegevens
- Formuliergroepen

### CSS Grid Layouts
- Fotogalerij
- Wedstrijdtabel
- Algemene pagina-indeling
- Responsieve kolommen

### Media Queries
Multiple breakpoints voor verschillende apparaatformaten:
- Mobiel (< 480px)
- Tablet (480px - 768px)
- Kleine desktop (768px - 1024px)
- Desktop (> 1024px)

### CSS Animaties
- Hover-effecten op knoppen en links
- Transitie-effecten op interactieve elementen
- Soepele overgangen tussen staten
- Galerij popup-animaties

## 🛠️ Technische Implementaties

### Semantische HTML5
- Correcte headings hiërarchie (h1-h6)
- Semantische elementen (header, nav, main, section, footer)
- Beschrijvende attributen en klassen
- Correcte nestingstructuur

### Toegankelijkheid
- Alt-teksten voor afbeeldingen
- Duidelijke focusstijlen
- Logische tabvolgorde
- Gekoppelde labels voor formulierelementen

### Organisatie
- Gestructureerde mappenstructuur
- Gecommentarieerde CSS-secties
- Consistente naamgevingsconventies
- Logische bestandsorganisatie

### Responsieve Strategieën
- Flexibele layouts
- Relatieve maateenheden (rem, %)
- Aanpasbare containerbreedte
- Conditionele weergave van elementen

## 🎯 Unieke Features

- Custom popup-galerij zonder JavaScript
- Volledig responsief ontwerp zonder externe frameworks
- Consistente branding met clubkleuren
- Uitgebreide CSS-variabelen voor eenvoudig thema-onderhoud
- Geoptimaliseerde afbeeldingen voor snellere laadtijden
