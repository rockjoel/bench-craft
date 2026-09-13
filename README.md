# Prototype QA notes

Template pubblici e checklist per **collaudo delimitato** di prototipi hardware / IoT a bassa tensione.

Obiettivo: rendere ripetibile il metodo (scope → prove → esito → limiti), senza fingere certificazioni.

## Contenuto

| File | Uso |
|---|---|
| [`templates/qa-report.md`](templates/qa-report.md) | Report di collaudo (pass / fail / partial / inconclusive) |
| [`checklists/lv-bench.md`](checklists/lv-bench.md) | Checklist banco LV prima di alimentare / saldare / concludere |
| [`checklists/reality-check.md`](checklists/reality-check.md) | Reality check piano digitale ↔ vincoli fisici |

## Esiti ammessi

- **pass** — criteri di accettazione soddisfatti nel perimetro dichiarato
- **fail** — almeno un criterio obbligatorio non soddisfatto
- **partial** — parte utile ok, resta lavoro o incertezza nota
- **inconclusive** — non si può decidere con le prove fatte (manca strumento, tempo, accesso, info)

## Cosa non è

Non è certificazione di prodotto, conformità CE, lavoro su rete elettrica, né audit di sicurezza professionale.

## Licenza

[MIT](LICENSE)
