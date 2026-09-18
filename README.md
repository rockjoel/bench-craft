# bench-craft

Public **templates, checklists, and sanitized technical background** for bounded prototype bring-up — low-voltage hardware, sensors, and shop fabrication.

Built from years of **hardware-first bench craft** (datasheets, forums, broken boards) before coding agents entered the loop. Phone and backend software was usually a collaborator’s lane; hardware choices were still discussed together. The point is a repeatable method: **scope → proofs → outcome → limits** — without pretending to certify products.

## What’s inside

| Path | Use |
|---|---|
| [`templates/qa-report.md`](templates/qa-report.md) | Bring-up / QA report (pass / fail / partial / inconclusive) |
| [`checklists/lv-bench.md`](checklists/lv-bench.md) | Low-voltage bench checklist |
| [`checklists/reality-check.md`](checklists/reality-check.md) | Plan vs physical world before you scale |
| [`background/`](background/) | Tools, component families, capabilities, honesty notes |

## Allowed outcomes

- **pass** — acceptance criteria met inside the declared perimeter  
- **fail** — a required criterion failed  
- **partial** — useful but incomplete; uncertainty stated  
- **inconclusive** — not decidable with the proofs that were run  

## What this is not

Not product certification, not medical/structural approval, not mains/electrician work, not a professional security audit.

## Related

- Profile: [rockjoel](https://github.com/rockjoel)  
- Post-AI tooling: [local-skill-router](https://github.com/rockjoel/local-skill-router)

## License

[MIT](LICENSE)
