# Bäsebeiz v1.1 – mit Menüpflege, Statussystem & Rapport

Ein einfaches digitales Bestellsystem für Gastronomiebetriebe mit Fokus auf Selbstbedienung oder Service am Tisch.

## 🔧 Funktionen

- **Menüpflege** über Admin-Ansicht (Menü & Preise direkt bearbeitbar)
- **Live-Statusanzeige** der Bestellungen für die Küche (alle 5 Sekunden aktualisiert)
- **Klingelton & Vibration**, wenn neue Bestellungen eingehen
- **Gästeansicht** mit klarer Info zu Selbstbedienung oder Service
- **Rapportseite** (Zugriffscode: `885700`) für Tagesübersicht und Statistik
- **Sortierung nach ältester Bestellung zuerst** für die Küchenbearbeitung
- **Anzahl offener Bestellungen pro Gericht** sichtbar
- Mobile optimiert

## 🚀 Verwendung

1. Projekt auf Render.com deployen (Node.js + `node server.js`)
2. `menu.json` dient zur Verwaltung des Speiseplans
3. Adminzugriff via `/admin.html`
4. Rapportseite über `/rapport.html`

## 📁 Projektstruktur
