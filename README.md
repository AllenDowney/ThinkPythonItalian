# ThinkPythonItalian
Sorgenti LaTeX della traduzione italiana di Think Python.

[Download della versione PDF della traduzione.](https://github.com/AllenDowney/ThinkPythonItalian/blob/master/thinkpython_italian.pdf)

Traduzione di Andrea Zanella.

La versione originale in inglese di Allen B. Downey si trova sul sito [thinkpython2.com](http://thinkpython2.com)

## Build

**Prerequisiti:**:

* latex:

```bash
$ sudo dnf install texlive-scheme-full
```

* hevea: necessario per la creazione dell'ebook in formato `html`

```bash
$ sudo dnf install hevea
```

* calibre: necessario per la creazione dell'ebook in formato `epub`

```bash
$ sudo dnf install calibre
```

### Build in formato Pdf

Per creare l'ebook in PDF occorre seguire i seguenti passi:

* spostarsi nella directory `2.0`:

```bash
$ cd 2.0
```

* eseguire la build usando il Makefile:

```bash
$ make
```

### Build in formato Epub:

* spostarsi nella directory `2.0`:

```bash
$ cd 2.0
```

* eseguire il build in `html`:

```bash
$ make hevea
```

* eseguire il build in `epub`:

```bash
$ make epub
```
