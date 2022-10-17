El DailyHack de les primeres dues setmanes està inspirat en "Conway's Game of Life".

Per aquest primer repte, els participants haureu de programar un taulell dividit en cel·les sobre el que s'apliquin les regles del famós joc:

1. Una cel·la es pot estar viva o morta.
2. Una cel·la es veu afectada per les cel·les amb les que està en contacte directe. Això vol dir, les seves cel·les adjacents vertical, horitzontal i diagonalment.
3. Si una cel·la viva té menys de dues cel·les vives adjacents, passa a estar morta per solitud.
4. Si una cel·la viva té dues o tres cel·les vives adjacents, segueix viva.
5. Si una cel·la viva té més de tres cel·les adjacents vives, passa a estar morta per sobrepoblació.
6. Si una cel·la morta té exactament tres cel·les vives adjacents, passa a estar viva per reproducció. 


Els requisits mínims per visualitzar i evaluar el joc són els següents:

- S'haurà de programar una representació gràfica del taulell on es distingeixin visualment les cel·les vives de les mortes. 

- S'han d'admetre dos modes diferents.
  - El primer és automàtic, on cada X temps el taulell s'actualitzarà sense acció de l'usuari que està executant el programa. Aquest temps haurà de ser suficientment gran com per a que es puguin observar les diverses iteracions del programa.
  - El segon mode és manual, on cada cop que l'usuari apreti un botó, el taulell avançarà al següent estat.

A part de programar el taulell, cada participant del DailyHack haurà de proposar una llavor inicial. Aquesta llavor es tractarà d'una distribució concreta de cel·les habitades. S'haurà de presentar també una explicació de què fa la llavor, com s'ha trobat, especificacions concretes així com qualsevol altre aspecte que es consideri important. 

S'evaluarà la presentació, l'originalitat de la llavor presentada i el raonament adjunt respecte a l'elecció d'aquesta
