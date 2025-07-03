# Dataset: Schede Di Dimissioni Ospedaliere –ASREM 2023

## Descrizione
Il presente dataset riporta le informazioni relative alle **schede di dimissione ospedaliera (SDO)** per l’anno **2023**, registrate presso l'Istituto ASREM della Regione Molise.

Contiene:
- Dati anagrafici e socio-demografici del paziente
- Informazioni sui ricoveri ospedalieri
- Reparti coinvolti (in ingresso, dimissione e trasferimenti interni)
- Indicatori amministrativi (tipo di record, priorità, istruzione, stato civile)

---

## Struttura del Dataset

| Colonna                                     | Descrizione                                                                 |
|---------------------------------------------|-----------------------------------------------------------------------------|
| `Regione`                                   | Regione di appartenenza della struttura ospedaliera                        |
| `Istituto Ospedaliero`                      | Nome della struttura presso cui è avvenuto il ricovero                     |
| `Anno Scheda Ricovero`                      | Anno di riferimento della scheda di dimissione                             |
| `ID Scheda`                                 | Codice univoco del ricovero                                                |
| `Genere Paziente`                           | Maschio / Femmina                                                           |
| `Data Nascita`                              | Data di nascita in formato AAAA/MM/GG                                      |
| `Comune di Nascita / Residenza`             | Informazioni territoriali anagrafiche                                      |
| `Cittadinanza`                              | Stato di cittadinanza del paziente                                         |
| `Istruzione`                                | Livello di istruzione dichiarato                                           |
| `Reparto Ammissione / Dimissione`           | Reparti di ingresso e uscita dal ricovero                                  |
| `Data Ammissione / Dimissione`              | Date del ricovero in formato AAAA/MM/GG                                    |
| `Trasferimenti Interni`                     | Fino a 5 reparti di trasferimento con relative date                        |
| `Tipo di Record`                            | Indicatore di tipologia della scheda (ordinaria/emergenza/neonatale ecc.)  |

---

## Dettagli sui Trasferimenti
Le colonne `Data Del Primo/Secondo/... Trasferimento` e `Reparto Del Primo/Secondo/... Trasferimento` riportano eventuali passaggi interni a reparti diversi durante il ricovero.

---

## Periodo di Riferimento
**Anno 2023**

## Fonte
**ASREM – Regione Molise**

## Formato File
- **Tipo**: CSV (Comma-Separated Values)
- **Separatore**: `,` (virgola)
- **Encoding**: UTF-8
- **Compatibilità**: Excel, Google Sheets, Python (pandas), R, strumenti BI

---

## Autore
**ASREM-- Regione Molise**

## Licenza
**CC BY 4.0 – Creative Commons Attribution 4.0 International**  
È consentito:
- **Utilizzare** il dataset
- **Condividerlo** e **modificarlo**
- **Adattarlo** anche per fini commerciali  
A condizione di citare la fonte: *ASREM, Regione Molise*

---

## Finalità e Applicazioni
Il dataset può essere utilizzato per:
- Analisi delle dinamiche di ricovero ospedaliero
- Studio dei profili socio-demografici della popolazione assistita
- Ottimizzazione dell'organizzazione ospedaliera
- Ricerca epidemiologica, valutazione della pressione su reparti specifici
- Progetti di data science e machine learning in ambito sanitario

---

