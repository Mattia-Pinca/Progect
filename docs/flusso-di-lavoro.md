# Flusso di lavoro per ogni commessa

Dalla candidatura alla consegna.

## 1. Valutazione del lavoro (prima di candidarsi)

- È fattibile con le competenze disponibili? Sì / No / Forse
- Requisiti chiari o ambigui? (Se ambigui, fai domande prima di accettare)
- I termini permettono l'uso di strumenti AI?
- Tempo stimato vs compenso: ne vale la pena?
- Ci sono rischi (dati sensibili, scadenze strette, cliente poco chiaro)?

## 2. Setup del progetto

```bash
cp -r _template-progetto progetti/AAAA-MM-cliente-tipo
```

- Compila `BRIEF.md` incollando la richiesta del cliente.
- Annota domande aperte e chiariscile col cliente.

## 3. Sviluppo

- Lavora in `src/`.
- Tieni il codice ordinato e commentato dove utile.
- Procedi a piccoli passi verificabili.

## 4. Test e verifica

- Segui la `CHECKLIST.md`.
- Esegui davvero il codice / prova la soluzione.
- Non consegnare mai output non verificato.

## 5. Consegna

- Prepara `consegna/` con file finali + istruzioni.
- Scrivi il messaggio per il cliente (vedi `MESSAGGIO-CONSEGNA.md`).
- Aggiorna lo stato nel `README.md` del progetto.

## 6. Revisioni e chiusura

- Annota le richieste di modifica nel `BRIEF.md`.
- Alla fine, segna lo stato come "chiuso".

## Regole d'oro

1. **Chiarisci prima, sviluppa dopo.** Un brief vago = lavoro rifatto.
2. **Verifica sempre.** Il nome sulla consegna è il tuo.
3. **Proteggi i dati.** Niente credenziali nel repo.
4. **Sii onesto sui tempi.** Meglio promettere meno e consegnare bene.
