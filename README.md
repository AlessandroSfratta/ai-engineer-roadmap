# AI Engineer Roadmap - Public

Repository pubblica della roadmap AI Engineer.

Questa repo contiene solo materiale condivisibile pubblicamente e adatto a LinkedIn/portfolio.

## File principali

- `roadmap-linkedin.md`: versione consigliata per LinkedIn e portfolio.
- `road-map-completa.md`: versione pubblica dettagliata della roadmap.
- `cert-checklist.md`: checklist pubblica delle competenze.

## Regola di sincronizzazione

Ogni aggiornamento della roadmap deve essere applicato in entrambe le repository:

- repo pubblica: `ai-engineer-roadmap`
- repo personale/privata: `ai-engineer-roadmap-private`

La repo pubblica deve contenere solo file condivisibili. La repo privata puo contenere anche note operative, materiale di studio, preparazione colloqui e contenuti personali.

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

## Comandi consigliati

```bash
git add README.md .gitignore cert-checklist.md road-map-completa.md roadmap-linkedin.md
git commit -m "Update public roadmap"
git push
```

Dopo il push pubblico, aggiornare e committare la repo privata.

## Link

- Versione LinkedIn: [`roadmap-linkedin.md`](./roadmap-linkedin.md)
- Roadmap dettagliata: [`road-map-completa.md`](./road-map-completa.md)
- Checklist competenze: [`cert-checklist.md`](./cert-checklist.md)
