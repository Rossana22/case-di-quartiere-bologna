# Case di Quartiere di Bologna — Knowledge Graph

Progetto d'esame: costruzione di un Knowledge Graph sulle 32 Case di Quartiere di Bologna,
combinando le ontologie OntoPiA e ArCo con la generazione di triple assistita da LLM
(Claude, Gemini) su tre tecniche di prompting (zero-shot, few-shot, chain-of-thought),
verificato tramite Protégé/HermiT e query SPARQL.

Sito pubblicato: `https://<tuo-username>.github.io/case-di-quartiere-bologna/`

## Team
- Rossana Pedroni
- Camilla Sabato
- Elena Tufoni

## Struttura del sito

```
index.html          homepage — titolo, abstract, team
topic.html           il progetto — cosa sono le Case di Quartiere, il gap identificato
methodology.html     metodologia — fasi del lavoro, strumenti usati
ontology.html        ontologia — classi/proprietà riusate e custom (namespace bo:)
llm.html              prompting — le 3 tecniche + confronto Claude vs Gemini
sparql.html           query SPARQL con risultati reali (tutte le keyword richieste)
results.html          sintesi dei risultati ottenuti
challenges.html       problemi tecnici incontrati e come risolti
css/style.css        foglio di stile condiviso (tema Bologna terracotta)
data/                schema Turtle e prompt utilizzati, scaricabili dal sito
images/              immagini del sito (placeholder da sostituire)
```

## Come pubblicare su GitHub Pages

1. Crea un repository su GitHub (es. `case-di-quartiere-bologna`) e carica tutti i file di
   questa cartella nella root del repository.
2. Vai su **Settings → Pages**, imposta come sorgente il branch `main` e cartella `/root`, salva.
3. Dopo qualche minuto il sito sarà online su `https://<tuo-username>.github.io/case-di-quartiere-bologna/`.
4. Per aggiornare il sito: modifica i file `.html`/`.css` e fai push — GitHub Pages si aggiorna da solo.

## Sostituire i placeholder immagine

Le sezioni con sfondo tratteggiato (`.img-placeholder`) vanno sostituite con immagini reali.
Aggiungi i file in `images/` e sostituisci il blocco, ad esempio:

```html
<img src="images/nome-file.jpg" alt="Descrizione" style="width:100%; border-radius:10px;">
```
