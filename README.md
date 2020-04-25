# Progetto-Bioinformatica

##### A CURA DI Lorenzo Mauri, Samuele Manessi, Francesco Talarico

--------------------------------------------------------------------------------------------

- Introduzione

Il lavoro collaborativo è volto a sviluppare un simulatore stocastico in grado di modellare la dinamica dell'infezione da Covid19, a valutare l'efficacia delle misure cautelative adottate e ad effettuare una previsione della dinamica.

- Svolgimento 

Stima dei parametri iniziali della dinamica tramite algoritmo ILS (iterated Local Search).

Implementazione del sistema di equazioni differenziali per il calcolo delle variazioni degli stati lungo l'orizzonte temporale da `t=0` fino a `t=t+x`  dove $x \in \{1,\dots,n\}$ 


- Ultimi aggiornamenti 

semplificazione del modello : togliere immuni, asintomatici

la funzione min(deriv) è la funzione obiettivo (minimizzazione dei minimi quadrati rispetto ai dati osservati (vedi link)


- Next steps 

stabilire il range dei k coefficienti (l'algoritmo valuta n^k combinazioni di valori, dove n = # di coeff e k= # possibili valori)

valutare l'aggiunta di una componente stocastica 




- Sorgente dati 

https://github.com/pcm-dpc/COVID-19/blob/master/dati-andamento-nazionale/dpc-covid19-ita-andamento-nazionale.csv

stima dei casi asintomatici rilevati
https://www.epicentro.iss.it/coronavirus/pdf/sars-cov-2-traduzione-RRA-ECDC-12-marzo-2020.pdf

<< In Italia, il 44% dei casi confermati in laboratorio è risultato asintomatico. In Giappone, lo 0,06% dei casi segnalati sono risultati asintomatici. Queste proporzioni basate su casi notificati a livello nazionale riflettono probabilmente le diverse strategie di utilizzo dei test di laboratorio piuttosto che stime realistiche di infezioni asintomatiche >>



