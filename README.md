# REPO projecte-smx2b-2026-2027

Llista de projectes d'SMX2B del curs 2026-2027.

### BoardSinc


### HoloTech360


### MetroCount
Desenvolupament d'una aplicacio per saber la quantitat que tan ple va el metro de Barcelona
 
![Text de prova](/img/metrocount1.jpg)
![Imatge esquema resumit](/img/metrocount2.jpg)

## Links

[Documentació de la API de TMB "Incluyent autobusos"](https://developer.tmb.cat/api-docs/v1 )

[Més dades per consultar de la API de TMB"](https://developer.tmb.cat/data)


## Context

La nostra idea és fer-hi en Python una demostració de com es podria fer un comptador de persones en els vagons del metro de Barcelona perquè així a través d'una aplicació es pogués consultar que tan ocupat va el metro i llavors els passatgers poguessin decidir si és convenient entrar o no al vagó

## Com es fara?

Resumidament, el que teníem pensat nosaltres és implementar uns sensors just a la porta dels vagons del metro perquè així compti les persones que hi passen, la nostra forma que havíem pensat d'implementar els sensors es tractaria de dos sensors, un que s'encarregui de comptar els que entren i l'altre dels que surten, si és possible fer els sensors s'actualitzin de manera ràpida i freqüent (cada 0,5 segons per exemple), i que els infrarojos sàpiguen diferenciar quan passen persones i quan no. <br>

 
(D'Aquest tema s'hi ha en parlaré en un altra secció sobre els que se'ns queda fora de l'abast i quins problemes podrien sorgir)

## Problemes i fora d'abast

Els problemes d'abast en els quals ens podríem arribar a trobar és la precisió d'aquestes dades, un dels principals reptes d'aquest projecte és que les dades no podran ser 100% precises, ja que podrien sorgir problemes com que hi ha una avalancha de persones que entrin juntes al vagó i que el sensor compta com si hagués entrat una persona, però en realitat hi ha entrat dues o tres persones o inclús més. <br>

També en la part de recollida de dades els repetidors de wifi que hi ha que serveixen per enviar les dades cap al servidor sobre les persones podria fallar per culpa de l'alta demanda de persones que estiguessin utilitzant la xarxa<br>

Per això la nostra visió és fer que les dades siguin aproximades, encara que sempre hi busquem que sigui el més precís possible resulta ser que es una tasca bastant complicada saber amb exactitud la quantitat real dels passatgers, per això la nostra idea és fer una barra amb colors (per exemple de verd a vermell) en la qual hi hagi una fletxa que indiqui que tan ocupat està el tren segons les dades recollides dels sensors.


### PackGo


### RBridge


### Remote-Smart-Plugs


### SafeTracking


### WearSafe
