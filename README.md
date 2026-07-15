# EasyCheck

**Soluzione per la gestione digitale degli assegni bancari**

EasyCheck è un'applicazione desktop Windows sviluppata da [AION Soft](https://www.aionsoft.it) per acquisire, archiviare, ricercare e gestire gli assegni bancari (e le cambiali) in modo digitale, ordinato e tracciabile.

Il servizio include lo scanner professionale **Panini Vision X** fornito in comodato d'uso per tutta la durata del contratto.

---

## Versione trial

Questo repository contiene la versione trial di EasyCheck, disponibile per valutazione gratuita per **15 giorni** dal primo avvio — non è richiesto alcun file di licenza per iniziare.

Durante il periodo di prova sono attive le seguenti funzionalità:

| Funzionalità | Trial |
|---|:---:|
| Scansione singola | ✅ |
| Archivio e ricerca assegni | ✅ |
| Modalità batch | ✅ |
| OCR importo e data | ✅ (fino a 100 assegni/mese) |
| Export CSV | ❌ |
| Statistiche avanzate | ❌ |
| Multi-postazione SQL Server | ❌ |

Negli ultimi 3 giorni di prova l'app mostra un avviso di scadenza imminente. Allo scadere dei 15 giorni è necessario attivare una licenza Standard o Professional per continuare a utilizzare il software.

Per attivare una licenza, contatta AION Soft.

---

## Download

Scarica l'ultima versione disponibile dalla sezione [Releases](https://github.com/AION-Soft-Org/easycheck-release/releases/latest).

---

## Requisiti di sistema

- Sistema operativo: **Windows 10 / Windows 11**
- RAM: minimo 4 GB consigliati
- Spazio su disco: minimo 200 MB
- Scanner: **Panini Vision X** (incluso nel servizio EasyCheck)
- Per la Licenza Professional con multi-postazione: **SQL Server** (versione compatibile da concordare con AION Soft)

---

## Installazione

1. Scarica il file di installazione dalla sezione [Releases](https://github.com/AION-Soft-Org/easycheck-release/releases/latest)
2. Esegui il file `.exe` e segui la procedura guidata
3. Al primo avvio parte automaticamente il periodo di prova gratuito di 15 giorni: non è richiesto alcun file di licenza. Quando la trial sta per scadere o vuoi attivare una licenza definitiva (Standard o Professional), carica il file di licenza fornito da AION Soft dalla schermata Licenza
4. Collega lo scanner Panini Vision X e configura le impostazioni iniziali

Per supporto all'installazione o configurazioni avanzate, contatta AION Soft.

---

## Funzionalità principali

- Scansione singola e batch degli assegni (fino a 50 assegni in modalità batch)
- Acquisizione immagine fronte e retro
- Lettura automatica del codice MICR
- OCR importo e data (Licenza Professional, incluso in trial con quota limitata)
- Gestione cambiali e vaglia in alternativa/affiancamento agli assegni, con campo debitore dedicato
- Archivio digitale consultabile con ricerca avanzata
- Filtri per data, importo, cliente, stato, codice MICR, tipo documento e altri campi
- Controllo automatico dei duplicati
- Associazione assegni a clienti, sedi o punti di raccolta
- Generazione distinte di versamento in formato PDF
- Export CSV
- Wizard di migrazione dati da precedenti installazioni della versione Java di EasyCheck
- Multi-postazione con SQL Server condiviso (Licenza Professional)

---

## Licenze disponibili

| | Licenza Standard | Licenza Professional |
|---|:---:|:---:|
| Scansione singola | ✅ | ✅ |
| Archivio assegni | ✅ | ✅ |
| Ricerca e consultazione | ✅ | ✅ |
| Export CSV | ✅ | ✅ |
| Modalità batch | ❌ | ✅ |
| OCR importo e data | ❌ | ✅ |
| Statistiche avanzate | ❌ | ✅ |
| Multi-postazione SQL Server | ❌ | ✅ |
| Scanner Panini Vision X in comodato d'uso | ✅ | ✅ |

Per informazioni sui prezzi e le condizioni contrattuali, visita [aionsoft.it](https://www.aionsoft.it/easycheck) o contatta direttamente AION Soft.

---

## Supporto

Per assistenza tecnica, attivazione licenza o informazioni commerciali:

- 🌐 [www.aionsoft.it](https://www.aionsoft.it)
- 📧 info@aionsoft.it

---

## Note legali

EasyCheck è un software proprietario sviluppato da AION Soft.
Tutti i diritti riservati. © 2026 AION Soft.

Il software è distribuito esclusivamente per utilizzo secondo le condizioni della licenza sottoscritta (o, per la versione trial, secondo i termini di valutazione gratuita descritti sopra).
È vietata la redistribuzione, la modifica o l'utilizzo commerciale non autorizzato.

Lo scanner Panini Vision X incluso nel servizio rimane di proprietà di AION Soft ed è fornito in comodato d'uso per tutta la durata del contratto. Alla cessazione del contratto il dispositivo deve essere restituito secondo le modalità concordate.

I dati acquisiti tramite EasyCheck sono salvati localmente presso il cliente. AION Soft non ha accesso ai dati del cliente. Il cliente è responsabile della conservazione, protezione e backup dei propri dati.
