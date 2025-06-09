# 📱 Sportvriend Hechtel - Voetbalclub Website

![Sportvriend Hechtel Logo](img/SVH-logo.png)

## 📋 Project Beschrijving

Deze website werd ontwikkeld als onderdeel van de cursus **Front-End Development** aan **UCLL**. Het betreft een statische website voor de lokale voetbalclub "Sportvriend Hechtel" uit Limburg, België. De site biedt informatie over de club, het team, activiteiten, wedstrijden en contactmogelijkheden.

### Schoolopdracht Context

Dit project werd gemaakt als onderdeel van Opdracht 2 voor het vak Front-End Development (Semester 2). De opdracht vereiste het ontwikkelen van een volledig responsieve, statische website met minimaal vier pagina's, zonder gebruik van frameworks, met toegepaste moderne CSS-technieken.

## 🚀 Functies

- **Responsief ontwerp** dat werkt op alle apparaten (mobiel, tablet, desktop)
- **Vier pagina's**: Home, Over ons, Foto's en Contact
- **Modern CSS** met gebruik van Flexbox en Grid voor layout
- **Contactformulier** voor bezoekers
- **Nieuwssectie** met recente clubupdates
- **Wedstrijdkalender** met aankomende wedstrijden
- **Fotogalerij** met clubactiviteiten en evenementen
- **Toegankelijke structuur** met semantisch correcte HTML

## 🛠️ Technologieën & Technieken

- **HTML5** met semantische structuur
- **CSS3** met geavanceerde technieken:
  - Flexbox voor flexibele layouts
  - CSS Grid voor complexere pagina-indelingen
  - Custom properties (CSS variabelen) voor consistente styling
  - Media queries voor responsief ontwerp
- **Font Awesome** voor iconografie (versie 6.5.1)
- **Responsive design** met mobile-first benadering
- **CRAP-principes** (Contrast, Repetition, Alignment, Proximity)
- **CSS-animaties** en visuele effecten (bij popups in de fotogalerij)

## 📁 Projectstructuur

```
sportvriend-hechtel-site/
│
├── index.html             # Homepagina met nieuwsberichten en wedstrijdkalender
├── over-ons.html          # Informatie over de club, geschiedenis en team
├── fotos.html             # Fotogalerij met clubactiviteiten
├── contact.html           # Contactformulier en contactgegevens
├── styles.css             # Hoofdstijlbestand met 900+ regels CSS
├── gallery.css            # Specifieke CSS voor de fotogalerij en popup functionaliteit
├── README.md              # Project documentatie
└── img/                   # Map met alle afbeeldingen
    ├── SVH-logo.png       # Club logo
    ├── match1.jpg         # Wedstrijdfoto's
    ├── match2.jpg         # Wedstrijdfoto's
    ├── seizoen2014.jpg    # Teamfoto's
    ├── seizoen2018.jpg    # Teamfoto's
    ├── seizoen2020.jpg    # Teamfoto's
    ├── map.PNG            # Kaart voor contactpagina
    ├── BBQ2.JPG           # Event foto's
    ├── kerstmarkt1.jpg    # Event foto's
    ├── toernoei-mille-*.jpg # Toernooi foto's
    ├── sponsor-*.jpg      # Sponsorfoto's
    └── uitstap2.jpg       # Uitstap foto's
```

## 📱 Responsief Design

De website is volledig responsief met CSS media queries op verschillende breekpunten:

- **Mobiel (< 480px)** 
  - Compacte weergave met verticale navigatie
  - Één-koloms layout voor optimale leesbaarheid
  - Aangepaste afbeeldingsgroottes voor snellere laadtijden
  - Hamburger menu voor betere gebruikservaring

- **Tablet (480px - 768px)**
  - Twee-koloms layouts waar mogelijk
  - Geoptimaliseerde tekst en afbeeldingen
  - Verbeterde navigatie met meer ruimte

- **Kleinere desktop (768px - 1024px)**
  - Drie-koloms layouts voor fotogalerij
  - Gemaximaliseerde inhoud voor betere leesbaarheid
  - Volledige navigatie

- **Desktop (> 1024px)**
  - Volledige site-ervaring met ruime whitespace
  - Interactieve hover-effecten
  - Maximale containerbreedte van 1200px

## 🎨 Design Kenmerken

