# Leggere la Costituzione

Un libro digitale sulla Costituzione Italiana realizzato con [mdBook](https://rust-lang.github.io/mdBook/).

## Struttura del libro

Il libro è organizzato secondo la struttura della Costituzione Italiana:

- **Prefazione** - Introduzione al progetto
- **Introduzione** - Contesto storico e importanza della Costituzione
- **Principi Fondamentali** - Articoli 1-12
- **Parte I - Diritti e Doveri dei Cittadini**
  - Titolo I - Rapporti Civili (Articoli 13-28)
  - Titolo II - Rapporti Etico-Sociali (Articoli 29-34)
  - Titolo III - Rapporti Economici (Articoli 35-47)
  - Titolo IV - Rapporti Politici (Articoli 48-54)
- **Parte II - Ordinamento della Repubblica**
  - Titolo I - Il Parlamento (Articoli 55-82)
  - Titolo II - Il Presidente della Repubblica (Articoli 83-91)
  - Titolo III - Il Governo (Articoli 92-100)
  - Titolo IV - La Magistratura (Articoli 101-113)
  - Titolo V - Le Regioni, le Province, i Comuni (Articoli 114-133)
  - Titolo VI - Garanzie Costituzionali (Articoli 134-139)
- **Disposizioni Transitorie e Finali**
- **Postfazione** - Riflessioni conclusive

## Prerequisiti

- [Rust](https://www.rust-lang.org/tools/install) e Cargo
- [mdBook](https://rust-lang.github.io/mdBook/guide/installation.html)

## Installazione

```bash
# Installa mdBook
cargo install mdbook
```

## Utilizzo

### Costruire il libro

```bash
mdbook build
```

Il libro HTML verrà generato nella directory `book/`.

### Servire il libro localmente

```bash
mdbook serve
```

Il libro sarà accessibile all'indirizzo `http://localhost:3000`.

### Testare il libro

```bash
mdbook test
```

## Struttura del progetto

```
.
├── book/           # Output HTML generato (non versionato)
├── src/            # Sorgenti markdown del libro
│   ├── SUMMARY.md  # Indice del libro
│   ├── prefazione.md
│   ├── introduzione.md
│   ├── articolo_001.md - articolo_139.md
│   ├── disposizioni_finali.md
│   └── postfazione.md
├── book.toml       # Configurazione mdBook
└── README.md       # Questo file
```

## Contribuire

I contenuti di ciascun articolo sono attualmente placeholder. Contributi per completare i contenuti sono benvenuti!

## Licenza

Vedere il file [LICENSE](LICENSE) per i dettagli.
