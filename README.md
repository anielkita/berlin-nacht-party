# Berlin Nacht — Party Anmeldung

Statische Party-Einladungsseite im Berlin-Style mit eingebettetem Google Formular für RSVPs.

## 1. Google Formular erstellen

1. Auf [forms.google.com](https://forms.google.com) ein neues Formular anlegen (z. B. Felder: Name, Anzahl Personen, E-Mail).
2. Oben rechts auf **Senden** klicken.
3. Tab **Einbetten `<>`** wählen, den `<iframe ...>`-Code kopieren.
4. In [index.html](index.html) den Platzhalter `DEINE_GOOGLE_FORMULAR_EMBED_URL_HIER_EINFUEGEN` im `<iframe src="...">` durch die echte URL aus dem kopierten Code ersetzen.
5. Antworten landen automatisch im Tab **Antworten** des Formulars bzw. optional in einer verknüpften Google-Tabelle.

## 2. Inhalte anpassen

In `index.html` Datum, Uhrzeit, Ort und Dresscode im Abschnitt `#details` anpassen.

## 3. Lokal testen

Einfach `index.html` im Browser öffnen, oder mit einem lokalen Server:

```bash
python -m http.server 8000
```

Dann `http://localhost:8000` öffnen.

## 4. Auf GitHub veröffentlichen

Siehe Anleitung im Chat / GitHub Pages Einstellungen des Repos.
