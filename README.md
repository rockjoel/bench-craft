# Prototype QA notes

Template pubblici, checklist e **background tecnico** per collaudo delimitato di prototipi (hardware / IoT a bassa tensione e oltre).

Obiettivo: rendere ripetibile il metodo (scope → prove → esito → limiti), senza fingere certificazioni.

## Contenuto

| Percorso | Uso |
|---|---|
| [`templates/qa-report.md`](templates/qa-report.md) | Report di collaudo (pass / fail / partial / inconclusive) |
| [`checklists/lv-bench.md`](checklists/lv-bench.md) | Checklist banco LV |
| [`checklists/reality-check.md`](checklists/reality-check.md) | Reality check piano ↔ fisico |
| [`background/`](background/) | **Strumenti, componenti e capacità** del percorso tecnico (sanitizzato) |

## Esiti ammessi

- **pass** — criteri soddisfatti nel perimetro dichiarato
- **fail** — criterio obbligatorio non soddisfatto
- **partial** — utile ma incompleto / incertezza nota
- **inconclusive** — non decidibile con le prove fatte

## Cosa non è

Non è certificazione di prodotto, conformità CE, lavoro su rete elettrica, né audit di sicurezza professionale.

## Licenza

[MIT](LICENSE)
