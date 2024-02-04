# Giochi

## Contenuti

Definizione di gioco finito (con due giocatori, perfetta informazione).

Esistenza di strategia vincente per uno dei due giocatori (volendo aggiungere la variante con il pareggio).

Divisione delle configurazioni in vincenti e perdenti: da ogni vincente esiste mossa che porta in perdente; da ogni perdente ogni mossa porta in vincente.

## Esempi

- pila con `n` monete, Alberto e Barbara tolgono 1, 2 o 3 monete; vince chi toglie l'ultima moneta
- tolgono 1, 2 o 4 monete
- si può togliere una pila oppure dividere una pila in 4 pile non vuote; perde chi toglie l'ultima moneta
- gioco dei piatti circolare da appoggiare su un tavolo rettangolare; perde chi non può posizionare un piatto senza intersecare un altro piatto (strategia con opposizione di mossa)
- si gioca sui divisori di `n`, dopo la prima mossa occorre dire un multiplo o un divisore del numero dichiarato dal giocatore precedente; perde chi ripete un numero già detto (vince il secondo giocatore se `n` non è un quadrato perfetto con la strategia di opposizione)
- si gioca sugli interi fino a `n`, ogni volta che viene detto un numero si cancellano tutti i suoi divisori (positivi), perde chi non può più dire un numero (il primo giocatore ha strategia vincente perché può decidere di cancellare o meno il numero `1`, totalmente non costruttiva)

## Indicazioni Esercizi

