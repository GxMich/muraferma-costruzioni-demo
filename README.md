# Muraferma Costruzioni — sito dimostrativo

**Demo online → https://gxmich.github.io/muraferma-costruzioni-demo/**

> ### Attività di fantasia
>
> **Muraferma Costruzioni non esiste.** Nome, indirizzo (Rocca Tessera è un paese inventato), telefono,
> email, orari e cantieri sono inventati. Le foto vengono da Unsplash e sono etichettate come
> «Foto dimostrativa»: non mostrano lavori reali.
>
> L'email usa il dominio `muraferma-costruzioni.example`, riservato dallo IANA. Il telefono è
> `+39 000 000 0000`. Il modulo di preventivo e il pulsante WhatsApp sono **simulati**: non inviano nulla.
>
> La pagina ha `<meta name="robots" content="noindex, nofollow">` e `robots.txt` blocca il sito.

Home di un'impresa edile di paese, in una sola pagina: HTML e CSS scritti a mano, pochi righi di JavaScript,
nessuna libreria esterna.

## Cosa mostra la demo

- **Apertura a due ante**: foto del cantiere da un lato, dall'altro titolo, preventivo, telefono e WhatsApp.
- **Fascia dei dati** (impresa, lavori, zona, telefono) subito sotto, per chi cerca solo il numero.
- **Quattro servizi** (casa, capannone, facciate, manutenzioni) con foto e testo breve. La fascia
  delle facciate è color intonaco.
- **Come lavoriamo** in quattro passi, **tre cantieri d'esempio**, **dove lavoriamo**.
- **Modulo di preventivo** con tre campi soltanto: controlla i dati, segnala gli errori campo per campo e
  mostra una conferma di prova.
- **Barra di contatto fissa** su telefono (chiama, WhatsApp, preventivo).

## Tecnologie

- HTML e CSS senza framework. I colori, i caratteri e le spaziature sono variabili CSS in `tokens.css`.
- Font Archivo (larghezza variabile) ospitato nel progetto, licenza SIL OFL (`assets/fonts/`).
- Foto WebP con `srcset` e una versione verticale per l'apertura su schermi larghi.
- Pubblicazione su GitHub Pages direttamente dal ramo `main`.

## Avviarla in locale

```bash
python -m http.server 8000
```

Poi apri http://127.0.0.1:8000/.

## Crediti

Foto da Unsplash, elencate in [CREDITI-FOTO.md](CREDITI-FOTO.md). Sito dimostrativo realizzato da
[Michele Modica](https://www.modicamichele.it).
