# Esercizi per la lezione 8

## Esercizio 8.1

Si definisca una semplice struttura di ereditarieta' delle forme geometriche,
seguendo l'esempio presentato ad inizio lezione.
  * Si aggiunga alla classe ```forma``` un membro ```private``` (ad esempio un'etichetta)
    e si verifichi che e' accessibile dalle classi derivate 
    solamente tramite un metodo aggiuntivo ```public``` o ```protected``` della classe base.
  * Si verifichi la sequenza delle chiamate dei costruttori e dei distruttori
    della parte base e derivata delle classi al momento della creazione e della distruzione
    dei diversi oggetti, inserendo in ogni costruttore e distruttore un messaggio a schemo.  

![linea](../immagini/linea.png)

## Esercizio 8.2 

Si modifichi la struttura precedente aggiungendo la funzione ```calcola_area``` 
in tutta la catena di ereditarieta'.
  * Si verifichi il comportamento polimorfico introdotto dal *dynamic binding*.
  * Si verifichi che, eliminando la parola chiave ```virtual```, 
    il *dynamic binding* non funziona.
  * Si verifichi che il *dynamic binding* avviene in esecuzione e non in fase di compilazione,
    implementando una funzione ```void stampa_area (forma * input)```
    che stampa a schermo l'area di un oggetto di tipo ```rettangolo``` 
    o ```quadrato``` a seconda della scelta dell'utente.

![linea](../immagini/linea.png)

## Esercizio 8.3

    
![linea](../immagini/linea.png)

## Esercizio 6.4


![linea](../immagini/linea.png)

## Esercizio 8.8


![linea](../immagini/linea.png)

## Esercizio 8.6


![linea](../immagini/linea.png)

## Esercizio 8.7


![linea](../immagini/linea.png)

## Esercizio 8.8


![linea](../immagini/linea.png)

## Esercizio 8.9