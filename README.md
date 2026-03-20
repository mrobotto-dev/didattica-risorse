# Risorse Didattiche

Materiali didattici interattivi per il laboratorio di informatica, pubblicati su GitHub Pages.

**Sito web:** https://mrobotto-dev.github.io/didattica-risorse/

## Struttura del repository

```
didattica-risorse/
├── index.html              ← homepage dinamica (legge risorse.json)
├── risorse.json            ← registro risorse pubblicate
└── ANNO/
    └── CLASSE-materia/
        └── modulo-slug/
            └── file-risorsa.html
```

### Convenzioni di nomenclatura

| Elemento         | Formato              | Esempio                    |
|------------------|----------------------|----------------------------|
| Anno scolastico  | `YYYY-YY`           | `2025-26`                  |
| Cartella classe  | `CLASSE-materia`     | `4G-sistemi-reti`          |
| Cartella modulo  | `slug-lowercase`     | `progetto-rete`            |
| File risorsa     | `PREFIX##.N_slug.html` | `SR06.2_diagrammi-rete.html` |

### URL pattern

```
https://mrobotto-dev.github.io/didattica-risorse/{anno}/{classe-slug}/{modulo-slug}/{filename}
```

## Come aggiungere nuove risorse

1. Copiare il file HTML nel path corretto: `ANNO/CLASSE-materia/modulo-slug/`
2. Aggiungere un'entry in `risorse.json`
3. Commit e push su `main` — GitHub Pages si aggiorna automaticamente (~1 min)
