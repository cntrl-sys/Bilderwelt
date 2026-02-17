# Bilderwelten - Galerie Website

Eine hochwertige, responsive Galerie-Website mit moderner Ästhetik.

## Struktur

### Startseite (index.html)
- 6 anklickbare Container-Boxen mit Kategorien
- Moderne Dark-Theme Ästhetik mit Orange-Akzenten
- Animierte Hover-Effekte
- Responsive Grid-Layout

### Galerieseiten
1. **galerie-natur.html** - 24 Naturbilder
2. **galerie-architektur.html** - 18 Architekturbilder
3. **galerie-urban.html** - 32 Urban Life Bilder
4. **galerie-abstrakt.html** - 27 Abstrakte Bilder
5. **galerie-meer.html** - 21 Meer & Küste Bilder
6. **galerie-berge.html** - 29 Bergbilder

### Features

✨ **Masonry Grid Layout**
- Automatische Spaltenanordnung (3 Spalten Desktop, 2 Tablet, 1 Mobile)
- Optimierte Bilddarstellung in verschiedenen Größen

🖼️ **Lightbox Funktionalität**
- Vollbild-Bildbetrachtung
- Tastaturnavigation (Pfeiltasten, ESC)
- Vor/Zurück Navigation
- Bildunterschriften

🎨 **Design Highlights**
- Grain-Overlay-Effekt für Film-Ästhetik
- Monospace Display Font (Courier New)
- Serif Body Font (Georgia)
- Gradient Akzente in Orange-Tönen
- Smooth Animations & Transitions
- Responsive Navigation

⚡ **Performance**
- CSS-only Animationen
- Lazy Load Ready
- Optimierte Bilder von Unsplash
- Minimale JavaScript-Nutzung

## Verwendung

1. Öffne `index.html` in deinem Browser
2. Klicke auf eine Kategorie-Box
3. In der Galerie: Klicke auf Bilder für Lightbox-Ansicht
4. Navigation: 
   - Zurück-Button → Zur Startseite
   - Pfeiltasten → Durch Bilder navigieren
   - ESC → Lightbox schließen

## Anpassung

### Farben ändern
Bearbeite die CSS-Variablen in `styles.css` und `gallery-styles.css`:
```css
:root {
    --color-accent: #ff6b35;        /* Hauptakzent */
    --color-accent-alt: #f7931e;    /* Sekundärakzent */
    --color-bg: #0a0e12;            /* Hintergrund */
}
```

### Eigene Bilder hinzufügen
Ersetze die Unsplash URLs in den HTML-Dateien mit deinen eigenen Bildpfaden:
```html
<img src="pfad/zu/deinem/bild.jpg" alt="Beschreibung">
```

### Neue Kategorien hinzufügen
1. Kopiere eine Galerie-HTML-Datei
2. Passe Titel und Bildanzahl an
3. Füge einen neuen Container in `index.html` hinzu

## Dateien

- `index.html` - Startseite
- `styles.css` - Styles für Startseite
- `gallery-styles.css` - Styles für Galerieseiten
- `gallery-script.js` - Lightbox-Funktionalität
- `galerie-*.html` - Einzelne Galerieseiten

## Browser-Kompatibilität

✅ Chrome/Edge (neueste Versionen)
✅ Firefox (neueste Versionen)
✅ Safari (neueste Versionen)
✅ Mobile Browser

## Technologien

- HTML5
- CSS3 (Grid, Flexbox, Custom Properties)
- Vanilla JavaScript (ES6+)
- SVG Icons

---

Erstellt mit Liebe zum Detail 🎨
