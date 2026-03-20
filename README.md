# Risorse Didattiche

Materiali didattici per il laboratorio di informatica, pubblicati su GitHub Pages.

**Sito web:** https://mrobotto-dev.github.io/didattica-risorse/

## Struttura del repository

```
didattica-risorse/
├── index.html                        ← homepage con indice generale
├── ANNO-SCOLASTICO/
│   ├── CLASSE-materia/
│   │   ├── file-risorsa.html
│   │   └── ...
│   └── ...
└── ...
```

### Convenzioni di nomenclatura

| Elemento         | Formato                  | Esempio              |
|------------------|--------------------------|----------------------|
| Anno scolastico  | `YYYY-YY`               | `2025-26`            |
| Cartella classe  | `CLASSE-materia`         | `4G-sistemi-reti`    |

### Classi disponibili (2025-26)

| Cartella              | Classe | Materia                                       |
|-----------------------|--------|-----------------------------------------------|
| `1P-informatica`      | 1P     | Informatica                                   |
| `3G-sistemi-reti`     | 3G     | Sistemi e Reti                                |
| `4G-sistemi-reti`     | 4G     | Sistemi e Reti                                |
| `4G-tps`              | 4G     | Tecnologie e Progettazione di Sistemi         |
| `5G-goi`              | 5G     | Gestione Progetto e Organizzazione d'Impresa  |
| `5G-informatica`      | 5G     | Informatica                                   |
| `5G-sistemi-reti`     | 5G     | Sistemi e Reti                                |
| `5G-tps`              | 5G     | Tecnologie e Progettazione di Sistemi         |

## Come aggiungere nuove risorse

1. Copiare il file nella cartella appropriata: `ANNO/CLASSE-materia/`
2. Aggiornare la sezione della classe in `index.html`
3. Commit e push su `main` — GitHub Pages si aggiorna automaticamente
