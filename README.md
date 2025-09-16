# Christian Buchholz – Personal Website

Diese Version ist für **GitHub Pages** vorbereitet und nutzt **Formspree** als Kontaktformular-Dienst, ohne dass eine E-Mail im Code sichtbar ist.

## Deploy (GitHub Pages)
1. Neues privates oder öffentliches GitHub-Repository anlegen (z. B. `christian-buchholz`).
2. Alle Dateien aus diesem Ordner ins Repo laden und committen.
3. **Settings → Pages**:
   - Source: `Deploy from a branch`
   - Branch: `main` / `/ (root)`
4. Nach ~1–2 Min. ist die Seite unter `https://<dein-username>.github.io/<repo-name>/` erreichbar.

## Formspree einrichten
1. Gehe zu https://formspree.io und melde dich an.
2. Lege ein neues Formular an → du erhältst eine Endpoint-URL wie `https://formspree.io/f/abcdwxyz`.
3. Öffne `index.html` und ersetze den Platzhalter `https://formspree.io/f/DEIN-ENDPOINT` im `action`-Attribut des Kontaktformulars durch deine echte Endpoint-URL.
4. Optional: Passe den Redirect in `thanks.html` oder im versteckten Feld `_next` an deine GitHub-Pages-URL an.

> Hinweis: Die E-Mail-Adresse bleibt bei dieser Lösung **unsichtbar** im Code. Der Versand und die Benachrichtigungen werden in Formspree konfiguriert.
