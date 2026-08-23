# ProtoLingua Edizioni — Landing Page

Landing page statica per **ProtoLingua Edizioni**, lezioni di italiano 1-to-1 per expat.

🔗 Sito live: [protolingua-edizioni.com](https://protolingua-edizioni.com) *(dopo il collegamento DNS)*

## Cosa contiene

Un'unica pagina HTML autonoma (nessun backend, nessuna build, nessuna dipendenza da installare):

- `index.html` — markup, stili e piccolo script inline per l'animazione del transcript in hero

## Stack

- HTML + CSS puro (variabili CSS per i design token)
- Un piccolo script vanilla JS per l'effetto di digitazione nella card "dialogo dal vivo"
- Font: [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) (display), [Inter](https://fonts.google.com/specimen/Inter) (testo), [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) (dettagli/transcript) via Google Fonts

## Design token

| Ruolo | Valore |
|---|---|
| Sfondo | `#050506` |
| Pannelli | `#121216` |
| Accento viola | `#6d4aff` |
| Accento viola chiaro | `#8a6bff` |
| Testo primario | `#f5f5f5` |
| Testo secondario | `#9ca3af` |

## Sviluppo locale

Nessuna build richiesta — basta aprire `index.html` nel browser, oppure servirlo con un server statico qualsiasi:

```bash
python3 -m http.server 8000
```

## Deploy

Il sito è collegato a **Netlify** con deploy automatico a ogni push su `main`.

1. Push su questo repository → Netlify rileva il commit e ripubblica automaticamente
2. Dominio personalizzato configurato su Netlify (Domain settings), DNS gestito su Hostinger

## Roadmap

Il piano di lancio completo (brand, prodotti digitali, marketing, revisione trimestrale) è tracciato separatamente su Notion — vedi `ProtoLingua_Roadmap.csv` nel workspace del progetto.

## Da fare / TODO

- [ ] Sostituire il CTA `mailto:` con l'embed Calendly una volta configurato
- [ ] Integrare la copy homepage definitiva (bozza attuale generata come placeholder)
- [ ] Collegare il form newsletter (Mailchimp/Formspree)

---
© 2026 ProtoLingua Edizioni
