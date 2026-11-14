# Base Template

Szablon startowy dla nowych repozytoriów. Nowe repo zakładaj z niego:

```sh
gh repo create PoppyTea/NAZWA --template PoppyTea/Base-Template --private --clone
```

Co dostajesz:

- `CLAUDE.md` z treścią instrukcji i `AGENTS.md` jako link symboliczny do niego,
- wspólny zestaw etykiet issues.

## Etykiety

GitHub nie kopiuje etykiet z template, tylko pliki. Dlatego zestaw leży w
`.github/workflows/labels.yml`, a workflow zakłada etykiety przy pierwszym pushu
nowego repo. Zmiana listy w tym pliku i push aktualizują etykiety w danym repo.
