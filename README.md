# Sportvriend Hechtel - Voetbalclub Website

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

> 💡 Voor een gedetailleerd technisch overzicht van alle functionaliteiten, zie [FEATURES.md](FEATURES.md)

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
├── opdracht2.md           # Opdrachtbeschrijving
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

De website is volledig responsief met CSS media queries op verschillende breekpunten en biedt een optimale gebruikerservaring op diverse apparaten:

- **Mobiel (< 480px)**: 
  - Compacte weergave
  - Verticaal gestapelde navigatie
  - Vereenvoudigde layouts met één kolom
  - Kleinere tekstgrootte en padding voor efficiënt ruimtegebruik

- **Tablet (480px - 768px)**:
  - Aangepaste layouts voor middelgrote schermen
  - Verbeterde typografie en spacing
  - Geoptimaliseerde grid-indelingen (2 kolommen)

- **Kleinere desktop (768px - 1024px)**:
  - Flexibele containers
  - Meer white space
  - Verbeterde tabelweergave

- **Desktop (> 1024px)**:
  - Volledige layout met ruimere weergave
  - Maximale containerbreedte van 1200px
  - Optimale leesafstanden en interactieve elementen

## ✨ Designprincipes & UI Features

Bij het ontwikkelen van deze website zijn de CRAP-designprincipes consequent toegepast:

- **Contrast**: 
  - Gebruik van clubkleuren (donkergroen en geel) tegen lichte achtergronden
  - Hoog contrast voor betere leesbaarheid en visuele hiërarchie
  - Duidelijke kleurcodering voor belangrijke elementen (knoppen, links, headers)

- **Repetition**: 
  - Consistente styling en kleuren door de hele website
  - Herhaald gebruik van iconografie en typografie
  - Uniforme componentenstijlen (knoppen, formulierelementen, tabellen)
  - CSS variabelen voor kleurconsistentie en herbruikbaarheid

- **Alignment**: 
  - Gestructureerde grid-gebaseerde layout voor betere leesbaarheid
  - Consistente marges en paddings door gebruik van CSS variabelen
  - Zorgvuldige uitlijning van elementen binnen secties
  - Responsieve uitlijning die zich aanpast aan verschillende schermformaten

- **Proximity**: 
  - Logische groepering van gerelateerde elementen
  - Duidelijke informatiehiërarchie door ruimtelijke ordening
  - Visueel gescheiden secties met passende witruimte
  - Intuïtieve navigatiestructuur

## 🧪 Validatie & Toegankelijkheid

### HTML & CSS Validatie
- HTML gevalideerd volgens W3C HTML5-standaarden
- CSS gevalideerd volgens W3C CSS3-standaarden
- Foutloos bij controle via validatietools

### Toegankelijkheid
- Semantische HTML5-structuur voor betere assistive technology ondersteuning
- Duidelijke, beschrijvende alt-teksten voor alle afbeeldingen
- Toegankelijke formulierelementen met gekoppelde labels
- Voldoende kleurcontrast volgens WCAG-richtlijnen
- Logische focus-volgorde voor toetsenbordnavigatie
- Correct gebruik van headers voor documentstructuur (h1-h6)
- ARIA-attributen waar nodig voor verbeterde toegankelijkheid

### Browsercompatibiliteit
- Getest in moderne browsers (Chrome, Firefox, Edge, Safari)
- Fallback-styling voor oudere browsers
- Consistente weergave op alle geteste platforms

## 📚 Leerdoelen & Toegepaste Vaardigheden

Dit project demonstreert beheersing van meerdere front-end vaardigheden:

### HTML Beheersing
- Correct gebruik van semantische HTML5-elementen (header, nav, main, section, footer)
- Goed gestructureerde documentopbouw en hiërarchie
- Formuliervalidatie en -opmaak met relevante veldtypen
- Tabellen voor gestructureerde data (wedstrijdkalender)
- Correcte integratie van externe bronnen (Font Awesome)

### CSS Expertise
- Geavanceerde selectors en specificiteitsbeheer
- CSS-variabelen (custom properties) voor consistente styling
- Flexbox voor één-dimensionale layouts
- CSS Grid voor complexe twee-dimensionale layouts
- Responsieve media queries op meerdere breekpunten
- Effectieve CSS-organisatie met commentaar en secties
- CSS-animaties en -transities voor visuele feedback

### Responsief Design
- Mobile-first benadering met progressieve verbetering
- Adaptieve layouts die zich aanpassen aan diverse schermformaten
- Responsieve typografie en afbeeldingen
- Efficiënt ruimtegebruik op kleinere schermen

### UI/UX Principes
- Consistente visuele taal door de hele website
- Intuïtieve navigatie en gebruikersinterface
- Effectieve visuele hiërarchie en informatiestructuur
- Toepassing van CRAP-principes in alle aspecten van het ontwerp
- Gebruiksvriendelijke interactieve elementen (formulieren, fotogalerij)

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

## 📝 Contactgegevens

- **Adres**: Hoefstraat 4, 3940 Hechtel
- **Email**: info@sportvriend-hechtel.be
- **Telefoon**: 0470 12 34 56

---

© 2025 | Gemaakt voor UCLL Front-End Development | Alle rechten voorbehouden

