# Osservazioni — Esercitazione 0

Gruppo:Nadia Pericoli, Marta del Greco (nadiapericoli, Marta-delgreco) 

URL del repository condiviso:

Chi ha usato la tastiera nello step 1 e nello step 2:entrambe

Compilate insieme le osservazioni e discutete le risposte: entrambi dovete
saper spiegare le prove svolte.

## Step 1 — Hello World: compilazione ed esecuzione

Comando di compilazione:gcc -std=c17 -Wall -Wextra -Wpedantic hello.c -o hello

Comando di esecuzione e risultato osservato: ./hello
abbiamo osservato che sul terminale è stato stampato correttamente: Hello, computational physics!

Che cosa ho capito su sorgente ed eseguibile: la sorgente è il programma che abbiamo scritto e che abbiamo chiamato hello.c, mentre l'eseguibile è il file hello che il computer sa eseguire.

Output richiesto e comportamento del programma prima della modifica: prima della modifica il programma, dopo esser stato lanciato, scrive il testo direttamente ed esclusivamente sul terminale.

Esito dopo la modifica e spiegazione della correzione: dopo la modifica il programma non scrive più il testo sul terminale, bensì crea un file di testo, che abbiamo chiamato output.txt, su cui scrive l'output e perdipiù sovrascrive ogni volta che eseguiamo il programma (l'abbiamo verificato).

## Step 1 — Git

Quali file ho incluso nel commit e perché: nel commit ho incluso hello.c e osservazioni.md perchè gli eseguibili sono ignorati da Git, quindi non serve aggiungere hello.

Come ho verificato che la versione provata sia presente su GitHub: abbiamo controllato nel repository la presenza dei file e abbiamo visto il tempo da quando sono stati caricati.

Che cosa ho osservato prima e dopo `git pull`, e perché non serve un nuovo clone: git pull serve a scaricare da GitHub i commit caricati. Non serve aggiungere un nuovo clone perchè il collegamento tra GitHub e il terminale c'è già, sarebbe dunque una ridondanza.

Verifica del git pull: abbiamo eseguito i comandi ed è stato verificato.

## Step 2 — Eco: prima prova

Argomenti passati, comando e risultato:
int intero = atoi(argv[2]);
double reale = atof(argv[3]);
printf("%s %d %f\n", testo, intero, reale);

./eco nadia 5 6.9

nadia 5 6.900000

Che cosa posso concludere: il programma è stato scritto e eseguito correttamente 

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato:
ciao 12 3.5, il comando è di svolgere il programma e salvare l'output su un file di testo e il risultato è corretto. 
Che cosa ho capito su testo, conversioni e stampa: Mentre se 12 viene scritto a lettere il programma dà errore poichè non sto passando un intero cme argomento, ma un testo.

## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`: vedi sopra

Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati:
il contenuto del file eco.txt è: "ciao 12 3.500000", sul terminale stampa correttamente con il comando cat.
Come un controllo automatico può riconoscere un errore:
il valore stampato nel main da echo permette di verificare se ci sono errori, il risultato 0 indica che è andato a buon fine.
## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti:
se devo solamente cambiare i parametri ricompilo dal terminale, invece per cambiare la formula modifico il codice.
## Step 2 — Git

Come riconosco nella cronologia i commit dei due step:

Come ho verificato che la versione finale sia presente su GitHub:
