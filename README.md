# IWNF02 Projekt Agiles Software Engineering – Quizsystem #

Modernes, interaktives Quizsystem mit Lobby. 
Entwickelt mit HTML, CSS, JavaScript, Node.js und Mongodb.

## Features ###

- 👥 Multiplayer-Lobby mit Spielmodi (z. B. Klassisch, Zeitangriff)
- 🛡 Admin-Bereich mit Modal-System zur Verwaltung
- 🎨 Responsives UI mit modernem CSS-Design
- 🗂 Deckverwaltung (Erstellen, Löschen, Bearbeiten)
- 📋 Fragen hinzufügen, bearbeiten und melden
- 📊 Leaderboard & Fortschrittsanzeige

### Setup ###

```bash
git clone https://github.com/MichaelSchmidt-IU/Projekt-Agiles-Software-Engineering.git
cd quiz-app
npm install
```

### .env Datei erstellen ###

Lege im Hauptverzeichnis eine Datei namens `.env` an und trage folgende Werte ein:

```env
PORT=3000
MONGO_URI=mongodb://localhost:27017/quizapp
JWT_SECRET=deinGeheimerJWTKey
```

> Achtung!!!!: Die `.env`-Datei **darf nicht** ins GitHub-Repository hochgeladen werden. Stelle sicher, dass `.env` in `.gitignore` enthalten ist.
erstelle dazu eine datei .gitignore

```gitignore
# Node.js & npm
node_modules/
package-lock.json

# Umgebungsvariablen
.env

# VS Code-Settings
.vscode/
```

### App starten ###

```bash
npm run dev

oder

npm run production
```

### - ###
