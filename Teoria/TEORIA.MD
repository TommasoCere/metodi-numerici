# Domande di teoria sull'intelligenza artificiale
- Intelligenza artificiale, Machine Learning e Deep Learning.
    +   Intelligenza artificiale: Riproduzione parziale dell’attività intellettuale propria dell’uomo (con particolare riguardo ai processi di
        apprendimento, di riconoscimento, di scelta) realizzata o attraverso l’elaborazione di modelli ideali, o,
        concretamente, con la messa a punto di macchine che utilizzano per lo più a tale fine elaboratori
        elettronici.
        + L'intelligenza Artificiale forte riguarda sistemi che sono progettati per risolvere problemi specifici in un settore particolare.
        + L'intelligenza Artificiale debole riguarda sistemi che sono progettati per risolvere problemi generici.
    +   Machine Learning: “Il Machine Learning è quella branca dell’informatica che permette a una macchina di imparare ad eseguire
        un compito senza essere esplicitamente programmata per farlo” - 1959 Herbert Simon 
    +   Deep Learning: o deep neural learning , è un sottoinsieme del machine learning , che utilizza le reti neurali
        per analizzare diversi fattori con una struttura simile al sistema neurale umano.
</br></br>
- Storia dell’intelligenza artificiale, Origini, I due Inverni, Tempi moderni: 2011 ad oggi Deep Learning
    + La storia
</br></br>
- Paradigma del machine Learning vs Paradigma di programmazione tradizionale.
    +   «Il Machine Learning è il campo di studi che fornisce ai computer la capacità di imparare a risolvere
        i problemi senza essere esplicitamente programmati» - Artur Samuel 1959.
        Prima era necessario istruire la macchina su come risolvere un specifico problema, mentre ora grazie 
        al machine learning la macchina è in grado di risolvere problemi di cui non è stata istruita.
</br></br>
- Preparazione dei dati (Training Set, Validation Set, Testing Set) – Modello – Predizione
    +   Training Set: è un insieme di dati utilizzati per addestrare un modello di machine learning. 
        Il training set è un sottoinsieme del dataset utilizzato per addestrare il modello.
    +   Validation Set: su questi dati vengono messi a punto gli iperparametri del modello.
    +   Testing Set: è un insieme di dati utilizzati per valutare le prestazioni di un modello di machine learning.
    +   Modello: è il nucleo di un sistema di machine learning. È il risultato dell'addestramento del modello
        su un training set. Il modello rappresenta la conoscenza acquisita dal sistema di machine learning.
    +   Predizione: è il processo di utilizzo di un modello per effettuare previsioni su dati sconosciuti.
</br></br>
- Task del Machine Learning: Classificazione, Regressione e Clustering
    +   Classificazione: il concetto di classe è correlato al concetto di etichetta. 
        L'obiettivo è quello di assegnare un'etichetta a un oggetto in base alle sue caratteristiche.
    +   Regressione: viene utilizzata per modellare la relazione tra una variabile dipendente e una o più variabili indipendenti,
        al fine di fare previsioni su nuovi dati.
    +   Clustering: è una tecnica di apprendimento non supervisionato che raggruppa gli oggetti in base alle loro caratteristiche.
</br></br>
- Necessità di una fase di feature extraction nel Machine learning
    + è la procedura di estrazione delle caratteristiche dai dati in modo da creare un nuovo e più contenuto insieme di dati
        in grado di descrivere in modo più efficace il problema che si vuole risolvere.
</br></br>
- Deep Learning vs Machine Learning
    +   Il machine learning è un campo che si occupa dello sviluppo di algoritmi che permettono ai computer di imparare dai dati e 
        di fare previsioni o prendere decisioni senza essere esplicitamente programmati. 
        Questi algoritmi analizzano i dati di input e identificano i modelli o le relazioni in essi contenuti per fare previsioni o prendere decisioni.
    +   Il deep learning è una sottocategoria del machine learning che utilizza reti neurali artificiali profonde per 
        l'apprendimento automatico delle caratteristiche dai dati. Queste reti neurali profonde sono composte da molti strati di neuroni artificiali 
        e possono apprendere direttamente dai dati senza la necessità di estrarre manualmente le caratteristiche.
    +   In sintesi, il deep learning è un approccio più avanzato in cui le reti neurali profonde possono imparare automaticamente 
        le caratteristiche dai dati, eliminando la necessità di una pre-elaborazione manuale. Tuttavia, richiede una grande quantità 
        di dati di addestramento e risorse computazionali per l'addestramento.
