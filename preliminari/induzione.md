# Induzione

## Principio

Come funziona il principio di induzione su N.
Come funziona l'induzione estesa.
Equivalenza con esistenza del minimo per ogni sottoinsieme non vuoto.


## Esempi

### Dimostrare formule senza capire da dove vengono

- somma `1..n`, somma `1^2..n^2`
- disuguaglianza di Bernulli
- determinante della Vandermonde


## Partire con un passo base più alto

- `n^2 < 2^n` (ma solo per `n > 3`)


## Usare una tesi più forte, ma più adatta al passo induttivo

- somma `i/4^i` è minore di `1/2` (è minore di `1/2 - 1/2^i`)


### Ricondursi a più di un caso precedente (usare due termini precedenti o anche tutti i termini precedenti)

- se `x+1/x` è razionale/intero, lo stesso è `x^k+1/x^k`
- una singola pila di monete inizialmente alta `n`; ad ogni mossa spezzo una pila `a+b` in una alta `a` e una alta `b`, guadagnando `ab`: quanto quadagno in tutto alla fine?
- ogni naturale si scrive come somma di fibonacci distinti e non consecutivi


### Costruzioni induttive

- ogni scacchiera `n \times n` (`n>=2`) si ricopre usando trimini a L e `2 \times 1`
- spostare torre di Hanoi
- teorema di Pick

