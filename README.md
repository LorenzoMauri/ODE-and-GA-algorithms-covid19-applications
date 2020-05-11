# Progetto-Bioinformatica

##### A CURA DI Lorenzo Mauri, Samuele Manessi, Francesco Talarico

--------------------------------------------------------------------------------------------

##### PARTE 1 
	


Il progetto richiede di analizzare il gene ACE2. I dati del gene si trovano alla pagina https://www.ensembl.org/Homo_sapiens/Gene/Summary?db=core;g=ENSG00000130234;r=X:15561033-15602148 

1. Leggere il file in un DataFrame, rimuovendo le righe che non si riferiscono al gene (il file contiene anche un miRNA).
2. Calcolare il numero di esoni per ogni trascritto
3. Calcolare la lunghezza di ogni trascritto
4. Le proteine associate a tali trascritti
5. Determinare le regioni genomiche (esone o porzione di esone) che sono presenti in tutti i trascritti. Ogni regione genomica è identificata da una posizione di inizio e una di fine.

Il file .gtf è contenuto nel folder data 


##### PARTE 2 

Il lavoro collaborativo è volto a sviluppare un simulatore stocastico in grado di modellare la dinamica dell'infezione da Covid19 e di effettuare previsioni.

- Premesse 

Siccome non vi è evidenza scientifica alcuna circa lo sviluppo dell'immunità, il numero iniziale è stato scelto arbitrariamente, ipotizzando che il 95% degli individui guariti sviluppi anticorpi della malattia.

- Svolgimento 

Utilizzo dell'algoritmo genetico (GA)

- Sorgente dati 

https://github.com/pcm-dpc/COVID-19/blob/master/dati-andamento-nazionale/dpc-covid19-ita-andamento-nazionale.csv

stima dei casi asintomatici rilevati
https://www.epicentro.iss.it/coronavirus/pdf/sars-cov-2-traduzione-RRA-ECDC-12-marzo-2020.pdf

<< In Italia, il 44% dei casi confermati in laboratorio è risultato asintomatico. In Giappone, lo 0,06% dei casi segnalati sono risultati asintomatici. Queste proporzioni basate su casi notificati a livello nazionale riflettono probabilmente le diverse strategie di utilizzo dei test di laboratorio piuttosto che stime realistiche di infezioni asintomatiche >>



