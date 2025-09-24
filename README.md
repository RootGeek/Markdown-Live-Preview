<h1>
  <a href="https://rootgeek.github.io/Markdown-Live-Preview/">
    📝 Markdown Live Preview <small><small>(Link)</small></small>
  </a>
</h1>


<a href="https://postimg.cc/qNHbFpjT">
  <img src="https://i.postimg.cc/RZNkNFtN/Markdown.png"
       alt="Markdown Live Preview Screenshot"
       width="800"
       style="border:1px solid #000; border-radius:4px;">
</a>

Ein leichter, rein clientseitiger **Markdown‑Editor mit Live‑Vorschau**, Syntax‑Highlighting, Wort‑/Zeichenzähler, Tastenkürzeln, synchronisiertem Scrollen, **Drag‑Resize** zwischen Editor & Preview sowie **HTML‑Export** als fertige, druckfreundliche Seite – **ohne Build‑Schritt, ohne Backend**. Einfach `index.html` im Browser öffnen und losschreiben.

---

## ✨ Features

- **Live‑Vorschau**: Sofortiges Rendern während du schreibst (marked + highlight.js)
- **Syntax‑Highlighting** für Codeblöcke (Auto‑Erkennung)
- **Toolbar‑Aktionen**: **Bold**, *Italic*, `Code`, ~~Strike~~, `H2`, `H3`, Liste, Zitat, Code‑Block, Link
- **Wort‑ & Zeichenzähler** in Echtzeit
- **Synchronisiertes Scrollen** zwischen Editor & Vorschau
- **Panel‑Resize** via Drag (Editor/Preview prozentual verstellbar)
- **Autosave** im `localStorage` (Offline‑fähig)
- **HTML‑Export**: Generiert eine eigenständige, hübsch formatierte HTML‑Datei mit Datumskopf, Druck‑Styles & responsivem Layout
- **Copy‑to‑Clipboard**: Exportiertes HTML direkt in die Zwischenablage kopieren
- **Mobile‑Responsive**: Auf kleinen Displays als vertikaler Split
- **Tastenkürzel**: Strg/⌘+B, Strg/⌘+I, Strg/⌘+K, Tab‑Einrückung

---

## 🧱 Tech‑Stack

- **[marked](https://github.com/markedjs/marked)** (CDN) – Markdown → HTML, GFM & Zeilenumbrüche aktiv
- **[highlight.js](https://highlightjs.org/)** (CDN) – Auto‑Erkennung & Syntax‑Highlighting
- **Vanilla HTML/CSS/JS** – Kein Build, kein Framework, sofort startklar

---

## 🚀 Schnellstart

1. Dieses Repository clonen oder als ZIP laden
2. `index.html` im Browser öffnen
3. Schreiben – rechts die Live‑Preview genießen

> Hinweis: Keine Server‑Komponenten. Alles läuft im Browser.

---

## 🧭 Bedienung

- Links: **Markdown Editor**
- Rechts: **Live Preview**
- **Toolbar** für gängige Markdown‑Snippets
- **Resize‑Handle** (Mitte) zum Anpassen der Spaltenbreite
- **Autosave**: Inhalte werden automatisch in `localStorage` gesichert
- **Copy HTML**: gerendertes HTML in die Zwischenablage
- **📄 HTML Download**: generiert eine eigenständige HTML‑Datei mit schönem Layout

---

## ⌨️ Tastenkürzel

| Aktion | Shortcut (Windows/Linux) | Shortcut (macOS) |
|---|---|---|
| Fett | Strg + B | ⌘ + B |
| Kursiv | Strg + I | ⌘ + I |
| Link einfügen | Strg + K | ⌘ + K |
| Einrücken | Tab | Tab |

---

## 🧾 HTML‑Export

Der Button **„📄 HTML Download"** erstellt eine vollständige, eigenständige HTML‑Datei:
- Enthält Datumskopf, sauberes Typo‑Layout, Druck‑Styles & Responsiveness
- Code‑Blöcke werden formatiert
- Keine externen Abhängigkeiten nötig, Datei lokal speicher‑ & druckbar

---

## 🛠️ Anpassungen

- **Buttons/Toolbar**: In `index.html` im Bereich `.toolbar` erweitern/anpassen
- **Styles**: Inlined CSS im `<style>`‑Block – Farben/Abstände einfach änderbar
- **marked/highlight.js**: Versionen via CDN‑URLs im `<head>` justieren
- **Export‑Theme**: Export‑Styles im Template der `downloadHTML()`‑Funktion anpassen

---

## 🌐 Kompatibilität

- Moderne Chromium‑, Firefox‑ und Safari‑Versionen
- Mobil & Desktop, Responsive Layout

---

## ⚠️ Bekannte Einschränkungen

- **Sicherheit**: Gerendertes HTML wird im Preview‑DIV gesetzt; keine fremden, untrusted Inhalte einfügen
- **LocalStorage**: Inhalte sind gerätespezifisch; kein Sync zwischen Geräten
- **Highlighting**: Auto‑Erkennung kann bei exotischen Sprachen danebenliegen

---

## 📜 Lizenz

MIT-Lizenz. Frei verwendbar, kommerziell & privat. Über Pull Requests/Stars freue ich mich ✨
