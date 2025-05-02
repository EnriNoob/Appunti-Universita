 Giocare in anticipo per quanto riguarda contranstare gli ostacoli permette di avere un diagramma dei goal più realistico e più completo (verranno aggiunti goal appositi per mitigare i vari ostacoli).

dovremo quindi
- identificare gli ostacoli
- definire la probabilità e la severità delle conseguenze
- ideare una possibile soluzione

è un processo prettamente iterativo fin quando non si raggiunge un punto fisso

![[Pasted image 20250424140553.png]]

Una buona prassi è quella di partire dai nodi foglia del diagramma dei goal, questo perchè i goal ai nodi foglia sono i più elementari e quindi più semplici da sviluppare una soluzione.

Ci si ferma quando si ha finto di analizzare i goal più critici e quando certe conseguenze che possono avvenire vengono ritenute accettabili in termini di severità


---
### Identificazione ostacoli

si parte dal nodo root

![[Pasted image 20250424141303.png]]

![[Pasted image 20250424141506.png]]
Si va ad invertire la proprietà di dominio
![[Pasted image 20250424141613.png]]
andiamo a vedere come avvengono questi ostacoli appena inseriti raffinando quest'ultimi
	
![[Pasted image 20250424141731.png]]
![[Pasted image 20250424141856.png]]

---
### Pattern per identificare gli ostacoli

Ad esempio con un mantain goal l'ostacolo principale è la mancanza di persistenza in un certo punto del tempo del mantain goal stesso

![[Pasted image 20250424143225.png]]

Con un achieve goal è simile l'identificazione dell'ostacolo

![[Pasted image 20250424143356.png]]


---
### Valutare gli ostacoli

Per valutare gli ostacoli abbiamo bisogno grande conoscenza del dominio. Un modo per ragionare per calcolare la probabilità di un ostacolo è quella di misurare sempre la probabilità ma dei sotto ostacoli relativo a quello

![[Pasted image 20250424144132.png]]


---
### Risoluzione ostacoli

Principalmente consiste nel creare nuovi goal che permettono di mitigare l'ostacolo

![[Pasted image 20250424144430.png]]

Si possono sostituire goal con ostacoli con altri goal meno rischiosi che non presentano ostacoli

![[Pasted image 20250424144748.png]]

Un altro modo per mitigare è assegnare ai goal degli agenti che presentano meno rischi

![[Pasted image 20250424145036.png]]

Un altro modo è quello di rilassare (indebolire) il goal perchè magari è troppo ideale

![[Pasted image 20250424145746.png]] 