# Master 2024 Installation Instructions

Gentili studentesse e gentili studenti,
 
al fine di prepararvi al meglio per l'inizio delle lezioni e non incorrere in problemi tecnici abbiamo preparato questa mail (densa di istruzioni), con lo scopo di fornirvi i dettagli per poter installare i software necessari prima dell'inizio dei corsi.
 
In questa email NON sono presenti informazioni relative al software da far girare su Windows, ovvero Sql Management Studio, che riceverete in seguito.
  
## ATTENZIONE: LEGGERE TUTTE LE ISTRUZIONI ATTENTAMENTE PRIMA DI PROSEGUIRE.

- **Installazione ANACONDA**
Anaconda è una piattaforma open-source contenente vari pacchetti e software che utilizzeremo durante il master.
Trovate il software al seguente link:
https://www.anaconda.com/products/individual
Installate la versione individuale (individual) di anaconda. Abbiate cura di selezionare correttamente il vostro sistema operativo (dovrebbe essere riconosciuto automaticamente, in ogni caso, al link sopra, trovate tutti i pacchetti per qualsiasi sistema operativo)

- **Installazione PYCHARM**
Pycharm è un ambiente di sviluppo. L'equivalente di Word per scrivere programmi.
Trovate il software al seguente link:
https://www.jetbrains.com/pycharm/download/
La versione da installare è la Community (free e open source). Anche qui, state attenti a scegliere l’installer corretto per il vostro sistema operativo.

- **Installazione Environment Master**
Dopo l'installazione di Anaconda, potrete avviare Anaconda-Navigator che è un'interfaccia grafica per aprire i vari software. Seguendo il video tutorial allegato e dopo aver scaricato il file .yml allegato, utilizzate il file .yml per installare i pacchetti python di cui avrete bisogno. Seguite il tutorial video per indicazioni puntuali. Fate questo solo DOPO aver correttamente installato Anaconda. Il comando da eseguire, e che trovate anche nel video, è: <code>conda env create -v -f env_master.yml</code>
La fase di installazione potrebbe richiedere un tempo variabile a seconda del vostro computer. Attendete pazientemente. Mentre l'installazione è in corso NON spegnere il PC o disconnettere da rete o corrente.
 
- **Test Environment Master**
Dopo la suddetta installazione, per testare l’environment master potete aprire un terminale (terminal su Mac o Windows Terminal su windows) e navigare fino alla cartella dove avete salvato il file test_master.py utilizzando il comando: cd [nome_cartella]. Guardate il video per avere un esempio di tale comando. Una volta arrivati nella cartella contenente il file, digitate: <code>conda activate env_master</code> premere invio, poi digitare <code>python test_master.py</code>
Se l’installazione è stata compiuta correttamente, vedrete apparire sul terminale la scritta "Hello World” (ci vorrà qualche minuto).
 
- **Studio Preliminare Python (questa attività NON è obbligatoria)**
Per quelli che fossero interessati a iniziare a studiare Python da autodidatti vi consigliamo il libro online e open source disponibile al link:
http://www.spronck.net/pythonbook/
SoBigData accademy course

- **DBeaver**
DBeaver è un software per la gestione di basi di dati. Per scaricarlo cliccare sul seguente link: https://dbeaver.io/download/
E selezionare la versione adatta al proprio Sistema Operativo. Proseguite dunque con le normali procedure di installazione di un qualsiasi software.
Ci vediamo agli installation days, per verificare la corretta installazione ed eventualmente aiutarvi se avete problemi.



