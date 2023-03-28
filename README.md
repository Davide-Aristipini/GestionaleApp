Gestione spese e entrate
========================

Questo progetto è un'applicazione web per la gestione delle spese e delle entrate personali. L'applicazione consente di visualizzare, aggiungere, aggiornare ed eliminare le spese e le entrate, nonché di analizzare i dati e di visualizzarli in modo grafico.

L'applicazione è stata sviluppata utilizzando il framework Angular per il frontend e PHP e MySQL per il backend.

Requisiti di sistema
--------------------

Per eseguire correttamente l'applicazione, sono necessari i seguenti requisiti di sistema:

-   Node.js versione 12 o successiva
-   Angular CLI versione 12 o successiva
-   PHP versione 7 o successiva
-   MySQL versione 5.7 o successiva

Installazione
-------------

Per installare l'applicazione, seguire i seguenti passaggi:

1.  Clonare il repository da GitHub:

    bashCopy code

    `git clone https://github.com/username/gestione-spese.git`

2.  Accedere alla cartella del progetto:

    bashCopy code

    `cd gestione-spese`

3.  Installare le dipendenze del frontend:

    Copy code

    `npm install`

4.  Creare il database MySQL per l'applicazione utilizzando il file "gestione_spese.sql" presente nella cartella "database".

5.  Configurare i dati di connessione al database nel file "config.php" presente nella cartella "backend".

6.  Avviare il backend PHP utilizzando il comando:

    Copy code

    `php -S localhost:8000 -t backend`

7.  Avviare l'applicazione frontend utilizzando il comando:

    Copy code

    `ng serve`

8.  Accedere all'applicazione nel browser all'indirizzo:

    arduinoCopy code

    `http://localhost:4200`
    
Utilizzo
--------

Una volta avviata l'applicazione, è possibile visualizzare le spese e le entrate attualmente presenti nel database, aggiungere nuove spese o entrate, aggiornare o eliminare le spese o le entrate esistenti.

L'applicazione consente inoltre di analizzare i dati delle spese e delle entrate, visualizzando le informazioni in modo grafico utilizzando la libreria Chart.js.

Contributi
----------

Se desideri contribuire al progetto, puoi aprire una nuova issue su GitHub o inviare una pull request. Saremo felici di valutare le tue proposte e di collaborare con te per migliorare l'applicazione.

Licenza
-------

Questo progetto è distribuito con licenza MIT. Per ulteriori informazioni, consultare il file LICENSE presente nella cartella principale del progetto.
