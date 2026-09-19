# Rugby Borgo — Pagine pubbliche

Repo pubblico per pagine HTML condivisibili (calendari, strumenti, esperimenti) legate al
Rugby Borgo (ASD Rugby Fiumicello), pubblicate via GitHub Pages.

⚠️ Repo **separato e pubblico**: nessun dato riservato (atleti, valutazioni, materiale interno)
va caricato qui — quello resta nel vault privato `Rugby BORGO-Coach-Vault`.

## Pagine disponibili

- [`calendario-completo-2026-27.html`](calendario-completo-2026-27.html) — Calendario Rugby Borgo
  2026/27, Serie B + Serie C sulla stessa pagina, risultato incolonnato in ogni card partita
- [`calendario-serie-b-2026-27.html`](calendario-serie-b-2026-27.html) — Calendario Serie B
  2026/27, Girone 2, con filtro per giornata (mobile-friendly)
- [`calendario-serie-c-girone1-2026-27.html`](calendario-serie-c-girone1-2026-27.html) — Calendario
  Serie C 2026/27, Girone 1 Lombardia, con filtro per giornata (mobile-friendly)

## Dati

- [`Risultati_Serie_B-C_2026-27.xlsx`](Risultati_Serie_B-C_2026-27.xlsx) — tabella con tutte le
  partite di Serie B e Serie C (un foglio per campionato), da compilare con i punteggi
  ("Punti Casa" / "Punti Ospiti", celle gialle) man mano che si giocano, in vista del calcolo
  delle classifiche. Per aggiornarla: scaricala, modificala in Excel, poi ricaricala su GitHub
  (via web: "Add file → Upload files" nella pagina del repo, oppure chiedi a Claude Code di farlo).
  I risultati inseriti qui non si riflettono automaticamente nei calendari HTML sopra — vanno
  riportati a parte.

## Come si aggiunge una nuova pagina

1. Aggiungi il file `.html` (self-contained, senza dipendenze esterne)
2. Aggiungilo all'elenco sopra e al link in `index.html`
3. Commit e push su `main` — GitHub Pages la pubblica automaticamente
