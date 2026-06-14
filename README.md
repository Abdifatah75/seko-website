# 🌐 SEKO e.V. – Website

Mehrsprachige Website (DE/SO/EN/AR) für die Somali European Cooperation e.V. mit Mitglieder-Registrierung.

## 🔗 Wichtige Links
- **Live-Website:** https://abdifatah75.github.io/seko-website
- **Mitglied werden:** https://abdifatah75.github.io/seko-website/mitglied.html
- **GitHub:** https://github.com/Abdifatah75/seko-website
- **Supabase (Datenbank):** https://supabase.com/dashboard/project/szxaihxcfczebijzqrmq
- **EmailJS:** https://www.emailjs.com

## 📁 Dateien
- `index.html` – Hauptseite (Hero, Angebote, Galerie, Projekte, Kontakt)
- `mitglied.html` – Mitglieder-Registrierung (mit Supabase + EmailJS)
- `logo.png` – SEKO Logo
- `bild1.webp` – `bild9.webp` – Galerie-Bilder
- `Bilder/` – Original-Bilder

## 🔑 Zugangsdaten (Backend)

### Supabase (Datenbank)
- **Projekt:** seko-mitglieder
- **URL:** https://szxaihxcfczebijzqrmq.supabase.co
- **Publishable Key:** sb_publishable_CjF4z4QI3GzwCGx0Rl6eLg_8jLz27Mt
- **Tabelle:** mitglieder
- **Mitglieder ansehen:** Supabase Dashboard → Table Editor → mitglieder

### EmailJS (E-Mail Bestätigung)
- **Service ID:** service_vwjnmkh
- **Template ID (Mitglied):** template_qikdl2d
- **Public Key:** TNZrFLFCzbvNLObnc
- **Absender:** abdifatah.mohomed75@gmail.com

## 🔄 Änderungen auf GitHub hochladen
```powershell
cd C:\Users\abdif\Documents\Projekte\SekoWebsite
git add .
git commit -m "Beschreibung der Änderung"
git pull origin main --rebase
git push
```
GitHub Pages aktualisiert die Website automatisch nach 2-3 Minuten.

## ✅ Funktionen (fertig)
- 4 Sprachen (DE/SO/EN/AR)
- Responsive Design (Mobile + Desktop)
- Galerie mit echten Fotos
- Mitglieder-Registrierung → Datenbank (Supabase)
- Automatische Mitgliedsnummer (SEKO-2026-XXXX)
- Bestätigungs-E-Mail an Mitglied

## 📋 Noch zu erledigen (To-Do)
- [ ] Admin-Benachrichtigung per E-Mail (bei neuer Registrierung)
- [ ] Admin-Dashboard (alle Mitglieder ansehen/exportieren)
- [ ] Spenden-System (Stripe / PayPal)
- [ ] RLS Sicherheit wieder aktivieren (aktuell deaktiviert)
