<!-- ELUCENIA technical documentation · apfel · it · no clinical/professional/rights approval -->

# Punteggio di Apfel (nausea e vomito postoperatori)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/apfel)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Sesso femminile

`fem`

### Non fumatore

`naofuma`

### Anamnesi di nausea e vomito postoperatori o cinetosi

`historia`

### Uso previsto di oppioidi nel postoperatorio

`opioide`

## Edizione del metodo

Apfel semplificato 1999: 4 fattori, 0–4; non il modello Koivuranta

## Formula documentata

1 punto per fattore: sesso femminile, non fumatore, storia di PONV o cinetosi, oppioide postoperatorio.

## Limiti e popolazione

L’Apfel semplificato del 1999 è stato studiato in adulti sottoposti ad anestesia inalatoria, senza profilassi antiemetica, per nausea o vomito nelle prime 24 ore. Le probabilità della coorte originale non sono automaticamente ricalibrate per bambini, altre tecniche anestesiologiche o persone già in profilassi. La strategia antiemetica dipende da una valutazione e da una linea guida proprie.

## Riferimenti

- [Apfel CC et al. A simplified risk score for predicting postoperative nausea and vomiting: conclusions from cross-validations between two centers. Anesthesiology, 1999.](https://doi.org/10.1097/00000542-199909000-00022)

- [Gan TJ et al. Fourth consensus guidelines for the management of postoperative nausea and vomiting. Anesth Analg, 2020.](https://doi.org/10.1213/ANE.0000000000004833)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