</br></br>
- Classificazione degli algoritmi di Machine Learning: Algoritmi Supervisionati (Regressione e classificazione), Algoritmi non supervisionati 
    (Clustering ed Associazione), Apprendimento Semi-supervisionato, Apprendimento con rinforzo.
    +   Supervisionato: è un tipo di apprendimento nel quale vengono presentati i dati di input e gli output che essi dovrebbe generare, 
        con lo scopo di apprendere una regola generale in grado di mappare la relazione tra gli stessi.
        +   Regressione: è un tipo di apprendimento supervisionato che si occupa di predire un valore numerico continuo. In altre parole,
            si tratta di modellare una relazione tra le variabili di input e una variabile di output continua.
        +   Classificazione: è un tipo di apprendimento supervisionato che si occupa di predire un valore discreto.
    +   Non supervisionato: è un tipo di apprendimento nel quale non vengono presentati gli output attesi, 
        ma il sistema deve essere in grado di trovare da solo la struttura dei dati. In questo modo si vanno a creare classi con dati più utili
        per le analisi successive e permettendo si scoprire nuove informazioni nei dati che non erano state considerate.
        +   Clustering: è un tipo di apprendimento non supervisionato che si occupa di raggruppare gli oggetti in base alle loro caratteristiche.
        +   Associazione: è un tipo di apprendimento non supervisionato che si occupa di trovare le relazioni tra gli oggetti.
    +   Semi-supervisionato: è un tipo di apprendimento nel quale vengono presentati sia dati di input che gli output attesi, 
        ma solo per una parte dei dati. Il sistema deve essere in grado di trovare da solo la struttura dei dati.
    +   Rinforzo: è un tipo di apprendimento nel quale il sistema deve imparare a prendere decisioni in base alle interazioni con l'ambiente. 
        Il sistema riceve un feedback in base alle sue azioni e deve imparare a massimizzare il feedback ricevuto.
</br></br>
- Reti Neurali Artificiali: Neurone Biologico e Neurone artificiale. Funzioni di attivazione. Percettrone a soglia e limiti.
    +   Neurone Biologico: è un tipo di cellula del sistema nervoso che è in grado di ricevere, elaborare e trasmettere informazioni.
        I neuroni sono collegati tra loro tramite sinapsi. Quando un neurone riceve un segnale da altri neuroni, 
        elabora le informazioni e trasmette il segnale ai neuroni collegati tramite sinapsi.
        E' composto da:
        +   Dendriti: sono le estremità del neurone che ricevono i segnali da altri neuroni.
        +   Corpo cellulare: elabora i segnali ricevuti dai dendriti e trasmette il segnale ai neuroni collegati tramite sinapsi.
        +   Assone: trasmette il segnale ai neuroni collegati tramite sinapsi.
        +   Sinapsi: sono le connessioni tra i neuroni. Quando un neurone riceve un segnale da altri neuroni, 
            elabora le informazioni e trasmette il segnale ai neuroni collegati tramite sinapsi.
    +   Neurone artificiale: è un modello matematico che si ispira al neurone biologico.
        E' composto da:
        +   Input: sono i segnali in ingresso al neurone.
        +   Pesi: sono i parametri che vengono utilizzati per modificare l'importanza dei segnali in ingresso.
        +   Funzione di attivazione: è una funzione che viene utilizzata per calcolare l'output del neurone.
        +   Output: è il segnale in uscita dal neurone.
    +   Funzioni di attivazione: serve per derminare se un neurone deve essere attivato o meno.
        Si tratta di una funzione non lineare che prende in input la somma pesata dei segnali in ingresso al neurone e restituisce un output.
    +   Percettrone a soglia: è un modello matematico di neurone artificiale che prende in input un vettore di valori numerici e 
        restituisce un output binario (0 o 1).
        Si tratta di una funzione non lineare che prende in input la somma pesata dei segnali in ingresso al neurone e restituisce un output.
        +   Limiti del Percettrone a soglia: il percettrone a soglia non è in grado di modellare funzioni non lineari.
            Per ovviare a questo problema sono state introdotte le reti neurali feedforward.
