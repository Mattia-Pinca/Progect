# Officina Lavori Freelance IT

Repository "officina" per gestire i lavori informatici presi dalle piattaforme
freelance (Upwork, Fiverr, Freelancer, AddLance, ecc.) e realizzati con il
supporto di Claude.

L'obiettivo è avere un flusso ripetibile per ogni commessa: dal brief del
cliente alla consegna finale, passando per sviluppo e test.

## Come funziona

Ogni lavoro è una cartella dentro `progetti/`, creata copiando il
`_template-progetto/`. Ogni progetto contiene:

- **`BRIEF.md`** — la richiesta del cliente, i requisiti, budget e scadenza.
- **`src/`** — il codice/lavoro vero e proprio.
- **`consegna/`** — il materiale finale da dare al cliente (file, guide, note).
- **`CHECKLIST.md`** — controlli da fare prima di consegnare.
- **`README.md`** — scheda riassuntiva del progetto.

## Avviare un nuovo lavoro

```bash
# Copia il template (sostituisci NOME-PROGETTO)
cp -r _template-progetto progetti/2026-01-nome-cliente-tipo-lavoro
```

Poi:
1. Compila `BRIEF.md` incollando la richiesta del cliente.
2. Sviluppa dentro `src/`.
3. Spunta la `CHECKLIST.md` prima della consegna.
4. Prepara la consegna in `consegna/`.

## Convenzione nomi cartelle

`AAAA-MM-cliente-tipo` — esempio: `2026-06-rossi-fix-wordpress`

Tiene i progetti ordinati cronologicamente e leggibili a colpo d'occhio.

## Struttura

```
.
├── _template-progetto/     # Modello da copiare per ogni nuovo lavoro
├── progetti/               # Tutti i lavori, uno per cartella
├── docs/                   # Note utili: piattaforme, prezzi, processi
└── README.md
```

## Promemoria importanti

- **Verifica sempre** il lavoro prima di consegnarlo: testarlo, non incollare
  output non controllato al cliente.
- **Controlla i termini** del singolo lavoro/piattaforma riguardo all'uso di
  strumenti AI.
- **Attenzione ai dati sensibili**: niente credenziali o dati personali dei
  clienti committati nel repo (vedi `.gitignore`).
- Vedi `docs/` per la lista delle piattaforme e i template operativi.
