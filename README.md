# I Tesori di Riwi · Esploratori dell'Invisibile

Prototipo di una piattaforma di libri personalizzati per bambini a tema scientifico. Il primo titolo è *Riwi e i tesori della cellula*, con testi di Loriana Vitillo e illustrazioni di Eleonora Balloi.

Il bambino diventa protagonista del viaggio con Riwi, il ragno esploratore, dentro una cellula della pelle: membrana, organelli, nucleo, DNA → RNA → proteina, fino alla cattura della proteina tesoro EGFR.

## Cosa c'è

- `index.html`: sito statico in una sola pagina, senza dipendenze a parte i Google Fonts.
  - **Configuratore**: nome, esploratrice o esploratore (con le concordanze nel testo), capelli, carnagione, acconciatura, occhiali, scuola e dedica.
  - **Anteprima sfogliabile**: 13 doppie pagine personalizzate, copertina e calamita tesoro finale con numero di matricola.
  - **La collana**: sei missioni, una per tipo di cellula.
  - **Il mondo di Riwi**: personaggi, oggetti ricorrenti, motto e formula di ogni missione.
  - **Scuole**: Edizione Classe, kit per l'insegnante, laboratorio con le autrici.
- `img/`: tavole estratte dal PDF del libro, più due ritagli (`riwi.png`, `navicella.png`).

## Come aprirlo

Apri `index.html` nel browser, oppure servi la cartella con un server statico qualsiasi. Si può pubblicare anche su GitHub Pages.

## Stato

È solo frontend. Non ci sono ancora carrello, pagamenti, salvataggio degli ordini né generazione del PDF di stampa. L'avatar del configuratore è un segnaposto in SVG: le varianti vere del protagonista saranno disegnate da Eleonora.

Da confermare: prezzo, formato, il nome del pianeta Telaria e i titoli delle missioni 2–6.

## Prossimi passi

1. **Negozio**: carrello e pagamenti, per esempio con Shopify.
2. **Generatore del libro**: il PDF di stampa si compone dal livello del protagonista, disegnato per ogni posa e variante, sopra gli sfondi delle tavole, con il testo personalizzato.
3. **Stampa**: integrazione con uno stampatore print-on-demand.
4. **Area scuole**: caricamento dell'elenco della classe per l'ordine di gruppo.

## Diritti

Illustrazioni © Eleonora Balloi. Testi © Loriana Vitillo. Tutti i diritti riservati.
