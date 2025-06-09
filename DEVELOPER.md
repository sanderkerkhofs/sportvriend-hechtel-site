# Sportvriend Hechtel Website - Ontwikkeldocumentatie

Deze documentatie is bedoeld voor ontwikkelaars en beschrijft de technische details en structuur van het project.

## Projectstructuur

```
sportvriend-hechtel-site/
│
├── index.html             # Hoofdpagina
├── over-ons.html          # Over ons pagina
├── fotos.html             # Fotogalerij pagina
├── contact.html           # Contactpagina
├── styles.css             # Hoofdstijlbestand
├── gallery.css            # Fotogalerij specifieke stijlen
├── README.md              # Projectbeschrijving
├── FEATURES.md            # Gedetailleerde functieoverzicht
├── DEVELOPER.md           # Deze ontwikkelaarsdocumentatie
└── img/                   # Afbeeldingen map
```

## CSS-structuur

Het CSS-bestand is georganiseerd in secties:

1. Reset & basis
2. Typografie
3. Layout & containers
4. Header & navigatie
5. Hero sectie
6. Secties op homepage
7. Over ons pagina
8. Fotogalerij
9. Contact pagina
10. Footer
11. Responsiveness

## CSS-variabelen

De website maakt gebruik van CSS-variabelen (custom properties) voor consistente styling:

```css
:root {
    /* Kleurenpalet */
    --primary: #1e5631;     /* Donkergroen */
    --primary-light: #3a7248;
    --secondary: #f8c91e;   /* Geel */
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

## Responsive Breakpoints

De responsieve layout gebruikt de volgende breakpoints:

- **Mobiel**: < 480px
- **Tablet**: 480px - 768px
- **Kleinere desktop**: 768px - 1024px
- **Desktop**: > 1024px

## Fotogalerij

De fotogalerij gebruikt een speciale CSS-implementatie met popup-functionaliteit:

- De popups worden geïmplementeerd via CSS target pseudo-class
- Galerij-items zijn georganiseerd in een CSS Grid
- Popup-navigatie werkt via anker-links

## HTML-structuur

Elke pagina gebruikt een consistente HTML-structuur:

```html
<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>[Paginatitel] - Sportvriend Hechtel</title>
    <link rel="stylesheet" href="styles.css">
    <!-- Extra CSS-bestanden indien nodig -->
</head>
<body>
    <header>
        <!-- Logo, titel en navigatie -->
    </header>
    <main>
        <!-- Paginaspecifieke inhoud -->
    </main>
    <footer>
        <!-- Footer inhoud -->
    </footer>
</body>
</html>
```

## Externe Bronnen

Het project gebruikt de volgende externe bronnen:

- **Font Awesome 6.5.1**: Voor iconen via CDN
- **Google Fonts**: Voor webfonts (Roboto, Montserrat, Open Sans)

## Onderhoudstips

### Afbeeldingen toevoegen

1. Plaats nieuwe afbeeldingen in de `img/` map
2. Optimaliseer afbeeldingen voor webgebruik (formaat en bestandsgrootte)
3. Gebruik beschrijvende bestandsnamen

### CSS aanpassen

1. Respecteer de bestaande secties in styles.css
2. Gebruik de bestaande CSS-variabelen voor consistentie
3. Documenteer complexe CSS met commentaar

### Wedstrijdkalender bijwerken

De wedstrijdkalender bevindt zich in index.html en kan bijgewerkt worden door de tabelrijen aan te passen:

```html
<tr>
    <td>[Datum]</td>
    <td>[Thuisploeg]</td>
    <td>[Uitploeg]</td>
    <td>[Tijd]</td>
    <td>[Locatie]</td>
</tr>
```

### Nieuwsberichten toevoegen

Nieuwe nieuwsberichten kunnen toegevoegd worden in de nieuws-sectie van index.html:

```html
<article class="news-item">
    <div class="news-date">[Datum]</div>
    <h4>[Titel]</h4>
    <p>[Inhoud]</p>
    <a href="#" class="read-more">Lees meer</a>
</article>
```
