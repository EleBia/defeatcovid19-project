# Applicabilità del metodo Machine Learning nella diagnosi precoce di COVID-19 - studio osservazionale

Sinossi dello studio, versione 1 del 25/03/2020


## Titolo

Applicabilità del metodo Machine Learning nella diagnosi precoce di COVID-19 - studio osservazionale


## Sede dello studio

........................................ *(UO di riferimento)* – Neosperience S.p.A., sedi di Milano, via Gaspare Gozzi 1a e Brescia, via Orzinuovi 20; Looptribe S.r.l sede di Brescia, via Cipro 66.


## Obiettivi dello studio

Lo studio intende:

1. Valutare la fattibilità e l’applicabilità del progetto Intelligenza Artificiale - Machine Learning nell’attuale e contingente emergenza COVID-19 e in particolare nella realtà ........................................ *(UO di riferimento)*. Il Machine Learning è definita come un insieme di  differenti meccanismi che permettono a una macchina intelligente di migliorare le proprie capacità e prestazioni nel tempo. La macchina, quindi, sarà in grado di imparare a svolgere determinati compiti migliorando, tramite l’esperienza, le proprie capacità, le proprie risposte e funzioni. Alla base dell’apprendimento automatico ci sono una serie di differenti algoritmi che, partendo da nozioni primitive, sapranno prendere una specifica decisione piuttosto che un’altra o effettuare azioni apprese nel tempo.

2. Inserire il maggior numero di dati e immagini possibili in modo da strutturare schemi predefiniti e standardizzati con cui confrontare e valutare i dati diagnostici.

3. Quantificare l’impatto di un’eventuale avviamento del progetto stesso in termini di:

  1. Incremento della possibilità di esito favorevole
  2. Diminuzione dei tempi di attesa
  3. Rapida individuazione delle ospedalizzazioni indispensabili rendendo più accessibili le postazioni di terapia intensiva
  4. Precisione di uno strumento operatore indipendente
  5. Minore utilizzo di altri metodi diagnostici operatore dipendente (che già scarseggiano sul territorio) con conseguente snellimento e alleggerimento del carico di lavoro dei laboratori di analisi

Lo studio si pone l'obiettivo di effettuare una prima analisi d'insieme identificando i dati certamente incompatibili con il quadro clinico polmonite da COVID19, che andranno ospedalizzati e/o trattati in modi e strutture differenti; e i casi dubbi o fortemente compatibili con il quadro clinico in esame, che andranno validati con ulteriori metodi diagnostici dalla Struttura Sanitaria e/o dall'ISS.


## Disegno dello studio

Studio osservazionale


## Popolazione dello studio

Saranno analizzati i dati (diagnostica per immagine  RX e/o eco cardiache/polmonari) di tutti i pazienti sani, affetti da patotologie cardiache e/o polmonari, identificati (o sospetti) COVID19 con patolgie cardiache e/o polmonari; afferenti alla ........................................ *(UO di riferimento)*, nel periodo marzo 2020 – dicembre 2020, che sono stati ricoverati presso la struttura.


## Periodo studiato

Marzo 2020 - Dicembre 2020


## Dati analizzati

- dati relativi ai risultati di diagnostica per immagine ottenuti tramite apparecchiatura RX e/o eco cardiaca/polmonare nella realtà dell’........................................ *(UO di riferimento)*
- dati relativi alle cartelle cliniche/ informazioni anamnesiche dei pazienti in esame con relative terapie farmacologiche in atto.
- dati derivati dal Registro Epidemiologico della Regione Lombardia
- valutazione tempo totale di attesa dei pazienti dall’accesso in ospedale alla diagnosi di COVID-19
- confronto di tali valutazioni con i dati sperimentali derivati dalle tecniche diagnostiche attualmente in uso nonché con i dati forniti dall’ISS


## Analisi statistica

I dati verranno analizzati, unitamente alle informazioni di referto, così da costruire un dataset utile all’addestramento del modello di machine learning. Sarà prodotto un modello di classificazione binaria della probabilità di diagnosi favorevole oppure sfavorevole, in base alle immagini fornite al sistema.

I dati verranno analizzati con modelli computazionali di deep neural network con architettura specifica per analizzare le immagini; per l’analisi dei modelli verranno usate metriche specifiche quali:
- Precision & Recall
- F1 score del modello
- valutazione dei threshold nell’ottica di importanza di falsi negativi/falsi positivi
- Curva del Receiver Operating Characteristic (ROC)
- Area under curve (AUC)


## Trattamento dei dati

Si rende noto che il trattamento dei dati avverrà nel rispetto dei principi fissati all’articolo 5 del Regolamento (UE) 2016/679, in forma anonima e per le finalità espressamente dichiarate nel presente documento.

I risultati degli studi condotti andranno a supporto gratuito di tutto il personale medico nazionale e saranno, pertanto, impiegabili in strutture private e pubbliche nei reparti preposti all’identificazione e al trattamento del COVID-19.

I dati verranno salvati in formato DICOM e trattati in una cartella protetta sui server di Neosperience S.p.A.

Neosperience S.p.A e Looptribe S.r.l. si fanno garanti del trattamento e della conservazione dei dati utilizzati e raccolti durante lo studio per un periodo di 2 anni (periodo di riferimento 2020-2021).
