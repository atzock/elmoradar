# elmoradar Website

Eine moderne, responsive Website für den Microsoft Flight Simulator & VATSIM Streamer elmoradar aus Berlin.

## 🚀 Features

- **Responsive Design** - Optimiert für Desktop, Tablet und Mobile
- **Moderne Animationen** - Schwebende Elemente, Hover-Effekte und smooth Transitions
- **Interactive Navigation** - Smooth Scrolling mit aktiver Sektionshervorhebung
- **VATSIM Integration** - Speziell für Aviation-Content designt
- **Partner Section** - Kooperationen mit virtuellen Airlines
- **Video Integration** - YouTube Embeds für Content-Highlights
- **Performance Optimiert** - Schnelle Ladezeiten und optimierte Assets

## 🛠️ Technologien

- **HTML5** - Semantisches Markup
- **CSS3** - Custom Animations und Gradients
- **JavaScript (Vanilla)** - Interactive Features ohne Frameworks
- **Tailwind CSS** - Utility-first CSS Framework via CDN
- **Google Fonts** - Inter Schriftart für professionelles Design

## 📁 Projektstruktur

```
elmoradar-website/
├── index.html              # Haupt-HTML-Datei
├── assets/                 # Asset-Ordner
│   ├── logo.png           # elmoradar Logo
│   ├── plane.png          # Flugzeug-Icon für Animationen
│   ├── nordfly.png        # Nordfly Partner Logo
│   └── munichairways.jpg  # MunichAirways Partner Logo
└── README.md              # Diese Datei
```

## 🎨 Design-Features

### Farbschema
- **Primär**: Rot (#dc2626) bis Dunkelrot (#991b1b)
- **Sekundär**: Orange (#f97316) bis Gelb (#fbbf24)
- **Hintergrund**: Grau-900 (#111827) bis Grau-800 (#1f2937)
- **Text**: Weiß (#ffffff) und Grau-Abstufungen

### Animationen
- **Float Animation** - Schwebende Hintergrund-Elemente
- **Fly Animation** - Animiertes Flugzeug-Icon
- **Card Hover** - 3D Hover-Effekte auf Karten
- **Live Indicator** - Pulsierender "ON AIR" Indikator
- **Gradient Glow** - Aviation-spezifische Leuchteffekte

## 📱 Sektionen

1. **Hero Section** - Willkommensbereich mit Live-Indikator
2. **Stats** - Flugstatistiken (Flugstunden, VATSIM Flüge, etc.)
3. **Über mich** - Persönliche Vorstellung und Expertise
4. **PC Specs** - Hardware-Spezifikationen für MSFS
5. **Partner** - Virtuelle Airlines und Kooperationen
6. **Videos** - YouTube Content-Integration
7. **Kontakt** - Social Media Links und Kontaktmöglichkeiten

## 🔧 Installation & Setup

1. **Repository klonen oder Dateien herunterladen**
2. **Assets vorbereiten** - Logos und Bilder in `/assets/` Ordner platzieren:
   - `logo.png` - Haupt-Logo (empfohlen: 256x256px)
   - `plane.png` - Flugzeug-Icon für Animationen
   - `nordfly.png` - Partner-Logo
   - `munichairways.jpg` - Partner-Logo

3. **Links anpassen** - Social Media und externe Links in `index.html` aktualisieren:
   ```html
   <!-- Beispiel: Twitch Link -->
   <a href="https://twitch.tv/DEIN_USERNAME">
   
   <!-- Beispiel: YouTube Links -->
   <a href="https://www.youtube.com/@DEIN_KANAL">
   ```

4. **Content personalisieren**:
   - Stats-Zahlen anpassen
   - PC-Spezifikationen aktualisieren
   - Partner-Informationen bearbeiten
   - YouTube-Videos einbetten

5. **Website deployen** - auf Webserver hochladen oder Hosting-Service nutzen

## 🎥 YouTube Integration

Videos können einfach durch Ersetzen der Video-ID eingebettet werden:

```html
<iframe 
    src="https://www.youtube-nocookie.com/embed/DEINE_VIDEO_ID?rel=0&modestbranding=1&showinfo=0"
    title="Video Titel">
</iframe>
```

## 🏷️ Anpassungen

### Stats aktualisieren
```html
<div class="text-3xl md:text-4xl font-bold text-red-400 stats-counter">1.8K</div>
<div class="text-gray-400 mt-2">Flugstunden</div>
```

### PC-Specs bearbeiten
Jede Komponente hat eine eigene Karte mit Icon, Name und Spezifikation.

### Partner hinzufügen
Neue Partner können durch Kopieren einer bestehenden Partner-Karte hinzugefügt werden.

## 🌐 Browser-Kompatibilität

- **Chrome/Edge** - Vollständig unterstützt
- **Firefox** - Vollständig unterstützt
- **Safari** - Vollständig unterstützt
- **Mobile Browser** - Responsive Design optimiert

## 📈 Performance

- **Lighthouse Score** - Optimiert für 90+ Performance Score
- **Lazy Loading** - YouTube Videos werden bei Bedarf geladen
- **CDN Assets** - Tailwind und Fonts über CDN
- **Optimierte Bilder** - Komprimierte Assets empfohlen

## 🤝 Contributing

Verbesserungsvorschläge und Bug-Reports sind willkommen! 

## 📄 Lizenz

© 2025 elmoradar. Alle Rechte vorbehalten.
Made by atzock

## 🛟 Support

Bei Fragen oder Problemen:
- Kontakt über die Social Media Links auf der Website
- Issues im Repository erstellen (falls verfügbar)

---

**Tipp**: Für beste Performance sollten alle Bilder im WebP-Format und unter 500KB sein. Die Website ist für VATSIM-Piloten und Aviation-Enthusiasten optimiert! ✈️