</br></br>
- Reti Neurali artificiali: Input Layer, Hidden Layer, Output Layer. Reti FeedForward, Reti ricorrenti.
    +   Una rete neurale artificiale è costituita da neuroni artificiali collegati tr loro. Ogni connessione, come in un cervello biologico,
        può trasmettere un segnale da un neurone all'altro. I neuroni sono organizzati in strati. Ogni connessione ha un peso che 
        determina l'importanza del segnale trasmesso.
        Le reti neurali artificiali sono composte da gruppi di neuroni artificiali organizzati in strati:
        +   Input Layer: è lo strato di input della rete neurale. I neuroni di questo strato ricevono i dati in input alla rete neurale.
        +   Hidden Layer: è uno strato intermedio tra lo strato di input e lo strato di output. 
            I neuroni di questo strato elaborano i dati ricevuti in input e trasmettono il segnale ai neuroni dello strato successivo.
        +   Output Layer: è lo strato di output della rete neurale. I neuroni di questo strato restituiscono il risultato della rete neurale.
    +   Reti FeedForward: è un tipo di rete neurale artificiale in cui i segnali si muovono in una sola direzione,
        dallo strato di input allo strato di output.
    +   Reti ricorrenti: è un tipo di rete neurale artificiale in cui i segnali si muovono in entrambe le direzioni,
        dallo strato di input allo strato di output e viceversa.
</br></br>
- MultiLayer Preceptron (MLP)
    +   E' un tipo di rete neurale artificiale feedforward in cui i neuroni sono organizzati in strati. Si tratta di uno dei modelli più utilizzati per il deep learning.
        L'MLP è in grado di apprendere relazioni complesse e non lineari tra i dati di input e l'output desiderato grazie alla sua struttura multistrato e alla capacità 
        di modellare rappresentazioni gerarchiche dei dati. L'addestramento dell'MLP avviene utilizzando algoritmi di ottimizzazione come la retropropagazione dell'errore, 
        che calcola e aggiorna i pesi delle connessioni in base all'errore tra l'output previsto e l'output desiderato.
        Il MLP più comune è l'FFNN (FeedForward Neural Network), ed è composto da:
        +   un input Layer: è lo strato di input della rete neurale. I neuroni di questo strato ricevono i dati in input alla rete neurale.
        +   uno o più Hidden Layer: è uno strato intermedio tra lo strato di input e lo strato di output. 
            I neuroni di questo strato elaborano i dati ricevuti in input e trasmettono il segnale ai neuroni dello strato successivo.
        +   un output Layer: è lo strato di output della rete neurale. I neuroni di questo strato restituiscono il risultato della rete neurale.
</br></br>
- Training di una rete neurale. Forward Propagagation e Backward Propagation.
    +   Training di una rete neurale: è il processo di addestramento di una rete neurale artificiale.
        Iterativamente, la rete neurale viene esposta a un insieme di dati di addestramento e viene aggiornata in base all'errore tra l'output previsto e l'output desiderato.
        L'obiettivo del training è quello di ridurre l'errore tra l'output previsto e l'output desiderato.
        +   Forward Propagation: è il processo di calcolo dell'output di una rete neurale artificiale.
            L'output di ogni neurone viene calcolato utilizzando la funzione di attivazione e i pesi delle connessioni.
        +   Backward Propagation: è il processo di aggiornamento dei pesi delle connessioni di una rete neurale artificiale.
            L'aggiornamento dei pesi delle connessioni avviene utilizzando l'algoritmo di ottimizzazione della retropropagazione dell'errore.
</br></br>
- Loss Function e Funzione costo.
    +   Loss Function: è una funzione che misura l'errore tra l'output previsto e l'output desiderato.
        L'obiettivo del training di una rete neurale artificiale è quello di ridurre l'errore tra l'output previsto e l'output desiderato.
        La loss function viene utilizzata per calcolare l'errore tra l'output previsto e l'output desiderato.
    +   Funzione costo: è una funzione che misura l'errore tra l'output previsto e l'output desiderato.
        L'obiettivo del training di una rete neurale artificiale è quello di ridurre l'errore tra l'output previsto e l'output desiderato.
        La funzione costo viene utilizzata per calcolare l'errore tra l'output previsto e l'output desiderato.
        La funzione costo viene calcolata come: $C = \frac{\sum_{i=1}^{n} L(y_i, \hat{y_i})}{n}$ dove $n$ è il numero di esempi di addestramento, $y_i$ è l'osservazione effettiva dell'esempio di training i-esimo, $\hat{y_i}$ è la previsione dell'esempio di training i-esimo.
</br></br>