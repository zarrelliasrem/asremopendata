# Dataset Informazioni Anagrafiche e Ricoveri

Questo dataset raccoglie dati anagrafici e socio-sanitari dei pazienti ricoverati durante l'anno 2023. Ogni riga rappresenta un paziente ricoverato e descrive alcune informazioni demografiche e di ammissione.

## Struttura del Dataset

| Colonna                                               | Descrizione                                                                 |
|--------------------------------------------------------|-----------------------------------------------------------------------------|
| Anno Della Scheda Di Ricovero                          | Anno in cui è stato registrato il ricovero                                 |
| Istituto Ospedaliero O Sanitario                       | Nome dell'ospedale in cui è avvenuto il ricovero                           |
| Genere Del Paziente (Es. 1 per Maschio, 2 per Femmina) | Genere del paziente. Alcuni valori possono essere in formato testuale      |
| Data Di Nascita Del Paziente                           | Data di nascita nel formato `aaaa/mm/gg`                                   |
| Cittadinanza                                           | Nazionalità dichiarata del paziente                                        |
| Livello Di Istruzione Del Paziente                     | Titolo di studio del paziente (es. Laurea, Licenza Elementare, ecc.)       |
| Reparto Di Ammissione                                  | Reparto in cui il paziente è stato inizialmente ricoverato                 |

##Note Tecniche

- Le date sono in formato `aaaa/mm/gg
- Alcuni valori del campo "Livello di Istruzione" possono essere mancanti o etichettati come `"Non dichiarato"`.
- Il campo "Reparto Di Ammissione" può includere reparti specifici o reparti pediatrici/neonatali (es. `Nido`).

##Possibili Analisi

- Distribuzione dei pazienti per età e genere.
- Correlazione tra livello di istruzione e tipo di reparto.
- Flussi di ricovero per fascia d’età o per cittadinanza.
- Valutazioni epidemiologiche in relazione ai reparti (es. analisi di carico in Psichiatria, Pediatria, ecc.).


