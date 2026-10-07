# BSOW — Press Book 2026

Press book officiel de **BSOW** (Smith Oswald Sylvenson BOCAMBO) — « Le Spirituel », LIKOUNDOU Beat.

- **`BSOW_Press_Book_2026.pdf`** — le press book final (A4, 14 pages, prêt à imprimer / envoyer).
- `pressbook/index.html` + `style.css` — la source (ouvrable dans un navigateur pour l’aperçu).
- `pressbook/assets/` — photos sélectionnées, pochettes, logo, QR codes, polices.
- `*.zip`, `image_de_coeur.jpeg` — photos d’origine.

## Régénérer le PDF

```bash
cd pressbook
npm install playwright   # une seule fois
node build.js            # écrit ../BSOW_Press_Book_2026.pdf
```

Pour modifier un texte ou une photo : éditer `pressbook/index.html`, puis relancer `node build.js`.
