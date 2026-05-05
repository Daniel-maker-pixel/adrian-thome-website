# Adrian Thomé Website – Netlify Deployment

## Dateien in diesem Paket

| Datei | Inhalt |
|-------|--------|
| `index.html` | Hauptseite (grüne Version mit SVG-Icons) |
| `impressum.html` | Impressum |
| `datenschutz.html` | Datenschutzerklärung |
| `netlify.toml` | Netlify-Konfiguration |

---

## Vor dem Veröffentlichen — Platzhalter ersetzen

Öffne `index.html` in einem Texteditor (z.B. Notepad++ oder VS Code)
und ersetze folgende Stellen:

### 1. Kajabi Buchungs-URL (3x)
Suche nach: `KAJABI_BUCHUNG_URL`
Ersetze mit: deiner Kajabi-Buchungsseiten-URL
Beispiel: `https://deinname.kajabi.com/erstgespraech`

### 2. Telefonnummer
Suche nach: `DEINE_TELEFONNUMMER`
Ersetze mit: deiner Telefonnummer
Beispiel: `+4917491234567`

### 3. Domain in Meta-Tags
Suche nach: `DEINE-DOMAIN.de`
Ersetze mit: deiner Domain
Beispiel: `adrian-thome.de`

### 4. Impressum vervollständigen
Öffne `impressum.html` und trage deine Adresse ein
(alle Stellen mit ⚠ markiert)

### 5. Datenschutz anpassen
Öffne `datenschutz.html` und trage deine Domain und
Kontaktdaten ein (alle Stellen mit ⚠ markiert)

---

## Website live schalten — 3 Schritte

### Schritt 1 — Netlify-Account erstellen
Gehe zu **netlify.com** → "Sign up" → mit E-Mail registrieren (kostenlos)

### Schritt 2 — Website hochladen
- Im Netlify-Dashboard: **"Add new site"** → **"Deploy manually"**
- Den kompletten Ordner mit allen Dateien per Drag & Drop ins
  Upload-Feld ziehen
- Netlify generiert automatisch eine URL (z.B. `zufaellig-123.netlify.app`)

### Schritt 3 — Eigene Domain verbinden (optional)
- Im Netlify-Dashboard: **"Domain settings"** → **"Add custom domain"**
- Domain bei deinem Registrar (Strato, IONOS etc.) auf Netlify zeigen lassen
- Anleitungen unter: docs.netlify.com/domains-https/custom-domains/

---

## Kajabi-URL später eintragen

Wenn du die Kajabi-Buchungsseite fertig eingerichtet hast:
1. `index.html` öffnen
2. `KAJABI_BUCHUNG_URL` durch die echte URL ersetzen
3. Datei erneut auf Netlify hochladen (Drag & Drop wie oben)

Netlify aktualisiert die Seite automatisch in ca. 30 Sekunden.

---

## Technische Details

- Keine Datenbank, kein Server-Backend
- Läuft komplett als statische HTML-Dateien
- SSL/HTTPS automatisch über Netlify (kostenlos)
- CDN (schnelle Ladezeiten weltweit) inklusive
- Unbegrenzte Besucher im Free Plan

---

© 2026 Adrian Thomé · Heilpraktiker für Psychotherapie
