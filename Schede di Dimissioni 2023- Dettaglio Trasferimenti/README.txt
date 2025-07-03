# Dataset Trasferimenti Ospedalieri

Questo dataset contiene informazioni su pazienti ricoverati e i loro trasferimenti tra reparti durante il periodo di degenza. Ogni riga rappresenta un singolo caso di ricovero.

##Contenuto del file

| Colonna                          | Descrizione                                                                 |
|----------------------------------|-----------------------------------------------------------------------------|
| Numero Progressivo Della Scheda | Identificativo univoco del ricovero                                        |
| Data Di Ricovero                | Data di ammissione del paziente                                            |
| Reparto Di Ammissione           | Reparto iniziale di ammissione                                             |
| Reparto Del Primo Trasferimento | Primo reparto verso cui il paziente è stato trasferito                     |
| Reparto Del Secondo Trasferimento| Secondo trasferimento                                                      |
| Reparto Del Terzo Trasferimento | Terzo trasferimento                                                        |
| Reparto Del Quarto Trasferimento| Quarto trasferimento                                                       |
| Reparto Del Quinto Trasferimento| Quinto trasferimento                                                       |
| Reparto Di Dimissione           | Reparto da cui il paziente è stato dimesso                                 |

## Formato

- Il file è strutturato in formato tabellare CSV.
- I campi di testo contengono nomi dei reparti, alcuni dei quali possono avere divisioni o diciture differenti.
- Le date sono in formato `aaaa/mm/gg`.

## Possibili utilizzi

- Analisi del flusso dei pazienti tra i reparti.
- Studio dei percorsi di cura in reparti critici (es. Terapia Intensiva, Cardiologia).
- Ottimizzazione della gestione dei posti letto e pianificazione ospedaliera.
- Visualizzazione delle sequenze di trasferimento.

