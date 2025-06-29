# QR-Profil System 🎯

Ein einfaches, kostenloses System zur Erstellung dynamischer Profile für T-Shirt QR-Codes.

## ✨ Features

- 📝 **Einfaches Admin-Interface** - Profile in Sekunden bearbeiten
- 📱 **QR-Code Generation** - Automatisch optimiert für T-Shirt Druck
- 🌐 **Social Media Integration** - Instagram, Twitter, LinkedIn, Facebook, YouTube, TikTok, Website
- 📟 **Responsive Design** - Funktioniert auf allen Geräten
- 💰 **100% Kostenlos** - Läuft auf GitHub Pages ohne laufende Kosten

## 🚀 Live Demo

👉 **[Demo ausprobieren](https://IHR-USERNAME.github.io/qr-profil-system)**

## 📸 Screenshots

### Admin Interface

![Admin Interface](docs/screenshot-admin.png)

### Profil-Vorschau

![Profil Vorschau](docs/screenshot-profile.png)

### QR-Code Generation

![QR-Code](docs/screenshot-qr.png)

## 🛠️ Installation & Setup

### Schritt 1: Repository forken

1. Klicken Sie auf “Fork” oben rechts
1. Wählen Sie Ihren GitHub Account

### Schritt 2: GitHub Pages aktivieren

1. Gehen Sie zu **Settings** in Ihrem geforkten Repository
1. Scrollen Sie zu **Pages**
1. Wählen Sie **Source: Deploy from a branch**
1. Wählen Sie **Branch: main** und **Folder: / (root)**
1. Klicken Sie **Save**

### Schritt 3: Ihre URL finden

Nach wenigen Minuten ist Ihr System verfügbar unter:

```
https://IHR-USERNAME.github.io/qr-profil-system
```

## 📋 Verwendung

### Profile erstellen

1. Öffnen Sie Ihre GitHub Pages URL
1. Gehen Sie zum Tab “Profil bearbeiten”
1. Füllen Sie Ihre Informationen aus
1. Klicken Sie “Profil speichern”

### QR-Code für T-Shirt

1. Wechseln Sie zum Tab “QR-Code”
1. Der QR-Code wird automatisch generiert
1. Rechtsklick → “Bild speichern unter…”
1. Verwenden Sie dieses Bild für den T-Shirt Druck

### T-Shirt Druck-Tipps

- **Mindestgröße:** 3x3 cm für zuverlässiges Scannen
- **Kontrast:** Schwarzer QR-Code auf weißem/hellem Untergrund
- **Position:** Brust oder Rücken, gut sichtbar
- **Material:** Glatte Oberflächen funktionieren am besten

## 🔧 Anpassungen

### Farben ändern

Bearbeiten Sie die CSS-Variablen in `index.html`:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
}
```

### Neue Social Media Plattformen hinzufügen

1. Erweitern Sie das `socialPlatforms` Objekt in `index.html`
1. Fügen Sie entsprechende Input-Felder hinzu
1. Aktualisieren Sie die CSS-Klassen

### Logo hinzufügen

Ersetzen Sie das 🎯 Emoji in der Überschrift mit Ihrem Logo:

```html
<h1><img src="logo.png" alt="Logo"> Ihr Firmenname</h1>
```

## 📱 Für Fortgeschrittene: Echte Datenbank

Wenn Sie viele Profile verwalten möchten, können Sie eine echte Datenbank integrieren:

### Firebase Integration (kostenlos bis 1GB)

1. Firebase Projekt erstellen
1. Firestore Datenbank aktivieren
1. Firebase SDK einbinden
1. Authentifizierung hinzufügen

### Netlify + Serverless Functions

1. Repository zu Netlify verbinden
1. Serverless Functions für API erstellen
1. Externe Datenbank (PlanetScale, Supabase) anbinden

## 🐛 Bekannte Limitationen

- **Keine Persistierung:** Profile werden nur temporär gespeichert
- **Ein Profil pro Instanz:** Für mehrere Profile benötigen Sie mehrere Deployments
- **Keine Benutzerauthentifizierung:** Jeder kann Profile bearbeiten

## 🔮 Roadmap

- [ ] Firebase Firestore Integration
- [ ] Benutzer-Accounts mit Login
- [ ] Mehrere Profile pro Account
- [ ] Bild-Upload für Profilfotos
- [ ] Analytics Dashboard
- [ ] Custom Domains
- [ ] Bulk QR-Code Generation
- [ ] PDF Export für Druckereien

## 🤝 Beitragen

Contributions sind willkommen! Bitte:

1. Forken Sie das Repository
1. Erstellen Sie einen Feature Branch (`git checkout -b feature/AmazingFeature`)
1. Committen Sie Ihre Änderungen (`git commit -m 'Add some AmazingFeature'`)
1. Pushen Sie den Branch (`git push origin feature/AmazingFeature`)
1. Öffnen Sie einen Pull Request

## 📄 Lizenz

Dieses Projekt steht unter der MIT Lizenz - siehe <LICENSE> Datei für Details.

## 💡 Support

- 📖 **Dokumentation:** Siehe [Wiki](../../wiki)
- 🐛 **Bug Reports:** [Issues](../../issues)
- 💬 **Diskussionen:** [Discussions](../../discussions)
- 📧 **Kontakt:** [Ihr Name](mailto:ihre-email@domain.com)

## 🙏 Credits

- QR-Code Generierung: [qrcode.js](https://github.com/davidshimjs/qrcodejs)
- Icons: Unicode Emojis
- Design: Custom CSS mit Gradient Themes

-----

⭐ **Gefällt Ihnen das Projekt?** Geben Sie uns einen Stern!

🔄 **Updates?** Aktivieren Sie “Watch” um über neue Features informiert zu werden.

-----

**Made with ❤️ for the T-Shirt QR-Code Community**