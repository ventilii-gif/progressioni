# Progressioni aritmetiche e geometriche

Web app didattica di matematica sulle **progressioni aritmetiche e geometriche**, per il
secondo biennio della scuola secondaria di secondo grado. Tutto in un unico file
(`index.html`): basta aprirlo nel browser, funziona anche **offline** e da **mobile**.
KaTeX è incluso localmente (cartella `katex/`), quindi non servono connessioni esterne.

## Struttura

Una **Home** di presentazione, una **Nota storica** comune e quattro sotto sezioni, più un
**quiz riepilogativo** finale. Ogni sotto sezione è organizzata in quattro schede:
**Teoria**, **Simulazione** interattiva, **Prova tu** (esercizi generati con correzione,
suggerimenti progressivi e soluzione) e un **Quiz** da 10 domande con correzione immediata e
ripasso finale degli errori.

1. **Nota storica** — Egizi e Babilonesi, Euclide e i numeri perfetti, Zenone e Archimede,
   la leggenda degli scacchi (Sissa) e il piccolo Gauss.
2. **Aritmetica · termine generale** — ragione costante, formula $a_n=a_1+(n-1)d$, termine
   medio aritmetico; simulazione della crescita lineare.
3. **Aritmetica · somma** — il trucco di Gauss e $S_n=\dfrac{n(a_1+a_n)}{2}$; simulazione del
   «rettangolo di Gauss» (termini + copia specchiata).
4. **Geometrica · termine generale** — rapporto costante, formula $a_n=a_1\,q^{\,n-1}$,
   comportamento al variare di $q$, termine medio geometrico; simulazione della crescita e
   decrescita esponenziale.
5. **Geometrica · somma** — $S_n=a_1\dfrac{q^{\,n}-1}{q-1}$ e la serie geometrica infinita
   $\dfrac{a_1}{1-q}$; simulazione delle somme parziali e della convergenza.
6. **Quiz riepilogativo** — 20 domande su tutto il percorso.

## Caratteristiche

- Tema **chiaro/scuro** con selettore e rispetto delle preferenze di sistema.
- Formule matematiche rese con **KaTeX**.
- Simulazioni su **canvas** reattive ai cursori.
- Accessibilità: niente coppie rosso/verde per corretto/errato (si usano blu/arancio con
  icone ✓/✕), focus visibile, navigazione a schede con `role="tab"`.

## Utilizzo

- In locale: aprire `index.html` con un qualsiasi browser moderno.
- Online: pubblicabile con GitHub Pages (Settings → Pages → branch di pubblicazione).
