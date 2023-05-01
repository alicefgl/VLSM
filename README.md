# VLSM

## Consegna dell'esercizio:
Realizzare il seguente esempio di subnetting con maschere di sottorete a lunghezza variabile su Cisco Packet Tracer:

<img src="images/consegna esercizio.png" alt="Consegna esercizio">

La rete deve contenere quindi:
- 3 router
- 6 switch
- 6 o più host
La rete deve essere suddivisa in 8 sottoreti, 6 che contengano gli host e 2 che favoriscano la comunicazione fra i vari router.

## Procedimento:
- **Variable Lenght Subnet Mask**: si utilizza nell'ambito del subnetting a scopo di ottenere delle subnet di dimensioni diverse e che quindi abbiano diversi valori relativi al numero massimo di host che ognuna di esse può contenere.

Per eseguire l'esercizio ci siamo basati sulla seguente tabella, che indica la dimensione relativa ad ogni subnet mask (espressa in slash notation):

<img src="images/Tabella CIDR.png" alt="Tabella CIDR">

Tramite questa tabella è possibile iniziare a pianificare la suddivisione della rete nelle varie subnet in base alla dimensione richiesta per ogni sottorete:

<img src="images/Progettazione excel.png" alt="Progettazione">

Dopo aver inserito i dati della tabella nella configurazione dei vari dispositivi, si ottiene una rete di questo tipo:

<img src="images/Rete Cisco.png" alt="Rete su Cisco">
