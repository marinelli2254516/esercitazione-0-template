# Osservazioni — Esercitazione 0

Gruppo: 

Componenti (nome, cognome e username GitHub di entrambi): Edoardo Leoni Edo-ardo00, Matteo Marinelli marinelli2254516

URL del repository condiviso: https://github.com/marinelli2254516/esercitazione-0-template.git

Chi ha usato la tastiera nello step 1 e nello step 2: Matteo step 1, Edoardo step 2

Compilate insieme le osservazioni e discutete le risposte: entrambi dovete
saper spiegare le prove svolte.

## Step 1 — Hello World: compilazione ed esecuzione

Comando di compilazione: gcc -std=c17 -Wall -Wextra -Wpedantic hello.c -o hello

Comando di esecuzione e risultato osservato: ./hello || Nessun output

Che cosa ho capito su sorgente ed eseguibile: La sorgente e' un file scritto dall'utente, mentre l'eseguibile e' un file binario che il computer fa girare.  

Output richiesto e comportamento del programma prima della modifica: L'output richiesto era "Hello, computational physics!", seguito da un a capo. Prima della modifica il file non stampava nulla a schermo, ma compilava.

Esito dopo la modifica e spiegazione della correzione: L'esito della modifica e' stato positivo, dopo aver inserito il comando di stampa e aver ricompilato il file, l'output richiesto viene stampato a schermo.

## Step 1 — Git 
Controllato su github e l'ultimo commit e' identico a quello del terminale

Quali file ho incluso nel commit e perché: Abbiamo incluso hello.c e osservazioni.md, perche' sono i due file di testo. Non abbiamo incluso hello essendo un eseguibile. 

Come ho verificato che la versione provata sia presente su GitHub: Abbiamo aperto il commit su github e abbiamo verificato che il codice fosse identico.

Che cosa ho osservato prima e dopo `git pull`, e perché non serve un nuovo clone: Prima di git pull la frase aggiunta su osservazioni.md da github, non c'era su pc dopo git pull e' comparsa. Non serve un clone perche' il computer e' gia' collegata a github e gitpull scarica gli aggiornamenti

## Step 2 — Eco: prima prova

Argomenti passati, comando e risultato: Argomenti passati : ciao, 12, 3.5. Il comando utilizzato e' stato ./eco ciao 12 3.5. Il risultato ottenuto a schermo e' stato ciao 12 3.500000

Che cosa posso concludere: Si puo concludere che le funzioni atoi e atof convertono le stringhe in numeri.

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato:  Argomenti passati : ciao, 12, 3.5,  Il comando utilizzato e' stato ./eco2 ciao 12 3.5. Il risultato ottenuto a schermo e' stato ciao 12 3.500000 

Che cosa ho capito su testo, conversioni e stampa: Gli argomenti arrivano sempre come stringhe. Le funzioni strtol e strtod permettono di controllare che il dato sia un numero valido. Infine printf stampa con %s il testo invariato, con %d un intero e %f un double.

## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`: Si prevede che se inseriti argomenti validi il codice produce correttamente il testo e lo salva su eco.txt, mentre sul terminale non appare nessun messaggio. Se invece si inserisce un valore sbagliato (ad esempio 'dodici') il codice segnala il tuo errore sul terminale e lascia il file vuoto.

Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati: Nel caso valido eco.txt contiene 'ciao, 12, 3.500000' e il codice di uscita è 0. Nel caso con errore il file eco.txt è vuoto e il codice stampa terminale l'errore dicendo 'il secondo argomento deve essere un argomento in base 10'.

Come un controllo automatico può riconoscere un errore: Legge il codice di uscita, se è 0 il codice è corretto e il comando è andato a buon fine, se è diverso da 0 l'esecuzione del codice si blocca e termina.

## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti: Serve ricompilare quando hai modificato il codice sorgente in c, basta cambiare gli argomenti per modificare i dati in input.

## Step 2 — Git

Come riconosco nella cronologia i commit dei due step: Scrivendo il comando git log--oneline si distinguono i messaggi dei commit dalla cronologia, uno per 'Hello.world.c' e uno per 'eco.c'.

Come ho verificato che la versione finale sia presente su GitHub: Controllando direttamente sul sito di github che gli ultimi commit salvati fossero presenti. 
