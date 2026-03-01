# SousChef Rezepte 🍽️

Persönliche vegane Rezeptsammlung  optimiert für den **Cookidoo-Import** via Schema.org/Recipe JSON-LD.

---

## 🚀 Setup: GitHub Pages aktivieren

1. **Repository erstellen** auf github.com:
   - Name: `souschef-rezepte`
   - **Public** auswählen
   - "Create repository" klicken

2. **Dateien hochladen:**
   - Im Repository auf **"Add file"** → **"Upload files"**
   - Alle Dateien aus diesem Ordner per Drag & Drop hochladen
   - "Commit changes" klicken

3. **GitHub Pages aktivieren:**
   - **Settings** → **Pages** (links im Menü)
   - Source: **Deploy from a branch**
   - Branch: **main** / Ordner: **/ (root)**
   - **Save** klicken

4. **Fertig!** Nach 1–2 Minuten ist deine Seite live unter:
   ```
   https://DEINNAME.github.io/souschef-rezepte/
   ```

---

## 📥 Cookidoo-Import

1. Cookidoo → **Meine Kreationen** → **Rezept importieren**
2. URL eingeben, z.B.:
   ```
   https://DEINNAME.github.io/souschef-rezepte/rezepte/miso-glasierte-aubergine.html
   ```
3. **Importieren** klicken
4. Prüfen, ob Zutaten und Thermomix-Schritte erkannt wurden
5. Bei Bedarf nachbearbeiten und speichern

---

## 📁 Struktur

```
souschef-rezepte/
├── index.html                              ← Rezeptübersicht
├── rezepte/
│   └── miso-glasierte-aubergine.html       ← Rezept mit JSON-LD
└── README.md                               ← Diese Datei
```

Neue Rezepte einfach als HTML in den `rezepte/`-Ordner legen und in `index.html` verlinken.
