# COVID19dataAnalysis
#### ultimo aggiornamento dati 14/04/2020
Repo for COVID19 Italy's data analysis based on data from Dipartimento Protezione Civile Italiana

## Fonti dati
I dati sono in gran parte forniti dalla [pagina GitHub](https://github.com/pcm-dpc/COVID-19) della Presidenza del Consiglio dei Ministri - Dipartimento della Protezione Civile che si occupa di aggiornare i dati ogni giorno alle 18:30 ora italiana.

Altri dati come la popolazione totale per regione, la quantità di posti letto in terapia intensiva per regione e la loro variazione sono presi da altri siti. (vedere [note](#note))


## Analisi dati
I dati qui forniti ed analizzati sono sotto forma di file excel .xlsx e suddivisi in fogli per regione.

I dati vengono analizzati fornendo svariati grafici dello stesso formato per ogni regione, oltre a grafici totali dell'andamento nazionale. I grafici ed i loro andamenti non vengono commentati per mancanza di esperienza in campo medico, statistico ed epidemiologico e per le conseguenze a cui analisi errate possono portare. 

Il raggruppamento dei dati in grafici serve quindi principalmente per dare un'idea approssimativa dell'andamento dell'epidemia che non deve essere scambiata per un parere esperto e si consiglia quindi di prenderli con la dovuta cautela.

Vengono fornite fonti per la migliore lettura e comprensione dei dati mostrati nei grafici.



## Altre fonti utili

### Interpretazione dati

Per poter meglio interpreatare i dati qui raggruppati si consigliano letture e video in merito all'argomento.

[Video di Abacaba](https://www.youtube.com/watch?v=LnQcbAKWkPE) sul **calcolo dei reali numeri del contagio** desunti dai dati dei casi accertati dopo un tampone (quindi in ritardo di 5-16 giorni sul reale singolo contagio) e **correlazione fra lockdown e diminuzione dei casi.**

[Video di 3Blue1Brown](https://youtu.be/Kas0tIxDvrg) in merito a crescite esponenziali e pandemie

[Video di MinutePhysics](https://youtu.be/54XLXg4fYsc) in merito a crescite esponenziali e pandemie

[Video di 3Blue1Brown](https://youtu.be/gxAaO2rsdIs) sulla simulazione di pandemie

[Video di Numberphile](https://youtu.be/k6nLfCbAzgo) sui modelli SIR e sul calcolo di R0

[Video di Tom Rocks](https://youtu.be/NKMHhm2Zbkw) sui modelli SIR e sul calcolo di R0

[Video di Khan Academy](https://youtu.be/mCa0JXEwDEk) sulla lettura e l'analisi di dati epidemiologici

[Articolo](https://medium.com/@tomaspueyo/coronavirus-act-today-or-people-will-die-f4d3d9cd99ca) ([in italiano](https://medium.com/tomas-pueyo/coronavirus-perché-agire-ora-bd6c02ee0785)) sulla lettura e l'analisi di dati epidemiologici molto dettagliato

[Articolo (in italiano)](https://www.linkedin.com/pulse/modellando-levoluzione-di-covid-19-italia-ettore-mariotti) su modelli SIR, calcolo di R0 ed evoluzione del Covid-19 in Italia

### Fonti varie di approfondimento su Covid-19

[Video di Kurzgesagt](https://youtu.be/BtN-goy9VOY) sul Covid-19

Canale YouTube di [Abacaba](https://www.youtube.com/user/1abacaba1) con video relativi alla diffusione mondiale del Covid19 e confronto con altre epidemie 

[Video di Dario Bressaini](https://youtu.be/gC1Y70My_iE) su epidemie e sull'importanza del distanziamento sociale

[Articolo del Sole 24 Ore](https://www.infodata.ilsole24ore.com/2020/04/11/coronavirus-dati-analisi-similazioni-selezione-fonti-luoghi-discussione-online/) contenente svariate fonti informative utili, gruppi FaceBook, siti di data analysis, articoli.




## Note

### Dati popolazione

I dati sulla popolazione sono dati ISTAT presi da [tuttitalia](https://www.tuttitalia.it/regioni/) e aggiornati al 1 Gennaio 2019, arrotondati per difetto al migliaio.

### Posti in terapia intensiva disponibili

I dati dei posti totali delle terapie intensive in Italia suddivisi per regione sono presi da [quotidianoSanità](http://www.quotidianosanita.it/m/studi-e-analisi/articolo.php?articolo_id=82888) e da [trueNumbers](https://www.truenumbers.it/coronavirus-terapia-intensiva/), essendo leggermente discostanti non sono stati presi per totalmente affidabili, soprattutto perché mancanti di dati temporali certi.

### Aggiornamento dei dati

Al momento i dati di questa repository che dovrebbero essere aggiornati con cadenza giornaliera in seguito alla pubblicazione da parte della Protezione Civile dei nuovi dati giornalieri (alle 18:30 ora italiana), non vengono aggiornati vista la mole di lavoro che comporta e a causa di una pessima scrittura dei collegamenti dei dati su Excel fra i fogli e i grafici. 

Per chi volesse aggiornare manualmente i dati (**più di un giorno mancante**) può scaricare il file [dpc-covid19-ita-regioni da qui](https://github.com/pcm-dpc/COVID-19/blob/master/dati-regioni/dpc-covid19-ita-regioni.csv) e sostituire i dati nel foglio excel 'cov[data]', ordinarli alfabeticamente per regione, copiare i dati di ogni regione e incollarli nel foglio della specifica regione, controllando che i grafici si aggiornino.

**In alternativa** si può prendere il file [dpc-covid19-ita-regioni-latest](https://github.com/pcm-dpc/COVID-19/blob/master/dati-regioni/dpc-covid19-ita-regioni-latest.csv) contenente solo i dati del giorno corrente ed incollarli in fondo agli altri dati nel foglio excel, copiando poi le singole nuove righe per ogni regione ed incollandole in fondo ai dati del foglio corrispondente.

In futuro il problema del lungo procedimento di copia manuale nei singoli fogli potrebbe essere risolto aggiungendo collegamenti dinamici fra i fogli (non so come fare, help).

