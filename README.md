Ciao ragazzi,
oggi pomeriggio ci sarà un'esercitazione di gruppo, ma è comunque richiesto che creiate ciascuno la vostra repo, in cui poi pusherete il risultato del lavoro del team
Nome repo: human-code
Ogni team e ogni esercizio è numerato, svolgete l'esercizio con il numero uguale a quello del vostro team, cioè team 1 svolge esercizio 1, team 2 svolge esercizio 2 e così via...
In quest'altro file trovate la lista degli esercizi da svolgere:
https://docs.google.com/document/d/1vbartx0ar-hSIMMsXG_xnNQk0VTcEVEuEQUVrJM-iGc/edit?usp=sharing
Ciascun team dovrà fare un brainstorming per analizzare e scomporre il problema assegnato e scrivere la soluzione per step, come mostrato questa mattina.
Avete 1 ora di tempo per ragionare sul vostro esercizio ed elaborare il diagramma di flusso, poi intorno alle 16 ci si ritroverà tutti assieme per esporre agli altri team quanto prodotto e discuterne insieme.
Attendete quindi la comunicazione dei tutor con orario e link zoom a cui collegarsi.
BONUS: realizzate anche il diagramma di flusso del problema
Buon lavoro e buon divertimento! (modificato)


<!-----------------------
    TRACCIA ESERCIZIO 
------------------------>

Scegliere cosa guardare su Netflix
Che barba, che noia, che noia, che barba!
Perché ci si mette sempre un’ora a scegliere cosa guardare la sera? Certo è difficile mettere d’accordo i gusti di tutti, poi dipende anche in base al tempo (o al sonno) che abbiamo. Delle volte si pensa di vedere quel bel film che ci hanno consigliato, mentre altre volte si viene risucchiati da quella serie tv che ci tiene incollati allo schermo. Che senso di vuoto quando poi finisce!

<!--------------
    ESERCIZIO 
---------------->

? SE Hai voglia di guardare Netflix
    > Verifica quanto tempo hai a disposizione
        >> ? SE hai tanto tempo a disposizione
            >>> Scegli il genere che più preferisci.
                >>>> ? SE ti piace il genere horror
                    >>>>> Controlla che ci sia un film horror che ti aggrada    <!-- Contatore ? -->
                        >>>>>> Guardalo. FINE
                        >>>>>> : ALTRIMENTI Torna alla scelta del genere.
                >>>> ? SE ti piace il genere commedia
                    >>>>> Controlla che ci sia una commedia che ti aggrada  <!-- Contatore ? -->
                        >>>>> Guardala. FINE
                        >>>>>  : ALTRIMENTI Torna alla scelta del genere.
        >> : ALTRIMENTI se hai poco tempo
            >>> Scegli il genere che più preferisci.
                >>>> ? SE ti piace il genere horror
                    >>>>> Controlla che ci sia una serie romantica che ti aggrada   <!-- Contatore ? -->
                        >>>>>> Guardala. FINE
                        >>>>>> : ALTRIMENTI Torna alla scelta del genere.
                >>>> ? SE ti piace il genere Thriller
                    >>>>> Controlla che ci sia una serie thriller che ti aggrada    <!-- Contatore ? -->
                        >>>>> Guardala. FINE
                        >>>>>  : ALTRIMENTI Torna alla scelta del genere.
    > : ALTRIMENTI Fai altro o vai a letto.