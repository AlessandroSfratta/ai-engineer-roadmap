# AI Engineer Roadmap

Repository pubblica della roadmap AI Engineer.

Questa repo contiene solo la versione condivisibile pubblicamente, pensata per LinkedIn e portfolio. La roadmap operativa completa resta nella repository privata.

## Contenuto pubblico

- `ai-engineer-roadmap/ai-engineer-roadmap.md`: roadmap pubblica per LinkedIn/portfolio.

## Regola di sincronizzazione

Ogni aggiornamento della roadmap deve essere applicato in entrambe le repository:

- repo pubblica: `ai-engineer-roadmap`
- repo personale/privata: `ai-engineer-roadmap-private`

La repo pubblica deve contenere solo file condivisibili. La repo privata contiene anche note operative, materiale di studio, preparazione colloqui, checklist personali e una copia tracciata di questa cartella pubblica.

## Ordine standard di commit

Usare sempre questo ordine:

1. Aggiornare e controllare la repo pubblica.
2. Fare commit e push della repo pubblica.
3. Aggiornare la repo personale/privata.
4. Fare commit e push della repo personale/privata.

Questo ordine forza un controllo esplicito di cio che diventa pubblico prima di archiviare la versione completa.

## Checklist prima del commit pubblico

Prima di ogni commit su questa repo:

```bash
git status --short
git diff --check
git diff --cached --name-only
```

Verificare che non siano presenti:

- file privati o personali
- note operative non pensate per il pubblico
- file `.env`, token, chiavi o credenziali
- dataset, modelli o output generati

## Aggiornamento esercizi e mini-progetti

Quando viene completato un esercizio o un mini-progetto:

1. Aprire `ai-engineer-roadmap/ai-engineer-roadmap.md`.
2. Trovare lo step collegato all'esercizio.
3. Aggiungere una voce sotto **Mini-progetti / esercizi**.
4. Usare il formato: `Nome progetto` - descrizione breve, competenza allenata, output prodotto, link eventuale.
5. Se il mini-progetto diventa portfolio, aggiornare anche la tabella **Portfolio Target**.

Questa sezione deve restare pubblica e sintetica: niente note personali, credenziali, dataset privati o dettagli non condivisibili.

## Comandi consigliati

```bash
git add README.md .gitignore ai-engineer-roadmap/ai-engineer-roadmap.md
git commit -m "Update public roadmap"
git push
```

Dopo il push pubblico, aggiornare e committare la repo privata.

## Link

- Roadmap pubblica: [`ai-engineer-roadmap/ai-engineer-roadmap.md`](./ai-engineer-roadmap/ai-engineer-roadmap.md)
