# DEDUCO — Print & Play

> Un mandante che nessuno ha mai visto ha ordinato la morte di una persona seduta a questo tavolo.

Gioco di **deduzione sociale** per 4–8 giocatori, 20 minuti. Due fazioni nemiche — i **civili** (gialli) e i **sicari** (rossi) — agiscono in segreto ogni turno: si interroga, si protegge, si colpisce. Il primo che raggiunge sei ferite chiude la partita e decide le sorti del tavolo.

**Autore:** Giovanni Addeo · **Edizione:** Print Edition

---

## 📦 Contenuto della repository

### `print/` — i PDF stampabili (scala 100%)

| # | File | Contenuto | Stampa |
|---|------|-----------|--------|
| 01 | `01-carte-ruolo.pdf` | 8 carte ruolo 63×88 mm fronte/retro (civili gialli, sicari rossi) | duplex, flip bordo lungo |
| 02 | `02-tessere-azione.pdf` | 10 tessere-azione 63×88 mm (metà gialla / metà rossa) fronte/retro | duplex, flip bordo lungo |
| 03 | `03-colpi-ferite.pdf` | 60 gettoni-ferita Ø24 mm | semplice |
| 04 | `04-gettoni-si-no-interroga-protetto.pdf` | 24 gettoni Ø30 mm: SÌ ×6, NO ×6, NON PUOI PIÙ INTERROGARE ×6, PROTETTO ×6 | semplice |
| 05 | `05-gettoni-ordine.pdf` | 8 gettoni numerati Ø30 mm (ordine dei posti) | semplice |
| 06 | `06-plancia-giocatore.pdf` | plancia giocatore: slot SECRET CARD 63×88 + 6 caselle colpi | semplice |
| 07 | `07-plancia-centrale.pdf` | plancia centrale grande (fondo azzurro, fazioni) | A4 orizzontale |
| 08 | `08-plancia-centrale-x4.pdf` | 4 plance centrali per foglio A4 | semplice |
| 09 | `09-schede-ruoli-simboli.pdf` | 4 schede di gioco fronte/retro (ruoli+foto / simboli) | duplex, flip bordo lungo |
| 10 | `10-guida-narratore.pdf` | guida illustrata 4 pagine (regole complete, foto componenti) | semplice |
| 11 | `11-scatola-copertina.pdf` | wrap copertina scatola 180×130×40 mm (fronte artwork / retro regole) | adesivo o 200 g |
| 12 | `12-fasi-segnalini.pdf` | segnalini fase: interrogatorio / protezione / azione + puntatore FASE CORRENTE | semplice |

### `console/` — la console del narratore
`Deduco-console.html` — registro digitale del narratore: guida passo-passo, traccia audio narrante, ferite, registro interrogatori, gettoni bruciati, tabellone. Si apre nel browser (anche dal telefono), funziona offline.

### `docs/`
`guida-testo-semplice.pdf` — versione solo-testo della guida (stampa economica).

### `src/` — sorgenti
`prep/` e `prep2/` contengono le immagini elaborate (fronti carte, retro, gettoni PNG, artwork scatola) usate per generare i PDF — utili per rigenerare o modificare con gli script.

---

## 🖨️ Come stampare

1. **Carta consigliata:** 200–300 g/m² per carte, plance e gettoni; adesivo lucido o 200 g per la scatola.
2. **Scala sempre 100%** (niente "adatta alla pagina").
3. **Fronte/retro:** stampa duplex con **flip sul bordo lungo** — i PDF sono già speculari, combaciano.
4. Prova prima la 01 su carta normale per verificare l'orientamento duplex della tua stampante.
5. Ritaglia lungo le guide sottili; i gettoni si ritagliano lungo i cerchi.
6. Le tessere-azione sono riscrivibili: cancella il pennarello a fine partita con un panno umido.

## 🎲 Il gioco in sintesi

- **Setup:** mazzetto ruoli per numero giocatori (tabella in guida), gettoni-numero in senso orario, cartine-ruolo coperte, una tessera-azione a testa.
- **Fase 1 · Interrogatorio:** dal numero 1, chi vuole fa una domanda chiusa; si risponde in segreto col gettone SÌ/NO e si dice la verità. Una domanda sola per tutta la partita.
- **Fase 2 · Protezione:** tutti indicano insieme chi proteggere. Il più votato è immune agli attacchi del turno. Parità = nessuno.
- **Fase 3 · Azione:** ognuno scrive in segreto il simbolo nello spazio del proprio colore. Le tessere raccolte e mescolate si rivelano: si vede la fazione, non la mano.
- **Fine:** il primo a sei ferite scopre il ruolo — assassino → vincono i civili; cittadino → vincono i sicari; altri → conta le ferite totali.

## 📁 Struttura

```
deduco/
├── print/       11 PDF pronti per la stampa
├── console/     console del narratore (HTML, offline)
├── docs/        guida in versione semplice
└── src/         sorgenti immagine (PNG/JPG)
```

## ⚖️ Licenza e uso

Progetto privato di Giovanni Addeo. Tutti i diritti riservati — riproduzione e distribuzione riservate all'autore.