### Kleurenpalet
- **Primaire kleuren**: Donkergroen (#1e5631) en geel (#f8c91e) van clublogo
- **Secundaire kleuren**: Wit, lichtgrijs en zwart voor inhoud en contrast
- **Accentkleuren**: Verschillende tinten groen voor visuele hiërarchie

### Typografie
- Sans-serif fonts voor goede leesbaarheid op alle apparaten
- Duidelijke hiërarchie met verschillende groottes en gewichten
- Consistente regelafstand en tekstuitlijning

### UI Componenten
- Uniforme knoppen met hover-effecten
- Responsieve tabellen voor wedstrijdinformatie
- Interactieve fotogalerij met popup-functionaliteit
- Formulierelementen met visuele feedback

## 🧪 Toegankelijkheid & Best Practices

- Semantische HTML5-elementen voor verbeterde toegankelijkheid
- Alt-teksten voor alle afbeeldingen
- ARIA-attributen waar nodig
- Toetsenbordnavigatie ondersteund
- Voldoende kleurcontrast volgens WCAG-richtlijnen
- Gevalideerde HTML en CSS volgens W3C-standaarden
- Getest in moderne browsers (Chrome, Firefox, Edge, Safari)
- Fallback-styling voor oudere browsers
- Consistente weergave op alle geteste platforms

## 💡 Speciale Functionaliteiten per Pagina

### Homepage (index.html)
- Hero-sectie met clublogo en welkomsttekst
- Nieuwsberichten met datum en afbeeldingen
- Responsieve wedstrijdkalender met komende wedstrijden
- Sponsorsectie met links

### Over Ons (over-ons.html)
- Clubgeschiedenis met tijdlijn
- Team-informatie met foto's
- Filosofie en kernwaarden
- Historische mijlpalen

### Fotogalerij (fotos.html)
- Responsief grid-systeem voor alle afbeeldingen
- Categorieën: Wedstrijden, Events, Team
- Overlay met informatie bij hover
- Popup-weergave bij klikken met CSS-animaties

### Contact (contact.html)
- Interactief contactformulier met validatie
- Ingebedde locatiekaart
- Contactgegevens met iconen
- Links naar sociale media

## 📚 Geleerde Technieken

Dit project toont beheersing van:

- **CSS Grid & Flexbox** voor complexe layouts
- **CSS Custom Properties** voor een onderhoudbaar stylesheet-systeem
- **Media Queries** voor verschillende apparaten
- **Mobile-first aanpak** met progressieve verbetering
- **CSS-animaties en -transities** voor interactieve elementen
- **Toegankelijkheidsprincipes** voor een inclusieve gebruikerservaring

## 🏆 Over de Club

Sportvriend Hechtel is een lokale veteranenvoetbalclub uit het Limburgse Hechtel. De club ontstond in 2023 uit de fusie van twee historische clubs: Sportvriend 74 (opgericht in 1974) en KWB 76 (opgericht in 1976). De club staat bekend om zijn vriendschappelijke sfeer, gemeenschapszin, en passie voor voetbal.

### Kernwaarden
De club hanteert een duidelijke filosofie met focus op:
- Sportiviteit en fair play
- Teamspirit en vriendschap
- Gemeenschapsbetrokkenheid
- Inclusiviteit en toegankelijkheid
- Plezier boven prestatie

De thuisbasis van de club ligt in het groene hart van Hechtel, waar ze regelmatig wedstrijden, trainingen en sociale activiteiten organiseren. De club is meer dan alleen voetbal - het is een social hub voor de lokale gemeenschap.

## 📷 Projectvoorbeelden

De website bevat diverse secties en pagina's:

### Thuispagina (index.html)
De homepage bevat een welkomsttekst, een wedstrijdkalender en recente nieuwsberichten over de club.

### Over Ons (over-ons.html) 
De "Over Ons" pagina bevat informatie over de clubgeschiedenis, de fusie van Sportvriend 74 en KWB 76 in 2023, en de kernwaarden van de club. De pagina bevat teamfoto's en beschrijft de clubcultuur.

### Fotogalerij (fotos.html)
Een interactieve fotogalerij met afbeeldingen van wedstrijden, teamfoto's en club-evenementen. De galerij gebruikt een popup-systeem met modern CSS voor een betere gebruikerservaring.

### Contact (contact.html)
Een contactpagina met contactgegevens, een formulier voor bezoekers en een kaart met de locatie van het clubterrein.

## 📝 Contactgegevens Club

- **Naam**: Sportvriend Hechtel
- **Adres**: Hoefstraat 4, 3940 Hechtel
- **Email**: info@sportvriend-hechtel.be
- **Telefoon**: 0470 12 34 56

## 🚀 Installatie & Gebruik

### Lokaal bekijken
1. Clone of download de repository:
   ```
   git clone https://github.com/yourusername/sportvriend-hechtel-site.git
   ```
2. Open de map en dubbelklik op `index.html` of open deze in uw favoriete browser
3. Navigeer door de site via het hoofdmenu

### Hosting
Deze statische website kan worden gehost op elke webserver of gratis hosting platforms zoals:
- GitHub Pages
- Netlify
- Vercel

---

© 2025 | Gemaakt voor UCLL Front-End Development | Alle rechten voorbehouden

