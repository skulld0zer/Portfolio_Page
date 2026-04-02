# Portfolio Connect

Statische Portfolio-Seite im hellen Frosted-Glass-Stil fuer kostenloses Hosting ueber GitHub Pages.

## Warum diese Loesung

- kostenlos
- einfacher normaler Link
- perfekt fuer GitHub-Links, Streamlit-Links und lokale PDFs
- kein Backend noetig

## Struktur

- `index.html` -> komplette Seite
- `styles.css` -> Design und Layout
- `assets/docs/` -> deine PDF-Dokumentationen

## Deine Inhalte einsetzen

1. Ersetze in `index.html` die Platzhalter fuer:
   - Projektnamen
   - Kurzbeschreibungen
   - GitHub-Links
   - Streamlit-Links
   - Footer-Links
2. Lege deine PDFs in `assets/docs/`.
3. Passe in `index.html` die Dateinamen der PDF-Links und `iframe`-Quellen an.

## PDF-Dateien

Beispiel:

- `assets/docs/ai-requirements-engine-doc.pdf`
- `assets/docs/compliance-llm-doc.pdf`

## Lokal testen

Am schnellsten:

1. Oeffne `index.html` direkt im Browser.

Besser fuer realistische Tests:

1. Im Projektordner ein Terminal oeffnen
2. Ausfuehren:

```bash
python -m http.server 8000
```

3. Dann im Browser aufrufen:

`http://localhost:8000`

## Deployment mit GitHub Pages

1. Erstelle ein neues GitHub-Repository.
2. Lade die Dateien aus diesem Ordner hoch.
3. Gehe in GitHub auf `Settings > Pages`.
4. Waehle `Deploy from a branch`.
5. Nimm Branch `main` und Ordner `/root`.
6. Nach kurzer Zeit bekommst du einen Link wie:

`https://deinname.github.io/repository-name/`

## Eigene Domain

Nicht noetig. GitHub Pages funktioniert kostenlos direkt mit GitHub-URL.
Falls du spaeter willst, kannst du trotzdem eine eigene Domain anschliessen.
