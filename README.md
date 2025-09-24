<h1>
  <a href="https://rootgeek.github.io/Markdown-Live-Preview/">
    📝 Markdown Live Preview <sup><small>(Link)</small></sup>
  </a>
</h1>

<a href="https://postimg.cc/qNHbFpjT">
  <img src="https://i.postimg.cc/RZNkNFtN/Markdown.png"
       alt="Markdown Live Preview Screenshot"
       width="800"
       style="border:1px solid #000; border-radius:4px;">
</a>

A lightweight, purely client-side **Markdown editor with live preview**, syntax highlighting, word/character counter, keyboard shortcuts, synchronized scrolling, **drag-resize** between editor & preview, and **HTML export** as a ready-to-print page – **no build step, no backend**. Simply open `index.html` in your browser and start writing.

---

## ✨ Features

- **Live Preview**: Instant rendering while you type (marked + highlight.js)
- **Syntax Highlighting** for code blocks (auto-detection)
- **Toolbar Actions**: **Bold**, *Italic*, `Code`, ~~Strike~~, `H2`, `H3`, List, Quote, Code Block, Link
- **Word & Character Counter** in real-time
- **Synchronized Scrolling** between editor & preview
- **Panel Resize** via drag (editor/preview proportionally adjustable)
- **Autosave** in `localStorage` (offline capable)
- **HTML Export**: Generates a standalone, beautifully formatted HTML file with date header, print styles & responsive layout
- **Copy to Clipboard**: Copy exported HTML directly to clipboard
- **Mobile Responsive**: Vertical split on small displays
- **Keyboard Shortcuts**: Ctrl/⌘+B, Ctrl/⌘+I, Ctrl/⌘+K, Tab indentation

---

## 🧱 Tech Stack

- **[marked](https://github.com/markedjs/marked)** (CDN) – Markdown → HTML, GFM & line breaks active
- **[highlight.js](https://highlightjs.org/)** (CDN) – Auto-detection & syntax highlighting
- **Vanilla HTML/CSS/JS** – No build, no framework, ready to go

---

## 🚀 Quick Start

1. Clone this repository or download as ZIP
2. Open `index.html` in your browser
3. Start writing – enjoy the live preview on the right

> Note: No server components. Everything runs in the browser.

---

## 🧭 Usage

- Left: **Markdown Editor**
- Right: **Live Preview**
- **Toolbar** for common Markdown snippets
- **Resize Handle** (center) to adjust column width
- **Autosave**: Content is automatically saved in `localStorage`
- **Copy HTML**: rendered HTML to clipboard
- **📄 HTML Download**: generates a standalone HTML file with beautiful layout

---

## ⌨️ Keyboard Shortcuts

| Action | Shortcut (Windows/Linux) | Shortcut (macOS) |
|---|---|---|
| Bold | Ctrl + B | ⌘ + B |
| Italic | Ctrl + I | ⌘ + I |
| Insert Link | Ctrl + K | ⌘ + K |
| Indent | Tab | Tab |

---

## 🧾 HTML Export

The **"📄 HTML Download"** button creates a complete, standalone HTML file:
- Contains date header, clean typography layout, print styles & responsiveness
- Code blocks are formatted
- No external dependencies needed, file is locally saveable & printable

---

## 🛠️ Customization

- **Buttons/Toolbar**: Extend/customize in `index.html` in the `.toolbar` section
- **Styles**: Inlined CSS in the `<style>` block – colors/spacing easily changeable
- **marked/highlight.js**: Adjust versions via CDN URLs in the `<head>`
- **Export Theme**: Customize export styles in the `downloadHTML()` function template

---

## 🌐 Compatibility

- Modern Chromium, Firefox, and Safari versions
- Mobile & Desktop, Responsive Layout

---

## ⚠️ Known Limitations

- **Security**: Rendered HTML is set in preview DIV; don't insert foreign, untrusted content
- **LocalStorage**: Content is device-specific; no sync between devices
- **Highlighting**: Auto-detection may fail with exotic languages

---

## 📜 License

MIT License. Free to use, commercial & private. Pull requests/stars are appreciated ✨
