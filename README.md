
## Personalizzazione veloce

- Colori: modifica le variabili CSS in cima a `style.css` (`:root { ... }`).
- Contenuti: modifica direttamente il testo in `index.html`, ogni sezione è racchiusa in un tag `<section>`.
- Font: attualmente usa Google Fonts "Inter", caricato via CDN nell'head di `index.html`.

## Note

- Il layout è **responsive**: su schermi piccoli la sidebar scorre sotto al contenuto principale.
- Nessuna dipendenza da build tool (no npm, no bundler): è puro HTML/CSS, quindi compatibile al 100% con GitHub Pages statico.
