# 🐦 Snopy — Modern Facility Management Platform

**Snopy** ist eine moderne **Facility Management** Anwendung, entwickelt mit **Laravel**, **React** und **Inertia.js**.  
Das Ziel: ein leistungsstarkes, benutzerfreundliches und skalierbares System, das Unternehmen hilft,  
Gebäude, Geräte, Wartungsaufgaben und Teams effizient zu verwalten.

---

## 🚀 Tech Stack

| Technologie | Beschreibung |
|--------------|---------------|
| **Laravel** | PHP-Framework für Backend, API, Authentifizierung und Business-Logik |
| **React** | Moderne JavaScript-Bibliothek für interaktive UI-Komponenten |
| **Inertia.js** | Brücke zwischen Laravel und React für eine nahtlose Single-Page-App-Erfahrung |
| **TypeScript** | Statisch typisierte Sprache für sauberen und wartbaren Frontend-Code |
| **Tailwind CSS** | Utility-First CSS-Framework für schnelles, responsives Design |
| **Pest** | Eleganter PHP-Test-Framework für moderne Laravel-Tests |

---

## ⚙️ Features (geplant & in Entwicklung)

- 🔐 Benutzer- und Rollenverwaltung
- 🏢 Objekt- und Anlagenmanagement
- 🧰 Wartungs- & Aufgabenplanung
- 🧾 Digitale Dokumentation & Berichte
- 💬 Interaktive Dashboards mit Echtzeitdaten
- ☁️ Cloud-bereit & skalierbar

---

## 🛠️ Installation

### Voraussetzungen
- PHP >= 8.2
- Composer
- Node.js & npm
- MySQL oder PostgreSQL
- XAMPP, Laravel Valet oder Sail (lokale Umgebung)

### Setup
```bash
# Repository klonen
git clone https://github.com/nccirtu/Snopy.git

cd Snopy

# Abhängigkeiten installieren
composer install
npm install

# .env-Datei einrichten
cp .env.example .env

# App-Key generieren
php artisan key:generate

# Datenbank migrieren
php artisan migrate --seed

# Entwicklungsserver starten
npm run dev
php artisan serve
```

Dann im Browser öffnen:  
👉 [http://localhost:8000](http://localhost:8000)

---

## 📸 Vorschau (demnächst)
> Screenshots und UI-Demos folgen in Kürze.

---

## 🧑‍💻 Autor

**Cristian Cirtu**  
🚀 Full Stack Developer  
📫 [GitHub @nccirtu](https://github.com/nccirtu)

---

## 📄 Lizenz

Dieses Projekt steht unter der **MIT-Lizenz**.  
Frei zur privaten und kommerziellen Nutzung, mit Namensnennung.
